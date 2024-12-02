## Naughts and Crosses Game

An interactive Naughts and Crosses game built with React, where two players can take turns to place their marks ("X" or "O") on a 3x3 grid, aiming to get three marks in a row, column, or diagonal to win.

---

## Project Screen Shot(s)
<img width="805" alt="NAC" src="https://github.com/user-attachments/assets/0d435318-4677-44bb-b9c3-066e48577378">


---

## Features

- **Dynamic Player Names**: Players can change their names by clicking on their respective symbols ("X" or "O").
- **Active Player Highlighting**: The current active player is visually highlighted.
- **Game Turns Log**: A log displays all the moves made during the game.
- **Game Over & Draw Detection**: The game announces the winner or displays a draw message when the game ends.
- **Restart Functionality**: After a win or draw, the game can be restarted for a new round.
- **Fully Responsive UI**: The game interface adapts to different screen sizes.

---

## Installation and Setup Instructions

1. Clone down this repository.
2. Navigate to the project folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
4. To run the application, use:
   ```bash
   npm start
5. open your browser and go to:
   ```bash
   http://localhost:3000

---

## Reflection

### Context
This project was built to practice handling state management in React, and I also wanted to implement a simple game logic to improve my understanding of React hooks and component design.

### What I Set Out to Build
I aimed to build a functional Naughts and Crosses game using React, focusing on applying core React concepts and software development principles. The project was designed to enhance my understanding of:

  - **Component-based Architecture**: Breaking the game into reusable components like `Player`, `GameBoard`, and `Log` for better organization and maintainability.
  
  - **State Management**: Using React's `useState` to track the game’s state, including the active player, game board, and move history.
  
  - **Conditional Rendering**: Dynamically showing different components based on game state, such as displaying the winner or draw and allowing for game restarts.
  
  - **Event Handling**: Managing user interactions for turn-based gameplay, ensuring only valid moves were made.
  
  - **Game Logic**: Implementing win conditions and draw logic to end the game properly and determine the winner.

  - **UI/UX Design**: Focusing on a clean, user-friendly interface that’s responsive across devices, making the game intuitive to play.


### Challenges
One of the main challenges I encountered was managing the game board state and determining the active player after each move. I implemented a `deriveActivePlayer` function to alternate between players after each turn. Another challenge was detecting the winning condition across multiple possible combinations in a 3x3 grid.

### Why Custom Functions
I used custom logic (e.g., `deriveActivePlayer`) for alternating players and managing turns rather than relying on pre-built libraries to keep the code simple and reusable.

## Libraries and Frameworks Used

- **React**: Used to build the interactive user interface and manage the state of the game.
- **React Hooks**: For state management (useState) and handling component lifecycle.
- **CSS**: Custom styles are used to build the game interface and layout.
