readme file 
spring works on inversion of  control mechanism
Dependency injection :- dependency injection is a technique whereby one object (or static method) supplies the dependencies of another object

Strut/js/mvc :- used in ui layer of spring
Security/transaction management :- used in business and service layer
Spring JDBC/Spring ORM :- used in data access layer

Spring modules(https://www.javatpoint.com/spring-modules):- 

Spring core:- Core/beans/Context/spEl
AOP/Aspect/Instrumentation/messaging

Data Access/Integration :- JDBC /ORM /JMS /OXM

Web :- Web /Servlet/Portlet/WebSocket

Test:- junit/testng

components of spring- 

Sprint ioc container :- 1. create  the object and hold them in memory  and injectign them in another object if required 
it takes beans and config 
The Spring IoC container is a core component of the Spring Framework that is responsible for creating, configuring, and assembling objects known as beans, as well as managing their life cycles. It is also known as the Dependency Injection (DI) container, as it uses DI to manage the components that make up an application.
The Spring IoC container can be configured using either XML configuration files or annotations. Once configured, the container can be used to create beans on demand. When a bean is created, the container will inject any dependencies that the bean has into it. This means that beans do not need to worry about how their dependencies are created or managed, as the container will take care of this for them.

Application Context :- 
The ApplicationContext interface in Spring is the central interface for accessing and configuring beans in a Spring container. It provides a number of methods for retrieving beans, publishing events, and accessing resources.
The ApplicationContext interface is extended by a number of other interfaces, each of which provides additional functionality. For example, the WebApplicationContext interface is extended by the ApplicationContext interface and provides additional functionality for web applications.
The ApplicationContext interface is implemented by a number of different classes, each of which provides a different implementation of the interface. For example, the ClassPathXmlApplicationContext class implements the ApplicationContext interface and provides an implementation that loads beans from XML configuration files.
The ApplicationContext interface is a powerful interface that provides a number of features for accessing and configuring beans in a Spring container. It is the central interface for interacting with a Spring container and is used by a wide variety of Spring applications.