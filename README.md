# TodoApi - Web API with ASP.NET Core

This project demonstrates building a simple web API using ASP.NET Core. It includes endpoints for managing to-do items.

## API Endpoints

### Get all to-do items

- **Endpoint**: `GET /api/todoitems`
  - Retrieves a list of all to-do items.

### Get a specific to-do item by ID

- **Endpoint**: `GET /api/todoitems/{id}`
  - Retrieves a specific to-do item by its unique ID.

### Add a new to-do item

- **Endpoint**: `POST /api/todoitems`
  - Adds a new to-do item.

### Update an existing to-do item

- **Endpoint**: `PUT /api/todoitems/{id}`
  - Updates an existing to-do item.

### Delete a to-do item

- **Endpoint**: `DELETE /api/todoitems/{id}`
  - Deletes a specific to-do item.

## Prerequisites

- Visual Studio 2022 Preview with the ASP.NET and web development workload.
- .NET 8.0 (Long Term Support)

## Getting Started

Create a new project in Visual Studio:

1. Select `New > Project`.
2. Search for “Web API” and choose the ASP.NET Core Web API template.
3. Name the project “TodoApi” and confirm the framework is .NET 8.0.
4. Enable controllers and OpenAPI support.
5. Select `Create`.

Add the required NuGet package:

- Install “Microsoft.EntityFrameworkCore.InMemory” package.

Test the project:

- Press `Ctrl+F5` to run without the debugger.
- Access Swagger at `https://localhost:<port>/swagger/index.html`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
