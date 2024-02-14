# ASP.NET Core with MongoDB Tutorial

The tutorial guides you through creating a web application using ASP.NET Core that performs CRUD operations on a MongoDB database. It demonstrates how to configure MongoDB, model entities in C#, and integrate MongoDB with an ASP.NET Core application to manage a list of books. Based on the following Microsoft Learning article: [Build a .NET web app with MongoDB](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-8.0&tabs=visual-studio).

As usual, more complexity was added to the sample to make it more interesting. In this case I've dockerized the application using docker compose, and seeded some documents inside the database collection.
If you run the application locally using docker compose, you will have the MongoDB image loaded and seeded, ready to use for CRUD operations.


## Requirements

- **.NET SDK**: The tutorial is compatible with ASP.NET Core 8.0. Ensure you have the .NET SDK installed for this version.
- **Visual Studio**: The tutorial instructions are provided for Visual Studio, with steps to create, run, and manage the project.
- **Docker Desktop**: Docker engine to run containers

## Project Setup

1. **Clone the Project**: Start by cloning the project repository or creating a new ASP.NET Core Web API project in Visual Studio.
2. **Configure MongoDB**: Ensure MongoDB is installed and running on your system. Update the application's `appsettings.json` file with the MongoDB connection string.
3. **Model Classes**: Create model classes that represent the data you wish to store in MongoDB. The tutorial uses a `Book` class as an example.
4. **Database Context**: Implement a database context class to handle the connection to MongoDB and operations on the database.
5. **CRUD Operations**: Implement controller actions to perform CRUD operations on the database using the MongoDB driver for .NET.
6. **Run the Application**: Finally, run the application in Visual Studio and test the CRUD operations through the provided API endpoints.
