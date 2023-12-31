---
title: 아이템 12. toString을 항상 재정의하라
date: 2023-02-01 12:11 +0900
categories:
  - Study
  - Effective Java
  - 3 Methods Common to All Objects
tags:
  - Effective Java
  - 이펙티브 자바
---
## 아이템 12. toString을 항상 재정의하라

> toString은 간결하면서 사람이 읽기 쉬운 형태의 유익한 정보를 반환해야 한다.

toString 규약은 *모든 하위 클래스에서 이 메서드를 재정의하라*고 한다.

toString은 엄청 중요하다고 할순 없는데 잘 만들면 매우 유용하다.

<br>

### 좋은 toString 만들기

- 그 객체가 가진 주요 정보를 모두 반환하는게 좋다.
- toString이 어떤 정보를 제공하려고 하는지, 의도를 명확히 밝혀야 한다.
- 반환 값에 대한 정보를 얻을 수 있는 api를 제공하자.
- AutoValue는 toString도 만들어준다!

***적어도 자동 생성해서 씁시다.***

