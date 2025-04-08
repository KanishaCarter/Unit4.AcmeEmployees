# Unit4.AcmeEmployees
Block 31 Express &amp; SQL Workshop

Overview
The Acme Company wants to create an application that allows them to track their employees. The front end of their application has already been built, so you will help by building the back end of the application. The back end will need to connect to the database, seed sample data, and start an Express server. It will also need to have routes that enable a web client to receive the front end. And, it will need an API route for the Acme Company employees.

Each employee will have:

An ID, which is SERIAL.
A name that is less than 50 characters.
A Boolean value that indicates if the employee is an administrator.
Getting Started
Using what you know about Express and SQL, complete the following coding challenges:

Navigate to the GitHub repoLinks to an external site. for the starter code that your instructor provided. 
Fork the starter repository, and then navigate to the directory.
Note that the setup of this repository resembles that in your guided practice. The front end is complete, and you can run your Vite server to test it. You'll need to create your Express server and API routes in the server/index.js file.
Requirements
In the server/index.js file, complete the following (and use the guided practice for guidance):

Create a pg client. (You can name your database acme_hr_db, but make sure that you have an environment variable so that your application is deployable.)
Create the tables, and seed the data.
Note that an employee has an ID, a name, and an is_admin field.
Create the Express app.
Listen on the server.
Use GET /api/employees.
Make your application deployable by enabling your Express server to serve the generated code (HTML, JS, and CSS), which the Vite build command generates:
Note the route for the homepage.
Note the static assets in the dist folder.
Test your application by serving it from your Express application.
The successful completion of these requirements should result in: 

An application that loads.
Acme employees being displayed.
The styling rendered.
Submission
Submit a link to your repo.
