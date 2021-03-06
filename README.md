# Predicting Energy Output of Wind Turbine based on the Weather Conditions

##### [app-release.apk](https://github.com/ArchitG358/windmill-predictor/raw/main/app-release.apkk) is the APK of the app for direct use
##### Link for [Video Demonstration](https://drive.google.com/file/d/1q9dVcpbUfYan_IngxCaiTasCRcZd-0Ox/view?resourcekey)

##### Link for [Presentation](https://docs.google.com/presentation/d/1AhFnLCZfqqcYKgrSO7_1jFqocmu9YiQY9kCky7qc1pM/edit?usp=sharing)


## Description of Project
Wind energy plays an increasing role in the supply of energy world-wide. The energy output of a wind farm is highly dependent on the wind conditions present at its site. If the output can be predicted more accurately, energy suppliers can coordinate the collaborative production of different energy sources more efficiently to avoid costly overproduction.

## Solution Offered through this project
We analyzed the data for a Windmill Farm and extracted the weather parameters (assuming other physical conditions like weight of blades, height of windmill to be same etc) that affect power generation the most. Then we prepared an ML model taking the obtained features in consideration, using Boosted Regressor Tree Model. Then for provinding solution quicker to the end-user, we made an Android app to obtain power predictions of next 72 hours on hourly basis in single click.

## Software Development Life Cycle(SDLC) Model Used
We used Iterative Waterfall SDLC model in making of this software. For the development of ML Model we tested it using IBM Watson Studio to get maximum accuracy. For developing the apps, in the initial phase all the requirements were fixed, then design of app was prepared and finally it was coded following Waterfall Model. Finally the app is deployed on Heroku server for public use.

## Technology Stack Used
Jupyter Notebook (Python3) for Data Preprocessing, IBM Watson Studio for ML Model Testing and Prototyping, Python3 for ML model development and Flutter for front-end app development and Flask for back-end and integration with the model.

## Other Reference
[Weather Underground](https://www.wunderground.com), [Kaggle](https://www.kaggle.com/berkerisen/wind-turbine-scada-dataset) for Windfarm data, [Climacell API](https://www.climacell.co/weather-api/), [Heroku](www.heroku.com) for hosting server

##### Climacell API key has been removed from app.py
