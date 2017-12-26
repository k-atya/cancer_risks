# cancer_risks
Determines most important factors contributing to cervical cancer

This is an analysis of a dataset of 857 women with and without cervical cancer from the UCI Machine Learning Repository. This is a 35-parameter dataset which includes age, number of sexual partners, number of pregnancies, as well as information on STDs, contraceptives, and smoking habits. This analysis employs forward selection to find the most important predictors, as well as principal component analysis, to create a logistic regression model classifying whether a patient has or does not have cervical cancer. Since there are only 55 examples of women with cervical cancer, the models were not learning. Manipulating the threshold for classification did not affect sensitivity, and so I created a smaller control to train and test the models.
