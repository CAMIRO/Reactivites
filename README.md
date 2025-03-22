# Reactivities

Reactivities is a full-stack application built with ASP.NET Core for the backend and React.js for the frontend (to be added in the future).

## Project Structure

```
Reactivities.sln
API/
  Controllers/
  Properties/
  appsettings.json
  Program.cs
Application/
Domain/
Persistence/
```

### Backend
- **API**: ASP.NET Core Web API project.
- **Application**: Contains business logic.
- **Domain**: Contains domain models.
- **Persistence**: Handles database access.

### Frontend
- React.js (to be added).

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (for React.js in the future)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/CAMIRO/Reactivites.git
   cd reactivities
   ```

2. Build and run the backend:
   ```bash
   cd API
   dotnet run
   ```

3. Build and run the frontend:
   ```bash
   cd client
   npm install
   npm start
   ```

4. Open the browser and navigate to `http://localhost:3000/` to view the application.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
