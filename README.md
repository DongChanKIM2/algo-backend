# connect mysql by docker-compose
- server 전체를 dockerfile로 이미지화해 build 된 index.js 실행 
  - 도커파일 스크립트 작성
  - docker build . -t algo-backend
    - 도커파일로 이미지 생성
    - docker build <Dockerfile 경로> -t <생성할 이미지 이름>
- docker-compose에서 Mysql, server 이미지 연결
