# VEGE-TURTLE : 베지터틀
- 채식지향 사용자들을 위한 정보공유 커뮤니티와 샵인샵 형태의 비건관련식품 쇼핑몰 웹 서비스 
- 개발기간 : 2022.10 ~ 2022.12 ( 2개월 )
- 개발인원 : 6명 ( 팀 프로젝트 )
- 개발환경 
  * 운영체제 : Window10
  * 개발방식 : Spring MVC
  * 개발언어 : Java, JavaScript, HTML5, CSS3, JSP
  * 프레임워크 : Spring, MyBatis
  * 개발툴 : Apache Tomcat 9.0 , STS4, MySQL
  * 형상관리 : GitHub
  * API, 라이브러리 : CKEditor API, RESTful API(JSON)
 
- 담당구현 기능 / Spring Framework를 이용, 샵인샵 쇼핑몰 형태 및 커뮤니티 웹서비스 구현
  * 브랜드별 상품리스트 : JSON , 동적 쿼리를 이용한 멀티체크박스 기능
  * 브랜드 팔로우 / 언팔로우 : 개인회원의 브랜드 팔로우/ 언팔로우 기능, 팔로우 상태표시 및 실시간 팔로워 수 표시가능
  * 브랜드별 상품리스트 정렬 : 최근등록순, 가격낮은순, 가격높은순 으로 상품정렬 기능
  * 커뮤니티 게시판 : 댓글 및 대댓글 기능구현, 
                     로그인 한 회원만 글,댓글 작성, 추천하기, 신고하기 가능,
                     본인이 작성한 글만 수정,삭제 버튼 표시,
                     회원당 1회 글 추천하기 기능,
                     부적절한 게시물 신고하기 기능,
                     기본 CRUD 및 파일업로드(3개 제한),
                     CKEditor API를 통한 글 작성,수정 시 글 꾸밈효과 사용,
                     게시판 페이징 처리,
                     게시판 검색기능 
  * 마이페이지 : 메인 나의 활동정보 표시(나의 적립금, 찜한 상품, 나의작성글, 주문내역, 팔로우 브랜드, 1:1문의글),
                주문목록 및 주문내역 상세조회,
                팔로우 브랜드 목록,
                1:1문의 목록 및 작성,
                신고내역
  * 메인페이지,카테고리별 배너 및 헤더, 푸터 제작              
  
---  
- ERD 
![테이블](https://user-images.githubusercontent.com/105136541/218317234-d0a13d06-9d2b-4f6f-afe3-d59280737b43.jpg)

---
- 메인화면
![베지터틀메인2-1](https://user-images.githubusercontent.com/105136541/218114234-918576e2-e390-4614-a29c-df9bef238291.jpg)

- 브랜드별 페이지 : 상품리스트 멀티체크박스
![멀티체크박스](https://user-images.githubusercontent.com/105136541/218317195-4354c61c-0096-41b0-a2e4-add71606e69a.jpg)

- 브랜드별 페이지 : 브랜드 팔로우 / 언팔로우
-![팔로우브랜드](https://user-images.githubusercontent.com/105136541/218317178-ba7cdff0-37e3-4e51-a55d-5746944175d1.jpg)

- 커뮤니티 게시판 (api)
![본인글만수정삭제가능](https://user-images.githubusercontent.com/105136541/218490836-bf707734-40fc-46b9-aebe-72bef66062df.jpg)

- 커뮤니티 게시판 (신고하기, 추천하기, 댓글대댓글)
![신고추천댓글대댓글](https://user-images.githubusercontent.com/105136541/218490841-4b5e38c5-91f3-47e3-8561-3d0e9a85552c.jpg)

- 커뮤니티 게시판 (신고팝업창)
![신고창](https://user-images.githubusercontent.com/105136541/218490839-8dfc7bf4-4975-40bc-9a03-ab79fbeaed15.jpg)


