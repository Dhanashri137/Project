The Startup Pitch Platform is a comprehensive web application built with Spring Boot, designed to help startups showcase their business ideas while allowing investors to provide funding. Users can register as either Startups or Investors, facilitating a seamless experience. Startups can submit detailed pitches that outline their projects and funding goals, while investors have the opportunity to browse these pitches and invest in those that interest them.

This project employs an H2 in-memory database for easy setup and quick testing. The architecture revolves around essential entities such as User, Pitch, and Investment, with CRUD operations managed through JPA repositories. All interactions, from user registration to pitch submissions, are conducted via secure RESTful API endpoints.

Key features of the platform include:

User Management: Handles registration, login, and actions based on user roles.
Pitch Submission: Startups can submit pitches, which are initially saved as "PENDING."
Investment Handling: Investors can record their contributions to pitches.
For testing, Postman can be used to ensure all functionalities work smoothly. Future improvements could involve adding JWT authentication, creating distinct dashboards for each user type, and implementing features like investment tracking and admin approvals for pitch reviews. Overall, this project serves as a practical introduction to key web development skills using Java and Spring Boot.
