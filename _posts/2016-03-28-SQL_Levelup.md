---
layout: post
title: SQL 레벨업
author: 미크 (지은이), 윤인성 (옮긴이)
tags: book
---

> '트랜잭션 매니저'와 '락 매니저'도 굉장히 중요합니다. 하지만 이러한 것들은 '하나의 SQL 구문을 처리하는 때'가 아니라 '여러 SQL 구문을 동시에 실행하는 때'의 성능과 관련있는 매커니즘입니다.

## 1
SQL이 실행되는 내부의 '이야기'를 잘 들려준다. 그리고 PostgreSQL을 기본으로 설명하기 때문에 꽤나 흥미롭게 읽었다.


> 하지만 RDB로써 기능을 제공한다는 목적은 모두 동일합니다. 따라서 모두 관계 모델이라는 수학적인 이론을 바탕으로 합니다.