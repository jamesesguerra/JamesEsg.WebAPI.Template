# JamesEsg.WebAPI.Template

A lightweight .NET Web API project template with sensible defaults to speed up API development.  

---

## Features

- **Centralized exception handling**
  - Catches all unhandled exceptions in the pipeline.
  - Returns a consistent JSON error response with `camelCase` properties.
  - Displays detailed stack traces in **Development**.
  - Shows generic error details in **Production**.

- **Customizable response format**
  - Uses an `ApiException` model for structured error messages.
  - Easy to extend for logging or custom error codes.

---

## Getting Started

### 1. Create a new project from this template
```bash
dotnet new install ./JamesEsg.WebAPI.Template
dotnet new jamesesg-webapi -n MyApi
```

### 2. Run the API
```bash
cd MyApi
dotnet run
```
