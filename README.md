# ProjectGhost

> Demo for the 87650 session

ProjectGhost is a web application built with ASP.NET Core. It includes a main application and a test project for unit testing.

## Project Structure

- `ProjectGhost/` - Main ASP.NET Core web application
  - `Pages/` - Razor Pages for the web UI
  - `wwwroot/` - Static files (CSS, JS, images)
  - `appsettings.json` - Application configuration
  - `Program.cs` - Application entry point
- `ProjectGhost.Test/` - Unit test project

## Getting Started

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

### Build and Run

1. Restore dependencies:
   ```sh
   dotnet restore
   ```
1. Build the solution:
   ```sh
   dotnet build
   ```
1. Run the web application:
   ```sh
   dotnet run --project ProjectGhost/ProjectGhost.csproj
   ```

### Running Tests

To run the unit tests:
```sh
dotnet test ProjectGhost.Test/ProjectGhost.Test.csproj
```

## Project Layout

```
ProjectGhost/
  Pages/           # Razor Pages
  wwwroot/         # Static files
  Program.cs       # Entry point
  ...
ProjectGhost.Test/ # Test project
```

## Continuous Integration

This project uses GitHub Actions for CI. See `.github/workflows/project-ghost.yml` for details.

## License

This project is licensed under the MIT License.
