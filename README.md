# Shopping-Project 
스프링부트 + 쇼핑몰 프로젝트

## 🖥️ 개요
- SpringFramework를 이용한 쇼핑몰 웹 프로젝트


## 🕰️ 프로젝트 기간
   2023. 02-13 ~ 2023. 03-13


## 🧑‍🤝‍🧑 참여 인원
- 팀장 : 이지창 - DB설계,장바구니 담기, 장바구니 조회 , 상품추가 , 마이페이지 , AWS EC2 배포
- 팀원1 : 강창신 - 페이지 Header&Footer layout , main&Admin 페이지 , 게시판 댓글 기능
- 팀원2 : 김득주 - 회원 CRUD , Spring Security
- 팀원3 : 장효선 - 상품 CRUD , 전체적인 디자인 수정
- 팀원4 : 허인경 - 게시판 CRUD, PPT제작


## ⚙️ 개발환경
- OS : Windows10
- Language : Java , HTML , CSS
- IDE : IntelliJ , MySQL workbench , Visual studio
- Framework : Springboot(2.x)
- Database : Oracle DB

## 📰 DB구조

![image](https://user-images.githubusercontent.com/116870832/231031994-045dab5d-5dba-4dd1-94a9-3762488410a8.png)

* Item 테이블에 member_id는 상품을 추가할 때 Member 테이블에 Role = ADMIN 관리자가 상품 추가한 목록을 확인하기 위함
* cartItem은 cart 와 Item 사이에 매개역할 : 장바구니에 여러 아이템이 생길 수 있는데 여러개 상품정보에 대한 중복 처리 & 관리에 용이

## 🔧 기능 소개





