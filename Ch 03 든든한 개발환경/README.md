# 백엔드 공부하기
## npm, 린터, 포메터 공부하기
#### 작업하고 있는 프로젝트가 npm 이 관리하는 패키지라는것을 알려주기위해 package.json을 만들어 줘야한다
```
npm init -y
```
#### package.json은 package에 메타 데이터를 포함하고 있다 패키지를 만들게 아니라면 script 빼곤 지워줘도 된다 
```
{
  "name": "vscode-setup",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "script":{
    "test": "echo\ "Error: no test specified\" && exit 1"
  },
  "keyword": [],
  "author": "",
  "license": "ISC"
}

```
#### 호출하는 명령어는 npm run script 의 key 값을 넣어주면 된다
```
npm run test
```



