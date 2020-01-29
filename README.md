# EmployeesWebApp

This is a Java Web application that uses HttpServlets and Java Beans to perform CRUD operations while dynamically generating the content on the server side. The Java classes were created using Object Oriented Programming principles such as Encapsulation, Abstraction, Polymorphism and Inheritance. The MVC design pattern was used to separate the Presentation, Controller, Business and Data layers.

## Getting Started

I've used Eclipse, JBoss Tools pluggin and JBoss WildFly to write this project. To see this project on your browser, use the employees.war file and run it with JBoss WildFly.

I will not be covering how to run this project in Eclipse because the process is very complicated and the compatibility of software versions is sometimes inconsistent. However, if you already have your environment set up, please feel free to run it in Eclipse .

### Prerequisites

JBoss WildFly (16.0.0 or newer version)

### Run Project

Download and install JBoss WildFly (16.0.0 or newer version).

Place the employees.war file in the standalone\deployments folder. 

Use Command Prompt to navigate to your wildfly-16.0.0.Final\bin directory and run this command to start WildFly:
```
standalone.bat
```

Lastly, go to this URL to check out this project:
```
http://localhost:8080/employees/
```

### Authors

* James Wong
