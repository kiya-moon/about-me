# Hi👋
### 문 : 🚪(노크) 안녕하세요 1일 1커밋 도전 중 입니다!
### 기 : 기지개 한 번 피고 오늘도 에러를 해결합니다🤔
### 연 : 연대해서 함께 하는 프로젝트가 즐겁습니다😊

</br></br>

## 📭 Contact
- 핸드폰 : 010-3055-9380 
- 이메일 : kiyamoon@daum.net
- 블로그 : https://turtlemoon.tistory.com
- 깃헙   : https://github.com/kiya-moon

</br></br>

## 💕It's me
> ### Introduce
JAVA를 주언어로 개발을 하고 있습니다.<br><br>
주로 사용하는 IDE는 이클립스와 인텔리제이 입니다.<br><br>
JSP, Spring, Spring Boot 개발을 할 수 있습니다.<br><br>
MyBatis에 익숙하고 JDBC, JPA를 사용할 수 있습니다.<br><br>
설계하고 구현하는 과정이 즐겁습니다.<br><br>
차분하게 문제를 해결합니다. 

</br></br>

> ### TimeLine
### 2022
- 12월 원티드 프리온보딩 [Android]Kotlin 강의<br>
- 11월 인프런 기출로 대비하는 CS 전공면접<br>
- 10월 토이 프로젝트<br>
```
<런드리고 웹사이트> | 기술스택 : JAVA11, SPRING MVC, MyBatis, MySQL, HTML5, CSS3, JavaScript
```
- 8월 스프링 공부 시작(남궁성 선생님 인터넷 강의)
- 7월 토이 프로젝트<br>
```
<여행플래너> | 기술스택 : JAVA8, MyBatis, Oracle, HTML5, CSS3, JQuery, JavaScript, JSP(MVC2), OpenAPI
```
- 6월 토이 프로젝트<br>
```
<주차 정산 프로그램> | 기술스택 : JAVA8, JDBC, Oracle
```
- 5월 CS 발표<br>
```
<OSI 7Layers> | 상세보기 https://turtlemoon.tistory.com/118 
```
- 5월 정보처리기사 필기 합격
- 4월 토이 프로젝트<br>
```
<방 탈출 게임> | 기술스택 : JAVA8)
```
- 3월 스터디 시작(수업 복습 및 백준 문제 풀이, 정보 교류 목적)
- 3월 소프트웨어 융합 풀스택 개발자 양성과정A 시작
- 1월 자바 입문

### 2021
- 10월 개발자 공부 시작(html, css, python)

</br>

> ### Education
- 고등학교 : 강원대학교사범대학부설고등학교 졸업🎓 | 이과
- 대학교   : 한림대학교 졸업🎓 | 컨벤션관광경영(전공) | 경영(복수전공) | 디지털미디어콘텐츠(복수전공)
- 코리아IT아카데미 '소프트웨어 융합 풀스택 개발자 양성과정A' 수료🎓

</br></br>

## 🐤Tech Stack

### F/E
HTML5, CSS3, JS, JQuery

### B/E
Java, JDBC, MyBatis, JSP, Spring MVC, JSTL, Thymeleaf

### 서버
Apache, Tomcat

### DB
Oracle, Mysql

### Framework
Spring Framework, Spring Boot

### 형상관리
Git

<br><br>

