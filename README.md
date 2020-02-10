# junit5-study

##Junit5 Start
기본 애노테이션<br>
@Test<br>
@BeforeAll/@AfterAll<br>
@BeforeEach/@AfterEach<br>
@Disabled

##Junit5: 테스트 이름 표기하기
@DisplayNameGeneration
- Method와 Class 레퍼런스를 사용해서 테스트 이름을 표기하는 방법 설정
- 기본 구현체로 ReplaceUnderscores 제공<br>
@DisplayName
- 어떤 테스트인지 테스트 이름을 보다 쉽게 표현할 수 있는 방법을 제공하는 애노테이션
- @DisplayNameGeneration보다 우선 순위가 높다.<br>
참고:
- https://junit.org/junit5/docs/current/user-guide/#writing-tests-display-names