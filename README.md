# football_analysis

Repository about Football

サッカー関連のリポジトリです。
主に機械学習によるJリーグの試合予想など

### ファイル説明

``` J1LeagueScrape.ipynb```

Football Labから試合データをスクレイピング

``` J1Predict_by_AutoML.ipynb ```

Jリーグの試合をAutoML (pycaret)を用いて、訓練予想

``` Prediction.ipynb ```

Jリーグの試合予想

Data by Football Lab

### 使い方

1. ```Prediction.ipynb```　のopen in colabボタンを押下し、Google Colabを起動


2. colabにてタブからFileを選択


![Screenshot 2022-07-04 at 15 36 21](https://user-images.githubusercontent.com/44284638/177095899-9171b8ce-317d-430d-b3f6-80f263feaa36.png)

![Screenshot 2023-10-01 at 14 25 23](https://github.com/aritanaoya/football_analysis/assets/44284638/68970a07-e8c5-42ea-8e71-9a89323fe769)



3. models配下にある```final_gbr_home_pred.pkl```と```final_gbr_away_pred.pkl```をuploadする



4. shift + Enterでコードを実行

※Prediction と記載がある箇所については予想する試合と、カテゴリー、年次、直近何試合を元に予想するかといった数値の指定が必要


![Screenshot 2022-07-04 at 15 57 10](https://user-images.githubusercontent.com/44284638/177098800-86806a33-e7f6-43ee-a643-2dd922699149.png)

5. 実行結果を確認する

   ![Screenshot 2023-10-01 at 14 14 12](https://github.com/aritanaoya/football_analysis/assets/44284638/547263db-43fe-4ade-b342-db4cbd69b624)



