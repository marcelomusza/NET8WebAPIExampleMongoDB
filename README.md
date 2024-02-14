# ASP.NET Core with MongoDB Tutorial

This README provides an overview and essential requirements for running the ASP.NET Core project that integrates MongoDB, as described in the Microsoft Learning article: [Build a .NET web app with MongoDB](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-8.0&tabs=visual-studio).

## Purpose

The tutorial guides you through creating a web application using ASP.NET Core that performs CRUD operations on a MongoDB database. It demonstrates how to configure MongoDB, model entities in C#, and integrate MongoDB with an ASP.NET Core application to manage a list of books.

## Requirements

- **.NET SDK**: The tutorial is compatible with ASP.NET Core 8.0. Ensure you have the .NET SDK installed for this version.
- **Visual Studio**: The tutorial instructions are provided for Visual Studio, with steps to create, run, and manage the project.
- **MongoDB**: The application requires MongoDB to be installed and running. The tutorial uses MongoDB to store data about books, including titles, authors, and prices.

## Project Setup

1. **Clone the Project**: Start by cloning the project repository or creating a new ASP.NET Core Web API project in Visual Studio.
2. **Configure MongoDB**: Ensure MongoDB is installed and running on your system. Update the application's `appsettings.json` file with the MongoDB connection string.
3. **Model Classes**: Create model classes that represent the data you wish to store in MongoDB. The tutorial uses a `Book` class as an example.
4. **Database Context**: Implement a database context class to handle the connection to MongoDB and operations on the database.
5. **CRUD Operations**: Implement controller actions to perform CRUD operations on the database using the MongoDB driver for .NET.
6. **Run the Application**: Finally, run the application in Visual Studio and test the CRUD operations through the provided API endpoints.

## Additional Resources

For detailed steps, including code snippets and configuration details, refer to the [Microsoft Learning article](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-8.0&tabs=visual-studio).

## License

This README and the accompanying tutorial are subject to the terms and conditions of the Microsoft Learning documentation.
