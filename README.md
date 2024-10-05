# SpaceXCapstone
A capstone project from IBM's Data Science Professional Certificate Course
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch.

## Methodology 📄
### 1. Collecting Data
Here, we will be collecting the data through SpaceX's API in the first part. The second part will utilize web scraping using BeautifulSoup to extract data from https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches.

### 2. Data Wrangling
In the second step of the model, we will be performing data wrangling such as feature engineering for 'Class', which holds a binary value. 0 meaning the mission outcome failed to land, while 1 means that the mission outcome has successfully landed.

### 3. Exploratory Data Analysis (EDA) with SQL
Here we will utilize SQL to gather insights about the data.

### 4. Exploratory Data Analysis (EDA) Visualization
Here we will visualize the data gathered through EDA using using numerous visualization libraries like seaborn plots, while performing feature engineering (one-hot encoding) to transform categorical data into binary.

### 5. Interactive Data Visualization
Here we will further visualize the data using an interactive medium such as Folium and Dash to create a user-friendly dashboard.

### 6. Predictive Analysis
We will train machine learning models (LinReg, KNN, Decision Tree and SVM) and test them, utilizing GridSearchCV to get the best parameters values to achieve a higher performance.

