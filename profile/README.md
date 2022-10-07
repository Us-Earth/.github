![Us-Earth](https://user-images.githubusercontent.com/99243066/194052653-ff4166a6-cd22-468a-8edc-6fcadd992c0d.png)
<br>
# 링크
* [Us-Earth 사이트](https://usearth.co.kr)
* [BE 깃허브 주소](https://github.com/Us-Earth/UsEarth.git)
* [FE 깃허브 주소](https://github.com/Us-Earth/us-earth_fe.git)
* [소개영상](https://youtu.be/cB17NoXBuds)
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
     ![로그인x페이지](https://user-images.githubusercontent.com/107628613/194065953-d089e883-5fe2-4040-8a5a-af3a9d0b2618.png)
- 메인페이지
    - 케러셀, 슬라이드, 무한스크롤 등 모바일 환경에 편리한 화면 구성했습니다.
    - 데이터를 소량으로 불러오는 페이징을 무한스크롤로 구현하여 끊김 없는 경험을 할 수 있습니다.
    ![메인페이지](https://user-images.githubusercontent.com/107628613/194065955-79661d87-b294-4621-8f1d-bdacb0c38d88.png)
- 환경 관련 지식을 가볍고 쉽게 접할 수 있는 소식지 페이지
    - 1시간 마다 업데이트 되는 4가지 환경지수를 제공합니다.
    - 환경 기사 크롤링을 통해 다양한 환경 지식을 가볍게 습득할 수 있도록 합니다.
    ![소식지](https://user-images.githubusercontent.com/107628613/194065957-2c684cd3-d953-432c-aed9-5d0b054c1100.png)
- 매일매일 만나는 간단한 환경 미션
    - 닉네임, 프로필 사진 변경을 통해 나만의 프로필을 만들 수 있습니다.
    - 매일 바뀌는 5가지의 환경 미션을 통해 에코라이프의 방향성을 제시합니다.
    - 일일 미션을 완수하면 경험치를 얻고 씨앗이 성장해서 나무가 됩니다. 
    ![내정보페이지](https://user-images.githubusercontent.com/107628613/194065947-edbd773b-d2a7-40d7-9520-69afc964d7c5.png)
- 내가 이룬 일일 미션의 주간, 월간통계
    - 완수한 미션을 주간, 월간 통계로 모아볼 수 있습니다.
  ![월간_주간통계](https://user-images.githubusercontent.com/107628613/194065958-8689190d-b614-43aa-9417-557aacbcca0d.png) 
- 함께 키우는 숲(그룹 페이지)
    - 커뮤니티 페이지에서 커스텀한 그룹 캠페인을 제시하고 다른 사람들과 함께 진행할 수 있습니다.
    - 그룹 캠페인 진행기간 동안 인증글을 올리며 서로 좋아요, 댓글을 통해 소통할 수 있습니다.
    - 그룹원 과반수가 나의 인증글에 좋아요를 누르면 그룹 숲이 점점 성장합니다.
    ![그룹_숲성장_이미지](https://user-images.githubusercontent.com/107628613/194065934-6797c871-8ea1-4061-8cf0-ae9dfa3b1439.png)
![그룹_인증글_댓글](https://user-images.githubusercontent.com/107628613/194065939-62efc509-45ed-40ee-a3b7-4dded503f411.png)
- 기타 페이지
    - 닉네임 수정, 프로필 수정이 가능합니다.
    - 자신이 가입한 그룹의 상태와 자신이 작성한 그룹을 확인할 수 있습니다.
    - 그룹글 작성페이지, 인증글 작성페이지, 댓글 모두 이미지를 업로드, 수정, 삭제가 가능합니다.
![기타페이지](https://user-images.githubusercontent.com/107628613/194067985-7e9ad038-da1a-4ebf-8d71-314ecd609c35.png)

# Architecture
![UsEarth아키텍처](https://user-images.githubusercontent.com/108817236/193409607-020133eb-0686-462b-8e87-ee643a1deb13.png)

# Tools
<details>
 <summary>[ FE ]</summary>
 <p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=ffffff">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=CSS3&logoColor=ffffff">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=000000">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
  <br/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
  <img src="https://img.shields.io/badge/React Router-CA4245?style=for-the-badge&logo=React Router&logoColor=ffffff">
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=ffffff">
  <img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styled components&logoColor=ffffff">
  <br/>
  <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=Yarn&logoColor=ffffff">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=ffffff">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=Vercel&logoColor=ffffff">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=ffffff">
  <br/>
  <img src="https://img.shields.io/badge/Naver Login-03C75A?style=for-the-badge&logo=Naver&logoColor=ffffff">
  <img src="https://img.shields.io/badge/Google Login-4285F4?style=for-the-badge&logo=Google&logoColor=ffffff">
  <img src="https://img.shields.io/badge/Kakao Login-FFCD00?style=for-the-badge&logo=Kakao&logoColor=000000">
</p>
 </details>
 
<details>
 <summary>[ BE ]</summary>
 <p>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/querydsl -F8DC75?style=for-the-badge&logo=querydsl&logoColor=white">
  <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"> 
  <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/codedeploy -569A31?style=for-the-badge&logo=codedeploy&logoColor=white">
  <img src="https://img.shields.io/badge/AmazonS3 -569A31?style=for-the-badge&logo=AmazonS3&logoColor=white"> 
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/githubactions -2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/postman -FF6C37?style=for-the-badge&logo=postman&logoColor=white">
  <img src="https://img.shields.io/badge/nginx -009639?style=for-the-badge&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/slack -4A154B?style=for-the-badge&logo=slack&logoColor=white">
  <img src="https://img.shields.io/badge/redis -DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Selenium -43B02A?style=for-the-badge&logo=Selenium&logoColor=white">
  <img src="https://img.shields.io/badge/jwt -000000?style=for-the-badge&logo=jwt&logoColor=white">
 </p>
</details>

# 트러블슈팅
 <details>
  <summary>[ FE ]</summary>
  1. [달력 라이브러리 이슈](https://github.com/Us-Earth/us-earth_fe/wiki/%EB%8B%AC%EB%A0%A5-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%9D%B4%EC%8A%88)
  2. [모바일 스크롤 이슈](https://github.com/Us-Earth/us-earth_fe/wiki/%EB%AA%A8%EB%B0%94%EC%9D%BC-%EC%8A%A4%ED%81%AC%EB%A1%A4-%EC%9D%B4%EC%8A%88)
  3. [이미지 업로드 이슈](https://github.com/Us-Earth/us-earth_fe/wiki/%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%97%85%EB%A1%9C%EB%93%9C-%EC%9D%B4%EC%8A%88)
 </details>
 <details>
  <summary>[ BE ]</summary>
  1. [CI/CD(지속적 통합 지속적 제공)-WIKI이동](https://github.com/Minkyu222341/UsEarth/wiki/CI-CD-(-%EC%A7%80%EC%86%8D%EC%A0%81-%ED%86%B5%ED%95%A9-%EC%A7%80%EC%86%8D%EC%A0%81-%EC%A0%9C%EA%B3%B5-))
  2. [웹페이지 크롤링-WIKI이동](https://github.com/Us-Earth/UsEarth/wiki/Selenium-%ED%81%AC%EB%A1%A4%EB%A7%81)
  3. [Slack Webook-WIKI이동](https://github.com/Us-Earth/UsEarth/wiki/Slack-WebWook---%EC%97%90%EB%9F%AC%EB%A1%9C%EA%B7%B8)
  4. [QueryDsl 도입-WIKI이동](https://github.com/pnci1029/hanghae_8D_BE/wiki/QueryDSL-%EC%A0%81%EC%9A%A9)
  5. [대기질 API 스케줄러 미작동-WIKI이동](https://github.com/Us-Earth/UsEarth-BE/wiki/%EB%8C%80%EA%B8%B0%EC%A7%88-API-%EC%8A%A4%EC%BC%80%EC%A4%84%EB%9F%AC-%EB%AF%B8%EC%9E%91%EB%8F%99-%EB%AC%B8%EC%A0%9C)
  6. [비속어 필터 메서드 실행속도-WIKI이동](https://github.com/Us-Earth/UsEarth-BE/wiki/%EB%B9%84%EC%86%8D%EC%96%B4-%ED%95%84%ED%84%B0-%EB%A9%94%EC%84%9C%EB%93%9C-%EC%8B%A4%ED%96%89%EC%86%8D%EB%8F%84-%EB%AC%B8%EC%A0%9C)
  7. [MySQL 8.0.20 LocalDate 타입 데이터 하루 전으로 들어가는 문제-WIKI이동](https://github.com/Us-Earth/UsEarth-BE/wiki/MySQL-8.2.0-LocalDate-%ED%83%80%EC%9E%85-%EB%8D%B0%EC%9D%B4%ED%84%B0-%ED%95%98%EB%A3%A8-%EC%A0%84%EC%9C%BC%EB%A1%9C-%EB%93%A4%EC%96%B4%EA%B0%80%EB%8A%94-%EB%AC%B8%EC%A0%9C)
  8. [이미지 리사이징-WIKI이동](https://github.com/Us-Earth/UsEarth-BE/wiki/%EC%9D%B4%EB%AF%B8%EC%A7%80-%EB%A6%AC%EC%82%AC%EC%9D%B4%EC%A7%95)
 </details>

# 유저평가 및 피드백
![image](https://user-images.githubusercontent.com/108817236/194044368-fe1ec4f0-c8f5-4d38-aff2-1e4c7d3368d4.png)
![image](https://user-images.githubusercontent.com/108817236/194044803-009e16a8-0514-409e-ab61-09f80e6f5c0a.png)

# 개선사항
![image](https://user-images.githubusercontent.com/108817236/194042261-38bfe0c1-24c2-4d36-99f6-150f5d62d6c8.png)
![image](https://user-images.githubusercontent.com/108817236/194042384-6fddfa37-2591-4de1-adb5-f0173270e4ee.png)
