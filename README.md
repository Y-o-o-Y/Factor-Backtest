## 資料準備
Stock pool: 864 tickers
## 單因子測試
中性化: Market (不另外做行業中性是因為避免標籤偏見)

起始資金: 10k
<img width="865" height="338" alt="image" src="https://github.com/user-attachments/assets/da2d6f72-d143-4bd5-8a8f-530d67c10b35" />

排名梯子圖 (理想的情況會從 Q5 往下排到Q1，這樣剛好符合做多高排名做空低排名)

<img width="865" height="281" alt="image" src="https://github.com/user-attachments/assets/189d2097-cde9-4e43-b4fa-b2ea96118439" />

 
## Alpha 信號多因子權種合成 (7個)
等權重
<img width="865" height="282" alt="image" src="https://github.com/user-attachments/assets/59fc0de6-63fd-48e2-bc49-5923f2dead42" />

 
Multiplicative Weight (online learning)
 <img width="865" height="275" alt="image" src="https://github.com/user-attachments/assets/8dc8e751-d57c-4466-96dc-2867ae3153f6" />
<img width="865" height="269" alt="image" src="https://github.com/user-attachments/assets/2886acca-f02d-4a83-9ee3-84f48215bbd9" />

 
## 投資組合風險優化
Ledoit-Wolf Shrinkage

Solver: OSQP

調整頻率: 月

<img width="865" height="143" alt="image" src="https://github.com/user-attachments/assets/f37aacae-c408-47be-a29d-96b2edbb9c77" />


 
## 歸因分析 (含常數項)
PCA top 5 components
 <img width="865" height="77" alt="image" src="https://github.com/user-attachments/assets/875b2d83-9195-4d44-934c-e2c5d380c9ea" />

 <img width="865" height="138" alt="image" src="https://github.com/user-attachments/assets/f8893d5a-02b8-4b71-b5dc-4a3752fee8c1" />


## Alpha (殘差) 統計檢定 (含常數項)

Equal Weight
 <img width="661" height="222" alt="image" src="https://github.com/user-attachments/assets/d1f014a6-2110-4af8-aec7-c5299413c784" />


Multiplicative Weight
<img width="694" height="209" alt="image" src="https://github.com/user-attachments/assets/0d9081d4-d941-4cec-b462-c32fe777f3d4" />


