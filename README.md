# Prediction-of-Product-Sales
##for DataScience Studies
**Author**: Jody Jacobs
### Business problem:
The purpose of of this project is to assist a retailer in understanding the properties of Products
and Outlets that play a crucial role in increasing Sales.
### Data:
Data Source: https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing
>This data set consist of 8523 rows and 12 columns

The dataset is as follows:
![image](https://github.com/Jody565/Prediction-of-Product-Sales/assets/138827084/0e6cd7e7-5f78-4e1a-85ce-c59f8c96b878)

## Methods

- I also cleaned the data by removing any missing data and removing all duplicates.
- During the exploratory Data Analysis a heatmap was done to explore the correlation between numeric features.
- A bar and box plot was done to understand which Outlet type generates the most Sales.
- A Histogram was also done to identify which products contributues to Sales.

## Results

#### Barplot
![image](https://github.com/Jody565/Prediction-of-Product-Sales/assets/138827084/2e161bc7-3167-4f30-942f-81b3ea0f2e08)

From the Barplot above we can see that the supermarket type 3 produces the most in sales.

#### Boxplot
![image](https://github.com/Jody565/Prediction-of-Product-Sales/assets/138827084/ca786c4c-58fe-41fb-88fa-791ee8df048e)

Above we can see the distribution of Sales between the different Outlet types. We can also see that the Supermarket Type 3
 has the highest mean as it produces the most sales.

#### Multivariate visualization plotting each Outlet Type vs. Item Outlet Sales
![image](https://github.com/Jody565/Prediction-of-Product-Sales/assets/138827084/9f574a4e-7587-4514-85d3-6ab50ff26183)

A multivariate visualizations showing the Outlet Type vs the Iten Outlet Sales

#### Histogram
![image](https://github.com/Jody565/Prediction-of-Product-Sales/assets/138827084/16202090-715c-4d54-a5fd-ff4b9292ee5a)

The graph above shows the Distribution of the items sold as we can see Fruits and vegatables are the highest items sold.

## Model

The following Machine Learning Models were used 

- Linear Regression Model

- Random Forest Model

- Tuned Random Forest Model


Report the most important metrics

- Linear Regression Model (Testing Set)

  * MAE = 805.621
  * MSE = 1,197,329.226
  * RMSE = 1,094.225
  * R^2 = 0.566
 
- Random Forest Model

  * MAE = 774.103
  * MSE = 1,252,845.362
  * RMSE = 1,119.306
  * R^2 = 0.546

- Tuned Random Forest Model

  * MAE = 736.057
  * MSE = 1,121,801.305
  * RMSE = 1,059.151
  * R^2 = 0.593
  
Refer to the metrics to describe how well the model would solve the business problem

-The Final Model Chosen was the Tuned Random Forest Regressor Model

  *For the testing set on the model, 59.3% of the variance in y was explained by x

  *The Mean Absolute Error was off by about $736.05

  *The Mean Squared Error was $1,121,801,30

  *The Root Mean Squared Error had a calculation of $1,059.15

The Tuned Random Forest model had the best scores but the model's performance still remains low and makes the model unreliable
as we take into account R2 and MAE scores.


## Recommendations:

- From the data presented we can ascertain that a higher number of Sales occur in Outlet Type 3, making that Outlet Type the
  more favourable Outlet Type for Customers.

- The Retailer could look at what makes Outlet Type 3 so sucessfull and try to adopt some of differences betweeen the Outlet
  types in an effort to increase Sales in the other Outlet Types

- The retailer could also looks at which products sell the most across which Outlet type and do specific target marketing
  for the Outlet type to increase sales and attract potential Customers.  

 
