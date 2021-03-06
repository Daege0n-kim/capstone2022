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

## [5월 25일]
### 13주차 작업 내용 (개발 일지)




저번 시간 작업에 이어서 MYPAGE를 마무리하겠다

## [1] MYPAGE 프론트엔드 작업물을 백엔드 기능 구현 

1. Mypage 유저프로필 수정화면(로그인 시 마이페이지 접속)


![mypageIndex](https://user-images.githubusercontent.com/70187585/170853415-af9e4d4b-b621-46f6-8c80-f9d386e95d48.PNG)



2. Mypage에 기능 입히기(작업순서: 컨트롤러-> 서비스-> DAO ->MAPPER)


2.1 컨트롤러 



![mypageController작업](https://user-images.githubusercontent.com/70187585/170853466-ed078abf-0238-4a0f-b8c0-3ba7a430a2e3.PNG)




2.2 컨트롤러를 연결하는 서비스구성


![mypageService](https://user-images.githubusercontent.com/70187585/170853482-697b86d7-ae46-4adb-b92b-023bd5660e73.PNG)



2.3 실제 DB에있는 데이터를 받는 DAO



![mypageDAO](https://user-images.githubusercontent.com/70187585/170853513-a93aba0f-70f1-4fa9-88f5-47a1bcd7eac5.PNG)






2.4 실제 DB에서 데이터를 가져오는 명령문을 나타내는 MAPPER

![mypageMapper1](https://user-images.githubusercontent.com/70187585/170853525-6b6b6523-1c48-491b-bf61-5e7cc27b2438.PNG)




※Resultmap 작성시 이름 동일하게 적어주기



2.4 실제 DB에서 데이터를 가져오는 명령문을 나타내는 MAPPER2


![mypageMapper2](https://user-images.githubusercontent.com/70187585/170853553-eaaa3c4b-6ff6-4f88-ab08-5c887db4965c.PNG)




## [2] SHOP 페이지 API 구현(이미지 추가)





![7페이지 SHOP 이미지API추가](https://user-images.githubusercontent.com/70187585/170853609-15f29458-1517-4a1a-8e16-0b41c93fc3f5.PNG)





※ 문제발생(10페이지 유저이미지 수정)


![10페이지 유저프로필api(문제발생)](https://user-images.githubusercontent.com/70187585/170853624-052aa5e3-4b14-422e-8109-5ffdd421de65.PNG)


문제: 다른 유저추가 시 장바구니에 물품을 담으면 유저별로 구분해서 나와야하는데 다른 유저에 상품목록까지 합해진 가격이 나온다




해결

->![image](https://user-images.githubusercontent.com/70187585/170853746-55c32363-d53d-43a8-8e76-405a350a36df.png)



---  
---




---  
---

## [5월 18일]
### 12주차 작업 내용 (개발 일지)



## [1] MYPAGE 배송지관리 페이지 API 

1. Mypage 배송지관리 페이지


![image](https://user-images.githubusercontent.com/70187585/169697608-e1b9ebb2-9c15-4e68-a72b-33acbf371970.png)



2. 배송지관리 페이지에 테이블 조회


테이블 조회시 현재 값x


->insert into 테이블명(컬럼명,컬럼명,컬럼명,컬럼명) values(값,값,값,값);


기존 shipping_adress 테이블 조회


![배송지 주소 입력값넣기(테스트)](https://user-images.githubusercontent.com/70187585/169697787-a317689b-789f-499a-a750-2fa2cca96ce3.PNG)




3. 배송지관리 페이지 실제기능 API테스트


![배송지관리 API(검토필요)](https://user-images.githubusercontent.com/70187585/169697828-0f51bae2-32c3-4701-b9ea-89d55af550e5.PNG)




## [2] MYPAGE 결제수단 등록페이지 API

1. Mypage 결제수단 등록페이지 테이블 조회 및 데이터 값 넣기



![결제수단 등록(테스트)](https://user-images.githubusercontent.com/70187585/169697883-f0203176-3e6c-4e0b-a17e-8adb39f5d7fe.PNG)



2. 결제수단 페이지 실제기능 API테스트 



![결제수단 등록 API(검토필요)](https://user-images.githubusercontent.com/70187585/169697896-34a71c59-de9f-4997-acea-e8e3cf9026a4.PNG)




※현재 페이지가 나오지않아 백엔드 API만 작성


＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠추후 페이지나오면 작성해논 API에 페이지 연동해서 결과확인하기＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠＠




※오류사항(해결x)



![테이블오류](https://user-images.githubusercontent.com/70187585/169697947-d11db686-c204-488e-b11a-f53d789ecd7e.PNG)




---  
---

## [5월 11일]
### 11주차 작업 내용 (개발 일지)



## [1] DB에서 값을 불러와서 메인화면의 NEW ARRIVE부분 DB입력값 들어가게하기

1. 초기화면(설정 전)
![DB데이터 불러오기전](https://user-images.githubusercontent.com/70187585/168424931-c6aad12f-5eab-452a-b39d-0ff53c88b252.png)



2. shopMapper.xml 수정

![수정상황2](https://user-images.githubusercontent.com/70187585/168425001-be836213-2337-42ac-9492-012adbd96945.PNG)


3. 메인 index.jsp 수정

![수정한부분](https://user-images.githubusercontent.com/70187585/168425117-c22e10a4-6b42-4500-a006-7d73aadec9d9.PNG)



4. 수정 후

![수정 후](https://user-images.githubusercontent.com/70187585/168425145-79d6ef5f-1d90-4ae9-b0ee-47309796eed4.PNG)




## [2] DB에있는 브랜드 정보 가져오기 및 여러작업


5. DB에 있는 값을 갖고오는 Brand.dto

![brand DTO](https://user-images.githubusercontent.com/70187585/168425240-b613b2f8-134b-4ac2-8a04-a734bc4219fe.PNG)


6. 상품상세페이지 쿼리문작성(페이지x, 시간 단축위해 명령문 작성)

![image](https://user-images.githubusercontent.com/70187585/168425369-418e73ba-79af-49ee-93c9-1f1e94b6f76d.png)


7. MYpage 관련상품성택 API

![image](https://user-images.githubusercontent.com/70187585/168425421-eabcc818-cb34-4d4c-8722-c4d2e85ee06b.png)




## [3] 로컬DB에 배송테이블,카드정보테이블 추가

<배송테이블>

![0509 졸작](https://user-images.githubusercontent.com/70187585/168425505-fcc9ce49-b010-4257-bfbb-4e10248ac0ad.PNG)


<카드정보 테이블>

![0509 2졸작](https://user-images.githubusercontent.com/70187585/168425517-0f8ce9c0-45d0-456a-9862-6257784a205c.PNG)




---  
---


---  
---

## [5월 4일]
### 10주차 작업 내용 (개발 일지)




1. DB의 테이블 구성

![image](https://user-images.githubusercontent.com/70187585/167254007-c9e1d613-a8cc-4c39-8a07-f8043e038086.png)
![image](https://user-images.githubusercontent.com/70187585/167254042-750665bd-e1cd-4fc4-b667-c5893e75a80e.png)



2. 구성한 테이블에 데이터값 넣기

![image](https://user-images.githubusercontent.com/70187585/167254101-d714be99-6ccd-47b7-a76f-59bf766ffd74.png)


3. 로그인에 필요한 RestShopController.java

![image](https://user-images.githubusercontent.com/70187585/167254329-587a1af1-9b96-4556-8600-d6802ee671b5.png)


4. shop페이지에들어가기 위한 ShopController.java

![image](https://user-images.githubusercontent.com/70187585/167254358-5d5d154a-11d0-4280-a8ec-b5ffe648198e.png)

5. sign-up.jsp에 DB값을 받기위한 데이터설정

![image](https://user-images.githubusercontent.com/70187585/167254431-a3c06b61-8037-4504-8c9c-ffb6d715ff91.png)

6. 마지막으로 로그인에 필요한 Mapper.xml 쿼리문

![image](https://user-images.githubusercontent.com/70187585/167254474-ab2eee92-caea-43f1-92fd-58cc145b6a7a.png)


7.실행결과

![image](https://user-images.githubusercontent.com/70187585/167254643-d15ded22-d98a-48e2-a1c0-8e89094f481d.png)




![image](https://user-images.githubusercontent.com/70187585/167254654-07d87b07-e43c-4d18-8bae-7c45f67a8c27.png)




---  
---






---  
---

## [4월 27일]
### 9주차 작업 내용 (개발 일지)




- STYLE페이지 html->jsp로 바꾸기(소스바꾸기)
     ->이미지 경로, css경로 전부 다 바꾸기..

![image](https://user-images.githubusercontent.com/70187585/166222996-6523ba6c-fc7d-42f0-b489-2b1ff7ccec33.png)



# 프론트 작업양이 많아 프론트 서포터 작업 


- 찾기편하게 페이지별로 나누기(main,login,mypage,shop등등)

![image](https://user-images.githubusercontent.com/70187585/166223145-d5ac3f75-68ab-484b-9604-b6ab15792b75.png)

- ※추후 작업할것은 DB구성이나오면 html에다가 디비 연결해서 이미지 및 텍스트 


---  
---





---  
---
## [4월 13일]
### 7주차 작업 내용 (개발 일지)

※ 프레임워크(이클립스->vscode로바꿈)

-로그인 기능구현
※로그인 페이지는 따로 만들어서 구현

## 컨트롤러: 리퀘스트 호출인식학고 ,프론트에서 로그인에 필요한 데이터를 받아주는역할을함
![image](https://user-images.githubusercontent.com/70187585/163704433-1139163b-6712-486f-b622-e89f7cdfa357.png)





## 서비스: 요청한 리퀘스트나 받아온값을 이용해 비즈니스 로직을 지음
![image](https://user-images.githubusercontent.com/70187585/163704521-79a4dc9d-6533-44b9-a711-39a7b533d7eb.png)






## dao: mapper랑 연결을 해줄 함수를 만든다
![image](https://user-images.githubusercontent.com/70187585/163704582-bd80f9df-daac-4fa7-90c3-801ae9c72870.png)






---
## 로컬에 있는 DB를 불러온다
![image](https://user-images.githubusercontent.com/70187585/163704600-4a04a438-5bd4-4579-a3c3-96f81d820202.png)

---


## [4월 6일]
### 6주차 작업 내용 (개발 일지)
```
- ??
- ??
- ??
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
