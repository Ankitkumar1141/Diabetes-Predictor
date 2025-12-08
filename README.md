# Diabetes Predictor

### 🎯 **Goal**

The main goal of this project is to develop a predictive model that can accurately determine the likelihood of diabetes in individuals based on their medical parameters. By leveraging deep learning techniques and a comprehensive dataset, the project aims to provide a reliable tool for early detection and risk assessment of diabetes.

### 🧵 **Dataset**

The dataset can be accessed from the following source:  [Kaggle: Diabetes Data Set](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)


### 🧾 **Description**

This project focuses on the development of a Deep learning model for predicting the likelihood of diabetes in individuals based on various medical parameters. Diabetes is a prevalent health condition affecting millions of people worldwide, and early detection plays a crucial role in managing the disease and preventing complications.

The project utilizes a comprehensive dataset containing medical information such as glucose levels, blood pressure, BMI, insulin levels, and other relevant features. By analyzing this data and applying Deep learning algorithms, the model aims to accurately classify individuals as either diabetic or non-diabetic.



### 📜 **Repo Structure**

```
Diabetes Prediction
|- Dataset
  |- diabetes.csv
  |- README.md
|- Images
  |- img1.png
  |- img2.png
       :
       :
  |- img11.png
  |- README.md
|- Models
  |- Diabetes Predictor.ipynb
  |- ann_model.h5
  |- lstm_model.h5
  |- rnn_model.h5
  |- README.md
|- Web App
  |- app.py
  |- snapshot.png
  |- Demo.mp4
  |- README.md
|- requirements.txt
```


### 🧮 **What I had done!**
- Added Deep Learning Models and Streamlit Application for Diabetic Prediction

- This project introduces Deep Learning models trained on diabetic data for diabetic prediction. It includes the implementation of artificial neural network (ANN), long short-term memory (LSTM), and recurrent neural network (RNN) models using TensorFlow.

- A Streamlit application has been developed to provide a user-friendly interface for predicting diabetes based on user input. The application allows users to input various parameters, such as glucose level, blood pressure, BMI, etc. and predicts the likelihood of diabetes using the trained models.

### 🚀 **Models Implemented**

- Artificial Neural Network (ANN)
- Long Short Term Memory (LSTM)
- Recurrent Neural Netowrk (RNN)

### 📚 **Libraries Needed**

- TensorFlow
- Pandas
- Plotly Graph Objects
- Seaborn
- Sklearn
- Matplotlib
- Streamlit

### Exploratory Data Analysis Results

![image](https://github.com/Ankitkumar1141/Diabetes-Predictor/blob/56a809c79da88afeae22a5b7da8fb6073db60933/Images/boxplot.png)

![image](https://github.com/Ankitkumar1141/Diabetes-Predictor/blob/56a809c79da88afeae22a5b7da8fb6073db60933/Images/pairplot.png)

![image](https://github.com/Ankitkumar1141/Diabetes-Predictor/blob/56a809c79da88afeae22a5b7da8fb6073db60933/Images/insulin%20%26%20glucose.png)

![image](https://github.com/Ankitkumar1141/Diabetes-Predictor/blob/56a809c79da88afeae22a5b7da8fb6073db60933/Images/distribution%20of%20outcome.png)

### ⚙️ **Usage**

1. **Exploring Notebooks**: Navigate to the `Models/` directory to explore Jupyter notebooks. These notebooks cover data analysis, preprocessing, model training, and evaluation steps.
   -  Navigate to the `Models/Diabetes Prediction.ipynb`
   -  Run all the cells
2. **Trained Models**: The `Models/` directory contains trained Deep Learning models saved in HDF5 format. These models can be loaded and used for making predictions.
3. **Streamlit App:** The `Web App/app.py` contains the source code for the Streamlit web application. To run the app locally, follow the instructions below:

    ```bash
    pip install -r requirements.txt
    cd Web App
    streamlit run app.py
    ```

    
### 📈 **Performance of the Models based on the Accuracy Scores**
<div align="center">
<table>
  <tr>
    <th>Model</th>
    <th>Validation Accuracy</th>
  </tr>
  <tr>
    <td>ANN</td>
    <td>77.2%</td>
  </tr>
  <tr>
    <td>LSTM</td>
    <td>75.3%</td>
  </tr>
  <tr>
    <td>RNN</td>
    <td>77.2%</td>
  </tr>
</table>
</div>



### 📢 **Conclusion**

Based on the validation accuracy scores, the ANN and RNN models achieved the highest accuracy of approximately 77.27%, while the LSTM model achieved slightly lower accuracy at 75.32%. Therefore, the ANN and RNN models can be considered the best-fitted models for this project.


### ✒️ **Signature**

  Ankit Kumar

