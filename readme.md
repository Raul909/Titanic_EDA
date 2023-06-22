# Titanic EDA
--------------
## Import the Libraries

- First I have imported the libraries that needed to be imported to do data manipulation(panda),perform calculations(numpy) and for data visualization(matplotlib)


## Load the Data Set
- This show the head of the dataset, the first 6 tuples/rows of the titanic dataset

if we execute this command ![df.head](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20000722.png)


## Data Cleaning and Preprocessing

- Then I have  processed and cleaned the dataset by filling missing values of the age in the dataset with mean

- Then I have done feature engineering that is merged two datasets and created a new more readable dataset family size


## Data Visualization

- ![Age Distribution](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20000756.png)

- ![Fare vs Age](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20000804.png)

- ![Survival Count](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20000813.png)


## Correlation Analysis

![Correlation Matrix](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20001831.png)


## Perfomed Calculations

Calculated the mean age,median age using *np.mean* and *np.median* respectively and then calculated the standard deviation of age and fare using *np.std* 

![](https://github.com/Raul909/Titanic_EDA/blob/main/screenshots/Screenshot%202023-06-23%20000902.png)