# Miss_Tempest 🌩️

**Miss_Tempest** is a 2D pixel art platformer game where players navigate through challenges, fight bosses, and compete on a dynamic scoreboard. Built with a custom-made set of pixel art sprites and a seamless backend in PHP, this game is hosted on a MySQL database with email notifications for key events like high scores.

## 🌐 Live Demo

Check out the live demo: [Miss_Tempest Live Demo](https://danielmarkus.web.elte.hu/Miss_Tempest/)

## 🧰 Tech Stack

### Frontend
- **HTML5 Canvas**: Custom 2D game rendering on a canvas
- **JavaScript**: Core game logic and user interactions
- **CSS**: Styling for game interface (minimalist and clean design)

### Backend
- **PHP**: Server-side logic and game state management
- **MySQL**: Database for player data, high scores, and game states

### Features

- 🎮 **2D Platformer Gameplay**: Custom pixel art sprites for a nostalgic platformer experience.
- 🏆 **Scoreboard**: Real-time display of player scores and high-score leaderboards.
- ⚔️ **Boss Fights**: Challenge yourself in epic boss battles at the end of each level.
- 📧 **Email Notifications**: Automated email updates when players achieve high scores or complete significant milestones.
- 💾 **MySQL Database**: Store player data and scores securely with persistent game state.
### Screenshots

Here are some screenshots from the game:

![Miss_Tempest Screenshot 1](https://pbs.twimg.com/media/GST5mtJXkAAzN4b?format=jpg&name=medium)

![Miss_Tempest Screenshot 2](https://pbs.twimg.com/media/GVGahb7W4AAsXH4?format=png&name=900x900)


### Video Demo

Check out a gameplay video on X (formerly Twitter):

[Miss_Tempest Gameplay Video](https://x.com/DashDrayme/status/1812208462442500308)


## 📦 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/DraymeM/Miss_Tempest.git
cd Miss_Tempest
```
### 2. 2. Set up the database

### 3. Set up the backend (PHP)

    Ensure you have a PHP server (e.g., XAMPP or LAMP stack) running.

    Modify the config.php file to add your MySQL credentials.
```php
<?php
$servername = "localhost";
$username = "root"; // Your MySQL username
$password = ""; // Your MySQL password
$dbname = "miss_tempest";

// Create connection
$conn = new mysqli($servername, $username, $password, $dbname);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
```

🧑‍💻 Author
- DraymeM – Frontend and Backend Developer, Game Design, Art and Animations.
## 🙌 Acknowledgments
- **Custom Pixel Art**: All pixel art for the game was created by myself, including the characters, environments, and animations.
- Game logic influenced by classic 2D platformers.
- Special thanks to the MySQL, PHP, and JavaScript communities for their resources.

