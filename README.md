# Car Finder
Responsive <b>Angular SPA</b> application. Deployed and available for test in Heroku.  
After accessing the login link the page will be accessible in about 30-60 sec. This time is needed to "wake up" application(a feature of the subscription plan in Heroku).  
Link to the login page https://offers-jwt-ngrx.herokuapp.com/home   
    
<b>Backend</b>: Java Spring REST API  
Link to GitHub https://github.com/IlkoPanchev/offers-rest-jwt-cookies-herocu/tree/master/cars-rest-jwt. Deployed in Heroku.  

Car Finder is a small application for car offers created as a coursework at the end of Front-end module in SoftUni.  
<b>Authentication</b> of registered users based on <b>JWT</b>.  
JSON Web Token (JWT) authentication is a stateless method of securely transmitting information between parties as a JavaScript Object Notation (JSON) object. It is often used to authenticate and authorize users in web applications and APIs.  
<b>State management</b> of the application based on <b>NgRX</b>.  
NgRx is a library for state management inspired by Redux. It implements the Redux principles for Angular, providing a predictable and structured way of managing the application state.

<b>Roles</b>:  

- &emsp;Guest  
- &emsp;Registered user  

<b>Actions</b>:

Guest:

- &emsp;view all offers page
- &emsp;search option  
- &emsp;view details of a specific offer

Registered user:

- &emsp;view all offers page
- &emsp;search option
- &emsp;view own offers page
- &emsp;add new offer
- &emsp;view/edit/delete own offer
- &emsp;view/edit profile



