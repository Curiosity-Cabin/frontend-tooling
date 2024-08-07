
### 👀 프론트엔드 개발에 왜 Node.js 가 필요할까?

1. 최신 스펙


> `babel` 이나 `WebPack` 같은 기술들은 대부분 `Node` 위에서 돌아가는 기술들이다.
> `TypeScript` , `SASS` 같은 고수준 프로그래밍 언어는 `트랜스파일러`가 필요한데, `Node` 환경이 뒷받침 되어야 한다.


2. 빌드 자동화

> 압축 > 난독화 작업 등을 거친 후 배포하는데 빌드 과정을 이해하는데 큰 역할을 한다.


3. 커스터마이징

> 개발 환경에서 툴을 그대로 사용할 수 없는 경우가 있을 때에는 `Node` 의 이해를 바탕으로 개발 환경을 구성하기 수월하다.

</br>

### 📌 Node.js 설치

https://nodejs.org/en

terminal 에서 node 명령어 입력 후 node cmd 창 확인 가능
> `node --version` / `npm`
>

<img width="200" alt="스크린샷 2024-08-07 20 22 12" src="https://github.com/user-attachments/assets/a68de235-e792-46e4-95ad-20b023003754">


![image](https://github.com/user-attachments/assets/2fdb0ab1-5cbe-4a73-b600-10bb0b1b585c)

### Project 생성

```bash
mkdir sample
cd sample

//project 생성하는 명령어 및 프로젝트 메타 정보를 입력할 수 있는 화면 제공
sample npm init
//npm init 으로 명령어를 입력해야 수행 가능
```
<img width="467" alt="스크린샷 2024-08-07 20 45 16" src="https://github.com/user-attachments/assets/7d5c96dd-d1b7-4afe-b4ff-82790ce232ab">

-> 수행 후에 확인해보면 `package.json` 이라는 파일이 생성되어 있다.

에디터로 열어보면 다음과 같다. 
<img width="562" alt="스크린샷 2024-08-07 20 45 46" src="https://github.com/user-attachments/assets/dad87961-2052-444e-bd1c-b2b8b4c15ddb">


### 프로젝트 명령어

<img width="408" alt="스크린샷 2024-08-07 20 47 34" src="https://github.com/user-attachments/assets/47870f3e-5de7-4636-9deb-6dd999d13b13">


terminal 을 이용해서 `npm test` 를 통해 test script 를 돌려보면 package.json 의 script 를 확인할 수 있다.

### npm command

npm 에서 사용하는 command 를 확인하려면 `npm` 명령어를 통해 확인할 수 있다.

```bash
All commands:

    access, adduser, audit, bugs, cache, ci, completion,
    config, dedupe, deprecate, diff, dist-tag, docs, doctor,
    edit, exec, explain, explore, find-dupes, fund, get, help,
    help-search, hook, init, install, install-ci-test,
    install-test, link, ll, login, logout, ls, org, outdated,
    owner, pack, ping, pkg, prefix, profile, prune, publish,
    query, rebuild, repo, restart, root, run-script, sbom,
    search, set, shrinkwrap, star, stars, start, stop, team,
    test, token, uninstall, unpublish, unstar, update, version,
    view, whoami

```

### command 를 추가하려면?
추가하고자 하는 command를 scripts 안에 작성한다.
```json
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "echo \"여기에 빌드 스크립트 command를 추가합니다\""
  },
```

`npm run build` 와 같이 command 를 build 하면 된다.

<img width="463" alt="스크린샷 2024-08-07 20 48 03" src="https://github.com/user-attachments/assets/c9392fc5-a6ed-4da7-b743-5abf4c24788b">


