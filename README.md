# Bitcoin-Predictor

uni capstone project

Python Version: 3.3 or higher

Development Environment: Jupter

The following libraries are required when running the code:

- bs4
- requests
- pandas
- calendar
- nltk
- matplotlib
- sklearn
- math
- statsmodels.api
- mlxtend
- tensorflow

The aim of this project is to identify, analyse the magnitude of impact of different factors influencing bitcoin price by exercising feature selection techniques and fundamental analysis. The project also aims at designing, developing, testing, evaluating as well as optimizing both machine learning and deep-learning models/systems to predict bitcoin next-day closing price base on the outcomes of factor analysis. The previous work does not take a wide range of external factors into consideration and merely achieves sub-optimal prediction performance. In addition, it does not provide an in-depth news sentiment analysis. In order to achieve the aims and close the gap stemming from the limitations by previous researches, the specific tasks are listed as follows:

Design and develop python scrapper to collect relevant data from reliable sources, write programs to consolidate all the data into a single spreadsheet and transform data from different sources into a consistent format. Write programs to conduct statistical analysis and visualise the pattern and insights. Write programs to perform sentiment analysis to study the relationship between bitcoin price and news sentiment. Write programs to apply feature selection and feature extraction techniques, build up machine learning and deep learning models for training and price prediction. Test, evaluate, debug and optimise the model and critically compare it with the existing peer machine learning models and systems.

The prediction modelling part presents Support Vector Regression (SVR), Linear Regression and Long Short-Term Memory (LSTM) with different combination of features as inputs to predict next-day bitcoin price. The results of the experiments show that LSTM outperforms the other two models with 115.17 RMSE and 62.1% accuracy of next-day bitcoin price (rise/drop) classification.

For detailed technical description and analysis, please refer to CP13-2_Final_Group_Report.PDF
