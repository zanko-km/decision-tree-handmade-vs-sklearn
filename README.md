# Decision Tree Handmade vs sklearn

## Project Overview

The goal of this project is to **predict whether a customer will wait at a restaurant** based on various features. The prediction is performed using **Decision Trees**.

## Dataset Features

The dataset includes the following features:

- **Alternate**: Whether there is a suitable alternative restaurant nearby (Yes/No).  
- **Bar**: Whether the restaurant has a comfortable waiting area at the bar (Yes/No).  
- **Fri/Sat**: Whether the day is Friday or Saturday (Yes/No).  
- **Hungry**: Whether the customer is hungry (Yes/No).  
- **Patrons**: Number of people present at the restaurant (`None`, `Some`, `Full`).  
- **Price**: Price range of the restaurant (`$`, `$$`, `$$$`).  
- **Raining**: Whether it is raining outside (Yes/No).  
- **Reservation**: Whether a reservation has been made (Yes/No).  
- **Type**: Type of restaurant (`French`, `Italian`, `Thai`, `Burger`).  
- **WaitEstimate**: Estimated waiting time (`0-10`, `10-30`, `30-60`, `>60` minutes).  

## Methodology

- **Decision Tree Implementation**:  
  - Manual decision tree (from scratch)  
  - Decision tree using a library (e.g., `scikit-learn`)  

**Conclusion:**  
When using a library, features that are not binary (e.g., `Patrons`, `Type`, `Price`) are **one-hot encoded**, which results in a tree structure that differs from the manual implementation.
