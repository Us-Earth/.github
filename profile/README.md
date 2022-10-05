# 링크
* [Us-Earth 사이트](https://usearth.co.kr)
* [BE 깃허브 주소](https://github.com/Us-Earth/UsEarth.git)
* [FE 깃허브 주소](https://github.com/Us-Earth/us-earth_fe.git)
* [소개영상]
* [노션 링크](https://www.notion.so/2fb82bcd1947457893f68acaee850f55)

# UsEarth
  * Us-Earth는 매일 바뀌는 환경미션을 완수하고 캐릭터(나무)를 성장시키는 환경지킴 서비스입니다. 
  * 커뮤니티를 통해 함께 환경 캠페인에 도전할 사람을 모으고, 환경 관련 소식도 받아볼 수 있습니다.
# 프로젝트 기간
 * 2022년 08월 26일 ~ 2022년 10월 06일
 * 배포일 : 2022년 09월 29일
# 팀원
|이름|포지션|깃허브 Or 블로그|담당 역할|
|:-----:|:---:|:---:|:---|
|이태민(팀장)|Spring / BE|[GitHub](https://github.com/PhiloMonx1)|1. 대기질API 핸들링 </br>2. 비속어필터(Redis)</br> 3. 오늘의 미션|
|박민규|Spring / BE|[GitHub](https://github.com/Minkyu222341)|1. CI/CD 및 무중단배포 </br> 2. 웹페이지 크롤링 </br>3. Slack연동 <br/>4. 토큰저장 및 재발급(Redis)|
|김원호(부팀장)|React / FE|[GitHub](https://github.com/loveyoujgb)|1. 소셜로그인 </br>2. 커뮤니티 리스트/상세보기/참여하기</br> 3. 소식지 페이지</br> 4. 내정보 오늘의미션/설정/그룹미션|
|김미리|React / FE|[GitHub](https://github.com/woonhk90/us-earth_fe)|1. 커뮤니티, 인증글, 댓글 CRUD </br>2. 마이페이지 주간통계, 월간통계</br> 3. 정보제공 환경지수 차트|
|조예린|Designer|[포트폴리오](http://kkyy0406.cafe24.com/styling.html)|1. 와이어프레임 제작 </br>2. UI/UX 디자인</br> 3. 그래픽 디자인|

# 주요 서비스
- 간단하게 접근할 수 있는 서비스
    - 회원가입 없이 소셜로그인만을 통해 쉽고 빠르게 서비스 이용 가능합니다
    - 조회 성격의 서비스는 로그인을 하지 않아도 이용할 수 있습니다
- 메인페이지
    - 케러셀, 슬라이드, 무한스크롤 등 모바일 환경에 편리한 화면 구성했습니다.
    - 데이터를 소량으로 불러오는 페이징을 무한스크롤로 구현하여 끊김 없는 경험을 할 수 있습니다.
- 환경 관련 지식을 가볍고 쉽게 접할 수 있는 소식지 페이지
    - 1시간 마다 업데이트 되는 4가지 환경지수를 제공합니다.
    - 환경 기사 크롤링을 통해 다양한 환경 지식을 가볍게 습득할 수 있도록 합니다.
- 매일매일 만나는 간단한 환경 미션
    - 닉네임, 프로필 사진 변경을 통해 나만의 프로필을 만들 수 있습니다.
    - 매일 바뀌는 5가지의 환경 미션을 통해 에코라이프의 방향성을 제시합니다.
    - 일일 미션을 완수하면 경험치를 얻고 씨앗이 성장해서 나무가 됩니다. 
- 내가 이룬 일일 미션의 주간, 월간통계
    - 완수한 미션을 주간, 월간 통계로 모아볼 수 있습니다.
- 함께 키우는 숲(그룹 페이지)
    - 커뮤니티 페이지에서 커스텀한 그룹 캠페인을 제시하고 다른 사람들과 함께 진행할 수 있습니다.
    - 그룹 캠페인 진행기간 동안 인증글을 올리며 서로 좋아요, 댓글을 통해 소통할 수 있습니다.
    - 그룹원 과반수가 나의 인증글에 좋아요를 누르면 그룹 숲이 점점 성장합니다.

# Architecture
![UsEarth아키텍처](https://user-images.githubusercontent.com/108817236/193409607-020133eb-0686-462b-8e87-ee643a1deb13.png)

# 유저평가 및 피드백
![image](https://user-images.githubusercontent.com/108817236/194044368-fe1ec4f0-c8f5-4d38-aff2-1e4c7d3368d4.png)
![image](https://user-images.githubusercontent.com/108817236/194044803-009e16a8-0514-409e-ab61-09f80e6f5c0a.png)

# 개선사항
![image](https://user-images.githubusercontent.com/108817236/194042261-38bfe0c1-24c2-4d36-99f6-150f5d62d6c8.png)
![image](https://user-images.githubusercontent.com/108817236/194042384-6fddfa37-2591-4de1-adb5-f0173270e4ee.png)
