# Movie-Success-Prediction
### Objective:
The primary aim of this project is to utilize advanced data mining techniques and appropriate tools to predict the success of movies. Through this analysis, we intend to assess and compare the scalability, efficiency, and applicability of different data mining methods in real-world scenarios. By completing a comprehensive data mining cycle and analysis, we aim to acquire practical skills and demonstrate our ability to address real-world data mining challenges related to predicting movie success.

### Dataset Background:
This project's goal is to develop a predictive model for movie success, taking into account various factors such as directors, actors, and plotlines. While renowned directors and actors may impact box office revenue, they do not guarantee a high IMDb score. Using a Kaggle dataset that contains 28 variables for 5043 movies spanning a century and multiple countries, with 2399 unique director names and numerous actors/actresses, the main challenge lies in effectively leveraging these predictors to create an advanced predictive model for IMDb scores.

### Approach:
In this project, we will categorize the target variable, "imdb_score," into three classes based on movie success levels. Movies with IMDb scores between 1 and 3 will be classified as "FLOP," movies with scores between 3 and 6 as "AVG" (average), and movies with scores between 6 and 10 as "HIT."
The objective is to utilize this categorical target variable to train machine learning models capable of accurately predicting a movie's success category based on various predictor variables available in the dataset. This categorization enables us to frame the problem as a multi-class classification task and employ appropriate evaluation metrics to assess model performance.

### Results:

- Category	    Flop	Average	  Hit 	Accuracy
- Random Forest	0.98  	0.85  	1.0	  0.995
- Gradient Boosting	0.89	1.0	    0.98  	0.998

### Conclusion:
When comparing the performance of two classifiers, Gradient Boosting and Random Forest, we observed interesting differences. The gradient boosting classifier achieved almost perfect accuracy by classifying the accuracy in general as 99.8% for all categories. On the other hand, the random forest classifier demonstrated high accuracy of approximately 99.56%, providing more balanced predictions. While the gradient boosting model might raise concerns due to its perfect classification, the random forest's accuracy, along with its balance, makes it a more reliable choice for making predictions in this context.
