# Capstone-1-Covid-19

## Description
This capstone project is a simple RNN project to predict the covid cases based on real data from Ministry of Health Malaysia using Tensorflow.Keras. (its also my first time posting here)
The architure is a simple LTSM based RNN where it have two layers of LTSM, one layer of Dropout Layer, and one output layer of 1 node.

## The process of how this model training been done

1. Import Packages
2. Data Loading
   - Load the given dataset
     
4. Create a pandas dataframe using the CSV file
5. Preprocess the dataset
   - Check & Replace Null values
   - Check duplicated values
     
7. Exploratory and inspection of data
8. Train Test Plot
   - the train data start from 2020 until end of 2022
   - the testing data start from start of 2023 until 2024
     
10. Spliting the data into training data and testing data
11. Normalization
    - Using the MinMaxScaler
      
13. Steps
14. Model Architecture
    - LSTM Layer x2
    - Dropout Layer x1
    - Dense Layer x1
      
16. Model Training
    - epoch = 200
    - batch size = 32
18. Prediction & Evaluation


## Screenshots
![Project Screenshot](path/to/screenshot.png)

## Acknowledgements
- Thanks to [MoH - Malaysia](https://github.com/MoH-Malaysia/covid19-public) for their amazing library.
- Also thanks to my SHRDC Trainers for giving me the opportunity and knowledges about coding, machine learning and deep learning
