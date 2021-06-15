
The sole objective of the dataset is to classify the news as fake or true news. 
0 being true and 1 being fake.You can get the dataset from here https://www.kaggle.com/c/fake-news/data
Over here we have used TfidfVectorizer and PassiveAgressiveClassifier.

TfidfVectorizer- It is used to transform text into a meaningful representation
		of numbers which is used to fit machine algorithm for prediction.
PassiveAgressiveClassifier- It remains passive for a correct classification outcome,
		 and turns aggressive in the event of a miscalculation, updating 
		 and adjusting.


We took the dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier,
and fit our model. We ended up obtaining an accuracy of 96.27% in magnitude.