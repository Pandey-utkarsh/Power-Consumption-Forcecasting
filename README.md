# Power-Consumption-Forcecasting
Formulated an ML model to predict power consumption for the three given zones for a particular time.

Downloaded data on Power Consumption from [Kaggle Competition](https://www.kaggle.com/competitions/zonal-load-forcecasting-recognizance23/data)
The data consists of several observations of energy consumption in a 20-minute window. There are six parameters on the basis of which we have to predict the value of power consumption.

![Screenshot from 2023-07-11 20-07-01](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/6a70044a-1552-4c97-bcf6-ade7523760fc)
Raw Data

The dataset consisted of data for the entire year 2017. Hence we will be able to leverage Datetime as well as a feature in forecasting Power consumption

![Screenshot from 2023-07-11 20-07-23](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/9c9b3368-982b-410d-83d1-95ba451bbe75)

After Preprocessing and splitting input data, it was trained on Linear Regression, RandomForestRegressor, K Nearest Neighbours algorithms and results were compared.

![Screenshot from 2023-07-11 20-22-33](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/22e18be7-425f-4e27-9879-487049ced2e3)
![Screenshot from 2023-07-11 20-22-43](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/60450f1b-3ca3-4a83-9380-f7176f323912)
![Screenshot from 2023-07-11 20-22-51](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/260c14bd-e42b-4c69-ad9c-89e546d6a78b)


**Result**

![Screenshot from 2023-07-11 20-23-04](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/b2ef12fe-e4fb-4aea-8aab-ea3aa3de2970)


**Scatter Plot**:

![Screenshot from 2023-07-11 20-30-12](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/663bf502-d128-4411-9f5d-da30fff6e830)
![Screenshot from 2023-07-11 20-30-21](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/e8a7328e-f222-4c9e-aad2-c4057d4fb54d)
![Screenshot from 2023-07-11 20-30-29](https://github.com/Pandey-utkarsh/Power-Consumption-Forcecasting/assets/91661580/8d0c6b7a-b251-46b1-83b7-fa8e68577aaa)

