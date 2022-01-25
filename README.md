# Sign-language-Digits

Kaggle : https://www.kaggle.com/ardamavi/sign-language-digits-dataset

It's a multi label classification project, aiming to classify sign language digits. 

![image](https://user-images.githubusercontent.com/62259863/150985780-eb3a6e4b-97f6-497c-aad1-41fdb905f4a1.png)

I first tried with classical machine learning models such as :
- LogisticRegression
- KNeighborsClassifier
- RandomForestClassifier
- Support Vector Classifier (SVC). (with OvR)

And ended up trying some deep learning model:
- MLP 
- CNN

As expected the CNN is the best model to tackle this problem, I obtained a 98.5% accuracy on the validation set. 

![image](https://user-images.githubusercontent.com/62259863/150985200-baf67718-b2d4-418c-b6fa-1ae002b51a7d.png)
