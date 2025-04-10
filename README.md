# <img src="./exec/img/logo.png" width="150">

## <img src="./exec/img/icon.png" width="25"> 프로젝트 소개

아이를 위한 곤충 육성 애플리케이션

### 1. 프로젝트 목표

- 아이들이 곤충을 관찰하고 돌보며 곤충 생태계를 학습할 수 있는 교육용 애플리케이션

<br>

### 2. 프로젝트를 하게 된 배경 또는 근거

**정서곤충**이란 사람들이 곁에 두고 기르며 자연을 이해하고 심리적 안정을 찾을 수 있게 도와주는 곤충을 의미한다. 이러한 곤충을 돌보는 것은 정서지능을 발달시키는 데 도움을 주며, 특히 우울, 스트레스, 불안을 줄여주는 효과가 있다고 알려져 있다.

- **정서적 안정과 정서지능 발달**: 곤충을 기르고 관찰하는 과정은 후천적으로 학습 가능한 정서지능을 발달시키는 데 도움이 된다. 이는 아이들이 감정을 더 잘 조절하고 타인과의 관계를 원만하게 유지하는 능력을 기르도록 한다.
- **곤충을 통한 심리적 안정**: 곤충을 돌보는 활동은 심리적인 안정감을 제공하며, 이는 스트레스와 불안을 줄여주는 긍정적인 효과로 이어질 수 있다.
- **자연과의 상호작용**: 직접 자연에서 곤충을 기르는 것보다 AR로 구현된 가상 환경에서 더 안전하고 접근성 높은 경험을 제공함으로써, 언제 어디서나 곤충 생태계를 쉽게 경험할 수 있다.

<br>

### 3. 주요 기능

- **사진으로 곤충 채집 및 AI 분류**
  - 사용자가 곤충을 찍으면 AI가 자동으로 곤충을 인식하고 분류해 도감에 저장
  - 곤충을 채집하고 관찰하는 과정을 통해 생태계에 대한 흥미를 유발
- **곤충 키우기 (AR 상호작용)**
  - AR 기능을 통해 곤충이 움직이고 먹이를 먹는 모습을 생생하게 관찰 가능

<br>

### 4. 프로젝트를 통한 기대효과

- **곤충 체험의 교육적 가치**
- **인지 기능 향상**
- **자연과의 정서적 연결**

<br>
<br>

## 🖥 기술스택

### 1. 아키텍처

<img src="./exec/img/아키텍처.png">

<br>

### 2. 기술스택

[![My Skills](https://skillicons.dev/icons?i=unity,spring,fastapi,mysql)](https://skillicons.dev)
<br>
[![My Skills](https://skillicons.dev/icons?i=docker,jenkins,idea,vscode,postman,git,gitlab,notion,figma)](https://skillicons.dev)

<br>
<br>

## 📱시연 움짤

<div style="width: 100%;">
<img src= "./readme/main.png" style="width:40%;"
/>
<img src= "./readme/catch.gif" style="width:40%; margin-left:10px;"
/>
</div>

- 시작화면, 채집한 곤충 화면
- `Unity` 활용

<br>

---

<div style="width: 100%;">
<img src= "./readme/ar.gif" style="width:40%;"
/>

</div>

- AR(증강 현실) 기술 사용
- `AR Foundation` 을 통한 평면 인식
- `AR Core` 를 통한 원근감 표현

<br>

---

<img src= "./readme/message.png" style="width:100%;"
/>

- 푸시 알림 구현
- 모바일에서 실시간으로 육성 이벤트를 확인할 수 있다.
- `Firebase` 활용

<br>
<br>

## 🔧 ERD

<img src="./exec/img/erd.png" />

<br>
<br>

## 😶 팀원소개

| <img src="./exec/img/민서.jpg" width="100%" height="100"> |                    <img src="./exec/img/민채.png" width="100%" height="100">                    |    <img src="./exec/img/지흔.jpg" width="100%" height="100">    |                         <img src="./exec/img/서희.jpg" width="100%" height="100">                         |       <img src="./exec/img/호성.jpg" width="100%" height="100">        |      <img src="./exec/img/원우.jpg" width="100%" height="100">       |
| :-------------------------------------------------------: | :---------------------------------------------------------------------------------------------: | :-------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------: | :------------------------------------------------------------------: |
|                          강민서                           |                                             김민채                                              |                             서지흔                              |                                                   서희                                                    |                                 정호성                                 |                                조원우                                |
|                           Infra                           |                                        Backend, Frontend                                        |                               AR                                |                                             Backend, Frontend                                             |                              AI, Frontend                              |                           Design, Frontend                           |
|                  기획, <br> Infra, CI/CD                  | 기획, DB설계, <br> 도감 관련 API 구현, <br> 푸시알림 구현, <br> 화면 구현 <br> (채집, 회원가입) | 기획, <br> AR 기능 구현, <br> 화면 구현 및 API 연동 <br> (육성) | 기획, DB설계, <br> 채집 및 육성 관련 API 구현, <br> 화면 구현 및 API 연동 <br> (채집결과, 곤충상세, 도감) | 기획, <br> 곤충 판별 AI 구현, <br> 화면 API 연동 <br> (채집, 회원가입) | 기획, <br> 화면 디자인, <br> 화면 구현 및 API 연동 <br> (메인페이지) |
