# UIA & STO Online Conference

[![Watch the video](assets/virtual_seoul2.gif)](http://virtualseoul.or.kr/)

## Table of Content

- [Role & Responsibility](#Role--Responsibility)
- [Work Flow](#Application-Work-Flow)
- [Demo](#Demo)
- [Project Description](#Project-Description)
- [Main Features](#Main-features)
- [Achievement](#Achievement)
- [Note](#note)

# Role & Responsibility

저의 업무는 프런트 엔드와 백 엔드 개발하는 것이었습니다. 고객의 요구사항과 최종 사용자의 편리함을 고려하며 필요한 기능을 완벽하게 구현하는 것에 집중했으며 그 결과 일정보다 여유있게 개발을 마무리할 수 있었습니다. 그 밖에도 어플리케이션 테스트 및 배포, 디버깅 그리고 유지 및 관리를 하였습니다. 이러한 과정에서 기획자, 디자이너 그리고 개발자들과의 협업 방식을 배울 수 있었으며 그 배움을 토대로 프로젝트를 성공적으로 이끌어 갈 수 있었습니다.

### 본 프로젝트에서의 저의 업무 내용입니다:

- Front-end 시스템 디자인 
- Expressjs RESTful API 구현
- Mysql Query 구현  
- User Authentication
- React Component 생성 (tables, banners, poppers, Modals, buttons 등)
- 푸쉬 알람, VOD 그리고 라이브 스트리밍 스케줄링
- 브라우저 호환 (Chrome, Safari, Firefox, MS Edge, IE11)
- Gitlab branch, PR 관리 
- 한국어 영어 번역
- 외국인 유저 기술 지원 & 상담
- 파일 업로드, 다운로드 기능 구현 
- 반응형 디자인 (모바일 기기, 테블릿 지원)
- 데이터 통계

[Jira](https://www.atlassian.com/software/jira)에서 저에게 할당된 이슈의 수입니다. 

![jira](assets/jira3.jpg)

#### 총 325개의 이슈 중에서 146개를 완료했습니다.

# Application Work Flow

#### 이 앱은 Reactjs, Redux, Expressjs MysqlDB, Babylonjs 그리고 AWS를 사용해 만들어졌습니다.


![diagram](assets/diagram.png)

# Demo

### News

#### 이 플랫폼은 아리랑뉴스를 통해 전세계에 소개되었습니다. 

[Link to the news](https://www.youtube.com/watch?v=ksBnRT1f2Ak&t=2s)

[![Watch the video](assets/news.jpg)](https://www.youtube.com/watch?v=ksBnRT1f2Ak&t=2s)

### Website URL

#### [Link to the website](http://virtualseoul.or.kr/)
참고 - 현재는 행사기간이 아닌 관계로 대부분의 기능에 대한 접근이 차단되었습니다.

[![Watch the video](assets/virtual_seoul2.gif)](http://virtualseoul.or.kr/)

### 데모 영상

- [Seoul Map](https://www.youtube.com/watch?v=6EdqKznxncA)
- [LIVE Streaming demo](https://www.youtube.com/watch?v=a9wX4MSkSyg)
- [Video Chat](https://www.youtube.com/watch?v=edzgNn5f5yQ)

# Project Description

이 플랫폼은 [Union of International Associations(UIA)](https://uia.org/) 그리고 [Seoul Tourism Organization(STO)](http://www.sto.or.kr/english/index)의 온라인 컨퍼런스 행사를 위해 만들어졌습니다.

- 개발 기간: 2020.06 ~ 2020.09
- 유지보수 기간: 2020.09 ~ 2021.04
- 행사기간 하루 평균 접속자 수: 3,000 ~ 5,000
- 접속 국가: 26개의 국가
- 브라우저: Chrome, IE, Firefox, Safari, Edge

## Main features

### Video chat

![assets/many_to_many_video_chat.png](assets/video_chat.jpg)

### Stamp Event

![stamp_tour.png](assets/stamp_tour.png)

### 3D Virtual Seoul tour

![virtual_seoul.png](assets/virtual_seoul.png)

### Live And VOD Streaming

![streaming](assets/live_streaming.jpg)

### Seoul Membership Card Event

![membership.png](assets/membership.png)


### 본 플랫폼을 통해 유저는 실제 행사장에 있는 듯한 현장감을 느낄 수 있습니다.


# Achievement

### 이 프로젝트의 성공은 10개 이상의 추가적인 계약을 성사 시켰습니다.

#### 참조 - 본인이 작업했던 온라인 컨퍼런스 행사의 리스트입니다. 
- [KHA Online Conference](https://khc2020.salin.co.kr) ( Korean Hospital Association ) 데모 계정 ID: host01@salin.co.kr PW: 1234
- Asia TEFL Online Conference (Teaching English as a second or foreign language)

### 재사용 가능한 컴포넌트와 API를 만들었습니다.

#### 참조 - [codesandbox]에 제작된 재사용 가능한 라디오 버튼입니다. (https://codesandbox.io/s/radio-3mtce?file=/src/App.jsx).

![reusable-component.gif](assets/reusable_component.gif)

### 이 프로젝트는 본인이 리액트 오픈소스를 제작하게 되는 동기가 되었습니다.

#### [Link To My Crontab library](https://www.npmjs.com/package/reactjs-crontab)
[![demo photo](assets/crontab.png)](https://www.npmjs.com/package/reactjs-crontab)

Crontab (scheduling jobs)은 구현하는 것이 복잡할 뿐만 아니라 테스트하기도 까다로운 기능입니다. 하지만 플랫폼 특성상 이 기능은 매번 필요했습니다. 그 때마다 기능구현을 반복하는 것보다 모듈화해 매번 필요할 때마다 재사용하는 것이 효율적일 것이라 생각했습니다. 그래서 react-crontab 모듈화를 이행했으며, 작업 후 NPM에 open-source형태로 퍼블리싱해 누구나 쉽게 사용할 수 있게 제공했습니다. 현재 주당 평균 300명의 유저가 다운로드 받고 있습니다. 

# 참고 사항
회사의 규정 상 본 프로젝트의 소스코드를 제공할 수 없습니다. 양해 부탁드립니다.
