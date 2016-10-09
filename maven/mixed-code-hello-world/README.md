Kotlin Mixed Code with Java
===========================

```
$ mvn clean package -Dmaven.test.skip
```

# Output
```

target/
├── lib
│   ├── kotlin-runtime-1.0.4.jar
│   └── kotlin-stdlib-1.0.4.jar
│
└── mixed-code-hello-world-1.0-SNAPSHOT.jar

$ java -jar target/mixed-code-hello-world-1.0-SNAPSHOT.jar
Hello from Kotlin!
Hello from Java!
