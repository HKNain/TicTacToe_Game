# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game implemented in C# using Windows Presentation Foundation (WPF). This project is a fun and interactive way to play the timeless game of Tic-Tac-Toe with a friend locally while showcasing the use of WPF for building desktop applications.

## Features

- **Two-player Mode**: Play locally with a friend.
- **Intuitive User Interface**: Easy-to-use WPF interface.
- **Real-time Game Updates**: Responsive game board that updates immediately upon player actions.
- **Win/Tie Detection**: Automatically detects wins and ties with a message display.
- **Replay Option**: Restart the game without closing the application.

## Technologies Used

- **Language**: C#
- **Framework**: Windows Presentation Foundation (WPF)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/tictactoe-wpf.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd tictactoe-wpf
   ```

3. **Open the project in Visual Studio:**
   - Ensure you have Visual Studio installed with the .NET desktop development workload.

4. **Build and run the application:**
   - Press `F5` or click on the "Start" button in Visual Studio to launch the application.

## How to Play

1. The game is played between two players:
   - Player X
   - Player O

2. The game starts with Player X making the first move.

3. Click on an empty cell in the grid to make your move.

4. The game ends when:
   - One player achieves three marks in a row (horizontally, vertically, or diagonally).
   - The board is full, resulting in a tie.

5. A message box will display the result. Use the replay option to start a new game.

## Project Structure

- **/TicTacToeApp**: Contains the main WPF application files.
  - `MainWindow.xaml`: UI layout and design.
  - `MainWindow.xaml.cs`: Code-behind for game logic and event handling.
- **/Assets**: Placeholder for assets like images or icons (if any).
- **/Properties**: Configuration and settings files.

## Future Enhancements

- Add single-player mode with AI.
- Implement online multiplayer mode.
- Add customizable themes and sound effects.
- Improve accessibility features.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your forked repository:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Inspiration from the classic game of Tic-Tac-Toe.
- Thanks to the WPF community for resources and guidance.

---
Feel free to reach out or open an issue if you have suggestions or feedback!

