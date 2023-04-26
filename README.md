# 👨‍👨‍👦‍👦 4조 우리 함께

<img src="https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0e410209-457a-4c22-9737-a1a4eff876b3/Untitled.png" width=1000px>


> 4조 우리 함께 자기소개 페이지

<aside>
📍 이준희, 이은엽, 김태홍, 이동현

이틀간 학습한 내용을 기반으로 팀원들중 비전공자도 있기에 각자의 수준을
고려하여 높은 수준의 화면구성을 하진 않았습니다.

비록 간단한 화면이지만 그동안 배운 내용들을 집약해서 만든 화면이기에
모두가 보람찬 시간이였습니다.

**>> 적절한 아이스브레이킹용 주제를 제시하며 대화주제 추천 시작**

# 🛠 개발 환경

![img](https://img.shields.io/badge/typescript-4.6.3-blue)
![img](https://img.shields.io/badge/ts--node-10.7.0-green)
![img](https://img.shields.io/badge/Mongoose-5.13.2-yellowgreen)
![img](https://img.shields.io/badge/Express-v4.18.1-green)

# ✉️ 프로젝트 폴더 구조

```
.
├── tsconfig.json
├── nodemone.json
├── package.json
└── src
    ├── config
    ├── controllers
    ├── interfaces
    ├── loaders
    ├── middlewares
    ├── models
          └── interface
    ├── modules
    ├── routes
    ├── services
    ├── types
    └──  index.ts
└── test
```

# ⚙️ Dependencies

```json
"devDependencies": {
  "@types/chai": "^4.3.1",
  "@types/cors": "^2.8.12",
  "@types/express": "^4.17.13",
  "@types/helmet": "^4.0.0",
  "@types/jsonwebtoken": "^8.5.8",
  "@types/mocha": "^9.1.1",
  "@types/mongoose": "^5.11.97",
  "@types/multer": "^1.4.7",
  "@types/multer-s3": "2",
  "@types/node": "^18.0.6",
  "@types/supertest": "^2.0.12",
  "@typescript-eslint/eslint-plugin": "^5.30.5",
  "@typescript-eslint/parser": "^5.30.5",
  "chai": "^4.3.6",
  "eslint": "^8.19.0",
  "eslint-config-airbnb-base": "^15.0.0",
  "eslint-config-airbnb-typescript": "^17.0.0",
  "eslint-config-prettier": "^8.5.0",
  "eslint-plugin-import": "^2.26.0",
  "eslint-plugin-prettier": "^4.2.1",
  "husky": "^8.0.1",
  "mocha": "^10.0.0",
  "nodemon": "^2.0.15",
  "supertest": "^6.2.4",
  "ts-node": "^10.9.1",
  "typescript": "^4.7.4"
},
"dependencies": {
  "@slack/client": "^5.0.2",
  "@types/bcrypt": "^5.0.0",
  "aws-sdk": "^2.1172.0",
  "bcrypt": "^5.0.1",
  "cors": "^2.8.5",
  "dotenv": "^16.0.0",
  "express": "^4.17.3",
  "express-validator": "^6.14.0",
  "helmet": "^5.1.0",
  "jsonwebtoken": "^8.5.1",
  "mongoose": "^6.3.1",
  "multer": "^1.4.4",
  "multer-s3": "2",
  "prettier": "^2.7.1",
  "slack-node": "^0.1.8"
}
```

# 📧API 명세서

[API 명세서 링크](https://joyous-ghost-8c7.notion.site/API-a2efdef81ae34b9c98bcf0d96cd5dd4f)

# 📋 Model Diagram

![image](https://user-images.githubusercontent.com/80771842/178112388-8ce96330-cae2-4169-b6de-7e66e4dac70f.png)

# ✉️ Commit Messge Rules

**서버** 들의 **Git Commit Message Rules**

- 반영사항을 바로 확인할 수 있도록 작은 기능 하나라도 구현되면 커밋을 권장합니다.
- 기능 구현이 완벽하지 않을 땐, 각자 브랜치에 커밋을 해주세요.

### 📌 Commit Convention

**[태그] 제목의 형태**

| 태그 이름 |                       설명                        |
| :-------: | :-----------------------------------------------: |
|   feat    |             새로운 기능을 추가할 경우             |
|    fix    |                 버그를 고친 경우                  |
|   chore   |                    짜잘한 수정                    |
|   docs    |                     문서 수정                     |
|   init    |                     초기 설정                     |
|   test    |      테스트 코드, 리펙토링 테스트 코드 추가       |
|  rename   | 파일 혹은 폴더명을 수정하거나 옮기는 작업인 경우  |
|   style   | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 |
| refactor  |                   코드 리팩토링                   |

### **커밋 타입**

- `[태그] 설명` 형식으로 커밋 메시지를 작성합니다.
- 태그는 영어를 쓰고 대문자로 작성합니다.

예시 >

```
  [FEAT] 검색 api 추가
```

## **💻 Github mangement**

**피클** 들의 WorkFlow : **Gitflow Workflow**

- Develop, Feature, Hotfix 브랜치

- 개발(develop): 기능들의 통합 브랜치

- 기능 단위 개발(feature): 기능 단위 브랜치

- 버그 수정 및 갑작스런 수정(hotfix): 수정 사항 발생 시 브랜치

- 개발 브랜치 아래 기능별 브랜치를 만들어 작성합니다.

## ✍🏻 Code Convention

[에어비앤비 코드 컨벤션](https://github.com/airbnb/javascript)

## 📍 Gitflow 규칙

- Develop에 직접적인 commit, push는 금지합니다.
- 커밋 메세지는 다른 사람들이 봐도 이해할 수 있게 써주세요.
- 작업 이전에 issue 작성 후 pullrequest 와 issue를 연동해 주세요.
- 풀리퀘스트를 통해 코드 리뷰를 전원이 코드리뷰를 진행합니다.
- 기능 개발 시 개발 브랜치에서 feat/기능 으로 브랜치를 파서 관리합니다.
- feat은 자세한 기능 한 가지를 담당하며, 기능 개발이 완료되면 각자의 브랜치로 Pull Request를 보냅니다.
- 각자가 기간 동안 맡은 역할을 전부 수행하면, 각자 브랜치에서 develop브랜치로 Pull Request를 보냅니다.  
  **develop 브랜치로의 Pull Request는 상대방의 코드리뷰 후에 merge할 수 있습니다.**

## ❗️ branch naming convention

- develop
- feature/issue_number or Short Description
- release/version_number
- hotfix/issue_number or Short Description

## 📋 Code Review Convention

- P1: 꼭 반영해주세요 (Request changes)
- P2: 적극적으로 고려해주세요 (Request changes)
- P3: 웬만하면 반영해 주세요 (Comment)
- P4: 반영해도 좋고 넘어가도 좋습니다 (Approve)
- P5: 그냥 사소한 의견입니다 (Approve)

- D-0 (ASAP)

긴급한 수정사항으로 바로 리뷰해 주세요. 앱의 오류로 인해 장애가 발생하거나, 빌드가 되지 않는 등 긴급 이슈가 발생할 때 사용합니다.

- D-N (Within N days)

“Working Day 기준으로 N일 이내에 리뷰해 주세요”

### 🙋🏻‍♀️ 담당

<details>
<summary>DB 설계</summary>
<div markdown="1">  
 
| 기능명 | 담당자 | 완료 여부 |
| :-----: | :---: | :---: |
| USER | 승빈 | ✅ |
| BALLOT | 가영 | ✅ |
| BOOKMARK | 동현 | ✅ |
| CARD | 승빈 | ✅ |
 
</div>
</details>

<details>
<summary>api 구현</summary>
<div markdown="1">

|               기능명               | Method | 담당자 | 완료 여부 |
| :--------------------------------: | :----: | :----: | :-------: |
| 간편 대화주제 카테고리 리스트 조회 |  GET   | `승빈` |    ✅     |
|  카테고리별 대화 주제 리스트 조회  |  GET   | `승빈` |    ✅     |
|     대화주제 추천 리스트 조회      |  GET   | `승빈` |    ✅     |
|               로그인               |  POST  | `동현` |    ✅     |
|            북마크 생성             |  POST  | `승빈` |    ✅     |
|            북마크 삭제             | DELETE | `승빈` |    ✅     |
|          유저 프로필 조회          |  GET   | `동현` |    ✅     |
|           투표 현황 조회           |  GET   | `동현` |    ✅     |
|          프로필 사진 수정          | PATCH  | `동현` |    ✅     |
|              투표하기              |  POST  | `가영` |    ✅     |
|       투표 주제 리스트 조회        |  GET   | `가영` |    ✅     |
|         북마크 리스트 조회         |  GET   | `동현` |    ✅     |
|            닉네임 수정             | PATCH  | `동현` |    ✅     |
|     Monthly 베스트 5 피클 조회     |  GET   | `가영` |    ✅     |
|              회원가입              |  POST  | `가영` |    ✅     |
|          비밀번호 재설정           | PATCH  | `가영` |  release  |
|          인증메일 보내기           |  POST  | `가영` |  release  |
|           인증 번호 확인           | PATCH  | `가영` |  release  |
|        공지사항 리스트 조회        |  GET   | `승빈` |  release  |
|         공지사항 상세 조회         |  GET   | `승빈` |  release  |

</div>
</details>

# Developers

|                                                                      윤가영                                                                      |                                                                        이동현                                                                        |                                                                      최승빈                                                                       |
| :----------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://user-images.githubusercontent.com/55686088/178484267-c6e315d1-e65c-4136-b387-8d198922b488.jpg" width="200px" height="200px" /> | <img src ="https://user-images.githubusercontent.com/55686088/178481391-5945e354-0549-43e8-b3de-cafafae76ae5.jpeg" width = "200px" height="200px" /> | <img src="https://user-images.githubusercontent.com/55686088/178481805-fc9f3aee-46d0-4bbf-bf4f-7b962a051ab7.jpeg" width="200px" height="200px" /> |
|                                                       [kyY00n](https://github.com/kyY00n)                                                        |                                                      [donglee99](https://github.com/donglee99)                                                       |                                                       [csb9427](https://github.com/csb9427)                                                       |
