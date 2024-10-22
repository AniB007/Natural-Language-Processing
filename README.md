# Conclusion
Used Label Encoder for converting airline sentimenmt to numbers.
Postive = 2
Negative = 0
Neutral = 1
After going through text I have used Regex library to remove all the tagged sign used in front of every sentences
Then I have used word tokenier & processed the text using Word Net Lemmatizer.
I have used Term Frequency-Inverse Document Frequency to convert text to vector.
Finally using logistic regression model the accuracy came to be 79%, which is ok for simple project like this.
Then I have used Confusion Matrix and plotted it using heatmap, to get the Actual VAlues and predicted values.
