# time-series-sentiment-forecasting--Prophet-time-series
## Tools and Technology used:
[![MATPLOTLIB](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge)](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge) [![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) [![Jupyter](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge)](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge) [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) [![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) <a href="https://seaborn.pydata.org/" rel="nofollow"><img alt="SEABORN" src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" style="max-width: 100%;"/></a>
<a href="https://www.microsoft.com/en-in/microsoft-365/excel" rel="nofollow"><img alt="Excel" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" data-canonical-src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" style="max-width: 100%;"/></a><a href="https://www.tableau.com/" rel="nofollow"><img alt="NodeJS" src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" data-canonical-src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" style="max-width: 100%;"/></a>
<a href="https://www.tableau.com/learn/articles/time-series-forecasting#:~:text=Time%20series%20forecasting%20occurs%20when,drive%20future%20strategic%20decision%2Dmaking." rel="nofollow"><img alt="Time-series-forecasting" src="https://img.shields.io/badge/-Time%20Series%20Forecasting-5bb5bf?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-Time%20Series%20Forecasting-5bb5bf?style=for-the-badge" style="max-width: 100%;"/></a>

Sentiment time series forecasting is a technique that uses historical data on sentiment to predict future sentiment. The goal is to identify patterns in the data, such as trends and seasonality, to inform future predictions. 

### Steps

A) Data Collection
- Collecting historical data on sentiment of customer reviews for the categories :  Amazon Home, Tools and Home Improvement.

B) Model Training & Evaluation 
- FbProphet is used to fit the model to the data, this step generates the forecasts for future values.
- The model's performance is evaluated using metrics such as mean squared error and root  mean squared error.

### Results for AMAZON HOME category products : 


 - Positive Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340318-88ed67e1-3ae2-4a15-802b-956b1b34c927.png)
- Neutral Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340346-ec58c3c5-dba5-47d0-8e75-76fa6a0b8b78.png)
-   Negative Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340352-e0276d36-4db5-4a7c-aed3-2ee6d9bbbd67.png)

### Results for TOOLS & HOME IMPROVEMENT category products : 

 - Positive Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340474-c202205d-1a76-4bcf-8bd3-1c36c6ebc282.png)

- Neutral Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340479-e4e9b8e4-6ca9-4785-8371-d21936dc6568.png)

- Negative Sentiment
![image](https://user-images.githubusercontent.com/84577478/229340484-93765856-04f0-4d6d-97cd-afa95a2edd1b.png)

### Forecasting of sentiment of few products using Tableau 

- For Amazon Home & Tools and Home Improvement, Positive sentiments are going to increase in customer reviews and a decline will be seen in negative and neutral.
- Few products which highly contribute to sales in Amazon Home can still be seen having negative trend in positive sentiments in upcoming years. So, they can be worked upon to provide better experience to customers.
- Link : https://public.tableau.com/app/profile/monish.lalani/viz/InventoryOptimizer_16743816983790/Dashboard1
![image](https://user-images.githubusercontent.com/84577478/229340571-64f0c814-f4b2-46aa-9715-ee7be775cf39.png)
