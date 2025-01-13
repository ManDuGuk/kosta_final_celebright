## 업무관리 협업 툴 서비스

![프로젝트 사진](https://github.com/user-attachments/assets/73dbf88e-7a4d-4485-a01b-fa4f0cbbe6b4)

- 배포 레파지토리 :  
[https://github.com/ManDuGuk/final_be_aws(백엔드)](https://github.com/ManDuGuk/final_be_aws)  
[https://github.com/ManDuGuk/final_fe_vercel(프론트)](https://github.com/ManDuGuk/final_fe_vercel)  




## 프로젝트 소개
"구독형 인플루언서 소셜 플랫폼"를 주제로 한 웹 기반 플랫폼입니다. 

누구나 소비자이자 생산자가 될 수 있는 공간을 제공합니다.
일반 유저는 간단한 인플루언서 신청을 통해 인플루언서로 활동할 수 있으며,인플루언서는 자신의 상품이나 서비스를 구독형 상품으로 만들어
이를 구독하는 유저들에게 독점적으로 제공할 수 있습니다.


<details>
  <summary>
    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
  <rect x="3" y="7" width="13" height="10" rx="2" ry="2"></rect>
  <polygon points="16 7 22 11 22 13 16 17 16 7"></polygon>
</svg>
    celebright  :  이미지를 클릭해서 영상을 시청하세요 
  </summary>

  [![유튜브 미리보기 이미지](https://img.youtube.com/vi/x802kp0CkQ8/0.jpg)](https://youtu.be/x802kp0CkQ8)
</details>


## 개발 기간
- 2024.11.11 ~ 2024.12.16  
  - **기획** 1주  
  - **디자인** 1주  
  - **개발** 3주  


## 팀원 소개
- **김준경** : 문서화,일정처리  /  마이페이지, 구독처리 작업
- **구태현** : 프로젝트 세팅  /  피드관련 페이지, 배포 작업
- **남윤호(본인)** : 기획,디자인  /  채팅, 공통 컴포넌트 작업
- **조영우** : 주제선정 리서치  /  로그인, 홈 작업
- **최규호** : 디비 설계  /  마이페이지, 구독처리, 관리자페이지 작업
- **김상기** : 레퍼런스 조사 / 피드관련 페이지 작업

페이지를 기준으로 프론트, 백엔드를 함께 구현하였습니다.


## 개발 환경
- **Front-end** : React, TypeScript, Mui, Zoostand, Antdesign
- **Back-end** : Node.js, Express.js, Axios 
- **Database** : MySQL, Sequelize
- **기타**: Figma, Swagger
- **배포**: AWS EC2, Vercel
- **CI/CD**: Github action


## 데이터베이스 설계
- **DB 엔진** : MySQL 8.0
- **주요 테이블**
<img src="https://github.com/user-attachments/assets/26c0cf93-30e6-4264-b9ee-efe0097ba777" alt="홈 화면 예시" />

## 페이지별 주요 기능
- **로그인/회원가입** : JWT 기반 Token 방식 구현, Oauth 기반 소셜 로그인
- **기본 CRUD** : Multer 라이브러리 사용, AWS S3로 반환된 URL 객체 데이터로 DB 처리
- **멤버쉽 & 결제** : DB논리 설계로 멤버쉽 구독처리 → 토스 결제 연동 API 사용
- **알림** : rabbitmq와 socket.io를 사용하여 실시간 알림을 구현
- **관리자** : antdesign 사용 데이터 일괄 관리
- **채팅** : socket.io 라이브러리 사용, 실시간 채팅 기능
