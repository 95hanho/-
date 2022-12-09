# 포트폴리오




## 버킷리스트 프로젝트

![image](https://user-images.githubusercontent.com/64001275/206623504-d07a4e7c-2ec6-4643-b590-823e1d890037.png)
>https://github.com/95hanho/FINAL_PROJECT_BUCKETSTORY/tree/HHS

### 목표 및 요약

교육원 자바과정에서의 두 번째 프로젝트
1. 자기가 하고싶고 이루고 싶은 버킷리스트를 등록하고 공유한다. 
2. 타임라인에서 자신의 버킷이나 다른 사람의 버킷을 가져와서 이루는 과정을 블로그형식을 작성한다. 
3. 기업에서 제휴하여 버킷을 이루는 것을 도와준다.
ex) 요리교습 같은 실습 지원이나 숙박, 여행사 등과 연계하여 비용 견적서를 내줌
### 언어

- JAVA
- HTML / CSS
- Oracle DB
- JSP
- JDBC template
- JavaScript
- Jquery
- Ajax
- Mybatis
- Springframework

=> Springframework과 jquery를 숙지하고, 화면단에서 jquery를 이용하여 jsp기본문법으로 선언하지 않고 더 깔끔하게 표현하고, 스프링과 mybatis의 MVC패턴으로 개발하였습니다.

### 주요 기능

1.메인 및 타임라인 페이지 제작 및 디자인

2.창크기에 따른 반응형UI

3.좋아요, 위시, 버킷등록

4.게시글 태그 기능

5.버킷카테고리별 사이드 메뉴바

6.검색API를 이용하여 태그, 회원, 버킷, 기업 네 가지로 검색결과 표출

7.웹소켓을 이용한 실시간 알람

-----------------------------------------------------
## 개인/단체톡 프로젝트

