Model logistic regression digunakan karena model ini cocok untuk masalah klasifikasi biner seperti ini (failure or no failure).

Model ini menunjukkan kinerja yang sangat baik berdasarkan evaluasi dengan accuracy 0.99 yang artinya model ini hampir selalu benar dalam memprediksi machine failure, precision 1.0 (False Positive : 0) dan recall 0.967 yang artinya model mampu mendeteksi 96.7% dari kegagalan alat yang terjadi meskipun ada beberapa kegagalan yang tidak terdeteksi (False Negative)

Selain itu, pada kurva precision-recall juga menunjukkan bahwa model ini sangat efektif karena precision yang tetap tinggi saat recall meningkat.

Dan juga dilihat dari kurva ROC dimana model yang baik akan memiliki kurva yang mendekati sudut kiri atas. Dan dengan nilai AUC yang mendekati 1 yaitu 0.98 menunjukkan bahwa model ini memiliki kinerja yang sangat baik.
