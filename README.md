# Docker

docker ps // 실행중인 컨테이너 조회 
docker ps -a // 중지중인 컨테이너까지 모두 조회 
docker images // 이미지 조회 
docker rm 컨테이너ID // 컨테이너 삭제, 중지된 것만 삭제가능
docker stop 컨테이너ID // 컨테이너 중지 
docker rmi 이미지명 // 이미지 삭제 
docker start 컨테이너ID // 컨테이너 시작 
docker restart 컨테이너ID // 컨테이너 재부팅 
docker attatch 컨테이너ID // 실행 중인 컨테이너에 접속


옵션     설명
-d      detached mode 흔히 말하는 백그라운드 모드
-p      호스트와 컨테이너의 포트를 연결 (포워딩)
-v      호스트와 컨테이너의 디렉토리를 연결 (마운트)
-e      컨테이너 내에서 사용할 환경변수 설정
–name   컨테이너 이름 설정
–rm     프로세스 종료시 컨테이너 자동 제거
-it      -i와 -t를 동시에 사용한 것으로 터미널 입력을 위한 옵션
–link   컨테이너 연결 [컨테이너명:별칭]
