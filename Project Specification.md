# **Project Specification**

## **1\. Data Preprocessing** 

* **Dataset:** Select a time-series dataset of your choice.  
* **Imputation:** Fill all missing values using the **K-Nearest Neighbors (KNN)** method.

## **2\. Modeling Requirements** 

You must implement and compare the following:

* **Persistence Model**  
* **Linear Model**  
* **Neural Model:** At least one architecture (e.g., FFNN, LSTM, GRU, or RNN).

## **3\. Input Strategies** 

For each model category, implement:

* **Purely Autoregressive (AR):** Models using only lagged values of the target variable.  
* **Autoregressive with Exogenous Inputs (ARX):** Models incorporating external features/variables.

## **4\. Optimization & Validation** 

* **Hyperparameter Tuning:** Perform a **Grid Search** for the neural network(s).  
* **Model Selection:** Use a dedicated **validation set** to identify and select the best-performing hyperparameters.  
* **Evaluation:** Report final performance on a held-out test set using standard metrics (e.g., MAE, RMSE).

## **5\. Extensions (Optional)** 

* **Architectural Comparisons:** (e.g., Feed-Forward vs. RNNs).  
* **Ensemble Methods:** Combining multiple model predictions.  
* **Probabilistic Forecasting:** Estimating uncertainty intervals.

