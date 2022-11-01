# Design Pattern

<br />

## Singleton pattern
* Singleton 패턴은 어떠한 클래스(객체)가 유일하게 1개만 존재할 때 사용
* 실물 세계 = 프린터, 실제 프로그래밍 = TCP Socket 통신에서 서버와 연결된 connect 객체

## Adapter pattern
* SOLID - OCP 원칙
* 호환성이 없는 기존 클래스의 인터페이스를 변환하여 재사용 할 수 있게 함

## Proxy pattern
* Proxy 패턴은 Proxy Class를 통해 대신해서 전달하는 형태로 설계되어 있음
* 실제 Client는 Proxy로부터 결과를 전달받고 Cache의 기능으로도 활용되고 있음.
* SOLID - OCP 원칙 & DIP 원칙

## Decorator pattern
* 기존 클래스는 유지하지만 이후 필요한 형태로 꾸밀 때 사용함
* 확장이 필요한 경우 상속의 대안으로 활요되기도 한다
* SOLID - OCP 원칙 & DIP 원칙

## Observer pattern
* 변화가 일어날 때 미리 등록된 다른 클래스에 통보해주는 패턴을 구현한 것.
* event listener에서 해당 패턴을 주로 사용함.

## Facade pattern
* 여러개의 객체와 실제 서브 객체 사이의 복잡한 의존관계가 형성될 때 중간에 facade 객체를 두고
facade 객체에서 제공하는 interface만을 활용하여 기능을 사용하는 방식이다.
  * 즉, facade는 자신이 가지고 있는 각 클래스의 기능을 명확히 인지하고 있어야한다.