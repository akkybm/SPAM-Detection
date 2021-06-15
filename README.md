# SPAM-Detection
SMS SPAM Detection Model using Natural Language Processing.

* Natural Language Processing, which basically consists of combining machine learning techniques with text, and using math and statistics to get that text in a format that the machine learning algorithms can understand!

* Using same I have detected spam messages from SMSSpamCollection dataset(find above) and train and evaluate the model to predict a message to be spam or not.

* Here I have first created the clasis model all by myself doing Vectorization, using TfidfTransformer and then training and testing the model using MultinomialNB() and then later had went to Sklearn's built in Pipeline Feature which helps in NLP and then later compare accuracy of Pipeline model with Random Forest Model and MultinomialNB()
model .
