# Flutter Solid Principles & Design Pattern

## DesignPatterns - BackGround
### What is DesignPattern?
1. 디자인 패턴은 테스트에 용이하고 재사용이 가능한 솔루션.
2. Software Engineering 문제를 해결하기 위해 사용되는 `Solution Template`
3. 유연하고 적응가능함. (어디서든 필요할 때마다 사용 가능)
4. 시간을 절약하기 위한 최적의 방식

### Why Use Them?
1. (다양한) 이전 프로젝트에서 셀 수 없이 많이 사용되어왔음 
2. 개발자들에게는 `meta-language`같은 존재.
  - 예를들어 `SingleTon Pattern`에 대해 여러 개발자가 알고있다면, 이 패턴이 어떻게 사용되고 적용되는지에 대해 공통적인 이해가 생김.
4. 서로 다른 언어를 사용해도 패턴이 달라도 이해 가능함. 

### Summary 
> 디자인패턴은 재사용 가능한 경험으로, 실수와 경험하지 못한 결정에 도움을 줌



## DesignPatterns - Introduction 
**7 most crucial design patterns**
### Creational  
1. Singleton Pattern
2. Factory Method Pattern
3. Builder Pattern 
> Creational Design Pattern은 객체 생성을 위해 사용된다. 이 패턴들은 객체를 유연하고 적응력이 뛰어나는 방법이며, 재사용성이 뛰어나다.

### Structural 
1. Adapter Pattern
> Structural Design Pattern은 엔티티간 관계를 효율적이고 사용성이 높게 결합하는 방법으로, 복잡한 구조적 계층의 객체를 생성하는데 가장 효율적으로 사용된다. 

### Behavioral 
1. Strategy Pattern 
2. Observer Pattern 
3. State Pattern
> Behavior Design Pattern은 객체간의 상호관계와 커뮤니테이션을 향상하기 위해 사용된다. 여기 패턴들은 객체간 메시지 교환 시에 결합도를 낮추는데 도움을 준다. 



## Software Architecture
### 복잡한 소트프웨어 시스템들은 아래와 같은 문제들로 고통을 받고 있다. 
1. 요구사항 변경으로 인한 개발 기간의 연장
2. 여러 개발자들의 협업의 힘듦
3. 코드와 문서의 부족함

위의 문제들은 **유지보수성**의 하락과 새로운 기능 추가에대한 **유연성**에 대해 문제가 쌓이게 된다. 
결국 잘 적립되지 않은 디자인 시스템은 유지보수의 어려움과 적용하기 힘든 소프트웨어가 된다. 

안전하고 튼튼한 고층 빌딩을 건설하기 위해서는 모든 작업이 포함된 높은 수준의 설계도면이 사용된다. 
소프트웨어 설계에서도 마찬가지로 Software Architecture가 설계도면 역할을 한다.

### 일반적인 개발 사이클 
[images](imgs/img.png)

소프트웨어 개발에서는 최종 결과물은 소스코드다. 좋은 소스코드를 만들기 위해서는 아키텍쳐가 중요한 역할을 하며, Design Pattern들은 이러한 측면에서 크게 기여한다.


