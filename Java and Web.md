## 1. Java의 특징?  
- 자바가상머신(JVM)만 설치하면 컴퓨터의 OS에 상관 없이 작동함.  
- 기본 자료형을 제외한 모든 요소들이 객체로 표현  
- 객체 지향 특징인 캡슐화, 상속, 다형성이 잘 적용.  
- Garbage Collector를 통한 자동적인 메모리 관리  
- 멀티 쓰레드 지원  

## 2. 객체지향 프로그래밍  
- 데이터를 객체로 취급하여 프로그램에 반영, 순차적으로 프로그램이 동작하는 C와 달리 객체와 객체의 상호작용을 통해 프로그램이 동작한다.  

### 2-1. 객체지향 언어 특징  
- 추상화 : 객체에서 공통된 속성과 행위를 추출하는 것을 추상화(Abstraction)라고 한다.
- 캡슐화 : 프로그램의 세부 구현을 외부로 드러나지 않도록 특정 모듈로 감추는 것이다.
- 상속 : 기존의 클래스를 재사용하여 새로운 클래스를 작성. 보다 적은 코드로 새로운 클래스를 작성할 수 있고 코드를 공통적으로 관리할 수 있기 때문에 코드의 추가 및 변경이 매우 용이하다.  
- 다형성 : 하나의 객체가 여러개의 자료형 타입을 가질 수 있는 것. (https://m.blog.naver.com/PostView.nhn?blogId=heartflow89&logNo=220979244668&proxyReferer=https:%2F%2Fwww.google.com%2F)  

## 3. Overloading Vs. Overriding  
- Overloading : 같은 이름의 메소드를 매개변수 타입을 다르게 하거나, 개수를 다르게 해 여러개 정의.  
- OVerriding : 상위 클래스의 메소드를 하위 클래스에서 재정의.  

## 4. 객체, 인스턴스, 클래스  
- 클래스 : 객체를 만들어 내기 위한 설계도 혹은 틀
- 객체 : 일반적으로 설계도인 클래스가 구체적인 실체인 인스턴스가 되었을 때 객체라고 부른다.  
- 인스턴스 : new 키워드를 이용해 클래스 변수에 메모리를 할당.  

## 5. Interface Vs. Abstact  
- 공통점 : new 연산자로 객체 생성 불가능. 사용하기 위해서는 하위 클래스에서 확장/구현 해야한다.  
- 차이점 : 추상 클래스는 메소드를 정의하고 구현할 수 있지만, 인터페이스는 선언만 가능. Interface는 다중상속이 가능하다.  

## 6. Garbage Collection  
- 시스템에서 더 이상 사용하지 않는 메모리를 찾아 사용 가능한 자원으로 회수하는 것. 가비지 컬렉션을 수행하는 부분을 가비지 컬렉터라고 한다.  

## 7. Primitive Type, Reference Type  
- Primitive Type : char, int, double, boolean 등  
- Reference Type : class, interface  
- primitive type을 객체로 다루기 위해 사용하는 Class를 Wrapper Class라고 한다.  
- Boxing : Primitive type -> Wrapper Class  
- UnBoxing : Wrapper Class -> Primitive Type  

## 8. Equals과 ==의 차이점  
- equals 메소드는 비교하고자 하는 대상의 Value를 비교하지만, == 연산자는 비교하고자 하는 대상의 Reference를 비교한다.  

## 9. Generics  
- 제네릭은 클래스, 메소드에서 사용할 데이터 타입을 인스턴스를 생성할 때나 메소드를 호출할 때 정하는 기법.  
- 제네릭을 사용하면 클래스 내부에서 사용하는 데이터의 타입을 지정할 수 있고, 타입을 잘못 사용하여 발생하는 에러를 최소화 할 수 있다.

![image](https://user-images.githubusercontent.com/32921115/111036023-7b94ac80-8460-11eb-822a-0a7065962a04.png)

## 10. Static  
- 객체를 생성하지 않고도 변수나 함수를 사용할 수 있다. 
