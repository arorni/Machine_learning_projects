#NYC Taxi Fare Prediction

This project tries to predict taxi fares in New York region using a machine learning model. The dataset includes details such as pickup and drop-off locations, date and time, passenger count, and distance traveled. The goal is to build a machine learning model that can provide a reasonable estimates for the taxi fares based on these features.

I used Python for data processing, feature engineering, and model training, leveraging XGBoost. Evaluation metrics include RMSE (Root Mean Squared Error) and R2 score to assess model performance.


## Acknowledgements

 - [Kaggle workbook](https://www.kaggle.com/code/breemen/nyc-taxi-fare-data-exploration)
 - [Chatgpt] (I have used chatgpt help in creating labels and colors for visualizations)


## Authors

- [@arorni](https://github.com/arorni)


## 🚀 About Me
I'm a passionate data professional, who loves to learn and experiment with new tools and technologies.


## Lessons Learned
As generally said in the data community, a good project is defined by the decisions you take and the understanding you build during the project. Below are some of the lessons I learned:

- It was a huge dataset with (approximately 55 million rows), and my laptop was not that poweful(8GB ram, Intel i5 processor), so how to ingest and process that dataset was a big challange.
- I had used vaex to ingest the entire training dataset in just 18 secs. During the project, I faced and overcame library incompatibility issues when changing laptops, emphasizing the importance of tracking library versions.
- Decisions such as how much data would be enough for my use case? How much data should I use for EDA (Used radom sampling technique) were crucial?
- I got an opportunity to learn about the Geopandas and Geopy libraries.
