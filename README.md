# Network-designs-for-house-price-prediction-using-ML
Code used for master thesis "On the comparison of network design alternatives for house price prediction using machine learning".

### Avg node degree
Calculates the average node degree of a network.

### Calculate SL geodistances
Calculates the straight-line geodistance between each pair of houses.

### Calculate dist_to_center
Calculates the distance to the city center of Seattle from each house, and adds it to the dataset.

### Calculate road distances
Calculates the road distances between each pair of houses using OSMR.

### Calculate similarities
Calculates the Cosine feature similarities between each pair of houses.

### Descriptive statistics
Some descriptive statistics on the network features "Node degree" and "Average price of all neighbors".

### Features Feat-cutoff netw
Adds network features to the Feat-cutoff network.

### Features Feat-kNN netw
Adds network features to the Feat-kNN network.

### Features Road-cutoff netw
Adds network features to the Road-cutoff network.

### Features Road-kNN netw
Adds network features to the Road-kNN network.

### Features SL-cutoff netw
Adds network features to the SL-cutoff network.

### Features SL-cutoff netw with PageRank
Adds network features to the SL-cutoff network, including PageRank.

### Features SL-kNN netw
Adds network features to the SL-kNN network.

### Filtering data on prices
Filters dataset to only include houses with zip code of Seattle and house price under 1 million dollars.

### Filtering data on zipcode
Filters dataset to only include houses with zip code of Seattle.

### GraphSage
GraphSage model.

### Map of Seattle
Plots all houses of the dataset on a map of Seattle.

### Multivariate regression
Multivariate regression model.

### Pickle Feat-cutoff netw
Creates a pickle file of the Feat-cutoff network, used as input for GraphSage model.

### Pickle Feat-kNN netw
Creates a pickle file of the Feat-kNN network, used as input for GraphSage model.

### Pickle Road-cutoff netw
Creates a pickle file of the Road-cutoff network, used as input for GraphSage model.

### Pickle Road-kNN netw
Creates a pickle file of the Road-kNN network, used as input for GraphSage model.

### Pickle SL-cutoff netw
Creates a pickle file of the SL-cutoff network, used as input for GraphSage model.

### Pickle SL-kNN netw
Creates a pickle file of the SL-kNN network, used as input for GraphSage model.

### Random Forest
Random Forest model.

### XGBoost
XGBoost model.

### my_filtered_dataset.csv 
KC_house_data via https://www.kaggle.com/datasets/astronautelvis/kc-house-data .
