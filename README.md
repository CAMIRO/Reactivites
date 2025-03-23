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
client/ (to be added for React.js frontend)
```

### Backend
- **API**: ASP.NET Core Web API project.
- **Application**: Contains business logic.
- **Domain**: Contains domain models.
- **Persistence**: Handles database access.

### Frontend
- **React.js**: (to be added).

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (for the backend)
- [Node.js](https://nodejs.org/) (for the React.js frontend)

## Getting Started

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/CAMIRO/Reactivites.git
   cd reactivities
   ```

2. Navigate to the `API` directory:
   ```bash
   cd API
   ```

3. Run the backend:
   ```bash
   dotnet run
   ```

### Frontend Setup (React.js)

1. Navigate to the `client` directory (to be added in the future):
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:3000/
   ```

## Features

- **Backend**:
  - RESTful API built with ASP.NET Core.
  - Database integration using Entity Framework Core with SQLite.
  - Automatic database migrations and seeding.

- **Frontend** (to be added):
  - React.js for building a responsive and interactive user interface.
  - State management using Redux or Context API (planned).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
