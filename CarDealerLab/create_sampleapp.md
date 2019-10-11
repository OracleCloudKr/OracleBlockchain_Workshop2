# Client용 Web Application 준비하기
이 Lab은 제조사와 Dealer에서 사용하는 Application을 준비하는 과정입니다. 자동차의 부품과 자동차에 대한 정보와 소유권은 체인코드를 통해 Blockchain Platform에 저장이 되게 됩니다. 이 체인코드는 SDK를 사용하거나 REST API를 통해서 호출할 수 있습니다. 여기서는 node.js용 application을 통해서 호출하게 됩니다. 먼저 node.js를 설치한 후에 web application을 실행해보도록 하겠습니다.

### 1. 로컬에 node.js 설치하기
먼저 https://nodejs.org/ko/download/ 에서 node.js를 로컬 컴퓨터에 다운로드 받은 후 실행해서 설치하시기 바랍니다.

### 2. 준비된 web application 다운로드 하기
node.js 용 web application ([다운로드](https://github.com/OracleCloudKr/OracleBlockchain_Workshop2/raw/master/CarDealerLab/artifacts/auto_webapp.zip))

### 3. 실행하기
1) 압축을 푼 후 auto_webapp/bin 디렉토리로 이동한 후 run을 (윈도우는:run.cmd, 맥은 터미널에서 run.sh)를 실행합니다.
윈도우의 경우 방화벽 오픈을 위해 다음과 같은 메세지가 나오게 되는데 이때 액세스 허용을 눌러 줍니다.
.
![](images/firewall.png)

2) 화면에서 다음과 같이 나오게 되면 8000 포트로 web application이 정상적으로 Listen하며 서비스가 되게 됩니다.
PORT: 8000, PROTOCOL: htt

3) 이제 브라우저를 열고 해당 포트로 접속해 봅니다.
http://localhost:8000/
![](images/webapp_init.png)

4) 오른쪽 상단의 동그라미 설정 버튼을 눌러 환경설정 화면으로 이동합니다.
5) 
6) 
---
[이전 Lab으로 이동](README.md)