
![Screenshot 2024-07-04 111637](https://github.com/Dassourav07/User_Design/assets/94233240/33a0afd7-ab4f-4e73-b241-2e81cb896d0c)


Project Description

This project is a comprehensive web application built with a strong focus on security, user management, and streamlined data handling. Below is an in-depth look into the key components and functionalities of our application:

1. checkForAuthenticationCookie in Node.js
This function is a crucial part of our security infrastructure. It verifies the presence and validity of an authentication cookie for each incoming request. If the cookie is missing or invalid, the user is redirected to the login page. This ensures that only authenticated users can access protected routes and resources.

2. User Schema
Our application utilizes a robust user schema to manage user data. This schema defines the structure of the user database, including fields such as username, email, password, and profile information. The schema ensures data integrity and facilitates efficient data retrieval and manipulation.

3. Using Salt
For enhanced security, we implement salt in our password hashing process. Salt is a random string added to the password before hashing to ensure that even identical passwords have unique hashes. This technique protects against rainbow table attacks and improves overall security.

4. Using Route Router (GET, POST, DELETE)
Our application features a well-structured routing system using Node.js' Express framework. We define routes for various operations:
router.get: Handles HTTP GET requests for fetching data, such as retrieving user profiles or displaying lists of items.
router.post: Manages HTTP POST requests for creating new entries, such as user registration or adding new items to a database.
router.delete: Facilitates HTTP DELETE requests to remove specific entries, such as deleting a user account or removing items from a list.

5. JWT Authentication
JSON Web Tokens (JWT) are employed for secure user authentication. When a user logs in, a JWT is generated and sent to the client. This token is included in subsequent requests to verify the user's identity. JWT authentication is stateless, scalable, and enhances the security of our application.

6. CSS
The visual appeal and user experience of our application are enhanced through carefully designed CSS. Our stylesheets ensure a consistent and responsive design across different devices and screen sizes. We prioritize usability and aesthetics to create an engaging and intuitive interface for our users.
