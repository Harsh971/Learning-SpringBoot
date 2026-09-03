# Spring Boot Learning Roadmap

| Phase | # | Topic | Subtopic | Link |
|---|---:|---|---|---|
| **Phase 0: Java Prerequisites** | 1 | **Java Language Basics** | Variables and data types | |
| | | | Primitive vs non-primitive types | |
| | | | Operators | |
| | | | Conditional statements | |
| | | | Loops | |
| | | | Methods | |
| | | | Method overloading | |
| | | | Pass by value in Java | |
| | | | Stack vs heap memory basics | |
| | 2 | **Object-Oriented Programming** | Class and Object | |
| | | | Encapsulation | |
| | | | Inheritance | |
| | | | Polymorphism | |
| | | | Abstraction | |
| | | | Interface | |
| | | | Abstract class | |
| | | | Constructor | |
| | | | Constructor chaining | |
| | | | this and super | |
| | | | Method overriding | |
| | | | Dynamic method dispatch | |
| | | | Composition vs inheritance | |
| | | | Association, aggregation, composition | |
| | | | Tight coupling vs loose coupling | |
| | 3 | **Important Java Keywords** | static | |
| | | | final | |
| | | | this | |
| | | | super | |
| | | | private, protected, public, default | |
| | | | abstract | |
| | | | interface | |
| | | | enum | |
| | | | transient | |
| | | | volatile | |
| | | | synchronized | |
| | 4 | **Java Memory Block** | Stack memory | |
| | | | Heap memory | |
| | | | Garbage collection | |
| | | | Object lifecycle | |
| | | | Strong, weak, soft references | |
| | | | Class loading basics | |
| | | | String pool | |
| | | | Immutable objects | |
| | 5 | **Exception Handling** | Checked exceptions | |
| | | | Unchecked exceptions | |
| | | | try-catch-finally | |
| | | | throw vs throws | |
| | | | Custom exceptions | |
| | | | Exception propagation | |
| | | | Best practices for exception design | |
| | | | Global exception handling thinking, useful for Spring Boot | |
| | 6 | **Collection Framework** | List | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ArrayList | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; LinkedList | |
| | | | Set | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; HashSet | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; LinkedHashSet | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; TreeSet | |
| | | | Map | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; HashMap | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; LinkedHashMap | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; TreeMap | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ConcurrentHashMap | |
| | | | Queue and Deque | |
| | | | Iterator and ListIterator | |
| | | | Comparable vs Comparator | |
| | | | Internal working of HashMap | |
| | | | Hashing | |
| | | | equals and hashCode contract | |
| | | | Fail-fast vs fail-safe iterators | |
| | | | Time complexity of common operations | |
| | 7 | **Java Generics** | Why generics are needed | |
| | | | Generic classes | |
| | | | Generic methods | |
| | | | Bounded types | |
| | | | Wildcards | |
| | | | ? extends | |
| | | | ? super | |
| | | | Type erasure | |
| | | | Generics in repositories, services, DTO mapping | |
| | 8 | **Java 8 Features** | Lambda expressions | |
| | | | Functional interfaces | |
| | | | Predicate | |
| | | | Function | |
| | | | Consumer | |
| | | | Supplier | |
| | | | Stream API | |
| | | | Intermediate operations | |
| | | | Terminal operations | |
| | | | map, filter, flatMap, collect | |
| | | | Optional | |
| | | | Method references | |
| | | | Default methods in interfaces | |
| | | | Date and Time API | |
| | | | CompletableFuture basics | |
| | 9 | **MultiThreading and Concurrency** | Thread lifecycle | |
| | | | Creating threads | |
| | | | Runnable vs Callable | |
| | | | ExecutorService | |
| | | | Thread pool | |
| | | | Future | |
| | | | CompletableFuture | |
| | | | Race condition | |
| | | | Deadlock | |
| | | | Synchronization | |
| | | | Locks | |
| | | | Atomic classes | |
| | | | Concurrent collections | |
| | | | ThreadLocal | |
| | | | Immutability in concurrent systems | |
| | | | Async execution in Spring Boot | |
| **Phase 1: Core Spring Foundation** | 1 | **Why Spring Exists** | Problems before Spring | |
| | | | Manual object creation problem | |
| | | | Tight coupling problem | |
| | | | Reusability issue | |
| | | | Testability issue | |
| | | | Boilerplate configuration problem | |
| | | | Enterprise application complexity | |
| | | | How Spring solves object creation and dependency management | |
| | 2 | **Inversion of Control (IoC)** | What is IoC? | |
| | | | Who controls object creation? | |
| | | | Traditional Java object creation vs Spring object creation | |
| | | | Spring IoC container | |
| | | | BeanFactory | |
| | | | ApplicationContext | |
| | | | Why IoC improves testability and flexibility | |
| | 3 | **Dependency Injection (DI)** | What is dependency? | |
| | | | What is injection? | |
| | | | Constructor injection | |
| | | | Setter injection | |
| | | | Field injection | |
| | | | Which injection is best and why? | |
| | | | Required dependencies vs optional dependencies | |
| | | | Circular dependency | |
| | | | How Spring resolves dependencies | |
| | | | Dependency resolution by type | |
| | | | Dependency resolution by name | |
| | | | Multiple bean conflict | |
| | | | **Important Annotations** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Autowired | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Qualifier | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Primary | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Lazy | |
| | 4 | **Spring Bean** | **Bean Basics** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; What is a bean? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Normal Java object vs Spring bean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Who creates beans? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Where are beans stored? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean identity | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean name | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean type | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean scope | |
| | | | **Bean Creation Methods** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @Component | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @Service | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @Repository | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @Controller | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @RestController | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using @Bean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using XML configuration, for understanding legacy systems | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Using Java configuration with @Configuration | |
| | | | **Bean Scope** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Singleton | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Prototype | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Request | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Session | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Application | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; WebSocket | |
| | | | **Bean Life Cycle** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 1. Bean definition loaded | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 2. Bean instantiated | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 3. Dependencies injected | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 4. Aware interfaces called | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 5. BeanPostProcessor before initialization | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 6. Initialization callback | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 7. BeanPostProcessor after initialization | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 8. Bean ready to use | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Stage 9. Destruction callback | |
| | | | **Topics** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Constructor | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Dependency Injection | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PostConstruct | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; InitializingBean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Custom init method | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BeanPostProcessor | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PreDestroy | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; DisposableBean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Custom Destroy Method | |
| | | | **Bean Lifecycle Interface** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BeanNameAware | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BeanFactoryAware | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ApplicationContextAware | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; InitializingBean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; DisposableBean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BeanPostProcessor | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BeanFactoryPostProcessor | |
| | 5 | **Spring Container** | IoC container | |
| | | | BeanFactory | |
| | | | ApplicationContext | |
| | | | Difference between BeanFactory and ApplicationContext | |
| | | | AnnotationConfigApplicationContext | |
| | | | ClassPathXmlApplicationContext | |
| | | | WebApplicationContext | |
| | | | BeanDefinition | |
| | | | BeanDefinitionRegistry | |
| | | | Environment | |
| | | | PropertySource | |
| | | | ResourceLoader | |
| | 6 | **Spring Configuration** | **Annotation Based Configuration** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Configuration | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Bean | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @ComponentScan | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PropertySource | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Value | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Import | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Profile | |
| | | | **XML Based Configuration** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean declaration in XML | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Constructor injection | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Setter injection | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean scope in XML | |
| | | | **Java Based Configuration** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Multiple config classes | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Importing config classes | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Conditional bean creation | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Environment-based beans | |
| | 7 | **Component Scanning** | What is component scanning? | |
| | | | Base package scanning | |
| | | | How Spring finds classes | |
| | | | Stereotype annotations | |
| | | | Include filters | |
| | | | Exclude filters | |
| | | | Difference between @Component, @Service, @Repository, @Controller | |
| **Phase 2: Spring AOP** | 1 | **AOP Basics** | What is AOP? | |
| | | | Why AOP exists? | |
| | | | Cross-cutting concerns | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Logging | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Security | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Transactions | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Auditing | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Metrics | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Exception handling | |
| | 2 | **AOP Terms** | Aspect | |
| | | | Advice | |
| | | | Join point | |
| | | | Pointcut | |
| | | | Weaving | |
| | | | Proxy | |
| | | | Target object | |
| | 3 | **Advice Types** | @Before | |
| | | | @After | |
| | | | @AfterReturning | |
| | | | @AfterThrowing | |
| | | | @Around | |
| | 4 | **Spring AOP Internals** | Proxy-based AOP | |
| | | | JDK dynamic proxy | |
| | | | CGLIB proxy | |
| | | | Self-invocation problem | |
| | | | Why private methods are not advised | |
| | | | AOP vs filters vs interceptors | |
| | | | AOP with annotations | |
| | | | Custom annotation-based AOP | |
| **Phase 3: Spring Boot Fundamentals** | 1 | **What is Spring Boot?** | Why Spring Boot was created | |
| | | | Difference between Spring and Spring Boot | |
| | | | Convention over configuration | |
| | | | Auto-configuration | |
| | | | Starter dependencies | |
| | | | Embedded server | |
| | | | Production-ready features | |
| | 2 | **Spring Boot Folder Structure** | Project structure | |
| | 3 | **Spring Boot Deep Dive** | @SpringBootConfiguration | |
| | | | @EnableAutoConfiguration | |
| | | | @ComponentScan | |
| | | | **Important Areas** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; What happens when application starts | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; SpringApplication.run() | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ApplicationContext creation | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Auto-Configuration loading | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bean Creation | |
| | 4 | **Spring Boot Auto Configuration** | What is auto-configuration? | |
| | | | How Spring Boot detects dependencies | |
| | | | Conditional configuration | |
| | | | @ConditionalOnClass | |
| | | | @ConditionalOnMissingBean | |
| | | | @ConditionalOnProperty | |
| | | | @ConditionalOnBean | |
| | | | AutoConfiguration classes | |
| | | | How to exclude auto-configuration | |
| | | | How to debug auto-configuration | |
| | | | spring-boot-autoconfigure | |
| | | | META-INF/spring.factories, older versions | |
| | | | AutoConfiguration.imports, newer versions | |
| | 5 | **Spring Boot Starters** | What are starters? | |
| | | | Why starters simplify dependency management | |
| | | | Common starters | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-web | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-data-jpa | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-security | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-validation | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-test | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-actuator | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-aop | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-cache | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-mail | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; spring-boot-starter-webflux | |
| | 6 | **Application Properties** | application.properties | |
| | | | application.yml | |
| | | | Configuration hierarchy | |
| | | | Externalized configuration | |
| | | | Environment variables | |
| | | | Command-line arguments | |
| | | | Default properties | |
| | | | Profile-specific properties | |
| | | | Property overriding order | |
| | | | @Value | |
| | | | @ConfigurationProperties | |
| | | | Type-safe configuration | |
| | | | Nested configuration properties | |
| | | | Validation on config properties | |
| | 7 | **Spring Profiles** | What is a profile? | |
| | | | application-local.yml | |
| | | | application-dev.yml | |
| | | | application-prod.yml | |
| | | | Activating profiles | |
| | | | Profile-specific beans | |
| | | | @Profile | |
| | | | Multiple active profiles | |
| | | | Default profile | |
| | | | Profile-based infrastructure config | |
| **Phase 4: REST APIs** | 1 | **Spring MVC Fundamentals** | What is Spring MVC? | |
| | | | DispatcherServlet | |
| | | | MVC request flow | |
| | | | HandlerMapping | |
| | | | HandlerAdapter | |
| | | | Controller | |
| | | | ViewResolver, even if REST does not use it much | |
| | | | Message converters | |
| | | | JSON conversion using Jackson | |
| | 2 | **REST API Development** | REST principles | |
| | | | Resource naming | |
| | | | HTTP methods | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; GET | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; POST | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; PUT | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; PATCH | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; DELETE | |
| | | | HTTP status codes | |
| | | | Request body | |
| | | | Response body | |
| | | | Path variables | |
| | | | Query parameters | |
| | | | Headers | |
| | | | Content negotiation | |
| | | | Idempotency | |
| | | | Safe methods | |
| | | | Statelessness | |
| | | | **Annotations** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RestController | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RequestMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @GetMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PostMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PutMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PatchMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @DeleteMapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RequestBody | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @ResponseBody | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PathVariable | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RequestParam | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RequestHeader | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @ResponseStatus | |
| | 3 | **API Response Standardization** | Standard API response wrapper | |
| | | | Success response format | |
| | | | Error response format | |
| | | | Metadata | |
| | | | Pagination metadata | |
| | | | Nested response structure | |
| | | | Request tracing | |
| | | | Correlation ID | |
| | | | Error codes | |
| | | | Validation errors | |
| | | | Field-level error response | |
| | 4 | **Request Validation** | Bean validation | |
| | | | Jakarta Validation | |
| | | | @Valid | |
| | | | @Validated | |
| | | | @NotNull | |
| | | | @NotBlank | |
| | | | @NotEmpty | |
| | | | @Size | |
| | | | @Min | |
| | | | @Max | |
| | | | @Email | |
| | | | @Pattern | |
| | | | Custom validators | |
| | | | Class-level validation | |
| | | | Validation groups | |
| | | | Handling validation errors globally | |
| | 5 | **Exception Handling** | Local exception handling | |
| | | | Global exception handling | |
| | | | @ControllerAdvice | |
| | | | @RestControllerAdvice | |
| | | | @ExceptionHandler | |
| | | | Custom exceptions | |
| | | | Business exceptions | |
| | | | Technical exceptions | |
| | | | Validation exceptions | |
| | | | Error response DTO | |
| | | | Error code enum | |
| | | | Logging exceptions properly | |
| | | | Not exposing internal stack traces | |
| | | | **Common custom exceptions** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ResourceNotFoundException | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; BadRequestException | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; UnauthorizedException | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ForbiddenException | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ConflictException | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Business Exception | |
| **Phase 5: Data Access Layer** | 1 | **JDBC Basics** | What is JDBC? | |
| | | | Connection | |
| | | | Statement | |
| | | | PreparedStatement | |
| | | | ResultSet | |
| | | | SQL injection | |
| | | | Connection pool | |
| | | | DataSource | |
| | | | JdbcTemplate | |
| | 2 | **Spring JDBC** | JdbcTemplate | |
| | | | NamedParameterJdbcTemplate | |
| | | | RowMapper | |
| | | | ResultSetExtractor | |
| | | | Batch updates | |
| | | | Transaction management with JDBC | |
| | 3 | **JPA and Hibernate** | **3.1 ORM Basics** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; What is ORM? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; What is JPA? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; What is Hibernate? | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; JPA vs Hibernate | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; EntityManager | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Persistence context | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Entity lifecycle | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; First-level cache | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Dirty checking | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Flush | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Detach | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Merge | |
| | | | **3.2 Entity Mapping** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Entity | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Table | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Id | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @GeneratedValue | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Column | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Transient | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Enumerated | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Lob | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @CreationTimestamp | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @UpdateTimestamp | |
| | | | **3.3 Relationships** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; One-to-One | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; One-to-Many | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Many-to-One | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Many-to-Many | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Unidirectional mapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Bidirectional mapping | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Owning side | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; mappedBy | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Join column | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Join table | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Cascade types | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Orphan removal | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Fetch types | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Lazy | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Eager | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; N+1 query problem | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; LazyInitializationException | |
| | | | **3.4 Spring Data JPA** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; JpaRepository | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; CrudRepository | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; PagingAndSortingRepository | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Query methods | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Derived queries | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Query | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; JPQL | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Native query | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Projections | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; DTO projection | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Pagination | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Sorting | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Specifications | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Criteria API | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Auditing | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; Soft delete | |
| | 4 | **Database Concepts** | SQL basics | |
| | | | Joins | |
| | | | Indexes | |
| | | | Primary key | |
| | | | Foreign key | |
| | | | Unique constraint | |
| | | | Composite key | |
| | | | Normalization | |
| | | | Transactions | |
| | | | Isolation levels | |
| | | | Locking | |
| | | | Optimistic locking | |
| | | | Pessimistic locking | |
| | | | Deadlocks | |
| | | | Query optimization | |
| | | | Explain plan basics | |
| | | | Connection pool tuning | |
| | 5 | **Transaction Management** | What is a transaction? | |
| | | | ACID properties | |
| | | | Declarative transaction management | |
| | | | Programmatic transaction management | |
| | | | @Transactional | |
| | | | Transaction propagation | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; REQUIRED | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; REQUIRES_NEW | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; SUPPORTS | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; NOT_SUPPORTED | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; MANDATORY | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; NEVER | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; NESTED | |
| | | | Isolation levels | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; READ_UNCOMMITTED | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; READ_COMMITTED | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; REPEATABLE_READ | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; SERIALIZABLE | |
| | | | Rollback rules | |
| | | | Checked vs unchecked exceptions in rollback | |
| | | | Read-only transaction | |
| | | | Transaction boundaries | |
| | | | Self-invocation issue with @Transactional | |
| | | | Transaction with async methods | |
| | | | Transaction with multiple databases | |
| **Phase 6: Logging and Monitoring** | 1 | **Logging in Spring Boot** | Why logging is needed | |
| | | | Logging vs debugging | |
| | | | Log levels | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; TRACE | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; DEBUG | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; INFO | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; WARN | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; ERROR | |
| | | | SLF4J | |
| | | | Logback | |
| | | | LoggerFactory | |
| | | | Logging pattern | |
| | | | Console logging | |
| | | | File logging | |
| | | | Rolling logs | |
| | | | Profile-based logging | |
| | | | Package-level logging | |
| | | | Logging request and response | |
| | | | Masking sensitive data | |
| | | | MDC | |
| | | | Correlation ID | |
| | | | Trace ID | |
| | | | Structured JSON logging | |
| | 2 | **Actuator** | What is Spring Boot Actuator? | |
| | | | Health endpoint | |
| | | | Info endpoint | |
| | | | Metrics endpoint | |
| | | | Beans endpoint | |
| | | | Environment endpoint | |
| | | | Loggers endpoint | |
| | | | Custom health indicators | |
| | | | Custom metrics | |
| | | | Exposing and securing actuator endpoints | |
| **Phase 7: Security** | 1 | **Spring Security Fundamentals** | Authentication | |
| | | | Authorization | |
| | | | Principal | |
| | | | GrantedAuthority | |
| | | | Role | |
| | | | Permission | |
| | | | SecurityContext | |
| | | | SecurityContextHolder | |
| | | | Filter chain | |
| | | | PasswordEncoder | |
| | | | BCrypt | |
| | | | UserDetails | |
| | | | UserDetailsService | |
| | | | AuthenticationManager | |
| | | | AuthenticationProvider | |
| | 2 | **Web Security** | Securing APIs | |
| | | | Public vs protected endpoints | |
| | | | Login flow | |
| | | | Basic authentication | |
| | | | Form login | |
| | | | Stateless authentication | |
| | | | Session-based security | |
| | | | CSRF | |
| | | | CORS | |
| | | | Security filters | |
| | | | Method-level security | |
| | | | **Annotations** | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PreAuthorize | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @PostAuthorize | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @Secured | |
| | | | &nbsp;&nbsp;&nbsp;&nbsp; @RolesAllowed | |
| | 3 | **JWT Security** | What is JWT? | |
| | | | Access token | |
| | | | Refresh token | |
| | | | Claims | |
| | | | Token signing | |
| | | | Token validation | |
| | | | Expiry | |
| | | | Stateless security | |
| | | | JWT filter | |
| | | | Authentication entry point | |
| | | | Role-based access | |
| | | | Token blacklist | |
| | | | Refresh token rotation | |
| | 4 | **OAuth2 and OpenID Connect** | OAuth2 basics | |
| | | | Authorization server | |
| | | | Resource server | |
| | | | Client | |
| | | | Authorization code flow | |
| | | | Client credentials flow | |
| | | | OIDC | |
| | | | ID token | |
| | | | Access token | |
| | | | Scope | |
| | | | Spring Security OAuth2 client | |
| | | | Spring Security resource server | |
| **Phase 8: Advanced Spring Boot** | 1 | **Async Processing** | @Async | |
| | | | @EnableAsync | |
| | | | TaskExecutor | |
| | | | ThreadPoolTaskExecutor | |
| | | | CompletableFuture | |
| | | | Exception handling in async | |
| | | | Async with transactions | |
| | | | Async logging | |
| | | | When not to use async | |
| | 2 | **Scheduling** | @Scheduled | |
| | | | @EnableScheduling | |
| | | | Fixed rate | |
| | | | Fixed delay | |
| | | | Cron expressions | |
| | | | Scheduler thread pool | |
| | | | Distributed scheduling problem | |
| | | | ShedLock | |
| | 3 | **Caching** | Why caching? | |
| | | | @EnableCaching | |
| | | | @Cacheable | |
| | | | @CachePut | |
| | | | @CacheEvict | |
| | | | Cache key | |
| | | | Conditional caching | |
| | | | Redis cache | |
| | | | Caffeine cache | |
| | | | Cache invalidation | |
| | | | Cache stampede | |
| | | | TTL | |
| | | | Distributed cache | |
| | 4 | **File Handling** | File upload | |
| | | | MultipartFile | |
| | | | File validation | |
| | | | File size limit | |
| | | | File storage | |
| | | | Download API | |
| | | | Streaming response | |
| | | | Content type | |
| | | | Large file handling | |
| | | | Cloud storage concept | |
| | 5 | **Email Integration** | JavaMailSender | |
| | | | SMTP configuration | |
| | | | Plain text email | |
| | | | HTML email | |
| | | | Attachment email | |
| | | | Template-based email | |
| | | | Retry on failure | |
| | | | Async email sending | |
| **Phase 9: API Documentation and Contracts** | 1 | **Swagger / OpenAPI** | API documentation | |
| | | | Swagger UI | |
| | | | OpenAPI specification | |
| | | | Request schema | |
| | | | Response schema | |
| | | | Error schema | |
| | | | Authentication in Swagger | |
| | | | API versioning documentation | |
| | 2 | **API Versioning** | URI versioning | |
| | | | Header versioning | |
| | | | Query parameter versioning | |
| | | | Media type versioning | |
| | | | Backward compatibility | |
| | | | Deprecation strategy | |
| **Phase 10: Messaging and Event Driven System** | 1 | **Messaging Basics** | Synchronous vs asynchronous communication | |
| | | | Queue vs topic | |
| | | | Producer | |
| | | | Consumer | |
| | | | Broker | |
| | | | Message acknowledgement | |
| | | | Retry | |
| | | | Dead letter queue | |
| | | | Idempotent consumers | |
| | | | Ordering | |
| | | | Exactly once vs at least once | |
| | 2 | **Kafka** | Kafka broker | |
| | | | Topic | |
| | | | Partition | |
| | | | Offset | |
| | | | Consumer group | |
| | | | Producer | |
| | | | Consumer | |
| | | | Replication | |
| | | | Retention | |
| | | | Kafka with Spring Boot | |
| | | | Error Handling | |
| | | | Retry Topic | |
| | | | Dead Letter topic | |
| | | | Idempotent message processing | |
| | 3 | **RabbitMQ** | Exchange | |
| | | | Queue | |
| | | | Binding | |
| | | | Routing key | |
| | | | Direct exchange | |
| | | | Topic exchange | |
| | | | Fanout exchange | |
| | | | Dead letter exchange | |
| | | | Spring AMQP | |
| **Phase 11: Microservices with Spring Boot** | 1 | **Microservices Fundamentals** | Monolith vs microservice | |
| | | | Service boundaries | |
| | | | Database per service | |
| | | | API gateway | |
| | | | Service discovery | |
| | | | Inter-service communication | |
| | | | Fault tolerance | |
| | | | Distributed transactions | |
| | | | Eventual consistency | |
| | | | Saga pattern | |
| | | | Circuit breaker | |
| | | | Rate limiting | |
| | | | Bulkhead pattern | |
| | 2 | **Spring Cloud** | Config Server | |
| | | | Eureka service discovery | |
| | | | Spring Cloud Gateway | |
| | | | OpenFeign | |
| | | | Load balancing | |
| | | | Resilience4j | |
| | | | Circuit breaker | |
| | | | Retry | |
| | | | Rate limiter | |
| | | | Bulkhead | |
| | | | Distributed tracing | |
| | | | Centralized configuration | |
| | 3 | **Inter-Service Communication** | RestTemplate, legacy | |
| | | | WebClient | |
| | | | OpenFeign | |
| | | | gRPC basics | |
| | | | Timeout | |
| | | | Retry | |
| | | | Circuit breaker | |
| | | | Fallback | |
| | | | Idempotency | |
| | | | API contract between services | |
| **Phase 12: Reactive Programming** | 1 | **Spring WebFlux** | Blocking vs non-blocking | |
| | | | Reactive programming | |
| | | | Mono | |
| | | | Flux | |
| | | | Backpressure | |
| | | | Netty | |
| | | | WebClient | |
| | | | Reactive repositories | |
| | | | When to use WebFlux | |
| | | | When not to use WebFlux | |
| | | | Difference between Spring MVC and WebFlux | |
