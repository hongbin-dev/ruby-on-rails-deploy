## 레일즈 API 개발 및 배포하기


### STEP 1
**환경 설치 및 레일즈 프로젝트 시작하기**

프로젝트 클론받기

```bash
git clone https://github.com/khb1109/ruby-on-rails-deploy.git
```


프로젝트 경로이동
```bash
cd ruby-on-rails-deploy
```

루비가 설치된 환경 다운 및 실행
```bash
docker-compose up -d
```


도커환경 배쉬로 진입
```bash
docker exec -it ubuntu /bin/bash
```


배쉬 내에서 프로젝트 생성
```bash
rails new my-app && cd my-app
```

---


### STEP 2 
**개발하기**

```bash
rails s -b 0.0.0.0
```

### STEP 3
**Capistrano로 배포하기**