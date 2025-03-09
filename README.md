# K-NN Apartment Price Prediction

공공 데이터를 분석하여 인공지능 라이브러리를 사용하지 않고 강남구의 아파트 매매 가격 증감을 예측하는 K-NN 모델을 개발하는 프로젝트입니다.

## 요구사항

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- FinanceDataReader

## 데이터셋 (2018.01~2022.12)

- 국토교통부 아파트매매 실거래 상세 자료
- 국토교통부 토지 매매 신고 자료
- KOSPI 시세정보 (FinanceDataReader)
- 한국은행 경제통계시스템 주택담보대출(LTV) 금리

## 상관관계 분석

아파트 가격과 관련된 다양한 변수를 분석하여 K-NN 모델의 입력 특성을 선정합니다.

![image](https://github.com/user-attachments/assets/44b6e392-262c-4fef-8732-3ff4b9a382ae)
- 상관관계 분석

![image](https://github.com/user-attachments/assets/97ccee1e-e43c-4362-b27a-d936466c599b)
- 산포도

![image](https://github.com/user-attachments/assets/f4a34611-57c7-486c-b6a9-1fae479256a1)
![image](https://github.com/user-attachments/assets/bc8393a5-2dc4-43ee-8a1b-90d9a27abce0)
- 꺾은선 그래프

![image](https://github.com/user-attachments/assets/b19a11d1-8eac-4ff4-8cb5-e69f151d14b0)
![image](https://github.com/user-attachments/assets/0f89de95-51db-4ed2-aa46-ec0d4cbc8345)
![image](https://github.com/user-attachments/assets/2313ebbd-87b1-4224-89f0-b9b41d11fcf4)
![image](https://github.com/user-attachments/assets/13aee46a-1675-4f3d-9a39-bbe350aa73d3)
- 히스토그램 시각화

![image](https://github.com/user-attachments/assets/941d521b-14e7-4280-9848-7b1352f9b98b)
![image](https://github.com/user-attachments/assets/0de73886-ca62-4162-a2ef-b0816d168b83)

## K-NN 모델
- 아파트 층수와 아파트 면적 데이터를 주요 입력 변수로 사용합니다.

## 결과

k가 4일 때, 정확도 94.43%

![image](https://github.com/user-attachments/assets/f8a3adf3-68ae-4d09-9cf2-425bb4b7ec21)
