# DesignPattern
## GoF의 디자인 패턴

### 생성 패턴(Creational Patterns)
 1. Abstract Factory
 - 구체적인 클래스를 지정하지 않고, **관련성을 갖는 객체들의 집합**을 생성하거나 **서로 독립적인 객체들의 집합**을 생성할 수 있는 인터페이스를 제공하는 패턴
   - (부모, child?)
   
 2. Builder
 - 복합 객체의 **생성 과정**과 **표현 방법**을 분리하여 동일한 생성 절차에서 서로 다른 표현 결과를 만들 수 있게 하는 패턴
   - (오버로딩?)
   
 3. Factory Method
 - 객체를 생성하는 인터페이스는 미리 정의하되, 인스턴스를 만들 클래스의 결정은 서브클래스 쪽에서 내리는 패턴, **클래스의 인스턴스를 만드는 시점을 서브클래스로 내림**
   - (부모 인스턴스는 없음?)

 4. Prototype
 - 생성할 객체의 종류를 명세하는데 원형이 되는 예시물을 이용하고, 그 **원형을 복사**함으로써 새로운 객체를 생성하는 패턴
   - (팩토리 메서드와 차이가?)
 
 5. Singleton
 - 어떤 클래스의 **인스턴스는 오직 하나**임을 보장, 이 인스턴스에 접근할 수 있는 **전역적인 접촉점을 제공**하는 패턴
   - (설정 같은 것들)
 
### 구조 패턴(Structural Patterns)
 6. Adpater
 - 클래스의 인터페이스를 사용자가 기대하는 다른 인터페이스로 변환하는 패턴. **호환성이 없는 인터페이스들을 동작할 수 있게** 처리
   - (C++ Wrapping?)
   
 7. Bridge
 - 구현부에서 추상층을 분리하여 각자 독립적으로 변형할 수 있게 하는 패턴
   - (어댑터의 반대인가?)
 
 8. Composite
 - 객체들의 관계를 트리 구조로 구성하여 부분-전체 계층을 표현하는 패턴. 사용자가 단일 객체와 복합 객체 모두 동일하게 다루도록 함
   - (????)
   
 9. Decorator
 - 주어진 상황 및 용도에 따라 어떤 객체에 책임을 덧붙이는 패턴. 기능 확장이 필요할 때 서브클래싱 대신 쓸 수 있는 *유연한* 대안
   - (기능 확장이라..)
   
 10. Facade(퍼사드)
 - 서브시스템에 있는 인터페이스 집합에 대해서 하나의 통합된 인터페이스를 제공하는 패턴. 서브시스템을 좀 더 사용하기 편하게 만드는 상위 수준의 인터페이스
   - ()
   
 11. Flyweight
 - 크기가 작은 객체가 여러 개 있을 때, 공유를 통해 이들을 효율적으로 지원하는 패턴
   - ()
 
 12. Proxy
 - 어떤 다른 객체로 접근하는 것을 통제하기 위해서 그 객체의 surrogate(대리자) 또는 placeholder(자리 채움자)를 제공하는 패턴
   - (내가 아는 프록시랑 다르네?ㅎㅎ)
 
### 행동 패턴(Behavioral Patterns)
 13. Chain of Responsibility
 - 요청을 처리할 수 있는 기회를 하나 이상의 객체에게 부여하여 요청을 보내는 객체와 그 요청을 받는 객체 사이의 결합을 피하는 패턴. 요청을 받을 수 있는 객체를 연쇄적으로 묶고, 실제 요청을 처리할 객체를 만날 때까지 객체 고리를 따라서 요청을 전달
   - (스케쥴링인가? 핸들러?)
   
 14. Command
 - 요청을 객체의 형태로 갭슐화하여 서로 요청이 다른 사용자의 매개변수화, 요청 저장 또는 로깅, 그리고 연산의 취소를 지원하게 만드는 패턴
   - ()
   
 15. Interpreter
 - 주어진 언어에 대해, 그 언어의 문법을 위한 표현 수단을 정의하고, 그 표현 수단을 사용하여 해당 언어로 작성된 문장을 해석하는 해석기를 정의하는 패턴
   - (헤더?도 여기에 해당할까?)
 
 16. Iterator
 - 내부 표현부를 노출하지 않고 어떤 객체 집합에 속한 원소들을 순차적으로 접근할 수 있도록 하는 패턴
   - (이건 그냥 반복문, set 등에서 사용되는 것인듯)
   
 17. Mediator
 18. Memento
 19. Observer
 20. State
 21. Strategy
 22. Templete Method
 23. Visitor
