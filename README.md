# guide
 파이썬 머신러닝 완벽 가이드

회귀실습
1) 자전거 대여 수요 예측
   - 캐글 Bike-Sharing-Demand
   - 자전거 대여 횟수 에측(count)
   - RMSE
   - 요일, 계절에 따라 자전거 사용이 차이가 났으며 원-핫 인코딩을 적용함
   - Linear Regression, Ridge, Lasso , 회귀트리
2) 주택 가격
   - 캐글 House Price:Advanced Regression Techniques
   - 주택 가격 예측
   - RMSLE
   - Null 값이 많은 변수가 있었으며 원핫 인코딩 적용
   - Linear Regression, Ridge, Lasso , 회귀트리, 스태킹
   - CV를 적용하며 Lasso 모델의 최적의 alpha 값을 찾음
   - 이상치 제거
  
 분류실습
  - 캐글 Santander Customer Satisfaction
  - 고객 만족 여부 예측(1:불만, 0:만족)
  - ROC-AUC
  - XGBoost, LightGBM
  - CV 및 하이퍼파라미터 튜닝
