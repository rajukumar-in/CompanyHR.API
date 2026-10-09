# Company HR Web API

A robust RESTful Web API designed for employee data management. This project demonstrates the implementation of full CRUD endpoints using the Entity Framework Core Database-First approach.

## Core Technologies
- **Backend Framework:** C# and ASP.NET Core Web API (.NET 8.0 )
- **Database ORM:** Entity Framework Core (EF Core)
- **Database Engine:** SQL Server Database (SSMS)
- **API Documentation & Testing:** Swagger UI

## Core Backend Features
- **Database-First Reverse Engineering:** Auto-generated C# data models and DbContext directly from the SQL Server schema using `Scaffold-DbContext`.
- **Full Async CRUD Endpoints:** Implementation of asynchronous actions (`GET`, `POST`, `PUT`, `DELETE`) using `async/await` and `ToListAsync()`.
- **Dependency Injection:** Registered `CompanyHrbdContext` within `Program.cs` for smooth database operations.
- **RESTful Routing:** Managed standard routing patterns using `[Route("api/[controller]")]`.

## Setup Instructions
1. Open the project in Visual Studio 2022.
2. Ensure the 'CompanyHRBD' database is running in your local SQL Server.
3. Update the connection string in appsettings.json.
4. Run the project (F5) to open the Swagger UI dashboard and test the endpoints.
