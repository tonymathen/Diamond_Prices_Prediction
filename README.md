# Diamond Prices Prediction using Machine Learning

Diamond is a rare gem found naturally in the form of carbon on earth. The oldest diamonds are believed to crystallize 3.3 billion years ago with the first being discovered in India and then in Brazil. Unlike gold and silver whose prices mostly depend on their weight, the price of a diamond is determined by an array of factors like the cut, clarity, carat, and color known as the 4C’s of a diamond. A comparative analysis of regressive machine learning models mainly between trivial and ensemble models like Decision Trees, Random Forest, and XGBoost to find the model that can predict the price of the diamond most accurately is performed. This project is based on the classic Diamonds dataset containing the price and various attributes of almost 54,000 diamonds to train the machine learning models. From the performance parameter metrics and the analysis, the Random Forest algorithm proved to be the most optimal algorithm.


## Dataset 
The Diamonds dataset consists of total of 53,940 unique samples of diamonds consisting the attributes of carat, cut, color, clarity and dimensional attributes x (length), y (width), z (depth), table (width of top of diamond relative to widest point) and depth (total depth percentage). Cut, color and clarity are categorical values whereas carat, x, y, z, table and depth are numerical values.

```markdown
| Name                           | Values                                                   | Datatype    |
|--------------------------------|----------------------------------------------------------|-------------|
| Price                          | ($326--$18,823)                                          | Numerical   |
| Carat                          | 0.2 - 5.01                                               | Numerical   |
| Cut                            | (Fair, Good, Very Good, Premium, Ideal)                  | Categorical |
| Color                          | J (worst) to D (best)                                    | Categorical |
| Clarity                        | (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))  | Categorical |
| X (length)                     | (0 - 10.74) mm                                           | Numerical   |
| Y (Width)                      | (0 - 58.9) mm                                            | Numerical   |
| Z (Depth)                      | (0 - 31.8) mm                                            | Numerical   |
| Depth (total depth percentage) | (43 - 79) mm                                             | Numerical   |
| Table                          | (43 - 95) mm                                             | Numerical   |
```

## Exploratory Data Analysis
- Data Cleaning
- Correlation Analysis
- Outlier Treatment

## Model Building
- Decision Tree
- Random Forest
- XGB Reggressor

## Results
<p align="center">
  <img src="https://github.com/tonymathen/tonymathen/blob/main/Images/accuracy_models_diamond_prices_prediction.png" width="600"/>
</p>

Our analysis and experiments conclude that among supervised learning algorithms like Decision Tress, Random Forests, and XGBoost , Random Forest algorithm performed better and is the most suitable algorithm for diamond price prediction concerning all the performance metrics. Different techniques of outlier removal and more significant hyperparameter tuning could further help in the accurate price prediction of diamond.
