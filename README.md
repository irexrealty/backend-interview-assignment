# backend-interview-assignment

## Using GIT

### clone
- Command
```
git clone git@github.com:irexrealty/backend-interview-assignment.git
cd interview-assignments
git checkout <name-dd-mm-yyyy>
```
## Using Maven

### build
- Command
```
mvn clean package spring-boot:repackage -DskipTests
```

### run
- Command
```
java -jar target/interview-0.0.1-SNAPSHOT.jar
```

## Using Gradle

### build
- Command
```
gradle clean build
```

### run
- Command
```
java -jar target/interview-0.0.1-SNAPSHOT.jar
```