# foursquare_location_matching
Foursquare - Location Matching (Kaggle Competition)

## Team Name

隊伍名稱截圖

![image](https://github.com/joeroy5376998/foursquare_location_matching/blob/main/image/team.PNG)

截至 6/5 在 leaderboard 上的排名

![image](https://github.com/joeroy5376998/foursquare_location_matching/blob/main/image/rank.PNG)

## Files

1. best_score.ipynb
     
     最佳分數的所使用的程式碼，相關的 input files 因檔案大小限制無法上傳 GitHub，因此以下連結為此檔案在 Kaggle 的連結，可直接於 Kaggle 上執行。
     
     https://www.kaggle.com/code/douhau/0-836-1h-inference-burning-up-kaggle-cpus

2. try_and_error folder
     
     此資料夾中放置兩個 try and error 的程式碼：
     
     1. binary-lgb-baseline.ipynb:
        https://www.kaggle.com/code/douhau/binary-lgb-baseline-0-834
        此為公開的 notebook，架構為 kNN 及 binary LightGBM model，調整參數 neighbors = 30 後，score = 0.835
     2. foursquare-model-lgb.ipynb, foursquare-predict.ipynb:
        https://www.kaggle.com/code/douhau/foursquare-model
        參考 binary-lgb-baseline.ipynb 架構之程式碼，score = 0.783
