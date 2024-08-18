# Blueberry Yield Prediction

## Problem Understanding

### Business Problem

Predicting the yield of wild blueberries is a significant challenge for farmers and agricultural planners. The yield of blueberry crops can be influenced by numerous factors such as weather conditions, soil quality, and pest and disease pressure. An accurate prediction model is essential to help farmers make informed decisions about harvesting and marketing their produce. This predictive capability also allows farmers to plan for future seasons, manage resources more efficiently, and maximize their yield and profit.

### Dataset Description

The dataset used in this project contains the following columns:

1. `clonesize`: Size of the blueberry clone.
2. `honeybee`: Number of honeybees observed.
3. `bumbles`: Number of bumblebees observed.
4. `andrena`: Number of Andrena bees observed.
5. `osmia`: Number of Osmia bees observed.
6. `MaxOfUpperTRange`: Maximum temperature of the upper range.
7. `MinOfUpperTRange`: Minimum temperature of the upper range.
8. `AverageOfUpperTRange`: Average temperature of the upper range.
9. `MaxOfLowerTRange`: Maximum temperature of the lower range.
10. `MinOfLowerTRange`: Minimum temperature of the lower range.
11. `AverageOfLowerTRange`: Average temperature of the lower range.
12. `RainingDays`: Number of raining days.
13. `AverageRainingDays`: Average number of raining days.
14. `fruitset`: Proportion of flowers that set fruit.
15. `fruitmass`: Mass of the fruit.
16. `seeds`: Number of seeds per fruit.
17. `yield`: The target variable representing the yield of blueberries.

### Requirements

The goal of this project is to develop a machine learning model that accurately predicts the yield of wild blueberries based on the factors listed above. This project involves several key steps:

1. **Define Problem / Problem Understanding**:
    - Clearly define the business problem and requirements.
    - Understand the factors affecting blueberry yield.

2. **Literature Survey**:
    - Research existing methods and models used for crop yield prediction.
    - Document findings to guide the development of the model.

3. **Social or Business Impact**:
    - Discuss the potential social and economic benefits of accurate yield predictions.

4. **Data Collection & Preparation**:
    - Collect the relevant dataset containing information about weather, soil quality, pest and disease pressure, and blueberry yields.
    - Prepare and clean the dataset for analysis.

5. **Exploratory Data Analysis (EDA)**:
    - Perform descriptive statistical analysis and visualizations to understand data distributions and relationships.

6. **Model Building**:
    - Train and evaluate multiple machine learning models using the dataset.
    - Perform hyperparameter tuning to improve model performance.

7. **Model Deployment**:
    - Save the best-performing model.
    - Develop a web application using Flask to allow users to input data and receive yield predictions.

8. **Project Demonstration & Documentation**:
    - Record a video explaining the project and its steps.
    - Document the entire project process step-by-step.

By following these steps, we aim to create a robust predictive model that will assist farmers in making data-driven decisions, ultimately leading to better management of blueberry crops and increased productivity.
