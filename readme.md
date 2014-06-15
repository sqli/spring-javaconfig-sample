# Spring Java Config Sample #

Since Spring 3.0, the JavaConfig features are included in the Core Spring module. Thus Java Developer could move Spring beans definition from configuration XML files to Java classes.

Based on Spring Framework 4.0, Spring Data JPA 1.6, Spring Security 3.2 and Hibernate 4.3, this sample show how to use the Spring's new Java-configuration support and its @Configuration-annotated class.

The following classes, interfaces and annotations are used in the sample:
* JavaConfig main classes and annotations: @Configuration, @Bean, @ComponentScan, @Import, @ImportResource, @Profile, Environment, JndiObjectFactoryBean, @Scope 
* Spring Test: @WebAppConfiguration, @ContextConfiguration, @ActiveProfiles;  @ContextHierarchy
* Advanced Spring Framework features: @EnableTransactionManagement, @EnableAsync, @EnableCaching,  @EnableAspectJAutoProxy 
* Spring Data Jpa annotations: @EnableJpaRepositories
* Spring Security classes: @EnableWebMvcSecurity, WebSecurityConfigurerAdapter
* Spring MVC features: @EnableWebMvc, WebMvcConfigurerAdapter, RequestMappingHandlerAdapter, InternalResourceViewResolver, ignoreDefaultModelOnRedirect 
