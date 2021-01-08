# Facebook_Live
Predicting user behavior from facebook live data


	Hypothesis or project topic
  
o	To characterize user behaviors of Facebook live as a direct selling tool and             
o	To assess the effectiveness of live streaming as compared to other Facebook contents
o	Prediction based on dataset
o	Classification problem

	Available data sources 
  
https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set
https://docs.google.com/viewer?a=v&pid=sites&srcid=dW10LmVkdS5wa3xkdHNjaXxneDpjYmM5YWUyNWJjOGE1YTA


	Description
  
Direct selling refers to the process of person-to-person selling of a consumer product or service, in an environment that is not a permanent retail location (Duffy 2005;). It is the most relational of all sales methods, and now it was reemerged in the social networking sites via live streaming. At an operational level, live streaming allows customers to observe the seller’s facial and verbal expression, their personality, and physical evidence including their house/store, their products, and to interact with sellers in real time with more personal touch that is lost in regular online marketing practices. A seller can also receive feedback via comments and emoticons. Thus, more communication senses (hearing, sight, movement) can be observed than the typical e-commerce, and should elicit more responses from customers than other contents (e.g. text, photo). Strategically, direct selling can be used to gain an access to a market. With this role, live streaming can be used by sellers to reach new customers when viewers invite others to join the live party. Tactically, live streaming sellers have to select selling tactics to achieve their business objective including consideration of the type of salesperson, the styles of salesperson, and their activities. Based on these operational, strategic, and tactical perspectives of direct selling (Peterson and Wotruba 1996), we expect that live streaming would generate more responses and share than, and different selling styles and activities from existing social commerce practice.


	Data Set
  
Thailand has the world’s highest proportion of shoppers buying directly from social media (PwC’s 2016) and also top the world ranking for the proportion of live streaming domestic viewers (Raman, Tyson, and Sastry 2018) so we extracted the data from Thai Facebook sellers selling fashion and beauty products, popular products sold online. Through an exhaustive data analysis of all content posted by 11 of Thailand’s foremost fashion retail and cosmetics direct sellers on Facebook, totalling between 74,000 and 380,000 followers, we seek to analyse the impact of Facebook Live on three statistical aspects of buyer-seller interactions: variability, seasonality, and outliers. We consider engagement for posts of a different nature (video, photos, statuses, and links). Engagement metrics consist of comments, shares, and reactions (Malhotra, Malhotra, and Kubowicz 2013) within which we distinguish traditional “likes” from the recently introduced reactions smileys (e.g. “love”, “wow”, “haha”, “sad” and “angry”) reflecting more varied sentiments (SandovalAlmazan, and Valle-Cruz 2018). For each Facebook page, the time-horizon of the study is broken down according to the date of first usage of Facebook Live for direct selling, into a before and after periods.


	Methodology
  
We followed the standard workflow of any data-science problem that was taught in the class, it was comprised of first reading the dataset in the .ipynb notebook. The tools we used for the project were
	Anaconda
  Jupyter
	Python 3.7.x
	Libraries
  Numpy
	Pandas
	MAtplotlib
	Seaborn
	Scikit learn
After reading the data we performed following steps to reach the conclusion 


	Data Exploration

In this step we just analyzed the raw data. This step was basically to make the initial sense of data and understand the features. And make the use of given data. We used different numpy and pandas functions to explore basic stats of the data.


	Data Visualization
Visualization was best in proving which features made the most impact on the data set. And which features were to be removed. We Used 

	Box Plots of multiple features
	Bar Plots of different features
	Co-relation stable 


	Data Preprocessing
In the step of preprocessing we used removed many features which were not necessary in the selected features and they were tinkering a lot with the prediction results. We removed the date, NaN values.
The features which were mostly zeroes (75%).

Then we engineered a new Feature based on the analyzing data and information we gained and made sense to our minds.

	Modelling(ML)
When the dataset was prepped we applied different algorithms. We used following Algorithms in the 70/30 train test model.

	Decision Tree Classifier
	SVM
	Logistic Regression
	K Neighbors Classifier


	Prediction metrics(results)

1.	The Decision Tree
	       Training Accuracy:  93.9412360689
	       Testing Accuracy:  83.1678486998

2.	SVC MODEL
		Training Accuracy 92.4822695035
		Testing Accuracy 68.841607565

3.	Logistic Regression MODEL
	       Training Accuracy 80.6281661601
	       Testing Accuracy 80.9929078014

4.	K Neighbors Classifier
	        Training Accuracy 85.7750759878
	        Testing Accuracy 84.0661938534

References
Facebook Live as a Direct Selling Channel Nassim Dehouche, Mahidol University International College Apiradee Wongkitrungrueng, Mahidol University International College
