# todoApp
Optimizing with sprping and react v6 versions

 
### Tech Stack

- Java 11
- Spring Boot
- Spring Data Jpa
- Spring Security
- Consumer Driven Contract Tests
- Javascript
- React.js V6
- ReactStrap

## Tech Stack


For building and running the application you need:
- [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or newer . 
- [Maven](https://maven.apache.org)
- [Lombok](https://projectlombok.org/)
- [MySQL](https://www.mysql.com/)



### Build & Run

 ###### Create DB 
```
CREATE DATABASE todo_dev;
CREATE DATABASE todo_test;
```
  ###### Backend
  
```
mvn clean install && mvn --projects backend spring-boot:run
```

  ###### Frontend
  
##### (Install all dependencies)
```
npm install
```

##### (Start Project)
```
npm start
```

##### (Port)
```
Backend :  http://localhost:8081
```

```
Frontend : http://localhost:3000
```

##### Use Postman collection 

### Integration tests && Contract tests
