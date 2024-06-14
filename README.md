# Color Catcher

Color Catcher is an interactive web-based game where players must click on appearing colored circles to score points. The game includes power-ups that add time or extra points, and the objective is to score as many points as possible before time runs out. High scores are saved using `localStorage`.

## Table of Contents
- [Color Catcher](#color-catcher)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Screenshots](#screenshots)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Game Mechanics](#game-mechanics)
    - [Power-Ups](#power-ups)
    - [Difficulty Levels](#difficulty-levels)
  - [Built With](#built-with)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Features
- Simple and intuitive gameplay.
- Randomly appearing colored circles and power-ups.
- Dynamic difficulty adjustment based on remaining time.
- High score saving using browser's `localStorage`.
- Responsive design suitable for various devices.

## Screenshots
![Game Start Menu](https://imgur.com/a/Sr9038l)
![In-Game Screenshot](https://source.unsplash.com/random/800x600?gameplay)

## Getting Started

### Prerequisites
To run this game locally, you need a web browser that supports HTML5, CSS3, and JavaScript.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/color-catcher.git
   ```
2. Navigate to the project directory:
   ```bash
   cd color-catcher
   ```
3. Open `index.html` in your preferred web browser.

## Play using netlify

![Follow this link](https://666be45b30c6602e6f6b3ab2--calm-paletas-d79b6f.netlify.app/)

## Usage
- Click the "Start" button to begin the game.
- Click on the appearing circles to earn points.
- Avoid letting circles disappear to keep the game going.
- Look out for power-ups to boost your score or extend your time.
- Try to beat your high score!

## Game Mechanics
- The game starts with a timer set to 15 seconds.
- Circles appear randomly within the game container.
- Clicking on circles increases the score.
- If a power-up appears, it provides either extra points or additional time when clicked.

### Power-Ups
- **Extra Time**: Adds 2 seconds to the timer.
- **Bonus Points**: Adds 2 points to the score.

### Difficulty Levels
- The game difficulty adjusts dynamically:
  - When time is between 10 and 5 seconds, circles appear more frequently.
  - When time is less than 5 seconds, circle size increases and appearance slows down to increase difficulty.

## Built With
- HTML5
- CSS3
- JavaScript

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Google Fonts](https://fonts.google.com/) for the Roboto font.
- [Unsplash](https://unsplash.com/) for placeholder images.
