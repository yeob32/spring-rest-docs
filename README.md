# spring-rest-docs

### 이슈
```
urlTemplate not found. If you are using MockMvc did you use RestDocumentationRequestBuilders to build the request?
java.lang.IllegalArgumentException: urlTemplate not found. If you are using MockMvc did you use RestDocumentationRequestBuilders to build the request?
	at org.springframework.util.Assert.notNull(Assert.java:198)
	at org.springframework.restdocs.request.PathParametersSnippet.extractUrlTemplate(PathParametersSnippet.java:126)
	at org.springframework.restdocs.request.PathParametersSnippet.extractActualParameters(PathParametersSnippet.java:113)
	at org.springframework.restdocs.request.AbstractParametersSnippet.verifyParameterDescriptors(AbstractParametersSnippet.java:89)
	at org.springframework.restdocs.request.AbstractParametersSnippet.createModel(AbstractParametersSnippet.java:74)
	at org.springframework.restdocs.request.PathParametersSnippet.createModel(PathParametersSnippet.java:98)
```
* https://stackoverflow.com/questions/32889070/pathparameters-documentation-exception-urltemplate-not-found

### 참고
* https://www.baeldung.com/spring-rest-docs
* https://docs.spring.io/spring-restdocs/docs/2.0.4.RELEASE/reference/html5/