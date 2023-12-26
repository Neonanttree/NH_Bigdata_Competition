# NH 투자증권에서 제공된 주식 데이터 및 웹크롤링을 통한 주식 데이터 이용
# 미국 주식 시장이 한국 주식 시장에 미치는 영향을 분석하는 것이 목표
# 미국 주가 데이터와 한국 주가 데이터를 1일의 차이를 두어 Fitting 함
# 업종 별 그래프의 유사도를 비교 (Euclidean Distance)
# 업종 별 분석을 진행했을 때 유의미한 영향이 있다고 판단
# 본선 대회에서 한국 주식 시장 내 (005930 KS Equity)의 데이터만 사용
# 추가적으로 Supply Chain을 이용해 Customer, Competitor, Supplier, 동일 업종의 데이터 이용
# 해당 변수를 각 칼럼으로 추가함
# Catboost를 이용해 모델 생성
# Optuna를 사용해 Fine Tuning 진행
