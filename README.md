## 배추 가격 예측 인공지능 소프트웨어
배추 가격을 예측하는 인공지능 소프트웨어입니다.

나동빈씨의 유튜브 강의를 참고하여 실습하였습니다.

[유튜브 링크](https://www.youtube.com/watch?v=wZvhBVqitn8&list=PLRx0vPvlEmdAbnmLH9yh03cw9UQU_o7PO&index=13)
[깃허브 링크](https://github.com/ndb796/vegita)


## 시스템 구성도
![시스템 구성도](https://user-images.githubusercontent.com/51303547/60179733-49d94d80-9859-11e9-90e8-a7b0fcb22e36.png)

## 참고 문헌
[기상청 전국 기온 및 강수량](https://data.kma.go.kr/climate/StatisticsDivision/selectStatisticsDivision.do?pgmNo=158) : 기상청 정보를 토대로 채소 가격에 영향을 미치는 요인을 분석하기 위해 참고하였습니다.

[월별 배추 가격](https://www.kamis.or.kr/customer/price/retail/period.do?action=monthly&yyyy=2018&period=10&countycode=&itemcategorycode=200&itemcode=211&kindcode=&productrankcode=&convert_kg_yn=N) : 실질적인 국내 월별 배추 가격을 분석하기 위해 참고하였습니다.

## 서버 실행 및 웹사이트 접속
본인이 원하는 경로에 파일을 다운받으셨다면 cmd창에서 해당 경로에 Web 폴더까지 이동합니다.
ex) D:\Python\AI-Website-master\Web 
python server.py 명령으로 server 파일을 실행해준뒤
브라우저에서 Flask 기본 포트번호인 5000번으로 접속합니다.
localhost:5000
