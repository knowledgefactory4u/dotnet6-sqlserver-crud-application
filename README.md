# Build REST CRUD APIs with .Net 6 and Microsoft SQL Server

# Local Setup and Run the application

<h2>Create database and table</h2>

```CREATE DATABASE testdb;```
```
CREATE TABLE users (
  id              INT           NOT NULL    IDENTITY    PRIMARY KEY,
  first_name      VARCHAR(100)  NOT NULL,
  last_name       VARCHAR(100),
  email           VARCHAR(100)  NOT NULL,
);
```

Download or clone the source code from GitHub to the local machine


You can start the api by running ```dotnet run``` from the command line in the project root folder (where the WebApi.csproj file is located)

OR

You can also start the application in debug mode in Visula Studio by opening the project root folder in Visual Studio and pressing F5 or by selecting Debug -> Start Debugging from the top menu, running in debug mode.
