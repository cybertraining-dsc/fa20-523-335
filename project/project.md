Introduction:
Crime is a difficult problem that we face everywhere in the United States; the police respond to hundreds of thousands of calls across the country of all different types. As individuals, we tend to view crime in a very broad sense, basing our opinions on crimes that we hear about or see on the news, or overall crime “waves” or trends we hear about. However, we have a very incomplete aspect of a much larger puzzle. Crime has many underlying causes, reasons, and patterns that are difficult to notice without an analysis of specific data points that we cannot make without make as individuals. In this paper, I wanted to analyze crime more thoroughly in a dataset with context to my life to highlight specific trends or patterns that are being exhibited. To conduct this analysis, I chose a dataset released by the City of San Jose, my hometown, that recorded all crimes and their relevant data points for the entirety of 2020, along with a similar dataset for 2019 and 2018.
This dataset records all crimes committed in the San Jose greater area, with a separate dataset recorded for each year. I’ll primarily be analyzing the 2020 dataset for this project, as it is the most relevant and current possible set available, and it is updated daily. Each element represents one crime; multiple calls for the same crime are represented as one element in the dataset. There are several attributes listed with each crime, which help us paint a picture and generate some questions that might help reveal trends and patterns within the data. The dataset starts with a CDTS column, which uniquely identifies each crime with a serial number using a police system tracker. The next column provides Electronic ID numbers for each element. There are four main attributes to this dataset; start date and time, type, response, and location. The next attribute is a start date / report date, which lists the day the infraction occurred or was reported. For the 2020 dataset, this spans everyday from January 1st to November 2nd. The dataset also provides us with an offense time attribute, which has the specific time that the offense was committed or called in to the dispatch. The next attribute is call type, which gives us more details on the situation for each crime element on the dataset. These range from disturbances and public intoxication calls to firearms being discharged and hit and runs. This attribute is also paired with an attribute that provides the police acronyms that these descriptions stem from, which should make it easier to categorize and sort the crimes by type. The next is the response attribute; listed as final dispatch, it records the aftermath and the polices reaction to the crime. This ranges from calls that didn’t require official reports, call cancellations, citations, and arrests. 

Python Library
https://github.com/yhat/pandasql/
https://scikit-learn.org/stable/
https://scikit-learn.org/stable/supervised_learning.html#supervised-learning
learn.org/stable/modules/svm.html#regression
process raw data
group data
create linear regression algorithm
visualization
steps
•	Group the data
•	Linear regression alg
•	

Do the police react more harshly in certain areas for the same crimes?
What 7 dates have the worst criminal offenses?
What is the most common crime for each different month?
Are certain areas more prone to certain types of crime? What is the underlying cause for this?
What crimes are common in the San Jose area? Have these change in the last 5 years?
How often do reports lead to arrests, and for which crimes is this the most common?
