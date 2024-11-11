게임의 간단한 소개
-게임 컨셉은 공포게임이다. 간단한 스토리 공포게임같은 느낌인데 우리나라든 어디마다 있는 괴담이나 시험중에 “절대 뒤를 돌아보지 마” 같은 내용에서 가져왔다.
게임은 어떤 숲에서 눈을 뜬 주인공인 집으로 돌아가는 이야기이고 주인공은 아무것도 하지말고 그저 집으로 가라고 들은 후 집으로 가는 중에 다른 행동을 할 때 마다 죽게되는 그런 공포게임이다. 아무것도 안하고 집에 도착하면 게임이 끝난다.
핵심 메카닉은 주인공이 좌우(,a,d)로 움직이고 이때 상호작용을 줄 수 있는 곳에 상,하키(w,s)로 상호작용이 가능하게 만들 것이다.(상호작용하면 죽는다)
![1](https://github.com/user-attachments/assets/195dfe2a-861b-46eb-a6a6-32edfdb2fa8e)
![2](https://github.com/user-attachments/assets/8abe126b-d392-414e-9dc5-fba71d3fec00)
![3](https://github.com/user-attachments/assets/6d080e65-0d46-41e6-986a-3c0ab92f47d5)

예상 게임 실행 흐름
처음시작에서 눈을 뜸 -> 경고를 받거나,집으로 가기 시작-> 계속 오른쪽으로 감-> 다른것에 상호작용시 사망->계속 아무것도 안하고 가기만 함-> 집 도착 시 게임 끝
![4](https://github.com/user-attachments/assets/9eaa3d05-d9bc-41a1-978e-cb47d50d40de)
![2](https://github.com/user-attachments/assets/ddd9f661-4edd-4fda-a801-652beef922ee)
![5](https://github.com/user-attachments/assets/532154a0-af2b-43d6-9261-e20ce4413140)

개발 내용
scene의 종류는 처음 시작하는 메뉴, 배경, 주인공, 상호작용시 나타나는 씬(사망 씬),키 설명씬 정도가 있다.
+메뉴씬이라기 보단 처음 시작하기전 씬이다. 배경(기본)은 6개에 씬으로 구성되어있고 상호작용씬은 데드씬으로 총 4개에 데드씬이 있다. 그외에 엔딩씬(게임이 끝날때 나오는씬)하나가 있다
전환 규칙은 배경씬은 주인공이 다음으로 넘어갈 때, 상호작용 씬은 주인공이 다른 상호작용을 클릭했을시 ,메뉴는 처음 등장할 때, 게임을 클리어 했을 때, 설명씬은 I키를 누르면 발동.
게임 프레임 워크에서 랜더링,입렵처리 정도를 사용할 것 같다.
+class에는 player, secene관리 정도 사용할것 같다.

게임 프레임 워크
기본 기능은 pico2d를 사용할 예정이다. 추후 다른 기능이 추가될 수 있다.

일정
10/28일 전까진 게임의 구성을 모두 설정하고, 필요한 리소스를 제작 완료 하도록 한다.
게임 구성에 필요한 함수들을 설정하고, 필요한 기술들을 공부한다.
+일정
1주차: 기본적인 씬 생성
2주차: 캐릭터 움직이기 생성
3주차: 데드씬을 제외한 씬들 추가
4주차: 데드씬 추가
5주차: 데드씬 추가
6주차: 엔딩씬 추가
7주차: 메인화면, 그외 기능들 보수밑 추가 

---------------------------------
프로젝트 제목: Go home
게임에 간단한 소개 : 간단한 공포 스토리 시뮬레이션 느낌에 게임이다. 게임에서 플레이어는 게임 제목처럼 집으로 가는것이 목표이며 집에 도착할시 게임이 끝난다.
게임에 스토리는 간단하다 주인공은 죽은 영혼 상태이고 다시 태어나기 위해서 집에 도착해야 하며 집으로 가는길 동안 아무것도 하지 않고 그저 앞으로만 가야 한다. 만약 호기심을 참지 못하고 다른 행도을 할시 죽는다.
무사히 집으로 도착하면 다시 태어날수 있게되는 것이다.

1차 발표 영상 링크
https://youtu.be/5OFAKzuJWak

