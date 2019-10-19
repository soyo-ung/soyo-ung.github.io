---
layout : post
title: React Native (1) 시작하기
categories : [React Native]

---

A. 모바일 개발을 처음 시작한다면 - 에게 가장 쉬운 방법은 Expo CLI 를 이용하는 것이다.  
> Expo 서비스를 이용하여 앱을 빌딩, 배포할 수 있다.  "managed"와  "bare" 워크플로우가 있는데, "managed" 에서는 오직 자바스크립트만 쓸 수  있고 Expo SDK를 통해서만 기기에 접근할 수 있다. 이 경우, xcode나 안드로이드 스튜디오는 사용하지 않는다. "bare" 워크플로우를 이용하면, Expo SDK와 React  Native와 함께 개발을 더 빨리 할 수 있고, iOS와 안드로이드 프로젝트를 완전히 통제할 수 있다.

> Expo SDK 는 자바스크립트로 다양한 디바이스 시스템에 접근할 수 있게 네이티브로 쓰여진 라이브러리들 세트이다. 플랫폼 간의 차이를 가능한 한 보완해주기 위해 디자인되었다.

B. 모바일 개발에 이미 익숙하다면 - React Native CLI  를 사용하고 싶을 것이다. 이것을 사용하려면 Xcode나 안드로이드 스튜디오가 필요하다.


A.
1.Expo CLI 설치

    npm install  -g expo-cli
 


2.새 프로젝트 생성

    expo init AwesomeProject
    cd AwesomeProject
    npm start #또는 expo start
    

3.Expo clien 앱을 모바일 기기에 설치한다. 모바일 앱과 개발에 사용하는 컴퓨터가 같은 와이파이를 공유하고 있어야 한다.
