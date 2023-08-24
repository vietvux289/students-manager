# Manage Students - Restful web

This repository contains a simple application for managing students using a RESTful web architecture. The project is divided into a back-end component built with Java Spring Boot and a front-end component built with ReactJS.
## Video Demo Website

Watch the demo video [***here***](https://youtu.be/zSU1DQnyw7g) to see the website in action.

## Back-end: api_create

To set up and run the back-end component:

1. **Create RESTful web services with Java Spring Boot:**
   - Configure the MySQL database connection.
   - Utilize JPA (Java Persistence API) and Hibernate for data persistence.

2. **Add sample data to the database:**
   - You can use MySQL Workbench or the integrated MySQL database in IntelliJ IDEA to populate the database with sample data.

3. **Run the web application:**
   - Start the Java Spring Boot application. The default port for Java Spring is 8080.
   - Test the RESTful APIs using Postman or any API testing tool by a GET request to `http://localhost:8080/`.

## Front-end: api_consume

To set up and run the front-end component:

1. **Consume APIs created by the Java Spring back-end using ReactJS:**
   - Utilize Axios to make API requests from the ReactJS application.

2. **Enable CORS (Cross-Origin Resource Sharing):**
   - CORS should be enabled either locally for each separate controller in the back-end or globally for the entire project.

3. **Start the web server for the Java Spring project:**
   - Ensure that the Java Spring server is running and reachable. Keep this server running; do not stop it.

4. **Start the ReactJS project:**
   - Use the command `npm start` in the terminal to initiate the ReactJS application.
   - Alternatively, you can use the shortcut `Shift + F10` if you're using IntelliJ IDEA.

## Notes

- The default port for the Java Spring application is `8080`.
- The default port for the ReactJS application is `3000`.

**Both the front-end and back-end servers must be running simultaneously for the application to work correctly.** You can set up the project in two independent windows in IntelliJ IDEA, or you can use IntelliJ IDEA for the Java Spring project and an alternative code editor like Visual Studio Code for the ReactJS project.

Remember to keep the Java Spring server running while testing and interacting with the ReactJS front-end.