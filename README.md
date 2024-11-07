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
![Model_Archicture](https://github.com/user-attachments/assets/2897c59e-ae2f-48f0-959b-cce09ced5a37)
![Model_Archicture_Compiler_Setting](https://github.com/user-attachments/assets/06185881-451c-4fa3-bf3b-85ab314c2455)
![TensorBoard_Loss_Graph](https://github.com/user-attachments/assets/c1ca28e4-5e25-4d11-9b7a-2d4f5417fada)
![TensorBoard_MAE_Graph](https://github.com/user-attachments/assets/6d736ac7-182b-4572-be7d-8ca0b4e17c6d)
![Model_Evaluation](https://github.com/user-attachments/assets/7de633ec-2750-49d6-9bb8-83b4c3195697)
![Pred_vs_True](https://github.com/user-attachments/assets/28b0ef9a-9d95-4c81-a440-7d70af8535e1)
![Pred_vs_True_30_Days](https://github.com/user-attachments/assets/879523ca-e9a1-4d60-9526-b5ed3bc676e8)


## Acknowledgements
- Thanks to [MoH - Malaysia](https://github.com/MoH-Malaysia/covid19-public) for their amazing library.
- Also thanks to my SHRDC Trainers for giving me the opportunity and knowledges about coding, machine learning and deep learning
