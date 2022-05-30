## Project Context:
Investments4Some is a long-standing Portuguese, privately held hedge funds management firm. They have been exploring Machine Learning models for market price forecasting, which is used to anticipate market trends. Our team was hired by Warner Buffer and Gil Bates, partners of Investments4Some, to develop a dashboard for their financial analysts. 
This Dashboard was thought as a tool to assist the internal financial team and external stakeholders in the investment planning, allowing them to collect useful insights and deeper knowledge about any arbitrary stock and digital currency, thus improving the quality of their portfolios and provide an easy way to keep track of the market trends.

## Description of the Dashboard:
The dashboard was built using streamlit and is composed of multiple pages, namely Home Page, Crypto Market Summary, Stock Market Summary, Trend Analysis, Forecast and Portfolio Page.
- In the Home Page, the investor can take a short quiz to find out which type of investor he/she is and, for new investors, some tips are provided.
- The Market Summary pages display important visualizations regarding the most important stocks and crypto currencies up to this date, such as market capitalization, volume, and volatility. 
- The Trend Analysis page includes plots from 3 key indicators such as Moving Average (MA), Moving Average Convergence Divergence (MACD) and Relative Strength Index (RSI) indicators, and a candlestick plot. This page is personalized for each stock or crypto the user wishes to analyze, which can be achieved through the input of the symbol in the input box on the top of the page.
- The Forecast page includes the predictions for the close price and the user can use this forecasting tool for any stock or crypto and choose the time frame for the predicting, up to 10 days. Similarly to the trend analysis, the investor can benefit from this forecasting tool for any stock or cryptocurrency.
- Finally, the Portfolio page is dedicated to each individual investor profile and designed to assist the assessment of the performance of acquired stocks, which can support the planning of future investments. The investors can insert the stocks and digital currencies they own, and additionally provide information about their respective acquisition to take advantage of the complete analysis offered in this page.

The dashboard can be run following the command “streamlit run app.py”, but was also deployed and the app is live in this link: https://bc5-5w01.onrender.com/

**Home Page**
![image](https://user-images.githubusercontent.com/90759149/170960584-ad9f6266-bfc3-4bad-a466-dce97e23b3a7.png)
**Crypto Market Summary Page**
![image](https://user-images.githubusercontent.com/90759149/170960701-9b026c94-b320-45f5-b7cd-0b6158dab103.png)
![image](https://user-images.githubusercontent.com/90759149/170960837-8bdf340b-1692-46d5-a80e-05b722f5e2fb.png)
**Stock Market Summary Page**
![image](https://user-images.githubusercontent.com/90759149/170960994-9edac0fb-8c76-4c11-bebb-e8539e024b47.png)
**Trend Analysis Page**
![image](https://user-images.githubusercontent.com/90759149/170961064-d6da4c10-dd06-4372-b549-37148fb0dfba.png)
![image](https://user-images.githubusercontent.com/90759149/170961112-19df7882-b6d7-404e-aa26-d1d879c14834.png)
**Forecast Page**
![image](https://user-images.githubusercontent.com/90759149/170961200-de3facae-986b-46c8-b05c-0fa7965b8461.png)
![image](https://user-images.githubusercontent.com/90759149/170961347-9845b97c-403a-4517-a045-d030470ec0b3.png)
**Portfolio Page**
![image](https://user-images.githubusercontent.com/90759149/170962571-213a8bb8-0d08-45ad-915c-81d110c6d945.png)






