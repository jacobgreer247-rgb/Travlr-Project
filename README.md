# Travlr-Project

Architecture:

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

I used Express and Handlebars to build the customer website, where the server puts together the pages before sending them to the browser. JavaScript handled the application logic, while the Angular admin side used a single page application to update content without reloading the whole page.

Why did the backend use a NoSQL MongoDB database?

MongoDB stored the trip information in flexible documents that worked well with the application’s data. It also made it easy to add, retrieve, and update trips through the backend.

Functionality:

How is JSON different from JavaScript, and how does it connect the frontend and backend?

JavaScript is a programming language, while JSON is a format for storing and transferring data. In my project, the backend sent trip information as JSON, and the Angular frontend used that information to display and update trips.

When did you refactor code, and what are the benefits of reusable UI components?

I refactored the customer website by moving repeated headers and footers into Handlebars partials. I also used reusable Angular trip cards. These changes reduced repeated code and made it easier to keep the design consistent and make updates.

Testing:

Explain methods, endpoints, and security in a full stack application.

Methods tell the API what action to perform, like GET for retrieving trips, POST for adding them, and PUT for updating them. Endpoints are the URLs where those requests go. I used Postman to test requests and responses. Adding login security also meant checking that protected requests had a valid token and that unauthorized requests were rejected.

Reflection:

How has this course helped your professional goals and career skills?

This course helped me understand how the frontend, backend, and database work together in a complete application. I gained experience with Angular, Express, MongoDB, API testing, and authentication. These skills gave me a stronger project for my portfolio and more experience I can bring into a software development job.
