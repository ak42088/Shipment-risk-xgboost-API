# Shipment-risk-xgboost-API
An open source API that can we used to predict shipment risk of COD orders from Indian Market context. How to use ?
Here steps that will help you to understand the different components and how to connect them to get things up to speed
Key components
    risk_calculation.py : This loads your orders data and calculates the input risks of pincode risk, customer risk, customer_rto_risk, address_risk.
    xgb_trained_model : An xgb model that will use the input risks and outputs shipment risk : The model is trained on 50k actual indian e-commerce data point and has current rmse of 0.0095 
    FAST API deployment : repo that can be used to deploy the model upload and risk prediction APIs
    Steps > Save the shipment
