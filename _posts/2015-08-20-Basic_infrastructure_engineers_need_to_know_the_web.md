---
layout: post
title: 웹 엔지니어가 알아야 할 인프라의 기본
author: 바바 토시아키,김병국(역)
tags: book
---

## 1
책이 눈에 들어와서 회사 객체에 문의해서 getBooks으로 획득했다. 즉, 본인이 돈을 내고 구매한 책이 아니기 떄문에 굉장히 객관적으로 적을 수 있다.

## 2
찬물과 더운물을 오가는 책이다. 앞 부분은 굉장히 평이하고 쉬운 내용이라 슝슝 책장을 넘길 수 있다. 반면에 뒷장으로 가면 약간은 고급스러운 이야기를 너무 쉽게 이야기하는 걸 경험하게 된다.

## 3
시스템 감시, 보틀넥(번역에 신경을 좀 써줬으면 좋았을텐데...)을 찾는 문제, 원포인트 튜닝에 대한 내용은 한번 쓱 읽어볼만 하다. 

## 4 
회사에 책을 꼭 구매해 달라고 요청하자. 절대로 본인 카드를 꺼내서 구매하는 일이 없도록 주의해야 한다. 그래도 뒷부분은 꼭 읽어보길 권한다. 생각보다 내용이 좋다.


-----

쉽게 상상할 수 없기 때문에 개발자는 항상 고통받고 살고 있는 것이다. 쉽게 상상할 수 있다면 더 심한 고통을 주려나?!
> 인프라는 문자 그대로 시스템을 기반으로 하며, 시스템의 그릇을 결정하는 중요한 요소이다. [...] 향후의 확장을 염두에 두고 구성할 필요가 있다. [...] 나중에 수정하는 것이 얼마나 어려울지 쉽게 상상할 수 있을 것이다.

조달청에 아마존 클라우드를 조달하는 순간까지...
> 또한, 조달 단계에 소요되는 시간은 필요한 요소에 따라 다르며, 최소 몇 분 정도인 경우도 있지만 몇 개월이 걸리는 경우도 있다.

많지 않은게 아니라 할 줄 아는 사람이 없는 것. 제대로 걸리면...
> 실제로는 인프라에 대한 사용자의 기능적 요건이 그렇게 많지는 않다. 이것은 필자의 경험으로 보아 인프라의 요건을 구체화할 수 있는 사람이 많지 않기 때문인 것같다. [...] '1년간 10분 이상 서비스를 정지시키지 않는다.' [...] 이때 비기능적 요건을 구현하기 위해 필요한 기능이 요건이 된다. 실제로 조달 단계에 들어설 때는 비 기능적 요건도 기능적 요건이 되어야만 한다.

~~(망할)~~ 예산의 벽은 무섭다.
> 비 기능적 요건을 얼마나 빠짐없이 구체화할 수 있는가, 예산과 기간 및 작업 과정의 제약 속에서 얼만큼 구현할 것인가 하는 것이 인프라 엔지니어의 능력을 뽐낼 수 있는 부분이다.

부하는 피하는 것이다. 운영체제 시간에 배우지 않았는가?! '교착상태 회피'
> 가동률을 높이기 위해서는 요소 각각의 기동률을 높이고, 요소를 조합해 전체의 가동률을 높이며, 적절한 프로비저닝으로 부하문제를 피하는 것

하나면 하나지 둘이 아니니까!
> N+1이 N이 된 다음 N+1이 될 때까지가 '장애 대응'이라는 것을 꼭 기억해 두자.

그렇게 함부로 삭제하면.... 이미지는 만들어두자!
> 클라우드 기반이라면 수리에 연연하지 말고 제거하는 것이 좋다. 다시 고장이 발생하면 또다시 만들면 된다.

훗... '대기행렬 이론'으로 병렬 처리 할 수 있는 방법이라니... 혹시나 이런 상황이 들이닥치면 '카드'를 꺼내자!
> 병렬 처리의 어림 계산에서 정밀도를 높이는 방법으로 '대기행렬 이론'을 사용할 수도 있다.

시스템 감시의 목적은 감시가 목적 아닌가?!
> 정상 상태를 유지하는 것이 시스템 감시의 목적













