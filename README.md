# 201740106_김대건_개발(백엔드)_팀원
## [팀명: 파란만장]  

```
- 문동환 (팀장-디자인)  

- 안다희 (팀원-프론트앤드) 
 
- 김대건 (팀원-백앤드)
```
- 졸업작품 소개 사이트 : https://daege0n-kim.github.io/capstone2022/
- 포트폴리오 소개 사이트 : URL
---
## [졸업 작품 소개]
- __작품명 : FLEX__
- 개발환경 : HTML, CSS, JSP, JAVA, XD
- 작품 소개 : 최근 굉장히 핫한 리셀 시장경쟁에 뛰어드는 리셀 플렛폼
- 작품의 특징 : 
```
- 모던하면서 고급지고 트렌디한 디자인 이면서 실용적인 홈페이지 구성

- 스타일 페이지를 중점으로 구성, 다른사람의 스타일과 아이탬을 공유함으로 구매욕구 증대

- 고객 DB 구축 및 로그인, 장바구니, 찜하기 등 고급 기능 구현
```
- 작품기획 :  
```
최근 개성을 중시하는 소비자가 늘어나면서 한정판 아이템 특유의 유니크함을 원하는 소비자들이 상당히 많이 늘어났다.
한정판 제품을 제 판매하는 '리셀'이라는 것이 유행처럼 번지며 안전하게 거래할 수 있는 리셀 플랫폼 또한 수요가 
높아지고 있는 중이다. 리셀 플랫폼은 2곳의 업체가 거의 반독점 하고 있기 때문에, 높은 신뢰도와 편리한 서비스를 제공
한다면 충분한 경쟁력이 있다고 판단된다. FLEX 플랫폼은 깔끔하고 고급스러운 디자인으로 신뢰감과 트렌디함을 더하고, 
좀 더 구매 욕구를 증대하기 위한 여러 디테일들이 숨어있다. 모바일 쇼핑몰은 대부분 비슷한 레이아웃으로 차별점이
없어, FLEX는 우리의 개성을 가장 잘 표현할 수 있는 PC 웹 기반으로 제작되었다.
```





---  
---

## [4월 13일]
### 7주차 작업 내용 (개발 일지)
```
※프레임워크(이클립스->vscode로바꿈)

-회원가입 페이지 

<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
<link rel="stylesheet" href="/resources/css/join.css">
</head>
<body>

<div class="wrapper">
	<form action="">
	<div class="wrap">
			<div class="subjecet">
				<span>회원가입</span>
			</div>
			<div class="mail_wrap">
				<div class="mail_name">이메일</div> 
				<div class="mail_input_box">
					<input class="mail_input">
				</div>
			</div>

			<div class="pw_wrap">
				<div class="pw_name">비밀번호</div>
				<div class="pw_input_box">
					<input class="pw_input">
				</div>
			</div>
			
			
			<div class="join_button_wrap">
				<input type="button" class="join_button" value="가입하기">
			</div>
		</div>
	</form>
</div>

</body>
</html>




- Flex_Member 테이블에 데이터를 저장하거나, 반환된 데이터를 담을 공간을 만들어보겠습니다


package com.pg.flex.dto;

public class MemberVO {
    private String userEmail;
	private String userPassword;
	
	
	
	public String getUserEmail() {
		return userEmail;
	}
	public void setUserEmail(String userEmail) {
		this.userEmail = userEmail;
	}
	public String getUserPassword() {
		return userPassword;
	}
	public void setUserPassword(String userPassword) {
		this.userPassword = userPassword;
	}

	
}







```
---

## [4월 6일]
### 6주차 작업 내용 (개발 일지)
```
---??


```
---



## [3월 30일]
### 5주차 작업 내용 (개발 일지)
```
- DB 구조변경(테이블 수정)
- 회원가입 기능 재구현(버튼 재배치)
- 네이버API를 이용한 네이버로그인(DB연동 부분제외 구현완료)
```
---

## [3월 23일]
### 4주차 작업 내용 (개발 일지)
```
- 장바구니 기능넣기(x)
- 좋아요 기능넣기(x)
```
---
## [3월 16일]  
### 3주차 작업 내용 (개발 일지)
```
- 로그인 기능 구현

- 회원가입 기능 구현

- 데이터베이스 구성

- 회원가입시 메인DB의 사용자 
```
---
## [3월 02일]  
### 1주차 : 팀원구성 주제 정하기 역할분담.  
### 회의내용  
```
- 주제설정 (리셀 플렛폼)

- 작품이미지 구성

- 역할 분담

- 팀명작
```
