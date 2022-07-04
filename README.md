# football_analysis

 My learning repo about football analysis


``` J1Predict_by_AutoML.ipynb ```

Jリーグの試合をAutoML (pycaret)を用いて、訓練予想

``` J1Prediction.ipynb ```

Jリーグの試合予想

Data by Football Lab

### How to use

1. ```J1Prediction.ipynb```　のopen in colabボタンを押下し、Google Colabを起動


2. colabにてタブからFileを選択


![Screenshot 2022-07-04 at 15 36 21](https://user-images.githubusercontent.com/44284638/177095899-9171b8ce-317d-430d-b3f6-80f263feaa36.png)

3. Work配下にある```gbr_model.pkl```をuploadする

![Screenshot 2022-07-04 at 15 39 04](https://user-images.githubusercontent.com/44284638/177096162-80831093-4345-4b7b-958b-2e39316ba50f.png)

4. shift + Enterでコードを実行

※Prediction と記載がある箇所については予想する試合と、カテゴリー、年次、直近何試合を元に予想するかといった数値の指定が必要


![Screenshot 2022-07-04 at 15 57 10](https://user-images.githubusercontent.com/44284638/177098800-86806a33-e7f6-43ee-a643-2dd922699149.png)

5. 実行結果を確認する

結果目安　※予想するための直近試合数が少ないほど結果の数値の絶対値が大きくなる傾向があります
|Home勝ち    | 引き分け   |Away勝ち     |
|----|----|----|
|約0.3以上    |0.3 ~ -0.2     |-0.2以下   |


![Screenshot 2022-07-04 at 16 03 07](https://user-images.githubusercontent.com/44284638/177099763-5232db6b-94b8-4d53-b60b-ae4ed0487eed.png)

