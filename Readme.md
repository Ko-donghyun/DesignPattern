## Introduce
 - 패턴을 만들고, 반복되는 작업에서 이용 (건축)
 - 소프트웨어 분야에도 적용

## Why?
 - 이미 성공했던 사례를 재사용하는 것이 좋다
 - 잘 구조화된 시스템과 패턴에 대한 지식을 바탕으로 더욱 유연하고 재사용성이 높은 프로젝트를 수행가능
 - 관계자들간의 커뮤니케이션에 활용가능

## Software Pattern
 - 요소
    - 문제 상황(Context)
    - 목표(Goal)
       - 조건(Constraints)
    - 해답(Solution)

## Patterns
 - 생성(Creational) : 생성에 관한 의무를 다른 클래스나 객체에 부여(operation/use 하는 클래스나 객체와 분리)
   - Factory Method (Class)
   - Abstract Factory (Object)
   - Builder (Object)
   - Prototype (Object)
   - Sigleton (Object)
 - 구조(Structural) : 임의의 클래스나 객체로 더 큰 객체를 만들거나, 객체들 간에 구조를 나눌 수 있도록 (상속 등을 활용)
   - Adapter (Class, Object)
   - Bridge (Object)
   - Composite (Object)
   - Decorator (Object)
   - Facade (Object)
   - Flyweight (Object)
   - Proxy (Object)
 - 행위(Behavioral) : 어떤 클래스가 어떤 responsibilty를 맡아야 하는가
   - Interpreter (Class)
   - Templete (Class)
   - CoR (Object)
   - Command (Object)
   - Iterator (Object)
   - Mediator (Object)
   - Memento (Object)
   - Observer (Object)
   - State (Object)
   - Strategy (Object)
   - Visitor (Object)
  
 - 클래스(Class) : Class들의 관계만을 이용해서 정의(상위 클래스, 하위 클래스)
 - 객체(Object) : 객체들간의 관계(Composition 관계 등), Deligation 수행 


### Example
 - [Iterator Pattern](https://www.google.com/url?sa=i&url=https%3A%2F%2Fjacekrojek.github.io%2FJacekRojek%2F2016%2Fc-iterator-design-pattern%2F&psig=AOvVaw05KxBeBY_NnVkeOUY8L94m&ust=1613728525428000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKjPrK6V8-4CFQAAAAAdAAAAABAh)
   - Context : collection of objects
   - Problem : 객체를 하나하나 볼 수 있어야 함. 단, collection의 implementation 자체는 노출되면 안됨
   - Solution : Encapsulate the iteration into a seperate class
   - 즉, 집합을 나타내는 클래스와 객체 내의 원소를 조회할 수 있는 클래스를 상속하여, 변종 클래스들이 일어나더라도 특정 인터페이스를 유지할 수 있도록 처리


## Key Feature
 - Intent : 의도, 목적
 - Problem : 해결하고자 하는 문제상황
 - Solution : 문제에 대한 해결책, 역할을 가져야 하는지
 - Participants and collaborators : 장단점, 이해는 쉬워지나 성능은 떨어짐
 - Implementation : 실제 구현 예시
 - Generic structure : 패턴의 일반적인 구조

## Levels of Pattern
 - Architectural Pattern : 소프트웨어의 전체적인 조직과 스키마를 정하는 작업에 쓰이는 패턴, 시스템 전체에 대한 구조
 - Design Pattern
    - 비교적 작은 규모의 서브시스템에서의 설계 및 그 시스템 간의 관계를 정하는데 쓰이는 패턴, 전체 시스템에 영향이 없음
    - 주로 컴포넌트 내부의 설계에 사용
 - Coding Pattern (programming idiom) : 특정 프로그래밍 언어에 특화된 레벨의 패턴(low-level)

### Example
 - [MVC Pattern]()
   - Architectural Pattern의 한 종류
   - Model, View, Controller라는 모듈로 나눌 수 있음
   - 각 모듈마다의 responsibility가 정해져 있음
   - 상호간에는 서로 직접 볼 수 없도록
 - [Observer]()
   - Design Pattern의 한 종류
   - MVC 패턴을 만족시키기 위한 디자인 패턴
   - Subject Interface <--> Observer
   - Observer 수준에서만 Model(Subject)애 접근할 수 있도록
 - [Counter Pointer]()
   - Coding idiom
   - C++ 만의 특정 메모리 관리 방식
   - 일반적인 포인터만으로 데이터를 공유하려고 하면 관리가 힘들어짐.

## Reference

### Head First Design Patterns
### Agile Software Development
### GoF Design Patterns
