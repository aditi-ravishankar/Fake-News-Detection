# Fake-News-Detection

Fake news is the deliberate spread of misinformation via traditional news media or via social media. False information spreads extraordinarily fast that sometimes fake news can become indistinguishable from accurate reporting. The extensive spread of fake news has the potential for extremely negative impacts on individuals and the society in general. In today’s day and age, due to the booming development of social media, fake news seems to be running rampant. One such scenario was witnessed during the 2016 United States Presidential election. When there are plenty of pieces of fake news, it becomes extremely difficult to detect whether a piece is real or fake. The objective of this project is to use news data collected about the 2016 US election and use machine learning to detect whether a piece of news is fake or real.
The dataset used in this project was downloaded from - https://s3.amazonaws.com/assets.datacamp.com/blog_assets/fake_or_real_news.csv.
NLP techniques were used to preprocess the text in the dataset. Cross Validation was performed to determine the best performing model.
GridSearch CV was employed for hyperparameter tuning. A Support Vector Machine model with an RBF kernel was finalled used for the classification process.
The accuracy obtained was 93.2%.
