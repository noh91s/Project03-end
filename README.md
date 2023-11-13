<p align="center">
<img src="img_read/logo.png">
</p>

# SIXMAN
## 시나리오형 쳇봇 웹 개발 프로젝트
## [프로젝트 소개 PDF(영상포함)](https://docs.google.com/presentation/d/1CkoOrN41lugsXsth9J_nlqLhLEDNJaqz/edit?usp=sharing&ouid=101047900780001156857&rtpof=true&sd=true)
## [프로젝트 DB ERD](https://drive.google.com/file/d/1QUiq3_GKrSkSBKNos43bwLWZHIhj4pq9/view?usp=sharing)
## 📅 프로젝트 기간 - 2023.10.26 ~ 2023.11.15

## 🖥️ 프로젝트 소개
- 이전 프로젝트(그룹웨어 프로젝트) 인터페이스 기반
- Spring MVC 패턴으로 개발하였습니다.
- 날씨api, 영화api, 버스api 를 연동하여 기능구현 하였습니다.
- 날씨, 영화, 버스 정보를 불러올수 있는 ChatBot을 구현하였습니다

## ⚙️ 개발 환경
- `Language` : Java 11, HTML5, CSS3, JavaScript
- `IDE` : IntelliJ IDEA, Visual Studio Code
- `Framework` : Springboot
- `Database` : MySQL
- `Template Engine` : Thymeleaf
- `ORM` : JPA <br>

## 🧑‍🤝‍🧑 팀 구성 및 역할
### 팀원 : 노승준 - 버스api <br>
#### `Controller` : BusController <br>
#### `Templates` : Bus <br>

<details>
<summary>데이터 모델링 및 Entity, Dto 상세보기</summary>
<br>
  <p align="center"><img src="img_read/2ckDB.png"></p> 
<br>
  <p align="center">회원(employee)와 결재문서(approval)을 중심으로 전체적인 테이블과 연관관계를 설정하였고,</p>
  <p align="center">결재선(approval_user)을 추가로 구성하여 결재,참조 구분</p>
<br>
</details>
<br>
<details>
<summary>결재 문서 페이지(approval) 상세보기</summary>
<br>
  <p align="center"><img src="img_read/ap01.png"></p> 
<br>
<br>
  <p align="center"><img src="img_read/ap02.png"></p> 
<br>
<br>
  <p align="center"><img src="img_read/ap03.png"></p> 
<br>
</details>
<br>

<details>
<summary>챗봇 동작(시나리오)</summary>
<br>
  <p align="center"><img src="img_read/bus_chatbot1.png"></p> 
  <p align="center">미리 등록한 시나리오를 통한 답변 요청</p>
<br>
</details>
<br>

<details>
<summary>챗봇 동작(채팅)</summary>
<br>
  <p align="center"><img src="img_read/bus_chatbot2.png"></p>
  <p align="center">메세지 입력을 통해서 바로 답변 요청</p>
<br>
</details>
<br>


#### 팀장 : 송** - 날씨api <br>
#### 팀원 : 박** - 영화api, 챗봇 <br>
#### 팀원 : 김** - 영화api <br>
#### 팀원 : 이** - 버스api <br>