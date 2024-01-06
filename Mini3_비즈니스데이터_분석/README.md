# 👩‍💻MINI PROJECT 3
### 👯 팀명 : 장뇌삼
팀원 : 김지원, 김효정, 배상빈, 이준언, 이호연

## 👩‍💼 대용량 데이터 비즈니스 데이터 분석해보기

#### 1. 목적
대용량 데이터를 다루어보고 비즈니스 데이터 분석해보기 
- DAU, MAU, ARPU, ARPPU, 리텐션(시간 코호트) 분석, RFM, 군집화

#### 2. 활용 데이터
용량이 총 14G(9G+5G)인 데이터셋
[eCommerce behavior data from multi category store | Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Oct.csv)

#### 3. 과정
1. 대용량의 데이터를 chunksize로 줄여보기(실패)
2. 필요한 컬럼만 불러오고 dtype을 정해 용량을 줄이고 합치기에 성공
3. parquet으로 불러오기
4. 전체 RFM 하기 위한 전체 데이터 전처리
5. 전체 데이터 RFM 구해보기
6. 전체 데이터 RFM으로 고객군 나누기
7. Smartphone 데이터에서 DAU, WAU
8. 다음 주 카테고리 스마트폰 WAU 예측
9. 삼성 / 애플 스마트폰 방문자수 예측

#### 4. 결과
결과는 노션에 추가
