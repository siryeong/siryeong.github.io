---
title: 아이템 4. 인스턴스화를 막고싶으면 private 생성자를 사용하라
date: 2023-01-31 12:03 +0900
categories:
  - Study
  - Effective Java
  - 2 Creating and Destroying Objects
tags:
  - Effective Java
  - 이펙티브 자바
---
## 아이템 4. 인스턴스화를 막고싶으면 private 생성자를 사용하라

> static factory method, static field만 있고 싶을때 사용한다.

외부에서 인스턴스를 만들 수 없고, 상속도 막을 수 있다.
