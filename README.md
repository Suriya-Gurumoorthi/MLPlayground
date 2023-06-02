# British Airways Customer Booking Prediction
This project is a machine learning model that predicts whether a customer will book a flight with British Airways. The model is trained on a dataset of historical customer data, and it can be used to predict whether a customer will book a flight given their features, such as their travel history, their demographics, and their preferences.

### Installation:
If you are new to jupyter notebook, install SHAP package, the rest will be pre installed already.
Code for SHAP Installation:<br><br>
 `pip install shap`<br><br>
 Sometimes, you may face the error `ImportError: Numba needs NumPy 1.20 or less`<br>
 
 In this case, execute the following codes in jupyter notebook and restart the kernel<br>
 ```
pip install numpy==1.21.4
pip install numba==0.53.0
pip install librosa
```
   
### Model

I used Decision Tree and Random Forest for this project. The model was implemented using the scikit-learn library.<br>
Also try to use `GridSearchCV` or `RandomizedSearchCV` for hyperparameter Tuning. This would really help you to achieve optimal model.<br><br>
The model was trained using 80% of the labeled data and evaluated on the remaining 20%.

### Results

After training the model, we achieved an accuracy value of `63%` and `85%` on the test set on `Decision Tree` and `Random Forest` respectively. I have concluded Random Forest Classifier indicating a good fit to the data. The predictions made by the model were also visually compared to the true values.

### Contributing

I welcome contributions to improve this project. If you encounter any bugs, have feature requests, or would like to make improvements, please submit an issue or a pull request.

### Contact

For any questions or inquiries, please contact `Suriya G` at `suriyagurumoorthi02@gmail.com`
