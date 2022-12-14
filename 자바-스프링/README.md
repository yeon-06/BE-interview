### 자바

- 사용하는 Java 버전
    - Java8에서 추가된 사항과 그 이유
- equals와 hashcode에 대해
- Java의 장점은 무엇인가요?
- java 접근제어자에 대해
- abstract class vs interface
    - 사용 목적 측면에서의 차이점
- 클래스, 메서드, 변수에 final이 붙은 경우
- Collection 구성 요소와 특징
    - 순서 유지해야하는 Map
- java memory 구조
    - (gc 언급해서) gc가 무엇인가
    - gc의 종류
- stream 사용해봤는지
    - 특정 상황에서 어떤식으로 stream 이용할지
    - 중간 연산자 최종 연산자 키워드 섞어서 설명하기
- entity vs dto vs vo
- OOP 5가지 설계 원칙
    - 모든걸 다 지키며 개발하는지
- ArrayList vs LinkedList
    - 데이터를 중간에 추가하는 경우 어떤 것이 더 빠른가
- GC 동작 과정
  - old 영역의 객체는 계속 보관되는가
  - young 영역에서의 gc와 old 영역의 gc 차이
  - old 영역에서 계속 지워지지 않는 객체가 있다면 어떻게 되는가
  - gc 관련 옵션들

<br/>

### 스프링

- bean scope 종류
- MVC 구동 과정 *
    - filter와 interceptor의 차이 *
- AOP란?
- Spring Framework와 Spring Boot 차이
- 스프링 트랜잭션 전파 레벨
- @Transactional 동작 원리 *
    - 롤백이 되는 예외와 롤백이 안되는 예외
    - 어떤 계기로 딥다이브 하게 되었는지
- DI/IoC란?
- 의존성 주입 방법 3가지
- Spring DI/IoC *
    - 어떨 때 사용하나요
    - DI를 사용하는 방법
        - (생성자,세터,필드 주입 답변) 본인은 어떤걸 사용하시는 편인가요
- @Transactional 사용할때 안할때 차이
- bean 등록하는 방법
- filter vs interceptor
    - 프로젝트에서 사용 경험
- 스프링에서 중요한 개념

<br/>

### JPA

- ORM이란?
- JPA와 MyBatis의 차이
- JPA N+1 경험 *
    - N+1 문제를 어떻게 파악하게 되었는지
- (JPA N+1) deleteAll을 @Query로 해결한 이유
    - (in 절과 관련한 답변) in절에서 문제가 발생하지 않을까요?
    - (못 알아들어서) Oracle은 in절에 1000개까지, MySQL에서는 너무 많으면 index 안타서 성능이 느려지는데 어떻게 대응할 수 있을까요
- JPQL과 QueryDSL 사용 기준

<br/>

### 기타

- 학교 시간표를 만든다고 생각해봅시다. 월1234 수업도 있고 월12+수34 같은 수업도 있을거예요. 어떤 식으로 구현하실건가요?
- 테스트 시 사용하는 도구? 테스트 하는 방법?
- 롬복의 동작 과정
