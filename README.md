# 🎬 PICKY - 영화 리뷰와 소셜플랫폼

<br />

[**PICKY**](https://www.picky-movie.com/)는 사용자가 선택한 영화 장르에 맞춰 영화를 추천받고, 영화 정보를 확인하며 리뷰를 남길 수 있는 플랫폼입니다. 또한, 영화를 사랑하는 사람들을 위한 소셜 기능을 제공하여, 특정 영화에 대한 관람평이나 관련 이야기를 다른 사용자들과 자유롭게 공유하고 소통할 수 있는 영화 리뷰 및 소셜 플랫폼 서비스입니다.

<br />

PICKY 이용해 보기 🐻 https://www.picky-movie.com/
<br />
<br />

![image](https://github.com/user-attachments/assets/22363d08-85f1-47db-9039-b082db4ceeaa)

<br/>
<br/>

# 🧑🏻‍💻 팀원 정보

|                      <img src="https://avatars.githubusercontent.com/u/94373324?v=4" width=150px>                       |      <img src="https://avatars.githubusercontent.com/u/96944509?v=4" width=150px>      |      <img src="https://avatars.githubusercontent.com/u/98721817?v=4" width=150px>      |      <img src="https://avatars.githubusercontent.com/u/166271843?v=4" width=150px>      |
| :---------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
|                                        [조계원](https://github.com/JGW-Korea)                                        |                          [전경원](https://github.com/jeonkyungwon)                           |                       [손성욱](https://github.com/ssohn3)                        |                       [최우진](https://github.com/jinnius02)                        |
|                                 [jgw6372@gmail.com](mailto:jgw6372@gmail.com)                                 |                   [ashjkw3218@gmail.com](mailto:ashjkw3218@gmail.com)                    |                   [sws19960708@gmail.com](mailto:sws19960708@gmail.com)               |                   [mostwj@gmail.com](mailto:mostwj@gmail.com)                |
|메인페이지 <br/> 장르 페이지 <br/> 관리자 페이지 <br/> 관리자 추천 영화 플레이리스트 페이지 <br/> 마이페이지 <br/> 알람 페이지 <br/> 스켈레톤 UI <br/> 로딩&splash | 프론트엔드 CI/CD 구축 <br/> 모든&영화 별 무비로그 조회 페이지 <br/> 무비로그 페이지 <br/> 무비로그 CRUD <br/> 무비로그 상세 페이지 <br/> 마이페이지 무비로그 탭|  소셜 로그인 / 회원가입 <br/> 검색 페이지 <br/> 영화 추천 페이지  |영화 상세 페이지 <br/> 영화 비하인드 모달창 <br/> 한줄평 CRUD <br/> 팔로우&팔로잉 <br/> |

<br />
<br />

# 🛠️ 기술 스택

|  |  |  |  |
|-----------------|----------------|----------------|----------------|
| <img src="https://i.namu.wiki/i/EY559r31H-um8uTtptPIbCZoBGxsumSlwEH0T_rA6WmxQq1UwqyAf3cJQJXN7Fv5CoEz0kv5CBXzjkkPU_XWig.svg" alt="TypeScript" width="100"> | <img src="https://github.com/user-attachments/assets/e3b49dbb-981b-4804-acf9-012c854a2fd2" alt="React" width="100"> | <img src="https://ko.vite.dev/logo.svg" alt="Vite" width="100"> | <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSii2UcY9fK5WXXPfa2z7urgqOcq63L5SObJQ&s" alt="Recoil" width="100"> |
| TypeScript | React | Vite | Recoil |
| <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTKIe10L8m6JqDfjl_5BFRTz8yHoowQUgW6cA&s" alt="Emotion" width="100"> | <img src="https://blog.kakaocdn.net/dn/997rV/btsIkARkTej/PdtiBI82EnMzFQjgHkbuI1/img.png" alt="Storybook" width="100"> | <img src="https://t1.kakaocdn.net/kakao_tech/image/2022/06/images/01.png" alt="React Query" width="100"> |  |
| Emotion | Storybook | React Query |  |

<br />
<br />

# 📁 디렉토리 구조

```planeText
LG-Uplus-Movie-SNS-PICKY-FE/
│
├── public/                         // 정적 파일 (HTML, 이미지 등)
│   
├── src/                            // 소스 코드 폴더
│   ├── api/                        // 서버 API 관리
│   │
│   ├── assets/                     // 정적 파일 (이미지, 폰트 등)
│   │   ├── icons/                  // 아이콘 파일
│   │   └── images/                 // 이미지 파일
│   │
│   ├── stories/                    // 전역에서 재사용 가능한 UI 컴포넌트
│   │   └── ComponentName/
│   │       ├── index.tsx           // 컴포넌트 코드
│   │       ├── index.style.tsx     // 스타일 코드
│   │       └── index.stories.tsx  // Storybook 스토리 파일
│   │
│   ├── constants/                 // 프로젝트 전역 상수
│   │   ├── errorCodes.ts          // 에러 코드 정의
│   │   ├── routes.ts              // 라우트 상수
│   │   └── globalConstants.ts     // 기타 글로벌 상수
│   │
│   ├── hooks/                     // 커스텀 훅
│   │
│   ├── pages/                     // 각 페이지별 컴포넌트
│   │   └── PageName/              // 예: 특정 페이지
│   │       ├── index.tsx          // 페이지 메인 컴포넌트
│   │       ├── index.styles.tsx   // 페이지 스타일 파일
│   │       └── components/        // 페이지 전용 하위 컴포넌트
│   │           └── ComponentName
│   │              ├── index.tsx
│   │              └── index.styles.tsx
│   │
│   ├── recoil/                    // 상태 관리 (Recoil)
│   │   ├── atoms/                 // Recoil Atom 정의
│   │   └── selectors/             // Recoil Selector 정의
│   │
│   ├── styles/                    // 글로벌 스타일 및 테마
│   │
│   ├── types/                     // TypeScript 타입 정의
│   │   ├── api.ts                 // API 관련 타입
│   │   ├── components.ts          // 컴포넌트 관련 타입
│   │   └── pages.ts               // 페이지 관련 타입
│   │
│   ├── routes/                    // 라우팅 관련 설정
│   │   ├── index.tsx              // 메인 라우팅 설정
│   │   └── privateRoutes.tsx      // Private Route 설정
│   │
│   ├── App.tsx                    // 메인 리액트 컴포넌트
│   └── main.tsx                   // 애플리케이션 진입점
│
├── vite.config.ts                 // Vite 설정 파일
├── package.json                   // 프로젝트 설정 파일
└── yarn.lock                      // 패키지 버전 관리 파일
```

---

### 설치 및 실행 방법

```bash
// 프로젝트 Clone 방법
git clone https://github.com/LG-Uplus-Movie-SNS-PICKY/PICKY-FE.git
cd LG-Uplus-Movie-SNS-PICKY

// 의존성 설치
yarn intall

// 패키지 추가
yarn add { 패키지명 }

// 로컬 서버 실행
yarn dev
```

---

<br />
<br />

# 📱 기능 상세
### 1. 소셜 로그인 / 회원가입
카카오, 네이버, 구글 로그인을 통해 서비스 이용이 가능해요!
![image](https://github.com/user-attachments/assets/db36f5b8-f7d6-40fb-9328-44ee7295051b)

<br/>

회원가입을 통해 개인 맞춤형 AI 추천을 받을 수 있어요!
![image](https://github.com/user-attachments/assets/923ec926-de11-4f14-83a3-f67598c77979)

<br/>

### 2. 메인 페이지
메인페이지에서 다양한 영화 콘텐츠를 추천 받을 수 있어요!
![image](https://github.com/user-attachments/assets/f83b0df2-da46-4d16-bedc-7cc605cc6617)

<br/>

### 3. 장르 페이지
장르 별 추천 영화를 볼 수 있어요!
![image](https://github.com/user-attachments/assets/491c3ca7-424a-4a1e-9907-b91fbf438390)

<br/>

### 4. PICKY / 추천 페이지
개인 맞춤형 AI 추천 영화 확인이 가능하고 관리자 추천 영화 플레이 리스트를 제공 받을 수 있어요!
![image](https://github.com/user-attachments/assets/8dd8595d-561a-4cbe-91f5-83e29fe568c2)

<br/>

### 5. 검색 페이지
Elasticsearch를 통해 연관 검색어 자동 완성이 가능하고 최근 검색어를 확인할 수 있어요!
![image](https://github.com/user-attachments/assets/517441b5-49e9-43cc-9dd2-aac8c6691259)

<br/>

### 6. 영화 상세 페이지
영화에 대한 상세 정보를 확인할 수 있어요!
![image](https://github.com/user-attachments/assets/45f95622-8424-4fd1-a55b-d7f83933bcde)

<br/>

### 7. 한줄평 페이지
한줄평을 조회, 등록 할 수 있고 데이터 기반 평점 분석이 가능해요!
![image](https://github.com/user-attachments/assets/185dd46e-d031-4d58-b816-4634c1676026)

<br/>

### 8. 무비로그 페이지 
Elasticsearch 자유롭게 영화에 대한 게시글을 등록/수정할 수 있어요!
![image](https://github.com/user-attachments/assets/7c953f62-42bb-4c64-afcc-7e8434195fe6)

<br/>

무비로그 소셜 피드에서 게시글을 조회하고 좋아요를 누르고 삭제하며 댓글 또한 남기면서 사람들과 자유롭게 소통할 수 있어요!
![image](https://github.com/user-attachments/assets/a24a455a-e9ec-42fc-9358-fb5f1da57ae1)

<br/>

### 9. 마이 페이지
내가 작성한 게시글, 한줄평, 좋아요한 영화에 대한 나만의 기록을 확인하고 프로필을 수정할 수 있어요!
![image](https://github.com/user-attachments/assets/9792dcdc-5128-4749-97e6-b5a123cbe83c)

<br/>

팔로우 / 팔로잉 목록을 확인하고 다른 유저를 팔로잉 할 수 있어요!
![image](https://github.com/user-attachments/assets/2fc2b7ed-852b-4b9d-a699-37daeace20c8)

<br/>

### 10. 알림 페이지
내가 좋아요한 영화 관련 게시글에 대한 알람을 받을 수 있어요!
![image](https://github.com/user-attachments/assets/d0a6c918-0926-44f5-87fa-66b7319ec192)

### 11. 관리자 페이지
관리자 기능을 통해 서비스를 관리할 수 있어요!

<br/>

# ℹ️ 공통
![PICKY-ERD](https://github.com/user-attachments/assets/a3426484-77e3-4729-bebb-c71f85675754)
[배포 주소](https://d3hxz5yj62y98w.cloudfront.net/)<br />
[피그마 페이지](https://www.figma.com/design/rpAlhiLds5pygwPfPpD4lp/PICKY-%EB%94%94%EC%9E%90%EC%9D%B8-%EC%99%84%EC%84%B1%EB%B3%B8?node-id=0-1&node-type=canvas&t=pwFCyVmMoN1a41le-0)<br />
[문서화(Notion)](https://glass-joggers-e59.notion.site/PICKY-13c9fc77f3f6802ab7f1c2ee59b3aa8c?pvs=74)
[요구사항 정의서](https://docs.google.com/spreadsheets/d/1puQoU2lwXWyVLx6mc33PdlVW_YVREmc3yd3hdZeMDHE/edit?usp=sharing)<br />
