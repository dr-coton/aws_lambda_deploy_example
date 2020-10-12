# AWS Lambda 서버리스 배포 

AWS Lambda 서버리스 코드를 Github Action 을 이용하여 배포하는 것을 연습하기 위한 Repo 입니다. 

## Build 

### 초기 설정 

1. Node.js 12.x 버전 설치 
2. npm, yarn 설치 

### Local 환경 테스트 
```bash
yarn dev   
```

### Serverless Offline 테스트 
```bash 
yarn offline 
```

### Custom 도메인 

#### 도메인 생성 
```bash
serverless create_domain
```

#### 배포 
```bash
serverless deploy
```

#### 도메인 삭제 
```bash 
serverless delete_domain
```

## Reference 

