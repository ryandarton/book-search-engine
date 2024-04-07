# Book-Lovers Saver

The Book-Lovers Saver is a comprehensive web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It empowers users to explore and discover books through the Google Books API, allowing them to save their favorite books for future reference. The application leverages Apollo Server for efficient GraphQL API management and utilizes Apollo Client to seamlessly handle state within the React frontend.

## Key Features:

Seamless book search functionality powered by the Google Books API
Detailed book information for informed decision-making
Personalized book saving feature for easy access to favorite titles
Intuitive saved books list for efficient book management
Effortless removal of books from the saved list

## Getting Started:

To run the Book-Lovers Saver application locally, ensure that you have the following prerequisites installed:
-Node.js
-npm
-MongoDB

## Follow these steps to set up the application:

1. Clone the repository using the command:
   git clone git@github.com:hyrumsdolan/Book-Saver-MERN-.git

2. Navigate to the root, client, and server directories and install the required NPM packages by running:
   npm run install

3. To start the application in development mode, use the command:
   npm run develop

4. To create a production-ready build of the application, run:
   npm run build

5. To launch the application in production mode, execute:
   npm start

## Application Architecture:

The Book-Lovers Saver application is structured into two main components:

Client: The client-side of the application is developed using React.js and resides in the client directory. It utilizes Apollo Client for efficient state management and seamless communication with the GraphQL API. The entry point for the client application is located at client/src/main.jsx.
Server: The server-side of the application is built with Express.js and Apollo Server, and is located in the server directory. It integrates with MongoDB as the database, utilizing Mongoose as the ODM (Object Data Modeling) tool. The main server entry point can be found at server/server.js.
