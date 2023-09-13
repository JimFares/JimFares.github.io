# College Football Outcome Prediction

## Project Overview

Welcome to the College Football Outcome Prediction project! The primary objective of this project is to leverage historical data from college football games (NCAA) to develop a predictive model. The goal is to create a system that can accurately forecast the results of future college football games, i.e. predicting the point spread. This predictive capability has the potential to inform profitable wagering decisions, specifically those related to the spread. This project represents the collaborative efforts of a team of individuals passionate about sports and data analytics.

**Note:** As this project involves proprietary models, the code for the optimization model itself will not be shared in this repository to maintain confidentiality and competitive advantage.

## Repository Structure

In this repository, you will find:

1. **Data:** This folder contains a dataset pertaining the 2016, 2017 and 2018 NCAA season used for training and testing the prediction model, as well as the 2019 season dataset used to test the model even further. These datasets include historical college football game data, which serves as the foundation for our predictive analysis and provide to us a better understanding of how well our model really is. The data was organized to use a single row to hold all the information from a single game including the information pertaining to both teams playing in the game. The key variables that were analyzed can be split into two categories: Game Information and Betting Information.

2. **Code:** While the specific model implementation is kept confidential, you will find code snippets and scripts related to model creation (CART and Random Forests), model evaluation and model tuning. This repository provides insights into parts of the data science pipeline and methodology used to create the predictive model. Steps pertaining data preprocessing, feature engineering and EDA were previously done, and the features in the dataset were assessed in order to select the ones that should be used in the model.

3. **Results:** Within this folder, you will discover summary reports, charts, and insights derived from the model's predictions. These results help us assess the model's accuracy and its potential for profitable outcomes.

4. **Documentation:** Detailed documentation and explanations of the project's objectives, methodologies, and findings can be found here. This section provides transparency about the project's approach and outcomes.

## Methods

In this section, I will quickly explain the methods used for this project. Two main methods were used to construct our final model. 

First, we created a probability prediction model, which calculates the percent chance that each side of the bet wins for every game. The probability prediction model is divided into three sub-parts: evaluating the necessary features for each betting model, training the model using CART as well as improving the findings with Random Forest, and optimizing the model’s accuracy using cross-validation. Second, we created an optimization model that aims to maximize expected profit by indicating which games to place bets on. The optimization model makes sure any bet it recommends to be placed conforms to the following three constraints: the expected profit of the bet is positive, both sides of the same type of bet are not being recommended, and the variance of the bet’s probability of success from the Random Forest is under the set threshold.

## Future Steps

Overall, we were able to successfully create a system that can accurately forecast the results of future college football games, i.e. predicting the point spread. This predictive capability has the potential to inform profitable wagering decisions. Our next step would be to test it on more datasets (i.e. 2020, 2021, 2022 and even the ongoing 2023 seasons) to see how well the model continues to perform, and get a stronger sense of its capabilities. We can also try it on different sports and see how we can improve it.

## Getting Started

To delve into the details of this project, including code snippets, visualizations, and insights, please refer to the [Jupyter Notebook](NCAA_Predict_Spread.ipynb).

Feel free to reach out if you have questions or feedback about this project!

## Contact Information

If you'd like to get in touch, you can reach me at [faresjimmy1@gmail.com](mailto:faresjimmy1@gmail.com).

Thank you for exploring the college football outcome prediction project!

## Disclaimer

This project is intended for research, educational, and informational purposes only. Betting or wagering on college football games should be done responsibly and in accordance with all applicable laws and regulations. The predictions generated by this model do not guarantee financial success, and any financial decisions made based on these predictions are the responsibility of the user.