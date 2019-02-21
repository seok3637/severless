# Serverless Region Error issue

*Serverless 구축완료 후 서버가동하여 접속 TEST 진행 오류 발생
curl localhost:8080 --> hello World 출력 (정상)
curl localhost:8080/todo --> 무응답 (정상)
{"message":"Missing region in config","code":"ConfigError","time..~} (오류)

npm start 하기전 export 처리함
* export AWS_REGION=us-east-2 (리전값은 cloud9 설치 리전 값)
