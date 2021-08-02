# Flask Rest API : NewYork AirBnb 가격 예측 

2019 New York City Airbnb Open Data를 이용한 뉴욕 에어비앤비 가격예측 웹 어플리케이션

## Outline 
2011-2019 뉴욕 에어비엔비 데이터를 머신러닝 회귀모델에 적용시켜 조건에 맞는 예측값을 보여준다. 

## Input Info
  Minimum night : 숙박가능 최소일수   
  Review : 리뷰 갯수  
  Host count : 호스트 수   
  Availability : 365일 중 이용가능 일 수

## Code structure
```
< PROJECT ROOT >
   |
   |-- static                              
   |     |-- css/style.css                 # html 스타일 지정 
   |          |-- img/background.jpg       # 배경화면
   |    
   |-- templates    
   |     |-- index.html          # html 페이지 
   |
   |-- data    
   |     |-- AB_NYC_2019.csv     # 머신러닝에 필요한 데이터
   | 
   |-- app.py                    # app 실행 
   |-- model.py                  # 머신러닝 모델 코드
   |
```

