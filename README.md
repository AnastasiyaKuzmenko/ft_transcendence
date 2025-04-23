# ft_transcendence
ft_transcendence is a full-stack single-page application (SPA) featuring a 3D ping pong game. This project was created as a group effort.

### Key features
- **User Authentication**: A secure login system with session management, game history tracking, and player statistics. You can add friends and view their profiles and game statistics.
- **Game Modes**: Includes Single Player, Local Multiplayer, and Tournament modes, with AI opponents available.
- 3D Graphics
- Security
- Responsive design
- API Integration

### Usage
1. Clone the repository
```bash
    ǵit clone https://github.com/AnastasiyaKuzmenko/ft_transcendence
`````

2. Create .env file to the root. Example:
```
    DATABASE_HOST='db'
    DATABASE_NAME='db_name'
    DATABASE_USER='db_user'
    DATABASE_PASSWORD='db_password'
    SECRET_KEY='secret_key'
    VITE_BACKEND_URL=http://backend:8000

```

2. Build the Docker images (if it's the first time you are setting up):

    ```bash
    docker-compose build
    ```
3. Start the app:
```bash
    docker-compose up
`````

4. The app will be accessible at:
```bash
    https://localhost:1443
`````

5. Close app with
```bash
    docker-compose down
`````
