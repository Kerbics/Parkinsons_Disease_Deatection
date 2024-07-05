Dataset link- https://archive.ics.uci.edu/dataset/470/parkinson+s+disease+classification

Info on Dataset:
The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages ranging from 33 to 87 (65.1Â±10.9).
Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.

Steps followed include:
1)Dataset analysis\
2)Feature Engineering\
3)Hyperparameter Tuning\
4)Model training

The models used for training were:\
-Naive Bayes:\
    Test set accuracy: 0.71 Mean cross-validation accuracy: 0.76 Standard deviation: 0.04 The mean cross-validation accuracy is slightly higher than the test set accuracy, and the standard deviation is relatively low, indicating that the Naive Bayes model is likely not overfitting.

-Multi-Layer Perceptron:\
    Test set accuracy: 0.96 Mean cross-validation accuracy: 0.94 Standard deviation: 0.03 The mean cross-validation accuracy is slightly lower than the test set accuracy, and the standard deviation is low. This suggests that the Multi-layer Perceptron model may be slightly overfitting, but not to a concerning degree.

-Random Forest Classifier:\
    Test set accuracy: 0.95 Mean cross-validation accuracy: 0.92 Standard deviation: 0.04 The mean cross-validation accuracy is lower than the test set accuracy, and the standard deviation is moderate. This may indicate that the Random Forest model is overfitting to some extent, but it's not a severe case.

-SVM linear kernel:\
    Test set accuracy: 0.93 Mean cross-validation accuracy: 0.90 Standard deviation: 0.04 The mean cross-validation accuracy is lower than the test set accuracy, and the standard deviation is moderate. This suggests that the SVM Linear Kernel model is overfitting to the training data, and regularization techniques or simpler models may be required.

-SVM RBF kernel:\
    Test set accuracy: 0.98 Mean cross-validation accuracy: 0.94 Standard deviation: 0.02 The mean cross-validation accuracy is lower than the test set accuracy, but the standard deviation is low. This indicates that the SVM RBF Kernel model may be overfitting to some extent, but it's not a major concern.


Highest Accuracy gainied: 98 percent using SVM RBF kernel
