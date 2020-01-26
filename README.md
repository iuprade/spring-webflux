``` 
Sample Spring boot webflux demo project with router and handler and one sample test case.
Handler intercepts incoming request and hands it over to Handler class. Handler class does the operation and returns Mono ServerResponse as String.class. 
```

`
mvn spring-boot:run
`

`
cutl localhost:8080/hello
`

