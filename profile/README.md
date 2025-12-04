# 스택가이즈 (Stack Guys)

- 크래프톤 정글 10기 나만무 프로젝트

## ✨ 프로젝트 한줄 소개
- 귀여운 외형과 반전 난이도를 가진 실시간 멀티플레이 장애물 레이스 웹 게임입니다.  
똑똑한 AI 봇과 재미난 아이템들이 곳곳에 배치되어 있어 매 경기마다 색다른 재미를 제공합니다.

## 🚀 발표영상 & 포스터

### 발표영상
[![발표영상](https://ytcards.demolab.com/?id=Fh3Ibfskyzw&title=발표영상&lang=ko&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=1&width=300&border_radius=5)](https://youtu.be/Fh3Ibfskyzw)

### 포스터
![나만무-포스터](https://github.com/user-attachments/assets/e3414ea0-205b-495d-a045-44de0a59d5e7)


## 🧭 프로젝트 개요
- 플레이어 + AI 봇 혼합 레이스
- 실시간 충돌/점프/다이브/잡기 등 풀 커맨드 지원
- 폭탄 / 점프 강화 / 속도 증가 / 무적 버프 등 다양한 아이템을 활용해 전략적인 플레이 가능
- 문이 열리고 닫히는 구조물, 움직이는 발판, 점프 패드 등 동적인 맵 요소로 매 판마다 다른 변수 발생
- Headless 서버 + Proximity 기반 네트워크 최적화로 다수의 플레이어와 봇도 안정적으로 처리

## 🏗️ 아키텍처 개요
### 🎮 Game Engine
- Unity 6.0
- Unity Netcode for GameObjects(NGO)

### 🧵 Server
- Unity Headless Server
- UnityTransport (WebSocket 사용)
- Proximity 기반 NetworkVisibility

### 🤖 AI Bot
- Unity Navigation(NavMesh, NavMeshAgent, NavMeshLink) 기반 서버 권위 AI

### 🎨 기타
- websocket-sharp 기반 부하 테스트
- 부하 테스트용 C# ConsoleApplication
  
## 📦 레포지토리
- [게임](https://github.com/May-I-Game/stack-guys)
- [인프라](https://github.com/May-I-Game/stack-guys-web)

## ✍️ 커밋 규칙 (Conventional Commits)

- 커밋 종류

  ```
  - feat 		: 새로운 기능 추가
  - fix 		: 버그 수정
  - docs 		: 문서 수정
  - refactor 	: 코드 리팩터링
  - comment   : 필요한 주석 추가 및 변경
  - test 		: 테스트 코드, 리팩토링 테스트 코드 추가
  - chore     : 빌드 업무 수정, 패키지 매니저 수정, 파일 혹은 폴더명 수정 및 삭제
  - style     : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
  - init      : 프로젝트 초기 생성
  ```

- 커밋 메시지 구조

  ```
  feat: 전체 내용 요약

  - 변경 사항 1
  - 변경 사항 2
  - 변경 사항 3
  ```
## 👨‍💻 팀원 소개 및 연락처
| Role | Member | Contact & Profile |
| :--- | :--- | :--- |
| **👑 Leader** | **강경찬** | [![Email](https://img.shields.io/badge/Gmail-kangkc09-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kangkc09@gmail.com) [![GitHub](https://img.shields.io/badge/Github-kkc1383-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kkc1383) |
| **🎮 Client** | **김도훈** | [![Email](https://img.shields.io/badge/Gmail-lookau1004-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lookau1004@gmail.com) [![GitHub](https://img.shields.io/badge/Github-sisyphusman-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sisyphusman) |
| **🖥️ Server** | **서 정** | [![Email](https://img.shields.io/badge/Gmail-seo980620-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:seo980620@gmail.com) [![GitHub](https://img.shields.io/badge/Github-sjk2915-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sjk2915) |
| **🎮 Client** | **이정호** | [![Email](https://img.shields.io/badge/Gmail-ljh991106-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ljh991106@gmail.com) [![GitHub](https://img.shields.io/badge/Github-JGLeejungHo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JGLeejungHo) |
| **♾️ DevOps** | **전석모** | [![Email](https://img.shields.io/badge/Gmail-wjstjrah2000-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wjstjrah2000@gmail.com) [![GitHub](https://img.shields.io/badge/Github-Seok--more-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Seok-more) |
     










