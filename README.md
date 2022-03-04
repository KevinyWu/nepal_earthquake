# Nepal Earthquake Damage Prediction

<img src="https://github.com/KevinyWu/KevinyWu/blob/main/images/nepal.png" alt="drawing" width="350"/>

Using the building struture dataset from the [2015 Nepal Earthquake: Open Data Portal](http://eq2015.npc.gov.np/#/download), I applied machine learning algorithms with Scikit-Learn and Keras to predict building damage, using Seaborn, Matplotlib, and GeoPandas for visualizations. 
- data: contains original and split data in .zip files, which should be unzipped prior to running the notebook
- figures: contains high-resolution images of plots and tables pertaining to data exploration, feature engineering, and model selection and results
- geopandas_map: contains data to generate a choropleth of the affected districts using the GeoPandas library
- models: contains the best performing model for each algorithm
- [nepal_earthquake.ipynb](https://github.com/KevinyWu/nepal_earthquake/blob/main/nepal_earthquake.ipynb): contains full pipeline
  - Exploration of categorical and continuous features
  - Creation of new features
  - Cleaning, capping, transforming, and scaling data
  - Feature selection
  - Training and validating models using 5-fold cross-validation
    - Multiple Linear Regressing with EN Regularization
    - Random Forest 
    - K-Nearest Neighbors
    - Neural Network
  - Model selection and results

Findings are summarized in [Predicting_Building_Damage_Caused_by_the_2015_Gorkha_Earthquake.pdf](https://github.com/KevinyWu/nepal_earthquake/blob/main/Predicting_Building_Damage_Caused_by_the_2015_Gorkha_Earthquake.pdf).
