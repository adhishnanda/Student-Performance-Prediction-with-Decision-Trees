# Student-Performance-Prediction-with-Decision-Trees
In this section, we're going to use decision trees to predict student performance using the students, past performance data. We'll use the student performance dataset, which is available on the UC Irvine Machine Learning repository. Our final goal is to predict whether the student has passed or failed. The dataset contains the data of about 649 students, with and 30 attributes for each student. The attributes formed are mixed categorically 􀁢 word and phrase, and numeric attributes. These mixed attributes cause a small problem that needs to be fixed. We will need to convert those word and phrase attributes into numbers. The following screenshot shows the first half of the attributes from the data:

   ![image](https://user-images.githubusercontent.com/30040796/148901699-585f5842-9f33-4efe-b786-50fdc15d5a5c.png)

You must have noticed how some of the attributes are categorical, such as the name of the school; sex; Mjob, which is the mother's occupation; Fjob, which is the father's occupation; reason; and guardian. Others, such as age and traveltime, are numeric. The following screenshot shows the second half of the attributes from the data:

![image](https://user-images.githubusercontent.com/30040796/148902012-91620305-3c21-4d51-a581-1eb99acd3e20.png)

It is clear that some of the attributes are better predictors, such as absences and the number of past failures, while others attributes are probably less predictive, such as whether or not the student is in a romantic relationship or whether the student's guardian is the mother, father, or someone else. The decision tree will attempt to identify the most important or predictive attributes using this information gain provided. We'll be able to look at the resulting tree and identify the most predictive attributes because the most predictive attributes will be the earliest questions.
