
#
#### OVERVIEW


A Fast Moving Consumer Goods (FMCG) company entered into the instant noodles business two
years back. Their higher management has noticed that there is a mismatch in the demand and
supply. Where the demand is high, supply is pretty low and vice-versa which results in a loss in
inventory cost and ultimately loss to the company. Hence, the higher management wants to
optimize the supply quantity in each and every warehouse in the entire country.
Create a model using : [Train dataset](https://drive.google.com/file/d/1eodz3D2p9HZYKzEJYBpyuDGek-BH0dbY/view)

#
#### GOALS
The objective of this exercise is to build a model, using historical data that will determine an
optimum weight of the product to be shipped each time from the respective warehouse.
1. Focus on all steps of data science (EDA, data processing, model, evaluation, charts)
2. Highlight any trend in data, deep insight, novel steps that you take
3. Highlight next steps and improvements.
4. Apply 5 to 6 machine learning algorithms and evaluate it using : [Test dataset](https://drive.google.com/file/d/11V08gQiXAHHz2-dy3FX6pbY21I9x9wle/view)

#

### Data Dictionary
#####

| Variable                    | Description                                                   |
|-----------------------------|---------------------------------------------------------------|
| Ware_house_ID               | Unique Warehouse id where product is prepared for dispatch.    |
| WH_Manager_ID               | Manager Id present in the warehouse.                           |
| zone                        | Zone of the Warehouse.                                        |
| WH_regional_zone            | Regional Zone of the warehouse.                                |
| num_refill_req_l3m          | Reﬁlling request received by the warehouse in the last 3 months.|
| transport_issue_l1y         | No. of transport issued for warehouse in last 1 year.         |
| Competitor_in_mkt           | No. of competitors in the market.                              |
| retail_shop_num             | Number of retail shops who sell noodles produced by the warehouse.|
| wh_owner_type               | The warehouse is owned by the company or it is on rent.        |
| distributor_num             | No. of distributor who works between warehouse and retail shops.|
| flood_impacted              | Is the warehouse in a ﬂood impacted area or not.              |
| flood_proof                 | Flood_proof: Warehouse is having ﬂood proof indicator.         |
| electric_supply             | Does the warehouse have proper electric supply along with some power backup.|
| dist_from_hub               | Distance from the warehouse to production hub.                 |
| workers_num                 | Number of workers in the warehouse.                            |
| wh_est_year                 | Warehouse establishment year.                                  |
| storage_issue_reported_l3m  | Storage issues reported by the warehouse in the last 3 months. |
| temp_reg_mach               | Warehouse having temperature regulating machine indicator or not.|
| approved_wh_govt_certificate| Type of approval warehouse having been issued by government.    |
| wh_breakdown_l3m            | Number of times the warehouse faces the breakdown in the last 3 months.|
| product_wg_ton              | Product weight.                                                |




## What i did in this Project
- Exploratory Analysis: Conducted an in-depth examination of the dataset, analyzing its structure, distributions, and attributes to gain a comprehensive understanding.
- Creation of New Attributes: Engineered new features based on existing data attributes, enhancing the dataset's predictive capabilities.
- Data Preprocessing: Cleaned and preprocessed the dataset, addressing missing values, outliers, and standardizing or normalizing features as necessary.
- Exploratory Data Analysis (EDA): Explored interrelationships among variables, identified trends, patterns, and outliers, extracting crucial insights.
- Visualization: Utilized diverse visualization techniques to depict data distributions, correlations, and trends effectively.
- Label Encoding: Converted categorical columns into numerical format using label encoding for better model compatibility.
- Correlation Analysis: Investigated correlations among attributes to comprehend the connections between different features.
- Train-Test Split: Separated the dataset into training and testing sets for model training and evaluation purposes.
- Algorithm Selection: Opted for various regression algorithms (Linear Regression, Decision Trees, Random Forest, Gradient Boosting, Support Vector Machine, XGBoost) to construct predictive models.
- Model Training & Evaluation: Trained models on the training data, refined hyperparameters, and evaluated performance using key metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared scores.
- Visualization of Model Performance: Generated scatter plots to compare model predictions against actual values, providing insights into algorithm behaviors.



## Algorithms Used in the Project

1. Linear Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting
5. Support Vector Machine
6. XGBoost

---

## Evaluation Metrics

### Linear Regression
- **Mean Absolute Error (MAE):** 1299.9551
- **Mean Squared Error (MSE):** 3119596.9403
- **R-squared Score (R2):** 0.9770

### Decision Tree
- **Mean Absolute Error (MAE):** 771.2642
- **Mean Squared Error (MSE):** 1299467.3815
- **R-squared Score (R2):** 0.9904

### Random Forest
- **Mean Absolute Error (MAE):** 690.0176
- **Mean Squared Error (MSE):** 903888.7051
- **R-squared Score (R2):** 0.9933

### Gradient Boosting
- **Mean Absolute Error (MAE):** 677.0715
- **Mean Squared Error (MSE):** 805277.1301
- **R-squared Score (R2):** 0.9941

### Support Vector Machine
- **Mean Absolute Error (MAE):** 9612.9720
- **Mean Squared Error (MSE):** 135583288.0584
- **R-squared Score (R2):** 0.0001

### XGBoost
- **Mean Absolute Error (MAE):** 654.6813
- **Mean Squared Error (MSE):** 778611.8524
- **R-squared Score (R2):** 0.9943

### Conclusion:
- Highlighted the strength of Gradient Boosting and XGBoost models in managing inventory dynamically due to their accuracy and robust performance. Proposed - -enhancing the Support Vector Machine by refining parameters to further optimize supply chain strategies.
