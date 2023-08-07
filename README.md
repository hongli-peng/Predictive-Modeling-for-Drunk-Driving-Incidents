# Predictive-Modeling-for-Drunk-Driving-Incidents
The primary goal of this project is to compare and evaluate the predictive performance of Random Forests, Linear Models, and Deep Learning Models. The focus is to predict the percentage of fatal accidents involving drunk driving using US demographic data.

# Datasets:
- `Raw State Data (raw_state_data_drunk_driving.csv)`: This dataset contains various demographic measures across all 50 US States, such as percentage of rural population, median income, total number of car accidents, and obesity rate. The target variable is the percentage of fatal accidents involving drunk driving.

Note: Unfortauntely, making predictions on a dataset with only 50 points is quite difficult. Thus, we will also consider a second dataset.
- `Census Tracts Data (census-tracts-dataset.csv)`: This extended dataset has 20,000 datapoints, created using clustered census tracts that resemble the demographic distributions of the 50 US States. It's created through a bootstrapping process and might contain imputed values and inconsistencies (e.g., demographic percentages totaling over 100). These anomalies are considered as byproducts of the bootstrap process and are not a concern for the analysis.
