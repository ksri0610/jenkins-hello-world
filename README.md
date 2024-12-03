# Springboot Hello World App
This repository is used for Jenkins Training Demo

### Build JAR
```
mvn clean package -DskipTests=true
```

### Unit Test Cases
```
mvn test
```
- Total 6 test cases, out of which
  - 5 test cases will pass and 
  - 1 test case fails!
 
### Deploy/Run
```
java -jar target/hello-demo-*.jar 
```

### Integration Testing (Return 200 OK response)
```
curl -s http://localhost:6767/hello"
```
this is updated text
added somecontent in it
added some text in it
added final text in it
added semifinal text in it
executing all the files
