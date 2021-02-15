# [Project 4: Potential Driven Stuedents App]()

Potential Driven Students(PDS) is a student structure established in the University Of Limpopo by students(I am one of them) in the school of mathematics and computer sciences. PDS assists fellow students in the school of mathematics and computer sciences with their modules in terms of extra classes. However, before getting help from this organization, the student should first fill a manual form and then deposit some fees in the organization's bank account. This manual process for the enrollment of students is an inconvenience in many ways. Among these inconveniences, one of them is the poor data management of the students.

PDS app is built(by Marumo AM) to champion most of these challenges encountered by the organization. The app allows students to enroll and pay on their mobile smartphones. The app is built with flutter, stripe payment gateway, and firebase.

# [Project 3: To Vaccinate or Not to Vaccinate: It’s not a Question by EXPLORE Data Science Academy](https://github.com/Abelmarumo/Vaccination_hackathon)

Although it may be many months before we see COVID-19 vaccines available on a global scale, it is important to monitor public sentiment towards vaccinations now and especially in the future when COVID-19 vaccines are offered to the public. The anti-vaccination sentiment could pose a serious threat to the global efforts to get COVID-19 under control in the long term.

The objective of this challenge is to develop a machine learning model to assess if a Twitter post related to vaccinations is positive, neutral, or negative. This solution could help governments and other public health actors monitor public sentiment towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs across the world.

We started off by exploring the text data, preprocess the text data using NLP tools and then trained base models. Lastly, we tried tuning hyperparameters to try and improve the performance of the models. Logistic regression out performed other models such as LinearSV, SVC, MultinomialNB, Xgboost, and Random forest.


# [Project 2: Climate Change Belief Analysis](https://github.com/Abelmarumo/Classification_Predict_EDSA)

Companies are looking to create products and services that are environmentally friendly. They would thus like to understand their consumers' view on climate change. To address this, we are going to create Machine Learning models that are able to classify whether or not a person believes in climate change, based on their novel tweet data. Correct classification of a tweet will help companies understand consumer sentiment, which will further guide their business strategies.

We started off by exploring the text data, preprocess the text data using NLP tools and then trained base models. Lastly, we tried tuning hyperparameters to try and improve the performance of the models. Our top five models are the LinearSVC, SVC, Random forest, logistic regression and a sequential neural network that we have trained. The performance metric that we were more interested in was the weighted average f1 score. The Built models are to be deployed to a Streamlit application which can be used remotely through the use of an AWS ec2 instance.


# [Project 1: Sendy Logistics Challenge by EXPLORE Data Science Academy](https://github.com/Abelmarumo/Regression_predict_EDSA)

Logistics in Sub-Saharan Africa increases the cost of manufactured goods by up to 320% and the inability to communicate an accurate delivery time has a negative impact on the relationship between the company and its customers. In reality, economies are better when logistics is efficient and affordable. To that end, Sendy has intiated a project aimed at accurately predicting the estimated time of delivery of orders, from the point of driver pickup to the point of arrival at final destination. The company has provided historical data with which to develop a solution to the logistics problem with the goal of ensuring effective communication, improved customer relations, cost-efficient services, improved resource management, informed order scheduling and reduced costs for business by finding an effective way of predicting accurate time of arrival to esure that businesses are being better with good logistics.

We have developed an LGBM regressor model and optimal features to realise this solution. This model has been tested on data provided by Sendy and has produced a best root mean square error score of 753.58. The solution will enable Sendy to realise cost savings, and ultimately reduce the cost of doing business, through improved resource management and planning for order scheduling.
