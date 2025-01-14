# 전자처방전 전자지갑 서비스 방갑다

---

![방갑다 서비스](https://github.com/user-attachments/assets/5d8fa7df-41ff-43c4-a920-d547e739b374)


배포 URL : [https://www.bangapda.com/](https://www.bangapda.com/)

## 💬 프로젝트 개요

---

**MZ세대를 위한 편리한 전자지갑 서비스는 이미 다양하게 존재하지만, 고령층 및 장애인 등 금융 소외계층을 위한 전자지갑 서비스는 아직 충분하지 않습니다. 비대면 금융이 점차 활성화되고 금융의 디지털화가 가속화되는 현 시점에서, 이들을 위한 맞춤형 UI와 기능을 갖춘 서비스가 필요한 시점입니다. 우리는 주민등록증뿐만 아니라, 장애인증, 건강보험증, 의료급여증, 장애인 증명서 등의 탑재 및 보험 청구 기능 등을 통합한 전자지갑을 개발하여, 이들에게 평생 금융 파트너로 자리매김하고자 합니다. 이를 통해 단순한 이윤 창출을 넘어, 동반 성장할 수 있는 바람직한 사회를 만들어 나가는 데 기여하고자 합니다.**

---

## 🧑‍🤝‍🧑 팀원 구성

---

| 한상민 | 김성헌 | 최규찬 | 임준수 | 김도은 | 문환희 |
| --- | --- | --- | --- | --- | --- |
| ![한상민](https://avatars.githubusercontent.com/u/105042038?v=4) | ![김성헌](https://avatars.githubusercontent.com/u/143686086?v=4) | ![최규찬](https://avatars.githubusercontent.com/u/169640483?v=4) | ![임준수](https://avatars.githubusercontent.com/u/123082095?v=4) | ![김도은](https://avatars.githubusercontent.com/u/109468226?v=4) | ![문환희](https://avatars.githubusercontent.com/u/109807723?v=4) |
| PM & Back End | Back End & Front End | Back End & Front End | Front End & UI/UX & Back End | Back End & CI/CD | Back End & AI |

### 🗓️ 개발 기간

---

2024.9.5 ~ 2024.9.11

- 아이디어 회의
- 개발 기획
- UI 설계

2024.09.12 ~ 2024.09.13

- 데이터베이스 스키마 설계
- UI 설계 및 수정
- 기능 명세서 작성
- API 명세서 작성

2024.09.14 ~ 2024.10.14

- 백엔드 개발 및 프론트엔드 개발
- 백엔드 프론트엔드 API 연동 및 디버깅
- CI/CD 설정 및 배포

2024.10.15 ~ 2024.10.16

- 프로젝트 발표 준비
- 프로젝트 발표

## 💻 개발 환경 및 기술

---

- Front End : Vue.js, PWA, TypeScript, FireBase, CVA(Class-Variancem-authority), Shadcn-Vue
- Back End : Spring Framework(6.x), Gradle(7.x), Spring Security(6.1.x), Fast API, MySQL, JWT, OAuth2
- 버전 관리 및 이슈 관리 : GitHub
- 협업 툴 : Notion, Slack, Discord
- CI/CD : GitHub Actions
- 배포 : AWS EC2
- UI/UX : Figma

## 📎 협업 과정

---

매주 1회씩 스크럼을 진행하며 진행상황을 공유. 컨벤션을 정해서 협업의 효율을 증대.

### 🧑🏻‍💻 브랜치 컨벤션

| 주요 브랜치 | 브랜치명 | 설명 |
| --- | --- | --- |
|  | develop | 기본 디폴트 브랜치 |
|  | release | 배포 브랜치 |
| 서브 브랜치 |  |  |
|  | feature/** | 기능 구현 브랜치 |
|  | hotfix/** | 긴급 수정 브랜치 |
|  | refactor/** | 리팩토링 브랜치 |

ex) `feature/login` : 로그인 기능 구현 브랜치

### 🗒️ 커밋 컨벤션

| `:tada:` | 🎉 | Init |  |
| --- | --- | --- | --- |
| `:sparkles:` | ✨ | Feat | 기능 구현 첫 커밋 할 때 |
| `:pencil2:` | ✏️ | Fix | 자잘한 코드 수정 |
| `:art:` | 🎨 | Refactor | 코드 수정 (기능 수정 없이 이쁘게 최적화) |
| `:ambulance:` | 🚑 | Hotfix | 급하게 치명적인 버그를 고쳐야하는 경우 |
| `:rewind:` | ⏪️ | Revert | 변경 사항 되돌리기 |
| **`:memo:`** | 🗒️ | docs | 문서 수정 (문서 추가, 수정, 삭제, README) |
| `:wrench:` | 🔧 | chore | 기타 변경사항 (빌드 스크립트 수정, assets, 패키지 매니저 등) |
| `:label:` | 🏷️ | rename | 파일 혹은 폴더명을 수정하거나 옮기는 작업만 한 경우 |
| `:coffin:` | ⚰️ | remove | 파일을 삭제하는 작업만 수행한 경우 |

### 💬 이슈 컨벤션

<aside>
💬 **`recommend`** **`custom`** **`not used`**

</aside>

🐛 **`bug`** : 버그 관련 Issue == 예기치 않은 문제 또는 의도하지 않은 동작이 발생

🛠️ **`fix`** : 버그 수정 관련 Issue == 버그 해결 등 기능 및 동작에 대한 수정

🔨 **`refactoring`** : 동작 결과에 대한 변경 없이 로직, 변수명 등을 변경

✨ **`feature`** : 새로운 기능 추가 관련 Issue == 기능 구현

---

✅ **`test`** : test 관련 Issue

📑 **`documentation`** : 문서화 관련 Issue == 문서 작성 및 수정

🎨 **`style`** : UI 관련 Issue에 사용

### 🗒️ PR 컨벤션

### Reviewer’s To-Do List

1. source-target 브랜치 확인
2. 코드 리뷰 꼼꼼히 하기
3. approve 하거나 리뷰 적기 (둘다 해도 좋음)
4. 백엔드는 작성자 제외하고 2명이상, 프론트는 작성자 제외하고 1명 이상의 approve를 얻어야 merge 가능

### Merge Request Body Template

<JIRA Issue Number> Header의 설명

```markdown
## 🔎 Summary

## 📑 Description

## 🔷 JIRA Issue Number

## ✅ Check List
- 소스-타겟 브랜치 확인하기
- 코드 리뷰하기
```

## 📎 데이터베이스 ERD

---

![image](https://github.com/user-attachments/assets/ca8e0bc5-f5e2-4e17-a03f-8f7ae25f3d19)


## ⚙️ 아키텍쳐 다이어그램

---

<img width="938" alt="image" src="https://github.com/user-attachments/assets/8cba61d0-ba6e-4d04-8184-b3329cf9be9c">


## 🔎 서비스 기능

---

### ✏️ 회원가입

<img width="918" alt="image" src="https://github.com/user-attachments/assets/063c9638-15a8-4531-92e0-e580c9ecf63d">


- 카카오 소셜 로그인으로 로그인
- 일반 회원, 의사, 약사로 선택해서 회원가입 가능
- 어플리케이션 설치 버튼으로 앱 설치처럼 바로가기 버튼 추가

### ✏️ 회원가입 (환자)

![image](https://github.com/user-attachments/assets/065a4098-b7ac-40f7-988b-767aaa8a09ed)


- 환자 회원은 계좌등록을 통해서 자동 결제 설정
- 알림 수신 동의를 필수로 함으로써 푸시알림을 필수적으로 설정

### ✏️ 회원가입(의사, 약사)

<img width="1129" alt="image" src="https://github.com/user-attachments/assets/91bbc334-e16f-44a4-99f3-c99f43ef6dcf">


- 각각 약사와 의사는 면허번호와 병원, 약국 주소를 기입하게 설정

### 📎 의사 처방전 작성

<img width="1066" alt="image" src="https://github.com/user-attachments/assets/cd91f491-ad29-4902-aa99-7bed5a47f602">

- 환자를 이름과 주민등록번호로 조회
- 질병 코드와 조제시 참고사항을 기입하도록 설정
- 약 등록 페이지에서 약을 선택, 아침, 점심, 저녁 별로 먹어야 할 약 개수와 총 복용일을 설정
- 해당 약들이 식후, 식전 몇분에 먹는지도 기입

### 📎 약사 처방전 QR 인식

<img width="1036" alt="image" src="https://github.com/user-attachments/assets/b61f9b31-be1f-4d89-a4ba-d75ac4f02acc">

<img width="1147" alt="image" src="https://github.com/user-attachments/assets/e1b9ab55-9b12-4cea-90e1-fb10ececa638">

- 환자의 처방전 QR을 찍을 수 있는 기능
- 해당 약국의 처방전 리스트들을 나열
- QR을 스캔하면 환자의 처방전이 기입되어 화면에 출력
- 해당 약들의 가격과 총 가격을 출력
- 결제 요청 버튼을 누르면 해당 환자에게 결제 알림 전송

### 📎 환자 메인 화면

<img width="1162" alt="image" src="https://github.com/user-attachments/assets/10f577db-7825-4e7e-b5cb-9c9378a2d17a">

- 아직 조제 받지 않은 처방전이 티켓형식으로 뜨도록 설정
- 약 받기 버튼을 누를 시, 해당 처방전의 QR이 생성
- 오늘 복용해야 할 약들이 출력되고 주의사항과 복용여부가 화면에 출력
- 복용여부를 터치로 설정가능
- 조제 받은 처방전을 기준으로 복용 주의사항, 운동 요령, 식단 등을 리포트로 분석
- 해당 리포트를 음성으로 출력
- 최근 5개의 처방전이 리스트로 출력

### 📎 환자 날짜 별 복용해야 할 약 리스트

<img width="1147" alt="image" src="https://github.com/user-attachments/assets/108886bc-be56-4f37-8f87-0e21405ea779">

- 날짜별로 복용해야 할 약 리스트 출력
- 확인 버튼으로 해당 약을 복용했는지 안했는지 체크 가능
- 터치 시, 해당 약에 대한 복용방법과 주의사항이 기입

### 📎 환자 처방전 상세 정보

<img width="1148" alt="image" src="https://github.com/user-attachments/assets/8a96fb38-7531-409c-a117-71bcef5d8fbb">

- 보험 청구 여부 확인버튼으로 청구 여부 체크
- 해당 앱으로 약을 수령하지 않았다면 체크하는 기능 추가
- 처방전의 개요(병원명, 의사명, 약국명, 약사명 등)이 표시
- 해당 처방전 원본과 전자 영수증 보기
- 처방전과 영수증을 PDF 파일로 저장 가능

### 📎 환자 마이페이지

<img width="1083" alt="image" src="https://github.com/user-attachments/assets/f4eed0f6-27fe-4a73-ac5c-308eefbd52c2">

- 해당 환자 회원의 계좌정보와 복약 시간이 출력
- 계좌정보 수정 가능
- 복약 시간을 수정함으로써, 복약 알림의 시간 설정 가능

## ⛏️ 이슈 해결 및 트러블 슈팅

---

- N+1 문제 해결 → 지연로딩으로 쿼리 호출 감소 시도
- 초기 로딩 시, 데이터의 과다한 요청으로 성능 지연 이슈 → 무한 스크롤로 페이지 전환없이 페이지네이션을 통한 데이터 로딩 최소화 시도
- 트랜잭션 매니저 충돌 → 트랜잭션 매니저가 두개였던 문제를 해결

## 🔎 개선 및 고도화 계획

---

<img width="1029" alt="image" src="https://github.com/user-attachments/assets/46335d71-9267-42ce-b16e-727d51e72797">

