
# Predict Global Selse of Video Games 


### Abstract:
The goal of the project is to scraping data from website and to predict the video games global sales depending on other features using linear regression model.

### Design:
This project is one of the T5 Data Science Boot Camp requirements the data provided by <a href="https://www.imdb.com/search/title/?title_type=video_game&num_votes=,5000,&sort=user_rating,desc&pf_rd_m=A2FGELUUNOQJNL&pf_rd_p=87cca6a7-a16d-42d9-b9de-6aace99ec40a&pf_rd_r=ERFX36S273PQKZHMN3NF&pf_rd_s=center-6&pf_rd_t=60601&pf_rd_i=video-games&ref_=fea_vg_scg_ats_toprated_hd">imdb website</a> and merging other data from <a href="https://www.kaggle.com/gregorut/videogamesales/version/2">Kaggle</a>. The problem is we want to predict the video games global sales depending on other features.

### Data Description:
The data will be used in this project is provided by  <a href="https://www.imdb.com/search/title/?title_type=video_game&num_votes=,5000,&sort=user_rating,desc&pf_rd_m=A2FGELUUNOQJNL&pf_rd_p=87cca6a7-a16d-42d9-b9de-6aace99ec40a&pf_rd_r=ERFX36S273PQKZHMN3NF&pf_rd_s=center-6&pf_rd_t=60601&pf_rd_i=video-games&ref_=fea_vg_scg_ats_toprated_hd">imdb website</a> and <a href="https://www.kaggle.com/gregorut/videogamesales/version/2">Kaggle</a>.  it contains of 658 rows and set of columns:

rate - Number of rate.

Rank - Ranking of overall sales.

NA_Sales - Sales in North America (in millions).

EU_Sales - Sales in Europe (in millions).

JP_Sales - Sales in Japan (in millions).

Other_Sales - Sales in the rest of the world (in millions)

Global_Sales - Total worldwide sales.

### Tools:

•	Beautifulsoup for scrap data from website 

•	Numpy and Pandas for data manipulation 

•	Matplotlie and Seaborn for visualise data

•	Sklearn for modle training 



