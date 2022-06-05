# foursquare_location_matching
Foursquare - Location Matching (Kaggle Competition)

## 最終結果

![image](https://github.com/joeroy5376998/foursquare_location_matching/blob/main/image/rank.PNG)

## 隊伍名稱

![image](https://github.com/joeroy5376998/foursquare_location_matching/blob/main/image/team.PNG)

## 檔案說明

1. best_score.ipynb
     
     最佳分數的所使用的程式碼，參考公開 notebook 並調整參數，得到分數為 0.845。
     
     相關的 input files 因檔案大小限制無法上傳 GitHub，因此以下連結為此檔案在 Kaggle 的連結，可直接於 Kaggle 上執行。
     
     https://www.kaggle.com/code/douhau/foursquare-catboost

2. try_and_error 資料夾
     
     此資料夾中放置兩個 try and error 的程式碼：
     
     1. binary-lgb-baseline.ipynb:

        此為公開的 notebook，架構為 kNN 及 binary LightGBM model，調整參數後，最高分數為 0.835。以下為 Kaggle 連結：
     
        https://www.kaggle.com/code/douhau/binary-lgb-baseline-0-834
        
     2. foursquare-model-lgb.ipynb, foursquare-predict.ipynb:
        
        參考 binary-lgb-baseline.ipynb 架構之程式碼，最高分數為 0.783。以下為 Kaggle 連結：
        
        https://www.kaggle.com/code/douhau/foursquare-model
