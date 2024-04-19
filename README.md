# credit-risk-classification
 
Throughout this module, I utilized diverse techniques to develop and assess a model focused on loan risk. Leveraging a dataset encompassing historical lending activities from a peer-to-peer lending service, I aimed to construct a model capable of discerning the creditworthiness of borrowers. Specifically, the model was trained to categorize loans as either "healthy" or "high-risk," drawing on factors such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status.

The initial step involved splitting the data into training and testing sets using the train_test_split function from the sklearn library. Subsequently, I constructed a logistic regression model using the training data (X_train and y_train), made predictions on the testing data (X_test), assessed the model's performance through a confusion matrix detailing true positives, true negatives, false positives, and false negatives, and generated a classification report.

The obtained results are promising, indicating an overall accuracy of 99%. Precision for healthy loans reached a perfect 100%, while for high-risk loans, it stood at a commendable 87%. Similarly, recall rates for healthy and high-risk loans were impressive at 100% and 89%, respectively. The logistic regression model achieved exceptional performance for healthy loans, with a flawless F1-score of 1, supported by a substantial sample size of 18,679 and a minimal count of 67 false negatives. Although the precision for high-risk loans slightly declined to 87%, with a recall of 89% and an F1-score of 0.88, the model remains robust, albeit the smaller sample size of 563. Overall, the model demonstrated strong efficacy for both loan categories.

Given its remarkable accuracy, precision, and recall, I wholeheartedly recommend this model to the lending services company. Its ability to mitigate false negatives, where healthy loans are misclassified as high-risk, underscores its utility in real-world lending scenarios.



I worked with classmates and UCB Resouces to complete this homework. 
