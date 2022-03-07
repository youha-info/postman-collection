# Postman Collection

- Postman collection 을 공유하는 저장소입니다. 
- 외부 API 를 편리하게 사용하기 위해서 Postman collection 을 구성하고 사용할 수 있습니다.


## 파일 구조
```
├──.gitignore
├──.README.md
├──collections
│   ├── youtube [collection name]
│   │   └── file_name.json
│   └── ...
└──
```

- collections : postman collection 의 상위 폴더
    - collection name : collection 의 분류 명으로 Youha 로 예시를 들면 Package (youtubeChannel ...) 을 뜻한다.
        - file_name : collection 내에서 사용되는 API 


## 사용 방법
1. Postman 을 설치한다. 설치가 되어있지 않은 경우 다음 경로를 통해서 설치를 한다. [Postman Download](https://www.postman.com/downloads/)
2. Repository 를 clone 받는다. 
3. Collections 의 file_name.json 파일을 Postman 에 Import 작업을 한다.

- 사용자가 팀원들이 필요할 수 있는 collection 또는 API 를 추가했으면 PR 을 통해 업데이트 한다.

## 주의 사항
- 사용하고있는 API 중 secret 등 민간함 정보가 있다면 빈칸 또는 `-` 값을 넣어서 배포하도록한다.

