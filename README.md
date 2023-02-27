![header](https://capsule-render.vercel.app/api?type=transparent&height=100&text=나의%20역할%20:%20Java,%20DB,%20Python&fontColor=0055ff&fontSize=50)
<!-- 나의 역할을 바로바로 띄워서 먼저 부각시켜 보여준 후 프로젝트 소개로 넘겨라 -->
### 1. Java와 JDBC를 활용해 웹 서비스의 백엔드 기능 구현
- 공고 상세 페이지 기능 구현
- 이미지 검색 기능 구현
- 유기/유실동물 등록 페이지 기능 구현 및 프론트엔드 제작

### 2. DB 설계 및 구축, 데이터 수집 및 전처리
- 테이블 설계 및 구축
- 크롤링을 활용해 동물보호센터, 동물보호관리시스템에서 데이터 수집
- 수집한 데이터를 웹페이지에 활용할 수 있도록 전처리
### 3. Python을 활용한 데이터 수집 및 딥러닝 모델 구현
- 동물보호센터, 동물보호관리시스템 데이터 수집 크롤링 기능 제작
- Mobilenet v2를 이용해 이미지 유사도 측정 기능 모델 구현
- Flask를 이용해 Java 프로젝트와 Python 모델 연동

## 📜 프로젝트를 진행하며 얻은 것
#### 학습한 것
  - 머신러닝, 딥러닝 모델의 구조 파악
  - Flask를 활용한 로컬 서버 연동
  - MVC 구조의 웹 페이지 제작 경험
  - 데이터 크롤링 및 자료 수집 방법에 대한 지식 습득
  - 데이터베이스 설계 및 구축과 XML을 통한 데이터베이스 연동
  - GitHub를 활용해 버전 관리 및 협업하는 방법
  - Google Drive를 활용한 서류 및 데이터 관리

#### 오류 및 아쉬웠던 점
  - 딥러닝 모델을 구현할 때 시간적 여유가 없어 학습되어 있는 모델을 이용했기에 기존에 구상했던 YOLO v5를 활용한 모델을 제작해보지 못한 점이 아쉬웠다.
  - 학습되어 있는 모델이더라도 다른 사람이 작성한 코드를 해석해서 우리 프로젝트에 맞게 수정을 해야 했기에 많은 시간이 걸렸고, 자신의 역량이 중요함을 깨달았다.
---

## 프로젝트 소개

- 개발 기간 : 2022년 11월 02일 ~ 2022년 12월 12일
- 개발 인원 : 5명

- 프로젝트 개발 목표 및 내용
  - 유실/목격/보호 동물을 등록할 수 있는 게시판 서비스를 제공   
    - 로그인 없이 사용 가능한 기능   
    - 연락처와 유실 일자, 이미지 파일은 필수로 입력
    - 축종, 품종, 털 색, 장소, 성별, 중성화 여부, 특이사항은 추가적으로 입력 가능

  - 등록된 유기/유실동물을 검색할 수 있는 기능 구현   
    - 축종, 품종, 유실 지역을 기본으로 선택하여 검색 가능
    - 추가적으로 이미지를 업로드 하면 이미지 비교를 통해 비슷한 공고를 출력 

  - 반려생활 길잡이를 통해 반려동물을 키우기 위한 정보를 제공
    - 축종별 사료 급여 방법, 예방접종과 검강검진, 외출시 필수사항을 확인할 수 있음
  
  - 커뮤니티 기능 구현
    - 로그인 했을 시에 글쓰기 버튼 출력
    - 본인이 등록한 게시글은 삭제 가능
    - 댓글 작성 및 삭제 기능 구현

- 사용한 데이터(출처 : 동물보호센터, 동물보호관리시스)
  - 연락처(개인정보일 경우, 게시글 주소를 제공)
  - 유실 일자
  - 축종
  - 품종
  - 털 색
  - 장소
  - 성별
  - 중성화 여부
  - 특이사항
  - 동물 이미지

- 산출문서   
  - 프로젝트 기획서(브레인스토밍, 아이디어 기획서)
  - 요구사항 정의서
  - 요구사항 추적표
  - 테이블 명세서
  - 데이터베이스 요구사항 분석서
  - 화면 설계서

---

## 1. 사용 기술
- 언어   
![Java](https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white)
![Javascript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![JSP](https://img.shields.io/badge/JSP-%2300599C.svg?style=for-the-badge&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)

- DB   
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

- Framworks   
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)

- IDEs   
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![VScode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white)

---

## 2. ER Diagram

![화면 캡처 2023-02-27 171513](https://user-images.githubusercontent.com/107980423/221509700-aac5e4fe-9085-470e-9fe4-d3f110b6e8b2.png)

---

## 3. 서비스 흐름도 및 시스템 구성도
- 서비스 흐름도   

![제목 없는 다이어그램](https://user-images.githubusercontent.com/107980423/221509902-d258e01a-0acb-41fd-9779-a8e3f96fc993.png)

- 시스템 구성도   

![화면 캡처 2023-02-27 171828](https://user-images.githubusercontent.com/107980423/221510301-01a8b575-cef3-4a69-afe1-b2266514fc79.png)

---

## 4. 프로젝트 일정

---

## 5. 구현 화면

---

## 6. 팀원 소개
|  이름  | Github 주소 |
| :----: | :-----------: |
| 한재정 | [Github](https://github.com/hanjaejeong) |
| 강혜지 | [Github](https://github.com/kkangji99) |
| 김기범 | [Github](https://github.com/colaage23) |
| 김소희 | [Github](https://github.com/kimsh100gun) |
| 신은지 | [Github](https://github.com/ejshin1016)  |

---


