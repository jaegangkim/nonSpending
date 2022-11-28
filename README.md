# 💲무지출챌린지💲
(팀명 : 얼죽코:얼어죽어도코딩)
![무지출챌린지_메인](https://user-images.githubusercontent.com/108074336/189463642-1dfcb065-cd04-4c34-a27c-0c8c1ffc2435.png)

# 👀 프로젝트 소개
* 프로젝트명 : 최근 MZ세대를 중심으로 유행중인 무지출챌린지 통합 지원 웹사이트 구현

* 개발배경 : 물가 상승으로 인한 소비자의 지출부담 + 저축을 해 이른나이에 조기은퇴를 꿈꾸는 '파이어족'의 증가로 1)무지출챌린지에 대한 사람들의 관심 증가 (ex)무지출챌린지, 짠테크 등)
<br>  1) 무지출챌린지 : 단순히 지출을 하지않는 것이 아닌 고정지출을 제외한 쓸모없는 지출을 줄여 저축금을 늘리기 위한 취지로 등장한 챌린지    

* 개발의 필요성 : 현재 무지출 챌린지는 단순히 블로그, SNS공유 형태로 진행되고 있으며 이를 통합 지원하는 수단이 존재하지 않음 
<br>따라서 본 개발을 통해 사용자의 무지출 챌린지를 효과적으로 지원하고, 지출을 줄이고 이를 공유하는 것이 부끄러운 것이 아니라 존중해야 할 삶의 한 형태로 자리잡기 원한다는 메세지 또한 전달하고자함

* 개발목표 : 
<br>  1️⃣ 사용자가 무지출챌린지를 효과적으로 달성할 수 있도록 지원하는 것을 최우선 목표로 한다.
<br>  2️⃣ 나와 챌린지 목표금액이 비슷한 사람들과 매칭되어 함께 챌린지 달성이 가능하도록 한다.
<br>  3️⃣ 정부 보조금이나 기업, 단체에서 진행되는 무료 이벤트, 절약정보를 확인하고 사용자들 간 공유할 수 있도록 한다.
<br>  4️⃣ 사용자가 주로 어디에 돈을 쓰는지 지출 항목을 분류하고 차트로 시각화 하여 지출 관리를 돕는다.

* UI설계도 : 피그마
![피그마](https://user-images.githubusercontent.com/108074336/189464650-29e9035b-4efe-4939-ab41-2d59db4cb26c.png)

# 🗓️ 프로젝트 기간
2022.08.16 ~ 2022.09.07 (약4주)

# ✨ 주요 기능
* <b>지출 입력</b>
  * 챌린지 기간 중 지출 발생 내역입력  
<br>![지출반성](https://user-images.githubusercontent.com/108074336/189464195-39227081-06f4-4d89-951e-3202f9ac4f76.png)

* <b>챌린지 진행 상황 관리</b>
<br>![레벨게시판](https://user-images.githubusercontent.com/108074336/189463412-0943d186-6a19-40f6-9936-e53dd9c17a73.png)
  * 지출 입력자료를 토대로 사용자의 챌린지 달성도확인
  * 등급 간 전체 달성도 현황확인
  * 챌린지 기간 중 TOP 5 순위확인
 
* <b>소비 분석</b>
<br>![3주소비차트](https://user-images.githubusercontent.com/108074336/189464267-72eb3c3d-9650-4020-b5c5-9f351ca2e428.png)
  * 챌린지 진행 기간 중 지출금 차트 확인
  
<br>![소비항목차트](https://user-images.githubusercontent.com/108074336/189464301-483c753b-3122-4d96-923d-158caa40c565.png)
  * 챌린지 진행 기간 중 지출이 많은 항목에 대한 차트확인
  * 쇼핑, 식비, 교통, 여가, 기타 총 5가지 항목에 따른 소비분석
  * 1년 소비차트를 통한 1년간의 소비 항목분석 
  
<br>![카드추천](https://user-images.githubusercontent.com/108074336/189464103-de6c996b-490b-4bba-b519-4914366b91fc.png)
  * 차트에서 많은 비율을 차지하는 항목에 대한 카드 추천
  
<br>![무지출달력](https://user-images.githubusercontent.com/108074336/189464337-b7d92062-dacb-48f1-9d1c-62901e0b4f0c.png)
  * 무지출에 성공한 날을 달력에 표시

* <b>등급 게시판</b>
  * '챌린지 목표금액'에 따른 사용자 등급분류
  <br> (본 개발에서의 등급분류는 아래와 같음)
<br>![등급분류표](https://user-images.githubusercontent.com/108074336/189463205-f90be6c5-f2e5-447c-97c1-ade4af176df1.png)
  * 등급 간 프라이빗 커뮤니티 존재
  
* <b>절약정보 게시판</b>
<br>![보조금](https://user-images.githubusercontent.com/108074336/189464067-79e591c9-3285-4a03-b6c5-cbc73373d28e.png)
  * 정부 보조금 정보 확인 
  * 기업이나 단체에서 진행하는 무료 이벤트 정보 확인

* <b>절약정보 게시판</b>
  * 전체 이용자간 커뮤니티를 통한 소통 가능 

# 💪🏻 기술스택
<table>
    <tr>
        <th>구분</th>
        <th>내용</th>
    </tr>
    <tr>
        <td>기본 사용언어</td>
        <td>
            <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>Frontend 프레임워크</td>
        <td>
           <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
           <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white">
           <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">
        </td>
    </tr>
    <tr>
        <td>Backend 프레임워크</td>
        <td>
           <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/> 
           <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"/>
        </td>
    </tr>
     <tr>
        <td>라이브러리</td>
        <td>
            <img src="https://img.shields.io/badge/BootStrap-7952B3?style=for-the-badge&logo=BootStrap&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>개발도구</td>
        <td>
            <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"/>
            <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>서버환경</td>
        <td>
            <img src="https://img.shields.io/badge/Apache Tomcat-D22128?style=for-the-badge&logo=Apache Tomcat&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>데이터베이스</td>
        <td>
             <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/> 
        </td>
    </tr>
    <tr>
        <td>협업도구</td>
        <td>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>
        </td>
    </tr>
</table>

# 📌Use-Case
![무지출챌린지_유스케이스](https://user-images.githubusercontent.com/108074336/189464506-48685e5f-6d64-4ffa-a2a5-6a8ddddd239b.png)

# 📌E-R Diagram
![무지출챌린지_ERD](https://user-images.githubusercontent.com/108074336/189464545-bb005a77-2aae-4bdb-bc0c-9a3555f8d94b.png)

# 💻화면 구성
* 서비스 흐름도
![서비스흐름도](https://user-images.githubusercontent.com/108074336/189464604-e02b98e1-76fb-4038-9693-161d98cd6133.png)

# 💻메뉴 구성도
![메뉴구성](https://user-images.githubusercontent.com/108074336/189464621-f58195be-435c-4cae-9b0e-2a5ad8d4ba3c.png)

# 👨‍👩‍👦‍👦 팀원 역할
![팀](https://user-images.githubusercontent.com/108074336/189464703-c073158e-80dd-4a62-8190-09a4206d6c54.png)

