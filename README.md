Hy-Vee GiftCards Management React-Spring-boot Application
-----

This is a multi-module Spring Boot React Apache Maven starter app and basic react app.

This project provides productive setup for building Spring Boot React applications. The application is divided into two Maven modules:

1. `backend`: This contains Java code of the application.
2. `frontend`: This contains all react JavaScript code of the application.

## Running the full application

You can build the package as a single artifact by running the `./mvnw clean install`.
Next, you can run the application by executing:

```bash
$ java -jar backend/target/backend-0.1.0-SNAPSHOT.jar
```

The application will be accessible at `http://localhost:8085`.

## Features


## Running the backend for development mode

There are multiple ways to run the backend. For development, you can use your favorite IDE and run the
`com.hyvee.giftcards.HyveeApplication`. As soon as your code compiles, Spring Boot DevTools will reload the code.

You can also run the application using Maven.

```bash
$ cd backend
$  ../mvnw spring-boot:run
```

## Running the frontend for development mode

**You will need 6.0+ and npm to run the dev server and build the project**.


To install all the required binaries for your project, you can run following command.

```
$ cd frontend
$ ../mvnw frontend:install-node-and-npm 
```

Once the above command finishes, you can start the frontend using the `npm start` command.

