---
layout: post
title:  "클래스 다이어 그램"
author: 유정민
categories: UML
excerpt: "클래스 다이어 그램이란 무엇일까?"
---
> "UML은 실전에서는 이것만 쓴다." (저자: 로버트 C. 마틴)을 참조한 내용입니다.

# 클래스 다이어 그램이란 무엇일까요?

클래스 다이어그램은 **클래스 내부의 정적인 내용이나 클래스 사이의 관계를 표기**할 때 사용합니다.<br/>
클래스 다이어 그램은 멤버 변수/함수를 표기하며, 클래스가 어떤 것을 상속/참조 하는 지 알려줍니다.<br/>

# 클래스 다이어 그램을 언제 사용할까요?

클래스 다이어그램은 다이어 그램이라는 시각적 효과를 활용해, 직접 소스코드를 통해 보는 것보다<br/>
좀 더 편리하게 개발자가 클래스 간의 의존관계와 클래스의 성질을 파악할 수 있게 합니다.<br/>

좀 더 복잡한 코드 구현으로 가면 클래스 의존 관계를 한 눈에 보여주어, 순환 의존이 발생하는 지점을<br/>
개발자가 쉽게 찾아내고 이 순환 고리를 어떻게 깨는 지 고민하는 데 도움을 주기도 합니다.<br/>

# 사용 예제

- ### 클래스 아이콘
  **<center>[클래스 아이콘의 그림과 설명]</center>**

  ![image](/assets/img/UML/classDiagram1.png)


  **<center>[클래스 아이콘과 코드 비교]</center>**

  ![image](/assets/img/UML/classDiagram2.png)

- ### 참조
  **<center>[참조의 그림과 코드 1]</center>**


  ![image](/assets/img/UML/classDiagram3.png)

  **<center>[참조의 그림과 코드 2]</center>**

  ![image](/assets/img/UML/classDiagram4.png)

- ### 상속
  **<center>[상속의 그림과 설명]</center>**

  ![image](/assets/img/UML/classDiagram5.png)

  **<center>[상속의 그림과 코드]</center>**

  ![image](/assets/img/UML/classDiagram6.png)

- ### 유틸리티/인터페이스
  **<center>[유틸리티 그림과 코드]</center>**

  ![image](/assets/img/UML/classDiagram7.png)

  **<center>[인터페이스의 그림과 코드]</center>**

  ![image](/assets/img/UML/classDiagram8.png)

- ### 합성
  **<center>[합성 클래스 그림]</center>**
  **<center>합성 관계에는 deep-copy를 하라는 의미가 내포 됩니다.</center>**

  ![image](/assets/img/UML/classDiagram9.png)

  **<center>[합성 클래스 코드]</center>**

  ![image](/assets/img/UML/classDiagram10.png)

- ### 다수성
  **<center>[인터페이스의 그림과 코드]</center>**
  **<center>스스로 다수의 객체를 참조할 수도 있습니다.</center>**

  ![image](/assets/img/UML/classDiagram11.png)

- ### 내부클래스
  **<center>[일반 내부 클래스 그림과 코드]</center>**

  ![image](/assets/img/UML/classDiagram12.png)

  **<center>[익명 내부 클래스 그림과 코드]</center>**

  ![image](/assets/img/UML/classDiagram13.png)

- ### 연관 한정사

  **<center>[연관 한정사 그림과 코드]</center>**
  **<center>어떤 종류의 키나 토큰을 이용해 연관을 구현할 경우</center>**
  **<center>예) 로그인 같은 기능을 구현 할 때 연관 한정사를 사용할 수 있습니다.</center>**

  ![image](/assets/img/UML/classDiagram14.png)

# 결론

클래스 다이어 그램은 위의 표기법만 다 알면 사실상 사용하는 데 지장 없습니다.<br/>
UML의 의미를 언제나 기억하고, 이걸 외우기 보다 CookBook 형태로 참고하고<br/>
실제 구현하기 전 설계 과정에서 실습하면서 자연스럽게 익히는 게 좋습니다.<br/>
