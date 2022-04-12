# Winter of Code , Machine Learning Division 
Repository for woc3 ML Essentials project by Brijesh kumar(20JE0279)
[WOC ML Essentials Report.pdf](https://github.com/bk167465/woc-ML-Essentials/files/6294485/WOC.ML.Essentials.Report.pdf)

Winter of Code is a platform where technology enthusiasts come together and contribute to tools that solve real-life problems. With the efforts of the whole Cyber Labs team, we are proud to announce WoC, the fourth Winter Open Source Hackathon of IIT(ISM) Dhanbad.

# 1. Exploratory Data Analysis
Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

● Explored different steps involved in EDA.  <br />
● Basic data exploration: missing values, shape, info.  <br />
● Analysed data through different plots (scatter plots, histograms ).  <br />
● Handling Outliers: Analysed data through Boxplot if any outliers may be present in values of features.  <br />
● Finding correlation between features.  <br />
● Univariate analysis: Label column is analysed by taking individual variable features into consideration.  <br />
● Bivariate analysis : Label column is analysed by taking both variable features into consideration.  <br />
● Normalization and Scaling : Scaling the values present in feature columns to the same range.It is very useful in case of algorithms based on principle of euclidean distance.  <br />

# 2. K-Means Clustering from Scratch
The K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.


● Splitted the data for the training and testing part. <br />
● Randomly initialized four points as centroids of clusters. <br />
● For the training part: clusters are assigned to the training dataseton the basis of Euclidean distance from randomly assigned centeroids. <br />
● To reach the correct position of centroids, the mean value of all the data points present in each cluster is assigned to the centroids. <br />
(Performed this step for multiple iterations until the position of centroids became almost constant). <br />
● Testing part: data points splitted for testing part is fitted in the model and predictions are made by model. <br />

# 3. Decision Tree from scratch
A decision tree is one of the supervised machine learning algorithms. This algorithm can be used for regression and classification problems — yet, is mostly used for classification problems. A decision tree follows a set of if-else conditions to visualize the data and classify it according to the conditions.  <br />

● The different aspects of Decision Tree : Nodes, Splitting, Branch, Entropy, Gini impurity, Information gain Types: Regressor and Classifier , Avoiding Overfitting. <br />
● Basic EDA is performed on given data to explore its differentaspects. <br />
● As features contain categorical string type values which will affect our algorithm during calculation so Label Encoder is used to avoid such issues. <br />
● Preparing the data: As data may contain some information which is irrelevant to our analysis . Such features are dropped. <br />
● Splitting the dataset for training and testing part (4:1). <br />
● Methods for entropy and information gain are defined in a class named Decision_tree. <br />

# 4. Implementing algorithm from Scikit Learn
Scikit-learn is an indispensable part of the Python machine learning toolkit at JPMorgan. It is very widely used across all parts of the bank for classification, predictive analytics, and very many other machine learning tasks.  <br />

● K-Means implementation: K-Means model is imported from “sklearn.cluster”. Dataset is splitted into training and testing parts . The Elbow plot is plotted for getting appropriate K-value. Training or Fitting of the model by training data.In the testing part cluster is predicted by model for testing data. <br />
<br />
● Decision Tree implementation: Basic EDA is performed .Label encoding. Preparing data by dropping features irrelevant to our analysis. Splitting dataset for training and testing. Importing Decision Tree Classifier from “sklearn.tree”. Training or fitting the model by training data. Predicting label for testing dataset . Evaluating the prediction of model by Classification report and Confusion Matrix. <br />

