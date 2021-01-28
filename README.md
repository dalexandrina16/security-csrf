Run using `mvn clean tomcat7:run`

The application contains a simple request that can only be performed on the client side, using the generated csrf token.
This way any other source of the request that does not contain the token will fail to perform.
