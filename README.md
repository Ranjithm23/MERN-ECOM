Description
An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

Buyers browse the store categories, products and brands
Sellers or Merchants manage their own brand component
Admins manage and control the entire store components
features:
Node provides the backend environment for this application
Express middleware is used to handle requests, routes
Mongoose schemas to model the application data
React for displaying UI components
Redux to manage application's state
Redux Thunk middleware to handle asynchronous redux actions
Quickstart Guide


Clone the repository

$ git clone https://github.com/Ganeshkumarg024/MERN-ECOM.git
Edit the dockercompose.yml file and update the the values for MONGO_URI and JWT_SECRET

Then simply start the docker compose:

$ docker compose -f dockercompose.yml up
Database Seed
The seed command will create an admin user in the database
The email and password are passed with the command as arguments
Like below command, replace brackets with email and password.
For more information, see code here
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
Demo
This application is deployed on Vercel Please check it out 😄 here.

See admin dashboard demo

Install
Some basic Git commands are:

$ git clone https://github.com/Ganeshkumarg024/MERN-ECOM.git
$ cd project
$ npm install
Start development
$ npm run dev
Simple build for production
$ npm run build
Run build for production
$ npm start
Languages & tools
Node

Express

Mongoose

React






