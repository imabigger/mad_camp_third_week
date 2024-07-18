## Outline

---

**Momentum**, 즉 운동량은 뉴턴 역학에서 물체의 질량과 속도의 곱으로 나타내는 물리량입니다. 

빠르게 움직이는 무거운 트럭이 있다고 가정해봅시다. 이 트럭은 운동량이 무척 클 것입니다. 이 트럭을 정지시키기 위해서는 어떻게 해야할까요?

어떤 선택이든, 트럭은 멈출수도, 쌩 하고 지나갈 수 도 있습니다.

*“모맨텀”, 하나의 움직임이 미래를 좌우한다.*

우리의 앱은 **Chat gpt api**를 이용해서, Text Rpg를 지원합니다.

사용자는 미리 만들어진 주제와, 선택한 키워드들을 이용해 가상의 세계를 탐험할 수 있습니다.

### Tech Stack

**Frontend**: React Native, Type Script (이효정)

**Backend**: Spring Boot(3.x) (이시준)

**Cloud**: Amazon Web Service

## Team

---

한양대학교 수학과 22학번 [이시준](https://www.notion.so/292bd77fee6748ca9ba5e5ad8e319051?pvs=21) 

[imabigger - Overview](https://github.com/imabigger)

한양대학교 컴퓨터소프트웨어학부 22학번 [이효정](https://www.notion.so/9b8328334b434e68840073cfc142c984?pvs=21) 

[LeeHyo-Jeong - Overview](https://github.com/LeeHyo-Jeong)

## Details

---

기본 생명력은 10이 주어집니다.

### 1) Splash Screen

[Screen_Recording_20240717_190402_momentum.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/d6491973-627a-43fa-a64d-c667eb8b87b8/Screen_Recording_20240717_190402_momentum.mp4)

### 2) Game Play Screen



https://github.com/user-attachments/assets/124890c7-603e-4b40-a167-432449e2008d

2-1) 회원가입 

토큰 발행

2-2) 로그인 

토큰 발행 

2-3) 홈스크린

- 최고기록
    
    스토리와 유저의 선택에 따라 gpt가 스코어를 생성합니다.
    
- 새 게임
- 기존 게임 로드

2-4) 새게임 - 주제 선정 

미래 중세 공포 우주

2-5) 각 주제 마다 키워드 3개 이하 선정 ( story 스타일 결정)

2-6) 방 제목 

2-7) 게임 캐릭터 초기 능력치 배분

- hp는 기본으로 10으로 주어집니다.

2-8) 게임 플레이 화면

- AI로부터 스토리와 그 다음 선택지가 주어집니다.
- 우측 위에 프로필 클릭시, 현재 캐릭터 스탯 및 아이템이 확인 가능합니다.


### 3) Game Over Logic

[Screen_Recording_20240717_204631_momentum.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/24d16cff-1eef-4368-9cce-7ffa1a23f7ef/Screen_Recording_20240717_204631_momentum.mp4)

## Api 및 스키마

---

<img width="1696" alt="스크린샷 2024-07-18 오후 1 30 43" src="https://github.com/user-attachments/assets/d302f323-83c1-4e97-84a0-d766d241f9b6">


<img width="1075" alt="스크린샷 2024-07-18 오후 1 31 22" src="https://github.com/user-attachments/assets/be7ae896-38c0-48b8-9f33-e32f895d6702">

