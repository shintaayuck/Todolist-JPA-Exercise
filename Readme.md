
<h1 align="center">
  <br>
  Todolist Application using Spring Boot, PostgreSQL, JPA, Hibernate REST API
  <br>
  <br>
</h1>

<h3 align="center">
Shinta Ayu C.K.
<br>
</h3>

<h6 align="center">
Credit to [Callicoder](https://www.callicoder.com/spring-boot-jpa-hibernate-postgresql-restful-crud-api-example/
)</h6>

## Steps to Setup

**1. Clone this repository**

**2. Configure PostgreSQL**

First, create a database named `postgres_demo`. Then, open `src/main/resources/application.properties` file and change the spring datasource username and password as per your PostgreSQL installation.

**3. Run the app**

Type the following command from the root directory of the project to run it -

```bash
mvn spring-boot:run
```

Alternatively, you can package the application in the form of a JAR file and then run it like so -

```bash
mvn clean package
java -jar target/postgres-demo-0.0.1-SNAPSHOT.jar
```

