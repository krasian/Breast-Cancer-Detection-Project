# Breast-Cancer-Detection-Project
Breast cancer is a common cancer among women worldwide, and early detection can significantly improve survival by encouraging patients to seek medical attention as soon as possible. It's incredible how data has the potential to be able to save lives. This project uses Python and Machine Learning.

I start by identifying and dropping an empty columns and I changed the categorical diagnosis data into numerical values. Next, I visualized the distribution of malignant and benign cases using histograms. This helped me understand the spread of the data and identify any potential imbalances.

I selected specific columns relevant to the analysis, converted them into arrays for the models to work with, and then split the data into training and testing sets. The training set was used to train the models, while the testing set was used to evaluate their performance on unseen data. Finally, I scaled the data to ensure all features are on the same scale, preventing any one feature from dominating the others.

With the data preprocessed, it's time to train the models! I trained three different models: logistic regression, decision tree, and random forest classifier. I then evaluated their performance on the training data. This helped me assess how well each model is learning from the data.

Once the models were trained, I tested them further on the unseen test data. I used confusion matrices and metric functions like accuracy, precision, recall, and F1 score from the scikit-learn library to assess their performance. Based on the evaluation, I found that the random forest classifier performed the best, so I focused on its predictions.
