# social-media-app

# Social Media API  
This project is the first of four parts in creating a social media clone website. It's built using React, Node.js, and JavaScript.
MongoDB is used for the backend, and Postman app aids in sending various requests. 


## Features

- CRUD operations for posts and users.
- Authentication system.
- Backend built with NodeJS and MongoDB.

## Dependencies

This project requires the following dependencies:

- bcrypt: A library to hash and compare passwords securely.
- dotenv: A module to load environment variables from a .env file.
- express: A web framework for Node.js that provides various features and middleware.
- helmet: A middleware that adds security headers to HTTP responses.
- mongoose: An object data modeling (ODM) library for MongoDB that simplifies schema definition, validation, and querying.
- morgan: A logging middleware that outputs request and response information to the console.
- nodemon: A utility that automatically restarts the server when code changes are detected.

## Installation & Usage

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies: `npm install`.
4. Create a .env file in the root folder and add the following variables:
    - MONGO_URI: Your MongoDB connection string. You can get it from MongoDB Atlas or your local MongoDB server.
    - PORT: The port number for your server. Default is 5000.
5. Start the server: `npm start`.
6. Use Postman or any API testing tool to send PUT, POST, DELETE, and UPDATE requests.

Stay tuned for the upcoming parts of this social media clone website!

## Contributing 

Feel free to fork this repository and make improvements/fixes in a separate branch. Please request a pull when ready.

## License 

MIT License - see `LICENSE.md` for details.
