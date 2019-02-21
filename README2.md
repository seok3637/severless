# Serverless Region Error issue

*Serverless 구축완료 후 서버가동하여 접속 TEST 진행 오류 발생 <br>
curl localhost:8080 --> hello World 출력 (정상) <br>
curl localhost:8080/todo --> 무응답 (정상) </br>
{"message":"Missing region in config","code":"ConfigError","time..~} (오류) <br>
<p></p>
npm start 하기전 export 처리함 <br>
* export AWS_REGION=us-east-2 (리전값은 cloud9 설치 리전 값)<br>
