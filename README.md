# README.md

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d404ad21-a3b0-46e0-952d-60c2b46ad1da/Untitled.png)

Python 3.9.10

npm: 8.7.0
node: 16.15.0

[DDOK-Di/README.md at main · NKLCBAE/DDOK-Di (github.com)](https://github.com/NKLCBAE/DDOK-Di/blob/main/DDOK-Di/README.md)

여긴 들어와지지? 예스

- 김영준, 김우석 공통 팀 리드미

[README](https://www.notion.so/README-2023d6b813f3486ca6b0320dbfe7dad3)

================================================================ =============================절취선==============================

================================================================

# WebTuna: 웹툰 추천 플랫폼

### 팀명: 툰툰이들

### 서비스명: 웹투나(WebTuna)

### 진행 기간

2022.08.29 ~ 2022.10.07(금) / 6주

### 기획 배경

 코로나19로 웹툰 이용자 수가 급증하여 한 달에 1000만명 수준인 상황. 그리고 사람들이 이용하는 웹툰 플랫폼에서는 저마다의 추천을 해주고 있지만, 설문조사 결과 현재 웹툰 이용자의 세 명중 두 명 정도는 추천 서비스를 이용하지 않고 있다. 그리고 그 이유에는 추천 서비스에 만족하지 못하는 여러 가지 이유 들이 있는데 그 이유는 다음과 같다.

1위. 내가 보는 것과 상관 없는 홍보성 웹툰 추천(44%)

2위. 추천해서 봤지만 막상 재미없는 웹툰 (43%)

3위. 불편한 UI (25%)

  이런 이유들로 추천 서비스를 이용하지 않는 사람들이 많았고, 설문조사 결과 적절한 웹툰 추천 서비스가 있다면 이용하겠다는 사용자의 비율이 무려 70%에 달했다. 우리 툰툰이들은 위의 문제점을 해결해서 더 깔끔하고 더 정확한 웹툰 추천 서비스를 제공하고 싶었고, 그것이 ‘웹투나(Webtuna)’가 세상에 등장한 배경이다. 서비스명 웹투나는 웹툰(Webtoon)과 참치(Tuna)의 합성어로, 세상의 모든 웹툰이 담긴 바닷속을 누비는 툰툰이라는 참치 캐릭터가 사용자에게 맞춤형 웹툰을 찾아준다는 컨셉이다.바다처럼 수 많은 웹툰을 보유하고 또 추천해주기 위해서 네이버, 카카오웹툰, 카카오페이지 의 모든 웹툰들을 웹투나 한 곳에서 추천 받을 수 있다. 

그리고 설문조사 결과 사람들이 웹툰을 선정하는 기준의 순위는 다음과 같다.

1. 스토리(85%)
2. 그림체(64%)
3. 장르(47%)
4. 작가(35%)

 그리고 현재 다양한 웹툰 플랫폼에서 여러 방법으로 추천해주고 있지만, 웹투나에서는 기존 플랫폼들과 차별화를 두기 위해 그림체를 위

### 서비스 설명

머신러닝을 활용해 자체적으로 분류한 6가지 그림체를 기반으로 사용자가 선호하는 그림체를 분석하여 웹툰을 추천한다.

### 기술 특장점

CNN을 활용한 웹툰 그림체 분류

teachablemachine을 활용한 실시간 데이터 분석

CF, CBF 기반 추천 알고리즘
Chart.js를 활용한 데이터 시각화
모바일, PC 모두 최적화된 반응형 웹 페이지 제공

## 주요 기능

### 회원가입 시 선호 그림체 선택

사진

콜드스타트 문제를 방지하기 위해 사전 선호 그림체를 수집한다.

### 메인 페이지

사진

6가지 그림체 별로 실시간 인기 TOP5 웹툰을 전시한다.

### 추천 페이지

사진

Collaborative Filtering(Item-based Filtering & User-based Filtering) 추천

선호 그림체 기반 / 선호 장르 기반 / 선호 태그 기반 / 오늘 날씨 기반 등 6가지 추천 방식을 통해 사용자에게 알맞은 웹툰을 추천한다.

### 명탐정 툰툰이

사진

유저가 업로드한 파일의 그림체를 분석하여 학습시킨 데이터를 뽑아내고 유사도가 높은 웹툰을 찾아준다.

### ToonBTI

사진

다양한 질문을 통해 유저의 성향을 파악한 뒤, 그것을 기준으로 다양한 웹툰을 추천해준다.

### 태그 찜 추가 및 삭제

사진

웹툰마다 존재하는 태그들 중 좋아하는 태그를 찜하여 유저의 취향기반 알고리즘에 사용한다.

프로필 페이지에서 찜 삭제와 검색을 통해 찜 추가도 가능하다. 

### 웹툰 상세 정보

사진

웹툰의 작가와 장르 및 줄거리와 같은 기본정보와 태그와 별점, 해당 웹툰을 선호하는 유저들의 정보를 포함한 다양한 분석 그래프도 함께 제공한다.

또한 웹툰 보러가기를 통해 해당 웹툰으로 직접 이동이 가능하다.

## 개발 환경

### 주요 기술 스택

**FrontEnd**

- React
- Redux-toolkit
- mui
- styled-components

**BackEnd**

- Django
- Tensorflow
- MySQL
- beautifulsoup
- JWT

**배포**

- AWS-RDS
- Ubuntu
- Jenkins
- Nginx

## 서버 아키텍처

![아키텍처](/uploads/15c59549c506dd5cc26ed55e83fdd8d6/아키텍처.png)

## 프로젝트 명 : 웹투나

## 팀 소개

### 역할

<<<<<<< HEAD
- 김민성 : BE
- 김영준 : FE / 팀장
- 김우석 : BE / Data 추출 및 분석
- 배윤호 : FE / 팀원 1일 1커밋
- 이동근 : FE
- 이홍주 : BE / 배포
=======
김영준 : FrontEnd, 팀장, UI/UX
김민성 : BackEnd, DataBase 관리
김우석 : BackEnd, ML, 발표
배윤호 : FrontEnd, 비즈니스 로직 설계, 기록물 관리
이동근 : FrontEnd, 컴포넌트 설계, 일정 관리
이홍주 : BackEnd, 배포, 디자인

================================================================ =============================절취선==============================

================================================================

# 위키에 넣을 내용 (추후 작성O)

- 시연 시나리오 (모든 기능)

여기 산출물 구역인가?

[웹툰원정대ERD (erdcloud.com)](https://www.erdcloud.com/d/Sd7QG6pyrNQ8bEYFN)

[와이어프레임.pptx - Google Slides](https://docs.google.com/presentation/d/1lls6BrnZksCDGVXeZn-ehaxjNcrOqQno/edit#slide=id.g150220aeff0_3_214)

[Webtuna – Figma](https://www.figma.com/file/a9LicgltWtTQe5dRMRP05N/Webtuna?node-id=0%3A1)

## 시연 시나리오

### 회원가입 (아직 하는 중)

### 로그인
![로그인](/uploads/9f123931645a75317bfdfb7099f0fa97/로그인.gif)

### 로그아웃
![로그아웃](/uploads/11aa282ad4667222a4d495fa0b450951/로그아웃.gif)

### 정보 수정
![정보수정](/uploads/ace3fa553deeec024c55af26824f38ad/정보수정.gif)

### 오늘의 운세 (아직 하는 중)

### 메인 추천 페이지
![메인추천페이지](/uploads/cd92f7f6fa8c8b13b84d4db1c1c3c21c/메인추천페이지.gif)

### 검색 기능
![검색](/uploads/58cd4eaa25919e09c4e02ea45a0010ff/검색.gif)

### 필터 검색
![필터](/uploads/86786cce9c13d5becae8b5fbb8a48169/필터.gif)

### 웹툰 디테일 페이지
![디테일페이지](/uploads/f5e1d255c898d184881958d88fc6835a/디테일페이지.gif)

### 프로필 페이지
![프로필페이지](/uploads/0adbee5e1f7f1518acdcd902eeafc7bd/프로필페이지.gif)

### 추천 페이지 (아직 하는 중)

### 명탐정 툰툰 페이지
![명탐정툰툰](/uploads/21fab027ed69add64788fdef42a72ffd/명탐정툰툰.gif)

### ToonBTI 페이지
![toonbti](/uploads/9e62b1894a139d584bd7a60bccd09741/toonbti.gif)

## 서비스 설계

### 1. 와이어 프레임 [🔗](https://docs.google.com/presentation/d/1lls6BrnZksCDGVXeZn-ehaxjNcrOqQno/edit#slide=id.g150220aeff0_3_214)

![와이어프레임](/uploads/8142c0222ae61d5aee881db1abbeb845/와이어프레임.png)

### 2. Figma [🔗](https://www.figma.com/file/a9LicgltWtTQe5dRMRP05N/Webtuna?node-id=0%3A1)

![figma](/uploads/55caedd4178336aad5c0a0fadb6b0afe/figma.png)

### 3. ERD

![erd](/uploads/75ae91e1db0837ecbc0f4bdd9571810a/erd.png)

## 협업

### 1. Git

- 노션에 Git 컨벤션을 설정하였습니다.
- 각자 맡은 기능에 맞게 `front`, `back` 에서 브랜치를 생성하고 기능 구현을 완료하면  다시`front`, `back` 브랜치로 머지 했습니다. 일정 주기로 `develop` 브랜치로 프론트와 백을 통합하였습니다.
- 현재 feat-b/deploy에 front, back 브랜치를 머지하고 Jenkins로 자동 빌드 및 배포중입니다.
- 충돌 상황을 최소화하기 위해 깃 푸시를 하기 전 공유를 하였습니다.
    
    
    영준우석이네 리드미처럼 낼 오전에 다 통합하고 브랜치 그래프 촤라락 하는 gif 있으면 좋을듯
    

### 2. JIRA

- 팀원들과의 목표 공유를 위하여, 협업 툴로 JIRA를 사용하였습니다.
- FE, BE 등의 라벨을 추가하여, 각 파트의 할 일을 한눈에 볼 수 있도록 했습니다.
- 매주 월요일 마다 백로그에 이슈들을 생성한 후 스프린트를 시작하였습니다.

![jira](/uploads/92c7d754af10ab4fa1708c6c32fc39f5/jira.png)

## 3. **Notion** [📎](https://www.notion.so/A403-4a1acd3d850f44f0aed8765d6056cfd2)

- 팀원들 간에 공유해야할 자료들은 노션에 백업하여 불필요한 소통을 줄였습니다.
- 프로젝트 종료 후에도 리마인드하기 쉽도록, 사용한 기술들이나 개발 과정에서 고민했던 부분들 또한 백업하였습니다.

![notion](/uploads/ccbc08dfad76293b736eea00a4bd66a6/notion.png)

![notion2](/uploads/c9aa6ce9a57fc8d98169dfb12336e089/notion2.png)

## 4. 소감

- 김영준
- 김민성
- 김우석
- 배윤호
- 이동근
- 이홍주
>>>>>>> 9dfc6cf (fix:readme)
