

# Predict Global Selse of Video Games 

### Abstract:
The goal of the project is to scraping data from website and to predict the video games global sales depending on other features using linear regression model.

### Design:
This project is one of the T5 Data Science Boot Camp requirements the data provided by <a href="https://www.imdb.com/search/title/?title_type=video_game&num_votes=,5000,&sort=user_rating,desc&pf_rd_m=A2FGELUUNOQJNL&pf_rd_p=87cca6a7-a16d-42d9-b9de-6aace99ec40a&pf_rd_r=ERFX36S273PQKZHMN3NF&pf_rd_s=center-6&pf_rd_t=60601&pf_rd_i=video-games&ref_=fea_vg_scg_ats_toprated_hd">imdb website</a> and merging other data from <a href="https://www.kaggle.com/gregorut/videogamesales/version/2">Kaggle</a>. The problem is we want to predict the video games global sales depending on other features.

### Data:
The data will be used in this project is provided by  <a href="https://www.imdb.com/search/title/?title_type=video_game&num_votes=,5000,&sort=user_rating,desc&pf_rd_m=A2FGELUUNOQJNL&pf_rd_p=87cca6a7-a16d-42d9-b9de-6aace99ec40a&pf_rd_r=ERFX36S273PQKZHMN3NF&pf_rd_s=center-6&pf_rd_t=60601&pf_rd_i=video-games&ref_=fea_vg_scg_ats_toprated_hd">imdb website</a> scraped 10 pages from this website and <a href="https://www.kaggle.com/gregorut/videogamesales/version/2">Kaggle</a>.  it contains of 658 rows and set of columns it contains 7 features and 1 target:

#### features:

rate - Number of rate.

Rank - Ranking of overall sales.

NA_Sales - Sales in North America (in millions).

EU_Sales - Sales in Europe (in millions).

JP_Sales - Sales in Japan (in millions).

Other_Sales - Sales in the rest of the world (in millions)


#### target:

Global_Sales - Total worldwide sales.

also we used data transform (Logarithmic transformation) we use it to make the data more normalized, We did several experiments and we used the best experiment which is polynomial with r-squared = 0.99.

### project workflow (steps):

1- Web scraping multiple pages 

2- Load data from Kaggle 

3- Merge dataset 

4- transform data using Log 

5- EDA

6- Apply experiment

7- Test model

7- Lasso & Readge



### Tools:

•	Beautifulsoup for scrap data from website 

•	Numpy and Pandas for data manipulation 

•	Matplotlie and Seaborn for visualise data

•	Sklearn for modle training 

Communication:
The slides are provided <a href="https://github.com/RazanAlzahrani1/VideoGames_Regression/blob/main/Linear_Regression_Presentation.pdf">here</a>, and proposal provided at <a href="https://github.com/RazanAlzahrani1/VideoGames_Regression/blob/main/README.md">Readme</a> file of the project.



