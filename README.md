# Study_springboot (2021.03)
Study about springboot through inflearn

스프링 입문 - 코드로 배우는 스프링 부트, 웹 MVC, DB 접근 기술 (김영한)
https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8/dashboard

**[Project Setting]**

- Java 11 
- Spring Boot : 2.3.x
- IDE: IntelliJ, Junit 5

**[Project Metadata]**

- Project : Gradle Project
- groupId : hello
- articatId : hello-spring
- Dependencies : Spring Web, Thymeleaf

**[Using Skill]**
1. Spring Boot
2. Gradle : 빌드 툴
3. JPA (Java Persistence API) : ORM (Object Relational Mapping) 기술 표준, SQL에 대해 자동으로 해결
4. HIBERNATE : JPA라는 ORM 기술표준을 구현한 것, RDB를 사용하면서 객체지향 어플리케이션 개발에 집중 가능
5. Thymeleaf : View 템플릿 (html 만드는 템플릿 엔진), 컨트롤러가 전달하는 데이터를 이용하여 동적으로 화면을 구성할 수 있게 함 (기존 JSP 한계 보완)
               변수식으로 사용하는 ${}와 메세지방식 #{}, 객체변수식인 *{}, 링크방식 @{}
7. Tomcat : WAS 서버
8. Junit : 테스트 프레임워크, 요즘엔 5버전을 많이 사용
9. H2 : 임시 데이터베이스

**[Thymeleaf 동작 방식]**
 
<img width="811" alt="image" src="https://user-images.githubusercontent.com/26623530/113508421-e54d3580-958a-11eb-935a-df7415894848.png">


<img width="819" alt="image" src="https://user-images.githubusercontent.com/26623530/113566507-c2348b80-9647-11eb-98fc-cf7f265f288d.png">


*Spring Doc
https://docs.spring.io/spring-boot/docs/current/reference/html/features.html#features
