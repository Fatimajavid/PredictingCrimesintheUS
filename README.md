
# Crime Prediction (CTP Project)
### Team Name: Data Cops
### Team Members: Bibata Rabba Idi, Fatima Javid, JianHui (Jake) Li

**Goal**: To predict total number of crimes in a year using the US community demographic factors.

**Motivation**: To better understand what demographics features affect total number of crimes to help build safer communities.

## :mag_right: Data Source: [Crimes in US Communities Dataset](https://www.kaggle.com/datasets/michaelbryantds/crimedata)

This dataset is from Kaggle and it contains 2215 observations and 146 attributes. It allows us to test and understand which demographic factors impact crime rates. The dataset is from 2018 and includes information about US communities such as population, age, race, income, types of crimes, overall crime rates, etc.

## :open_book: Summary

1. Performed exploratory data analysis and data cleaning.
2. Built model using random forest regressor.
3. Evaluated model performance.
4. Visualized prediction results.

## :dart: Results

The top 5 most importance feautes in descending order are:
1. numbUrban: number of people living in areas classified as urban
2. NumUnderPov: number of people under the poverty level
3. population: population of the community
4. NumKidsBornNeverMar: number of kids born to unmarried parents
5. NumStreet: number of homeless people on the street

Using only these 5 features, our model yielded an R^2 of 0.93.

We also built an web app using Streamlit for users to interact with our model, check it out [here](https://fatimajavid-crimepredictionapp-homepage-lp2yy9.streamlit.app/).

## :hammer_and_wrench: Tech Stack

**Language:** Python

**Libraries:** pandas, Scikit-learn, Plotly, Pickle

**Framework:** Streamlit

**Tool:** Jupter Notebook

