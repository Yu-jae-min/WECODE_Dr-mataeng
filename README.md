# Dr-Mataeng

닥터마틴 사이트를 참조하여 학습 목적으로 제작 된 프로젝트입니다.

<br />

## 🎉 **데모 영상 및 레포 주소**

- <a href="https://youtu.be/GlK28FnB0Ho" target='_blank'>Demo Video Link</a>
- <a href="https://github.com/wecode-bootcamp-korea/29-1st-Dr-Mataeng-frontend" target='_blank'>Frontend Github Link</a> / <a href="https://github.com/wecode-bootcamp-korea/29-1st-Dr-Mataeng-backend
  " target='_blank'>Backend Github Link</a>

<br />

## 👬 **팀원**

- Frontend 3명, Backend 2명

<br>

## 📅 **개발 기간**

- 2022년 01월 24일 ~ 2022년 02월 10일

<br />

## 🔧 **기술스택**

- Front-End : React, Sass
- Back-End : Python, Django, Bcrypt, PyJWT
- Common : AWS, RESTful API
- 협업 및 일정관리 : GitHub, Slack, Trello, Notion

<br />

## 💻 **설치 및 실행 방법**

1. repository 클론

```
git clone https://github.com/Yu-jae-min/WECODE_Dr-mataeng.git
```

2. dependencies 설치

```
npm install
```

3. 실행

```
npm start
```

## 📒 **구현 목록**

|                                                        회원가입                                                        |                                                          로그인                                                          |                                                            메인                                                            |
| :--------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|  ![0 회원가입](https://user-images.githubusercontent.com/85284246/172942677-574c9768-112c-41ed-9702-62b832446eaf.jpg)  |    ![1 로그인](https://user-images.githubusercontent.com/85284246/172942694-be8d3f30-f95d-4864-8713-f417de9e1960.jpg)    |      ![2 메인](https://user-images.githubusercontent.com/85284246/172942711-041d6b68-0e16-486e-905e-406f395d2007.jpg)      |
|                                                           검색                                                           |                                                       네비게이션                                                       |                                                       상품리스트                                                       |
|     ![3 검색](https://user-images.githubusercontent.com/85284246/172942723-317aa71c-d91d-44a1-bc75-f44b7ef4b850.jpg)     | ![4 네비게이션](https://user-images.githubusercontent.com/85284246/172942732-be686844-32f5-40db-a024-7d30bff40326.jpg) | ![5 상품리스트](https://user-images.githubusercontent.com/85284246/172942751-07a023fb-fef0-439e-80eb-0e4c1d614bad.jpg) |
|                                                       상세페이지                                                       |                                                        장바구니                                                         |                                                            결제                                                            |
| ![6 상세페이지](https://user-images.githubusercontent.com/85284246/172942768-8bc52b64-0e38-479a-a9d8-88376f0e6575.jpg) |  ![7 장바구니](https://user-images.githubusercontent.com/85284246/172942780-80ae5094-86e7-41f9-a676-7474cad3d83e.jpg)   |      ![8 결제](https://user-images.githubusercontent.com/85284246/172942791-b02eab0a-0cc3-480e-8ef9-ab3151ef0a22.jpg)      |
|                                                        회원정보                                                        |
|  ![9 회원정보](https://user-images.githubusercontent.com/85284246/172942804-5355f44b-9b36-417a-9c5a-da1501d10ff3.jpg)  |

<br />

### # 헤더 (담당 기능)

- [x] 토글 버튼 클릭 시 네비게이션 노출

- [x] 헤더 로고 클릭 시 메인 페이지 이동

- [x] 검색 창에 검색어 입력 후 클릭 및 엔터 시 해당 제품 검색 리스트 노출

- [x] 검색 결과 없는 경우 검색 결과 없음 표시

- [x] 로그인, 로그아웃 상태에 따른 버튼 노출

<br />

### # 네비게이션 (담당 기능)

- [x] 네비게이션 카테고리 클릭 시 메뉴 드롭다운

- [x] 네비게이션 메뉴 클릭 시 해당 상품 리스트 페이지로 이동

<br />

### # 회원가입

- [x] 정규표현식과 테스트 메소드를 이용한 유효성 검사 및 조건에 따른 에러메시지 노출

- [x] 유효성 검사 통과 시 데이터 전달 및 로그인 페이지 이동

- [x] 스크롤 위치에 따른 탑버튼 노출

<br />

### # 로그인

- [x] 유효성 검사 조건에 따른 에러메시지 노출

- [x] 로그인 성공 시 로컬스토리지에 User Id & JWT Token 저장 및 메인페이지 이동

- [x] 로그아웃 시 JWT Token 제거 기능

<br />

### # 메인

- [x] 상단 슬라이드

<br />

### # 상품 리스트

- [x] 상세 페이지 이동을 위한 동적 라우팅

- [x] 제품 필터링 기능

- [x] 쿼리스트링 전달을 통한 페이지네이션 구현

- [x] 토글 버튼 클릭 시 필터 노출

<br />

### # 상세 페이지 (담당 기능)

- [x] 스크롤 위치에 따른 주문 컨텐츠 고정 기능

- [x] 제품 수량에 따른 수량 안내 텍스트 노출

- [x] 수량 조절과 재고에 따른 주문 수량 제한 기능

- [x] 결제 버튼 클릭 시 해당 제품 데이터 전달 및 페이지 이동

<br />

### # 장바구니

- [x] 장바구니 목록 총 합계 금액 기능

- [x] 장바구니 목록 없을 시 조건부 렌더링을 통한 페이지 렌더링

- [x] 장바구니 목록에 따른 동적 쿼리스트링 전달

- [x] x버튼 클릭 시 해당 장바구니 목록 삭제

<br />

### # 결제 (담당 기능)

- [x] 주문 목록에 따른 동적 쿼리스트링 전달

- [x] 회원 정보를 받아와 주문 정보에 표시

- [x] 주문 목록 합계 산출 기능

- [x] 결제하기 버튼 클릭 시 보유 포인트를 통한 결제

<br />

### # 회원 정보 (담당 기능)

- [x] 보유 포인트 확인 가능, 결제 후 보유 포인트 차감

- [x] 주문 목록 조건부 렌더링 기능 및 토글 기능

- [x] 주문 정보 표시

<br />
