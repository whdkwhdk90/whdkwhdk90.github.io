---
제목 : "Profile"
날짜 : 2021 년 04 월 14 일 12:00 -0400
---

## 소개
- 이름 : 이준혁</li>
- 생년월일 : '94.10.26
- 성별 : 남
- 군필 여부 : 육군 제2포병여단 통신소대장(중위 예편)
- 취미 : 탁구, 노래부르기, 당구, 만화
- 성격유형(MBTI) : ESFJ-T
- Email : whdkwhdk90@naver.com
- GitHub: [github.com/whdkwhdk90](https://github.com/whdkwhdk90)

## 수료교육
- JAVA를 이용한 웹개발자 양성과정(2020.03 ~ 2020.10)

## 학력
- 화홍고등학교 졸업(2010.3 ~ 2013.2)
- 단국대학교 응용컴퓨터공학과 졸업(2013.3 ~ 2017.2)   

## 자격증
- 운전면허(1종 보통)
- 워드프로세서 단일등급

## 기술스택
### Language
- java
- javascript/jquery
- html/jsp/css

### DB
- oracle
- [https://www.erdcloud.com/](https://www.erdcloud.com/) &nbsp;(modeling tool)

### framework
- spring
  - mvc
- mybatis

### IDE
- eclipse
- intelliJ
- VSCODE
- DBeaver

### 버전관리
- svn
- github

### ETC
- Ajax
- apache / tomcat

## 프로젝트 이력

### Semi Project
- 프로젝트 명 : GOLMUCK SIKDANG
- 수행 기간 : 2020년 07월 01일 ~ 2020년 07월 27일(27일간)
- 개발 목표 : 대세 TV프로그램 '골목 식당'처럼 음식을 카테고리 별, 혹은 랜덤으로 추천하는 기능으로 음식 선택에 어려움을 느끼는 사람들에게
                   조금이나마 고민거리를 덜어 줄 수 있도록 하는 사이트 구현
- 개발 환경
  - OS : Windows
  - IDE : Eclipse,DBeaver
  - DB : Oracle DataBase 11g
  - SERVER : Apache Tomcat 9.0
  - Design Tool : Bootstrap
  - Language : Java, HTML5, CSS3, Javascript, JQuery

- 구현기능

  - 전체페이지
    - 좋아요 버튼 클릭 사용 기능
    - 음식 클릭 후 레시피 조회 기능
    - 카테고리별(나라/조리) 음식 페이지 조회 기능
    - 연령/성별 좋아요 기반 인기 랭킹 기능
    - 해당 음식에 대한 음식점 지도 & 음식점 위치 카톡링크 전송 기능

  - 회원서비스
    - SNS 및 일반 회원가입 / 마이페이지 / 회원탈퇴 기능
    - SNS 및 일반 로그인 / 좋아요 클릭 버튼 및 조회 기능

- 담당 역할 
  - MVC패턴(Model 2 설계 및 구현
  - DAUM POST API를 이용한 회원가입 / 마이페이지 / 로그인 / 로그아웃 / 회원탈퇴 기능

- 첨부자료
  - [세미프로젝트 pptx 파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/PROJECT%20GOLMUCK_-728.pptx)
  - [세미프로젝트 zip파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/SEMI_1_REAL_FINISH.zip)
  - [세미프로젝트 기획안](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/1%EC%A1%B0_%EA%B8%B0%ED%9A%8D%EC%95%88.txt)

- DB모델링
  - <img src='/assets/세미프로젝트모델링.PNG' width=150px height=150px/> 
      
      
      
##### *SNS & 일반 로그인

<img src="/assets/로그인페이지.PNG" height="30%" width="35%" >
<img src="/assets/카카오로그인.PNG" height="100%" width="65%" >
&nbsp;
<br/>

###### 기존 회원들은 REGISTER를 통해서 회원가입을 통해 로그인을 진행하고 SNS로그인은 각각 KAKAO API와 네아로(네이버 아이디로 로그인) API를 통해 진행한다. 만약 ID가 존재한다면, 가입하지않고 존재하지않는다면 즉시 가입시켜 로그인한다.

<a href="url"><img src="/assets/회원가입페이지.PNG" align="left" height="100%" width="40%" ></a>
<a href="url"><img src="/assets/postapi.PNG" align="left" height="100%" width="60%" ></a> <br/><br/>

&nbsp;
<br/><br/><br/><br/><br/>
###### LOGIN에서 REGISTER로 넘어가면 ID입력란으로 자동 포커싱되고 모든 항목은 그 입력란에서 벗어나는 순간 AJAX로 정규식을 통해 검사를 진행한다. 만약 ID입력란의 값이 없거나 중복체크가 제대로 되지 않다면 다른 입력란을 눌러도 자동으로 ID입력란으로 포커싱이 넘어가고 모든 입력란의 체크가 완료되어야 회원가입이 된다.

<a href="url"><img src="/assets/id바르게.PNG" align="left" height="100%" width="40%" ></a>
<a href="url"><img src="/assets/ID중복.PNG" align="left" height="100%" width="60%" ></a> <br/><br/>

&nbsp;
<br/>
###### ID는 먼저 정규식을 통해 1차 필터링을 진행하고, 1차 필터링이 통과 되었다면 DB에 그 ID가 존재하는지 확인한다. 1차 필터링이 걸리거나 DB상에 ID가 존재하는 경우에는 중복이라고 뜨며 ID입력란에 focus를 못 벗어나도록 구현하였다.
            
  
  
  
  ### Final Project
- 프로젝트 명 : WESCHE(we + schedule)
- 수행 기간 : 2020년 08월 30일 ~ 2020년 10월 29일(61일간)
- 개발 목표 : 포스트 코로나 시대에 있어서 스터디에 필요한 동영상 검색, 스터디 조 매칭, 질문게시판 및 타이머를 사용할 수 있는 사이트 구현
- 개발 환경
  - OS : Windows, MAC
  - IDE : Eclipse,DBeaver
  - DB : Oracle DataBase 11g
  - SERVER : Apache Tomcat 9.0
  - Design Tool : Bootstrap
  - Language : Java, HTML5, CSS3, Javascript, JQuery

- 구현기능

  - 전체페이지
    - 실시간 질의응답(채팅 기능) – 1:1 채팅방 생성
    - 캘린더 - 작성된 일정 마우스로 이동 및 삭제
            - 스케줄 및 끝내지 못한 일 미루기
    - 타이머(공부량 체크) – 일/주/월 별 공부량 그래프화
    - 유튜브 영상 검색 기능
    - 질문 및 게시판 - 사진 및 이미지 업로드
                    - 해시태그를 통한 검색 기능

  - 회원서비스
    - 회원가입 / 마이페이지 / 회원탈퇴 기능
    - 로그인 / 좋아요 클릭 버튼 및 조회 기능

- 담당 역할 
  - spring framework MVC패턴(Model 2) 설계 및 구현
  - youtube Search API 활용 영상 검색 게시판 구현
  - Google Calendar API 활용 화면 구현
  - 질문 게시판 및 페이징 처리 구현
  - 회원가입, 로그인, 로그아웃, 마이페이지 수정, 회원 탈퇴 기능 구현

- 첨부자료
  - [파이널프로젝트 pptx 파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/Final_Project_PPT_1028%EC%88%98%EC%A0%95.pptx)
  - [파이널프로젝트 zip파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/20201028Final.zip)
  - [파이널프로젝트 기획안](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/%ED%8C%8C%EC%9D%B4%EB%84%90%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EA%B8%B0%ED%9A%8D%EC%95%88.txt)

- DB모델링
  - <img src='/assets/세미프로젝트모델링.PNG' width=150px height=150px/> 
  
      

![세미프로젝트모델링](/assets/세미프로젝트모델링.PNG)

#### 기타 자료

pptx : [세미프로젝트 pptx 파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/PROJECT%20GOLMUCK_-728.pptx) <br/>
zip : [세미프로젝트 zip파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/SEMI_1_REAL_FINISH.zip) <br/>
기획안 : [세미프로젝트 기획안](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/1%EC%A1%B0_%EA%B8%B0%ED%9A%8D%EC%95%88.txt) <br/>

#### 구현 기능

##### SNS & 일반 로그인

<a href="url"><img src="/assets/로그인페이지.PNG" align="left" height="30%" width="35%" ></a>
<a href="url"><img src="/assets/카카오로그인.PNG" align="left" height="100%" width="65%" ></a> 
&nbsp;
<br/>
###### 기존 회원들은 REGISTER를 통해서 회원가입을 통해 로그인을 진행하고 SNS로그인은 각각 KAKAO API와 네아로(네이버 아이디로 로그인) API를 통해 진행한다. 만약 ID가 존재한다면, 가입하지않고 존재하지않는다면 즉시 가입시켜 로그인한다.

<a href="url"><img src="/assets/회원가입페이지.PNG" align="left" height="100%" width="40%" ></a>
<a href="url"><img src="/assets/postapi.PNG" align="left" height="100%" width="60%" ></a> <br/><br/>

&nbsp;
<br/><br/><br/><br/><br/>
###### LOGIN에서 REGISTER로 넘어가면 ID입력란으로 자동 포커싱되고 모든 항목은 그 입력란에서 벗어나는 순간 AJAX로 정규식을 통해 검사를 진행한다. 만약 ID입력란의 값이 없거나 중복체크가 제대로 되지 않다면 다른 입력란을 눌러도 자동으로 ID입력란으로 포커싱이 넘어가고 모든 입력란의 체크가 완료되어야 회원가입이 된다.

<a href="url"><img src="/assets/id바르게.PNG" align="left" height="100%" width="40%" ></a>
<a href="url"><img src="/assets/ID중복.PNG" align="left" height="100%" width="60%" ></a> <br/><br/>

&nbsp;
<br/>
###### ID는 먼저 정규식을 통해 1차 필터링을 진행하고, 1차 필터링이 통과 되었다면 DB에 그 ID가 존재하는지 확인한다. 1차 필터링이 걸리거나 DB상에 ID가 존재하는 경우에는 중복이라고 뜨며 ID입력란에 focus를 못 벗어나도록 구현하였다.
  

