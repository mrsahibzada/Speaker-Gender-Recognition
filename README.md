# Speaker-and-Gender-Recognition
Data was used to train different Machine Learning Models including Multi-Class logisitic Regression, Gaussian Naive Bayes, Linear Support Vector Machine and Multi-Layered Perceptron. Models were created for both Gender Recognition and Speaker Recognition.

## Data Collection
Data was collected from a class of 148 students. Each student had to record 10 audios of his/her own voice. These audios were then splitted with a ratio of 6-2-2 for training, validation and testing respectively. 

## Feature Extraction
For feature extraction each WAVE file was represented by 13-dimentional Melfrequency Cepstral Coefficients (MFCCs). 

## Multi-Class Logistic Regression
Multi-class Logistic Regression was carried out from scratch. No scikit learn libraries were used for this. It could predict gender with accuracy of 76% and accuracy achieved for Speaker Recognition was 91%.

## Classifiers Used
For Gaussian Naive Bayes, Linear Support Vector Machine and Multi-Layered Perceptron I used Scikit-Learn libraries. Grid search CV was used to train Multi-layered Perceptron with best parameters. Multi-layer perceptron showed best classification report with F1-Macro score of Gender Recognition to be 83% and of Speaker Recognition to be 93%. Other classifiers also performed well but their F1-macro score was less than Multi-Layered perceptron.
