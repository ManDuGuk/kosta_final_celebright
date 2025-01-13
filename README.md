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
    TeamToast.mp4  :  이미지를 클릭해서 영상을 시청하세요 
  </summary>

  [![유튜브 미리보기 이미지](https://img.youtube.com/vi/4sR4FVVXjDQ/0.jpg)](https://youtu.be/x802kp0CkQ8)
</details>


## 개발 기간
- 2024.11.11 ~ 2024.12.16  
  - **기획** 1주  
  - **디자인** 1주  
  - **개발** 3주  


## 팀원 소개
- **[김정연](https://github.com/lakelover0611)** : 기획 담당  /  팀목록page, 결제/구독page
- **[김현진](https://github.com/0515khj)** : 퍼블리싱 담당  /  인트로page, 로그인/회원가입page, 스페이스page, 프로필page
- **[조하영](https://github.com/bigbro5232)** : ERD 담당  /  백로그page, 이슈 상세page
- **[최세은](https://github.com/CuteSeeun)** : 퍼블리싱 담당  /  활성스프린트page, 대시보드page, 이슈목록page, 타임라인page, 채팅page
- **[한채경](https://github.com/gch2505)** : 디자인 담당  /  프로젝트page, 이슈 생성 modal

페이지를 기준으로 프론트, 백엔드를 함께 구현하였습니다.


## 개발 환경
- **Front-end** : React, TypeScript, Recoil, Styled-components
- **Back-end** : Node.js, Express.js
- **Database** : MySQL


## 데이터베이스 설계
- **DB 엔진** : MySQL 8.0
- **주요 테이블**
<img src="https://github.com/CuteSeeun/Web-TeamToast/blob/main/table.png" alt="홈 화면 예시" width="900" />

## 페이지별 주요 기능
- **로그인/회원가입** : coolSMS 사용해 인증코드 발송, JWT 토큰 사용
- **기본 CRUD** : 스페이스, 프로젝트, 스프린트, 이슈, 댓글, 채팅 채널, 팀원  →  생성/수정/삭제
- **결제** : 10명 이상 시 구독 결제 → 토스 연동
- **권한** : 권한에 따른 팀원 초대, 플랜 결제, 스페이스명과 팀원 권한 수정
- **칸반보드** : react-dnd 라이브러리 사용, 드래그 앤 드랍 기능
- **대시보드** : chart.js 라이브러리 사용, 다양한 그래프 기능
- **간트차트** : gantt-task-react 라이브러리 사용, 타임라인 기능
- **채팅** : socket.io 라이브러리 사용, 실시간 채팅 기능
