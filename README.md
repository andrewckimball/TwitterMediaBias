# Twitter Media Bias Project

As part of my final project for my Predictive Analytics course, I developed a fully automated machine learning pipeline, including data importing, data preparation, data segregation, model training, model evaluation, and model deployment.

My thesis was that machine learning models would be able to perform well in distinguishing the Twitter styles of various American media outlets:  CNN, MSNBC, FoxNews, Newsmax, Democracynow, Wall Street Journal, New York Times, Vox, New York Post, and Breitbart News. By scraping thousands of tweets from each of the aforementioned media outlets, I was able to create an automated pipeline to clean and normalize the data and run the cleaned data through 6 different classification machine leanring models.

After training, the two best performing models (Extreme Gradient Boosting Classifier and Random Forest Classifier) were able to predict the correct media account with over 60% accuracy -- which is 6 times better than the baseline accuracy of 10%. This confirmed my intuition that machine learning models would be able to detect unique differences in reporting between some of the United State's largest media organizations, thus proving some sort of bias/variance in style, reporting content, images, and grammar among media coverage on social media.

My pipleline used extensive web scraping (leveraging the Twitter Developer API and Imagga's Image Recognition API) to gather the data, and I used Scikit Learn's machine learning API for the training and testing. 
