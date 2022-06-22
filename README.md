# Wine-Quality-Prediction
Predicting the Quality of Wine using Machine Learning Algorithms for Regression Analysis, Data Visualizations and Data Analysis

# Abstrat

Wine classification is a difficult task since taste is the least understood of the human  senses. A good wine quality prediction can be very useful in the certification phase, since currently the sensory analysis is performed by human tasters, being clearly a subjective approach. An automatic predictive system can be integrated into a decision support system, helping the speed and quality of the performance. Furthermore, a feature selection process can help to analyze the impact of the analytical tests. If it is concluded that several input variables are highly relevant to predict the wine quality, since in the production process some variables can be controlled, this information can be used to improve the wine quality. Classification models used here is Random Forest.

# Dataset

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult:  reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g., there is no data about grape types, wine brand, wine selling price, etc.)

1)fixed acidity
2) volatile acidity
3) citric acid
4) residual sugar
5) chlorides
6)free sulfur dioxide
7)total sulfur dioxide
8)density
9)pH
10) sulphates
11) alcohol
Output variable (based on sensory data):
12)quality (score between 0 and 10)

# Algorithm Applied

### Random Forest Classifier:

It is one of the most powerful Supervised Machine Learning Algorithm. It is can used for equally for regression and classification problem. It works well with default hyper-parameters.It is similar to decision tree; it builds multipledecision trees and combine them all together.It gives more accurate and stable predictions. Whether we’ve got a regression or classification problem, Random Forest Classifier is an applicable model for our needs. It can handle numerical features, categorical features, and binary features. Before using this algorithm, pre-processing is needed that needs to be done. It is not necessary for the data to be rescaledor changed.

# Acknowledgement

This dataset is available on the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality ( I am not the owner of this dataset ).

# Reference 

• Benjamin, B.A. and Podolny, J.M. (1999). Status, quality, and social order in the California wine industry. Administrative Science Quarterly, 44, 563–589.CrossRefGoogle Scholar
• Cicchetti, D.V. (2004a). Who won the 1976 blind tasting of French Bordeaux and U.S. cabernets? Parametrics to the rescue. Journal of Wine Research, 15, 211–220.CrossRefGoogle Scholar
• Cicchetti, D.V. (2004b). On designing experiments and analysing data to assess the reliability and accuracy of blind wine tastings. Journal of Wine Research, 15, 221–226.CrossRefGoogle Scholar.
• Cicchetti, D.V. (2006). The Paris 1976 wine tastings revisited once more: comparing ratings of consistent and inconsistent tasters. Journal of Wine Economics, 1, 125–140.CrossRefGoogle Scholar.
• Hulkower, N. (2009). The judgment of Paris according to Borda, Journal of Wine Research, 20, 171–182.CrossRefGoogle Scholar.
• Schnabel, H. and Storchmann, K. (2010). Prices as quality signals: evidence from the wine market. Journal of Agricultural & Food Industrial Organization, 8, 1–21.CrossRefGoogle Scholar.
