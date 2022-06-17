# CelebrityFaceRecognition_MachineLearning


1-How do you detect face and eyes? with Haar Cascade
![image](https://user-images.githubusercontent.com/83788186/174264748-240b5fe2-3483-4dca-b263-63324bd9092c.png)


2-Crop the facial region of the image
![image](https://user-images.githubusercontent.com/83788186/174264845-23a1b108-4cb1-4631-baa1-3ebb26732444.png)


3-Used wavelet transfrom as a feature for training our model
![image](https://user-images.githubusercontent.com/83788186/174264953-b371b5f2-f665-462a-b8cd-4642d66910d5.png)


4-Training Model
SVM with rbf kernel tuned with heuristic finetuning

5-Let's use GridSearch to try out different models with different paramets.
Goal is to come up with best model with best fine tuned parameters
![image](https://user-images.githubusercontent.com/83788186/174265216-4d327a9c-20bb-4ac8-b8af-b235d0f078ca.png)


So:
Librarys : matplotlib,pywt, seaborn
for model : svm, randomforestclassifier, logistic regression, Grid search CV, confusion matrix
then we saved trained model with joblib and class dictionary with json





