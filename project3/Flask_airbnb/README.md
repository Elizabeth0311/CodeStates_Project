# Flask를 이용한 Rest API : NewYork AirBnb 가격 예측 

2019 New York City Airbnb Open Data를 머신러닝 모델에 적용하여 뉴욕 에어비앤비 가격을 예측해주는 웹 어플리케이션


```
< PROJECT ROOT >
   |
   |-- static                      # Implements app logic
   |     |-- css/style.css                # Base Blueprint - handles the authentication
   |          |-- img/background.jpg                # Home Blueprint - serve UI Kit pages
   |    
   |-- templates    
   |     |-- img/background.jpg
   |-- requirements.txt          # Development modules - SQLite storage
   |-- requirements-mysql.txt    # Production modules  - Mysql DMBS
   |-- requirements-pqsql.txt    # Production modules  - PostgreSql DMBS
   |
   |-- app.py                      # Inject Configuration via Environment
   |-- model.plk                 # Set up the app
   |-- model.py                   # Start the app - WSGI gateway
   |
   |-- ************************************************************************
