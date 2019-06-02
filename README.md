# posys
Point Of Sale

# Project Structure
Example
[Document](https://www.javaguides.net/2019/01/spring-mvc-project-structure.html)
~~~~
── pom.xml
└── src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── companyname
    │   │           └── projectname
    │   │               ├── domain
    │   │               │   └── MyDomain.java
    │   │               ├── repository
    │   │               │   └── MyDomainRepository.java
    │   │               ├── service
    │   │               │   ├── MyDomainService.java
    │   │               │   └── internal
    │   │               │       └── MyDomainServiceImpl.java
    │   │               └── web
    │   │                   └── MyDomainController.java
    │   ├── resources
    │   │   ├── META-INF
    │   │   │   └── spring
    │   │   │       ├── applicationContext.xml
    │   │   │       └── database.properties
    │   │   ├── logback-access.xml
    │   │   └── logback.xml
    │   └── webapp
    │       ├── WEB-INF
    │       │   ├── classes
    │       │   ├── i18n
    │       │   ├── layouts
    │       │   ├── spring
    │       │   │   └── webmvc-config.xml
    │       │   ├── views
    │       │   │   ├── myDomain
    │       │   │   │   ├── create.jsp
    │       │   │   │   ├── list.jsp
    │       │   │   │   ├── show.jsp
    │       │   │   │   └── update.jsp
    │       │   │   ├── dataAccessFailure.jsp
    │       │   │   ├── index.jsp
    │       │   │   ├── resourceNotFound.jsp
    │       │   │   ├── uncaughtException.jsp
    │       │   │   └── views.xml
    │       │   └── web.xml
    │       ├── images
    │       └── styles
    ├── site
    │   ├── apt
    │   ├── fml
    │   ├── site.xml
    │   └── xdoc
    └── test
        ├── java
        │   └── com
        │       └── companyname
        │           └── projectname
        │               └── service
        │                   └── MyDomainServiceTests.java
        └── resources
            ├── com
            │   └── companyname
            │       └── projectname
            │           └── service
            │               └── MyDomainServiceTests-context.xml
            └── logback-test.xml
~~~~

# Layout

~~~~
-----------------------------------------
|         Banner                        |
|---------------------------------------|
|         |                             |
|         |                             |
|         |                             |
|         |          Main               |
| Left    |          Content            |
|   Bar   |                             |
|         |                             |
|         |                             |
|         |                             |
|         |                             |
|         |                             |
|         |                             |
|         |                             |
-----------------------------------------
~~~~