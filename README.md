# GameStore

GameStore is a full-stack application that allows users to manage a catalog of games. It consists of a frontend for user interaction and a backend that handles data and API requests.

## Features

### Frontend

- Allows users to add games to the catalog.
- Users can select the genre of each game.
- Users can set the price and release date of the game.
- Runs using the command:
  ```sh
  dotnet watch
  ```

### Backend

- Contains models representing games and genres.
- Provides APIs to control different UI buttons and handle game-related operations.
- Uses SQLite as the database.
- Runs using the command:
  ```sh
  dotnet run
  ```

## Tech Stack

- **Frontend:** ASP.NET Core Blazor / Razor Pages
- **Backend:** ASP.NET Core Web API
- **Database:** SQLite
- **Development Tools:** .NET CLI

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/GameStore.git
   cd GameStore
   ```
2. Navigate to the backend folder and run the backend server:
   ```sh
   cd GameStore.Api
   dotnet run
   ```
3. Open a new terminal, navigate to the frontend folder, and start the frontend:
   ```sh
   cd GameStore.Frontend
   dotnet watch
   ```
4. Access the application via your browser at `http://localhost:5000` (or as specified in your configuration).

## Database Setup

- The application uses SQLite as the database.
- Ensure you have Entity Framework Core installed.
- To apply migrations and update the database, run:
  ```sh
  dotnet ef database update
  ```

## API Endpoints

- **GET** `/api/games` - Retrieve all games
- **POST** `/api/games` - Add a new game
- **PUT** `/api/games/{id}` - Update game details
- **DELETE** `/api/games/{id}` - Remove a game

## Contributing

1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your fork.
5. Create a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries, feel free to reach out via email at `your-email@example.com`.
