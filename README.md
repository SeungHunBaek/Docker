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
