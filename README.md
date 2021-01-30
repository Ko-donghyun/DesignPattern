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
 7. Bridge
 8. Composite
 9. Decorator
 10. Facade
 11. Flyweight
 12. Proxy
 
### 행동 패턴(Behavioral Patterns)
 13. Chain of Responsibility
 14. Command
 15. Interpreter
 16. Iterator
 17. Mediator
 18. Memento
 19. Observer
 20. State
 21. Strategy
 22. Templete Method
 23. Visitor
