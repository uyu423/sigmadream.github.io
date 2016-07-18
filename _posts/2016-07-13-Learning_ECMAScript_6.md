---
layout: post
title: ECMAScript 6 길들이기
author: 나라얀 프루스티 (지은이), 이일웅 (옮긴이)
tags: book
---

## 1
[Firebase](https://www.firebase.com/) 스터디를 진행하면서 몇가지 자잘한 기술을 배워야 했다. 해당 기술(React)이 'ES6'기반이라 코드를 C-c/C-p를 붙여넣었기 코드에 대한 이해없이 기능 구현에 집중했다.

## 2
몇가지 이유 떄문에 ES6를 좀 배우고 싶었기 때문에 이 책을 빌려서 읽어보았다. 구매해서 읽은게 아니라 '가격대비 가치'는 잘 모르겠지만, ES6에 관련된 문법을 '정말 핵심적'으로 '알차게' 소개해주고 있어서 2틀 정도만에 다 읽을 수 있었다.

## 3
기존의 자바스크립트 개발자인 경우 ES6 문법을 짧고 굵게 학습하고 싶다면 이 책은 좋은 선택이 될꺼라고 생각한다. 그리고, 코드를 만들어서 사용할게 아니라 기존의 snippet 코드를 붙여서 사용할 '웰.알.못' 개발자 분들에게도 충분히 좋은 책이다.

----

> 스코프(scope)와 콘텍스트(context)의 차이를 명확하게 구분해야 한다. 스코프는 어떤 함수를 호출할 때마다 변수를 접근할 수 있는 범위이고, 콘텍스트는 현재 실행 중인 코드를 소유한 객체의 참조값, 즉 this 값을 말한다. - 옮긴이

> [...] NaN는 자기 자신과도 동등하지 않은 유일무이한 값으로, NaN == Nan, NaN === NaN은 모두 false다.

> 자바스크립트 소스코드는 기본적으로 UTF-16 코드 유닛으로 표현한다. 소스코드의 인코딩 스키마가 UTF-8이면 자바스크립트 엔진이 UTF-8 코드 유닛으로 해석하도록 지시한다. 자바스크립트 문자열은 언제나 UTF-16 코드 포인트로 이루어진다.

> HTML5는 메인 스레드와 병렬로 실행되는, 웹 워커(web worker)라는 실제 스레드를 도입했다. 웹 워커의 실행이 끝나거나 메인 스레드에 알림이 필요할 때 새 이벤트를 그냥 큐에 넣는다.