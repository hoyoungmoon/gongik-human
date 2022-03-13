<!-- <div align='center'>
  <h1>공익인간</h1>
  <p>사회복무요원을 위한 종합 관리 어플리케이션</P>
</div> -->

<h1 align="center">
  <img alt="cgapp logo" src="./images/playstore.png" width="220px"/><br/>
  공익인간
</h1>

<p align="center">사회복무요원들을 위한 월급, 휴가, 복무지 관리 어플리케이션</p>
<p align="center">
  사용한 휴가와 진급에 따라 매달 월급을 계산하고 복무지에 대한 리뷰와 질문을 자유롭게 할 수 있는 커뮤니티 개발
</p>
<p></p>


## 🚀 Downloads

[![Medium Badge](http://img.shields.io/badge/android-download-12100E?style=for-the-badge&logo=android&link=https://play.google.com/store/apps/details?id=com.project.realproject&hl=ko&gl=US)](https://play.google.com/store/apps/details?id=com.project.realproject&hl=ko&gl=US)
&nbsp;
[![Medium Badge](http://img.shields.io/badge/iOS-download-12100E?style=for-the-badge&logo=apple&link=https://apps.apple.com/kr/app/공익인간/id1551639457)](https://apps.apple.com/kr/app/공익인간/id1551639457)

`2022.02 기준`
- 안드로이드 - MAU 약 **1.6만** / DAU 약 **3.7천**
- iOS - 누적 판매량 약 **1.5만**

## 🔭 Introduction

<span>
  <img src="https://user-images.githubusercontent.com/53747019/156013657-93efd280-989d-4a23-b3b0-e32023883b16.gif" width="200" />
  &nbsp;  &nbsp;
  <img src="https://user-images.githubusercontent.com/53747019/156014627-433a7935-6132-44ce-b5fd-f255c9ca9703.gif" width="200" />
</span>

### 프로젝트 소개

- `개발 동기` : 사회복무요원 특성상 여러 종류의 휴가를 사용할 수 있고 2020년부터 매년 개정된 월급으로 인해 매달 월급이 조금씩 달라집니다.
  내가 갈 복무지에 대한 정보가 부족하여 물어볼 곳 또한 마땅치 않습니다. 이를 해결하기 위해 사용한 휴가와 계급에 따라 월급을 매달 계산해주고, 공공 api를 이용하여 복무지에 대한 리뷰와 질문을 할 수 있도록 커뮤니티를 만드는 프로젝트를 기획하고 개발하였습니다.
  
- `기능 소개`
  - 휴가 관리 및 월급 계산
  - 복무지 리뷰
  - 커뮤니티

### Tech Stack

- React Native
- Node.js, Sequelize, MySQL
- AWS EC2, RDS, S3, Docker

### Architecture
<img width="700" alt="스크린샷 2022-03-14 오전 12 11 43" src="https://user-images.githubusercontent.com/53747019/158066320-43458303-0353-419d-938b-4c0dc2870872.png">

### CI/CD

<img width="700" alt="스크린샷 2022-03-14 오전 4 21 32" src="https://user-images.githubusercontent.com/53747019/158075814-f7b5e801-8595-440d-8f30-20041feb1c1e.png">

### ERD
- TODO: png 추가

## 🔖 Develop Story

- [디자인 시스템 및 다크모드 추가](https://hoyoungmoon.github.io/javascript/react-native/side-project/gongikHumanV2-refactor-before-upgrade/) 
- [회원가입 및 로그인 유지](https://hoyoungmoon.github.io/javascript/react-native/side-project/gongikHumanV2-add-login/)
- [브랜치 전략 및 배포 자동화 구현](https://hoyoungmoon.github.io/javascript/react-native/side-project/gongikHumanV2-set-automatic-deploy/)
