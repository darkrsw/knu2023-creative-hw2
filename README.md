# 실습과제 2번

### 기본 동작
```
$ curl -X GET http://localhost:8000/review-sentiments?appid=APPID
```
이 때 각 parameter의 기본 값은
- count: 10
- lang: `en`
- country: `us`

### 모든 옵션 부여
```
$ curl -X GET http://localhost:8000/review-sentiments?appid=APPID&count=10&lang=en&country=us
```

### 일부 옵션만 부여
```
$ curl -X GET http://localhost:8000/review-sentiments?appid=APPID&count=10&lang=en
```
