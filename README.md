# -MACHINE-LEARNING-MODEL-IMPLEMENTATION
COMPANY : CODTECH IT SOLUTIONS

NAME : MOTHKUR AKSHITHA REDDY

INTERN ID : CT06DA128

DOMAIN : PYTHON PROGRAMMING

DURATION : 6 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION :
This project focuses on building a machine learning model to predict loan defaults based on various borrower attributes, using a Random Forest classifier. The dataset contains detailed loan application data such as employment length, home ownership status, income, loan amount, interest rate, loan intent, credit grade, and credit bureau default status. The target variable is loan status, which indicates whether a loan has been defaulted or not. This classification problem is crucial for financial institutions to assess risk and make informed lending decisions.

The initial step involved data preprocessing to prepare the dataset for modeling. Some features, like employment length and loan interest rate, had missing values. These were imputed with their respective median values to avoid bias and preserve the dataset’s integrity. Since many features were categorical, such as home ownership and loan intent, they were transformed into numerical form using label encoding. This transformation is essential because machine learning algorithms like Random Forest require numerical inputs.

Following preprocessing, the data was split into training and testing sets using an 80-20 ratio to evaluate model performance on unseen data effectively. A Random Forest classifier was chosen due to its strength in handling mixed data types and its ability to reduce overfitting through ensemble learning. The model was trained on the training set, learning complex patterns that distinguish defaulted loans from non-defaulted ones.

Once training was complete, predictions were made on the test set. The model’s accuracy was calculated to measure overall performance, indicating the proportion of correctly classified loans. Beyond accuracy, a detailed classification report was generated, providing precision, recall, and F1-scores for each class, which help understand the model’s behavior in more depth, especially its ability to correctly identify defaults and non-defaults. A confusion matrix was also plotted, visually displaying the count of true positives, false positives, true negatives, and false negatives, making it easier to interpret the types of prediction errors.

The results demonstrated that the Random Forest model is effective in predicting loan default status with a high degree of accuracy. The visual and numeric evaluations provide confidence that the features selected are informative and the model is robust enough to support financial risk assessment tasks.

Overall, this project illustrates the complete workflow from data cleaning and preprocessing to model training, evaluation, and visualization. It highlights practical machine learning skills such as handling missing data, encoding categorical variables, splitting datasets, training ensemble models, and interpreting classification metrics. This approach lays a foundation for further enhancements, such as feature engineering, parameter tuning, or deploying the model for real-world loan risk management applications.

output

![{9E7F04CD-3914-456B-ABB0-8C4EB83715AF}](https://github.com/user-attachments/assets/db5c7ed7-fd1f-4ce8-bdab-64e61ff63bc7)


![{9E7F04CD-3914-456B-ABB0-8C4EB83715AF}](https://github.com/user-attachments/assets/9e2990ea-e6ff-4cfb-ac53-643812d43d09)













