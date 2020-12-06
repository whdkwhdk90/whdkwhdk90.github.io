---
title: "입사지원서"
date: 2020-12-06 12:00:00 -0400
categories: jekyll update
---

## 기본 사항

성명  | 이준혁 
:-------------: | :-------------:
성명(영문) | Lee Jun Hyeok
생년월일  | 1994년 10월 26일 
성별  | 남

## 학력 사항

입학 년 월  | 졸업 년 월 | 출신학교 및 전공 | 구분 
:-------------: | :-------------: | :-------------: | :-------------:
2013년 03월 | 2017년 02월 | 단국대학교/ 응용컴퓨터공학과 | 학사 졸업
2010년 03월 | 2013년 02월 | 화홍고등학교                | 졸업  

## 병역

병역  | 복무기간 | 군별
:-------------: | :-------------: | :-------------: 
필 | 2017년 03월 01일 ~ 2019년 06월 30일 | 육군 중위

## 자격증

자격면허  | 취득년월 | 발행처
:-------------: | :-------------: | :-------------: 
운전면허(1종 보통) | 2012년 12월 | 경기지방경찰청
워드프로세서 | 2019년 09월 | 대한상공회의소

## 교육사항

기간  | 교육기관 | 교육과목 | 출석률 | 교육내용
:-------------: | :-------------: | :-------------: | :-------------: | :------------- 
2020년 03월 25일 ~ 2020년 10월 29일 | KH정보교육원 | 스마트 콘텐츠 융합 응용 SW 엔지니어 양성 과정 | 100% |*ORACLE <br/>  SQL Programming<br/><br/> *JAVA  <br/>  Servlet / JSP, jdbc, Spring Framework, Mybatis, Ajax  <br/><br/> *HTML / CSS / JavaScript

-------

# 세미프로젝트

### 프로젝트 명 : GOLMUCK SIKDANG

### 수행 기간 : 2020년 07월 01일 ~ 2020년 07월 27일(27일간)

### 개발 목표 : 대세 TV프로그램 '골목 식당'처럼 음식을 카테고리 별, 혹은 랜덤으로 추천하는 기능으로 음식 선택에 어려움을 느끼는 사람들에게 조금이나마 고민거리를 덜어 줄 수 있도록 하는 사이트 구현 <br/>

### 개발 환경

**OS**  | Windows 
:-------------: | :-------------:
**IDE** | Eclipse, DBeaver
**DBMS**  | Oracle Data Base 11g 
**SERVER**  | Apache Tomcat 9.0
**Design Tool**  | Bootstrap
**Language**  | Java, HTML5, CSS3, Javascript, JQuery

### 구현 기능  

####   * 전체 페이지
                  * 좋아요 버튼 클릭 사용 기능
                  * 음식 클릭 후 레시피 조회 기능
                  * 카테고리별(나라/조리) 음식 페이지 조회 기능
                  * 연령/성별 좋아요 기반 인기 랭킹 기능
                  * 해당 음식에 대한 음식점 지도 &
                   음식점 위치 카톡링크 전송 기능

####   * 회원 서비스
                  * SNS 및 일반 로그인 / 좋아요 클릭 버튼 및 조회 기능
              
    
### 담당 역할 : MVC패턴(Model 2) 설계 및 구현, Kakao Login API & 일반 로그인/ 로그아웃, Daum POST API를 통한 회원가입 기능 담당

### DB 설계

![세미프로젝트모델링](/assets/세미프로젝트모델링.PNG)

### 기타 자료

pptx : [세미프로젝트 pptx 파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/PROJECT%20GOLMUCK_-728.pptx) <br/>
zip : [세미프로젝트 zip파일](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/SEMI_1_REAL_FINISH.zip) <br/>
기획안 : [세미프로젝트 기획안](https://github.com/whdkwhdk90/whdkwhdk90.github.io/blob/main/assets/1%EC%A1%B0_%EA%B8%B0%ED%9A%8D%EC%95%88.txt) <br/>

### 구현 기능

#### SNS & 일반 로그인

<a href="url"><img src="/assets/로그인페이지.PNG" align="left" height="30%" width="31%" ></a>
<a href="url"><img src="/assets/카카오로그인.PNG" align="left" height="100%" width="65%" ></a> 
&nbsp;
<br/>
##### 기존 회원들은 REGISTER를 통해서 회원가입을 통해 로그인을 진행하고 SNS로그인은 각각 KAKAO API와 네아로(네이버 아이디로 로그인) API를 통해 진행한다. 만약 ID가 존재한다면, 가입하지않고 존재하지않는다면 즉시 가입시켜 로그인한다.

<a href="url"><img src="/assets/회원가입페이지.PNG" align="left" height="100%" width="35%" ></a> <br/><br/>

<a href="url"><img src="/assets/postapi.PNG" align="left" height="100%" width="35%" ></a> <br/><br/>

<a href="url"><img src="/assets/id바르게.PNG" align="left" height="100%" width="35%" ></a> <br/><br/>

<a href="url"><img src="/assets/ID중복.PNG" align="left" height="100%" width="35%" ></a> <br/><br/>







