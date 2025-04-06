# Chess Academy Management System

A simple Java console application for managing chess players and tournaments, designed for chess academies and clubs.

## Features

- **User Authentication System**: Secure login with different access levels (admin/regular)
- **Player Management**:
  - Add new players with personal details and ratings
  - Display complete player roster
  - Search for specific players by registration number
- **Tournament Management**:
  - Create and schedule new tournaments
  - View all upcoming and past tournaments
  - Search for tournaments by name
- **Access Control**: Admin and regular user roles with appropriate permissions
- **Data Persistence**: Player and tournament data saved to files for persistent storage

## System Requirements

- Java Runtime Environment (JRE) 8 or higher
- 50MB of disk space

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Anuja-jayasinghe/ChessAcademySystem_Java.git
   ```

2. Navigate to the project directory:
   ```
   cd chess-academy
   ```

3. Compile the Java file:
   ```
   javac chessAcademy.java
   ```

4. Run the application:
   ```
   java chessAcademy
   ```

## Usage

### Default Login Credentials

- **Admin Access**:
  - Username: `admin`
  - Password: `admin123`

- **Regular User Access**:
  - Username: `ChessAcademy`
  - Password: `password123`

### Admin Features

- Add new players to the system
- View all players
- Search for specific players
- Create new tournaments
- View all tournaments
- Search for tournaments

### Regular User Features

- View all players
- View all tournaments
- Search for tournaments

## Data Format

### Player Data
Players are stored in `data.txt` with the following format:
```
RegNumber,FirstName,LastName,DateOfBirth,Rating
```

### Tournament Data
Tournaments are stored in `tournaments.txt` with the following format:
```
TournamentName,Date,Location
```

## Future Enhancements

- Player statistics tracking
- Tournament results and standings
- User registration system
- Rating calculation based on tournament performance
- GUI implementation


## Author

© Anuja Jayasinghe