## ✨ Projects
### 2022년 9월 <런드리고 웹사이트>
### 소개
'우리집 모바일 세탁소, 런드리고' 어플의 웹사이트 버전<br>
런드리고 프로젝트는 기존의 어플을 제가 실제로 사용할 때, 웹사이트로는 수거신청을 할 수 없음에 가끔 불편함을 느껴 제작하게 되었습니다.<br>
에러 없는 꼼꼼한 백엔드를 구축함과 동시에 고객의 유입을 위한 프론트단 역시 중요하다고 여겨 안팎으로 완벽한 웹사이트를 만들기 위해 노력했습니다.<br><br>
진행기간 : FrontEnd | 2022-08-07 ~ 2022-08-21 / BackEnd | 2022-09-18 ~ 2022-10-12<br><br>
기술 스택<br>
JAVA11, SPRING MVC, MyBatis, MySQL, HTML5, CSS3, JavaScript<br><br>
👉[프로젝트 상세 설명](https://github.com/kiya-moon/Laundrygo_project.git) 참고<br><br>

### 느낀 점
 - 프로젝트를 하며 Spring Framework에서 프론트단과 백단의 흐름에 익숙해지게 되었습니다.<br>
 - 협업을 ‘어떻게’ 잘 할 수 있을 지에 대해 생각해 보고, AWS 배포나 REST API 같은 새로운 기술에 도전해보는 시간이었습니다. <br><br>

### 트러블 이슈
 - 첫 번째. ‘문의하기에서 등록한 이미지 가져오기’<br>
이미지를 여러 장 저장하고 가져오는 로직은 처음이었고, 한 장일 때처럼 짰더니 DB에 값이 있음에도 Null이 들어왔습니다. 때문에 if문을 돌려 List에 담아왔고, 뷰단에서 foreach문을 사용하여 뿌려주도록 하였습니다. 하지만 이중 foreach문을 사용하면서 로직에 문제가 생겨 파싱 에러가 났고, 로직을 점검해 시도하여 성공할 수 있었습니다.<br>
 - 두 번째. ‘rest api 설계’<br>
restful api의 이론을 배우고 프로젝트에서 실습하려고 했습니다. 이론은 머릿속에 있었지만 실제로 설계하는 일은 어려웠습니다. 명사만을 사용해야 했는데 하다보니 몇 부분이 동사로 되어있었고, 모달창을 많이 사용하여 api가 필요없는 곳도 많아 혼란스러웠습니다. 최종 결과물을 놓고 보니, patch나 put을 표현하지 않고 대부분 post를 사용해 수정이 이루어져 있었습니다. 따라서 restful api 설계를 다시 공부한 뒤, 프로젝트를 보완하려고 합니다.

<br>
<hr>
<br>

### 2022년 7월 <여행플래너>
### 소개
코로나가 풀리며 지자체는 물론 정부 차원에서도 국내 여행을 다방면으로 지원하고 있는 흐름에 발맞춰 만든 국내여행 플래너</br>
공공데이터 OpenApi를 통해 관광정보를 가져오는 것을 핵심으로 하는 팀 프로젝트<br><br>
진행 기간: 2022.5.17 ~ 2022.7.1</br></br>
기술 스택</br>
JAVA8, DBMS(Oracle), HTML5, CSS3, JQuery, JavaScript, JSP(MVC2), MYBatis, OpenAPI</br></br>
👉[프로젝트 상세 설명](https://github.com/kiya-moon/JSP-project.git) 참고<br><br>
 ### 느낀 점
 - 공공 api 데이터 가져오기, 이메일 발송 등 새로운 기술을 가득 담아 만든 웹사이트였습니다.<br>
 - 시간 관리의 필요성을 깨달았습니다. 기술 구현에 많은 시간이 빼앗겼고 촉박하게 프로젝트를 완성해야 했습니다. 이 과정을 통해 기간 내에 프로젝트를 완성할 수 있도록 시간 관리가 필요함을 깨달았습니다.<br>
 - 깃을 통해 형상관리를 하려고 했지만 이해가 부족했습니다. 아쉬움이 많이 남아 다음 프로젝트에선 꼭 제대로 사용하기 위해 공부하고 있습니다.<br>

<br>
<hr>
<br>

### 2022년 6월 <주차 정산 프로그램>
### 소개
월정액/시간제 별로 입출차 시간을 계산하여 정산해주는 프로그램<br>
이클립스와 DBMS 연결 및 활용 연습을 목적으로 한 팀 프로젝트<br><br>
진행 기간: 2022.5.12 ~ 2022.6.5</br></br>
기술 스택</br>
JAVA8, DBMS(Oracle)</br></br>
👉[프로젝트 상세 설명](https://github.com/kiya-moon/Second-Java-Project.git) 참고<br><br>
### 느낀 점
- 수업 시간에 하지 않은 부분을 따로 공부하고 그를 활용하기 위해 자발적으로 시작한 첫 팀프로젝트 입니다.<br>
- 각자 맡은 파트는 다르지만 팀원들과 호흡을 맞추고, 모여서 서로서로 코드를 봐주며 팀 프로젝트의 장점을 깨달았습니다.<br>

<br>
<hr>
<br>

### 2022년 4월 <방탈출 게임>
### 소개
자유롭게 가장 하고 싶은 주제로 만든 자바 개인 프로젝트<br><br>
진행 기간: 2022.3.19 ~ 2022.4.6<br><br>
기술 스택</br>
JAVA8</br></br>
👉[프로젝트 상세 설명](https://turtlemoon.tistory.com/65?category=1091485t) 참고<br><br>
### 느낀 점
- 자유롭게 가장 하고 싶은 주제로 진행한 첫번째 프로젝트로, 제가 만든 프로그램을 누군가 즐겁게 쓰는 기쁨을 처음으로 느꼈습니다.

</br></br>

# Bye👋