![image](https://user-images.githubusercontent.com/64001275/206623570-8250961a-f478-4153-ac82-b6602941118e.png)
>https://github.com/95hanho/BootChatting

### 목표 및 요약
회사 입사 후 스프링부트를 숙지하면서 만든 첫 개인프로젝트로 부트를 최대한 활용하여 스프링에서 복잡했던 것을 최대한 바꾸고, 웹소캣을 최대한 활용할 수 있는 카카오톡과 유사한 프로그램을 만들면서 여태껏 해보지 못한 기능들을 최대한 해 볼 수 있게 개발하였습니다.
### 언어
- JAVA
- HTML / CSS
- Oracle DB
- JSP
- JDBC template
- JavaScript
- Jquery
- Ajax
- Mybatis
- SpringBoot
### 중요 과제
1. 스프링부트의 활용(mvc설정, DB와 mybatis설정 및 Alias관리)
2. 인터셉터를 이용한 AOP 활용(요청마다 세션 연장)
3. @Async 다중스레드의 활용(세션시간 종료 시 자동로그아웃)
4. 웹소켓을 최대한 활용한 실시간 반응(실시간 채팅)
5. 채팅 반응성
6. 파파고번역 기능 추가(영 -> 한, 한 -> 영)
### 주요 기능

  카카오톡에서 기본적으로 볼 수 있는 기능들을 대부분 집어 넣으려고 했습니다. 기능위주로 디자인은 필요한 수준으로만 꾸렸습니다.
  
  개인/단체 톡이 따로 있고 읽지 않은 메시지 갯수를 알려주고, 톡방에 초대되면 톡방리스트에 추가됩니다.
  
  톡방 안에서는 채팅 뿐만 아니라 간단한 사진이나 메모를 보낼 수 있고 다운로드 할 수 있으며, 대화를 보지않은 사람의 수 표현이나 채팅방에서 나가고 들어오고의 시점에 따른 이전 채팅이 안보이게 하는거 뿐만 아니라 개인톡에서는 따로 나가는 표시를 하지않고, 상대방에 나간 상태에서 다시 채팅을 날릴 시에 다시 초대되는 등의 세부사항까지 표현하였습니다.
  
 파파고번역을 넣어서 영어로 판단되는 텍스트를 한글로 번역 할 수 있습니다. 

-------------------------------------------------------
## 뷰/기본프로젝트 프로젝트

![Uploading image.png…]()
> https://github.com/95hanho/SpringVueExample.git

> https://github.com/95hanho/ExpressVueExample.git

### 목표 및 요약

리눅스와 nodejs, 뷰를 처음으로 접하여서 만든 프로젝트로 기본기능 조회, 수정, 삭제를가진 restAPI 스프링부트, express 둘 다에 빌드하여서 개발하였습니다. 

### 언어
※ 여기부터 사용량이 높은 것 위주로 표시
- SpringBoot
- Express
- Vue(Axios, Router)
- Javascript
- 부트스트랩

### 중요 과제

1. vue 기본 문법 및 요청, url매핑 사용
2. vue FE단과 restAPI BE단 여러 서버에 연결

### 주요 기능

- 가상번호와 멘트경로 정보를 조회, 입력, 삭제, 수정
- 유저 추가

-------------------------------------------------------

## ELK로그분석 조회웹

![image](https://user-images.githubusercontent.com/64001275/206623405-bed0413f-d91d-42d3-8918-978a6dee9a61.png)
> https://github.com/95hanho/LogSearch

### 목표 및 요약

 기존 ejs화면으로 구성된 다중 페이지 express API를 vue를 이용하여 SPA로 바꾸는 작업을 하였습니다. 메시지관련 로그를 검색파라미터 또는 엑셀파일로 다중 검색하는 웹으로 express, vue이외에도 elasticsearch, logstash, filebeat 를 이용한 필터링 및 데이터 작업을 진행하였습니다. 깃허브에는 FE단만 온전히 개발하여서 올렸고, BE단은 passport를 이용한 로그인 세션관리를 FE단의 토큰방식으로 바꾸고, 다수의 elasticsearch쿼리문수정, 그리고 반환값을 restAPI로 수정하긴 하였지만 회사 내용이 많을 수도 있어서 제외하였습니다.
 
### 언어
※ 사용량이 높은 것 위주로 표시
- Express
- Vue(Axios, Router, Vuex, cookies)
- Javascript
- 부트스트랩

### 중요 과제 및 기능

1. 부트스트랩 디자인의 기초
2. 뷰 컴포넌트마다의 데이터 이동/공유하기
3. 뷰 디렉티브 활용
4. jwt기반 토큰을 이용한 사용자 인증
5. 뷰 컴포넌트 페이징 처리
6. FE에서 업로드/다운로드
7. vuex 데이터 유지 / 공통 메소드 처리

-----------------------------------------------------

## 가상 번호 조회 웹

![main](https://user-images.githubusercontent.com/64001275/206630687-1c4ffd24-5893-4291-b167-ecf83f4cdb04.png)
> https://github.com/95hanho/VirtualNum

### 목표 및 요약

 가상 번호와 일정, 멘트파일 등 여러 객체를 조회, 입력, 수정, 삭제를 하여야 하고, 조합하여 Set등록을 하여야 한다. 서버의 설정에 따라서 데이터를 요청할 때는 AES암호화가 필요할 수 있어서 서버암호화 확인 및 파라미터 암호화를 추가하였습니다.

### 언어
- Java(API와 연결)
- Vue(Axios, Router, Vuex, cookies)
- Javascript
- 부트스트랩

### 중요 과제 및 기능

1. AES128 암호화
2. 이벤트버스를 이용한 컴포넌트로 데이터 이동 및 메소드실행

-----------------------------------------------------
## 통화기록 조회 웹

> https://github.com/95hanho/Phone-Log

### 목표 및 요약

 통화기록 조회 웹으로 vue 내부에서 토큰을 만들어서 서버에 저장을 하고, 서버에서 조회 시에 결과값이 XML로 반환되어 따로 매핑을 해줬습니다.

### 언어
- Java(API와 연결)
- Vue(Axios, Router, Vuex, cookies, jsonwebtoken)
- Javascript
- 부트스트랩

### 중요 과제 및 기능

1. 내부 토큰화를 이용한 로그인 유지시간 관리
2. XML결과 값 매핑

