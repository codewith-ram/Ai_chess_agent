# ♜ ChessMaster AI: Advanced Chess 

An advanced Chess game system featuring two AI chess engines competing against each other using Autogen in a Streamlit application. Built with robust move validation and game state management.

> **Note**: This project is an enhanced version of the original [Ai_chess_agent](https://github.com/codewith-ram/Ai_chess_agent) by [@codewith-ram](https://github.com/codewith-ram).

## Features

### Multi-Agent Architecture
- GrandMaster (White): Advanced strategic decision maker
- DeepThinker (Black): Tactical analysis expert
- Board Validator: Ensures move legality and maintains game state integrity

### Safety & Validation
- Robust move verification system
- Illegal move prevention
- Real-time board state monitoring
- Secure game progression control

### Strategic Gameplay
- AI-powered position evaluation
- Deep tactical analysis
- Dynamic strategy adaptation
- Complete chess ruleset implementation


## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- OpenAI API key
- Git (for cloning the repository)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/codewith-ram/Ai_chess_agent
``

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   This will install all necessary packages including:
   - streamlit
   - python-chess
   - autogen
   - openai

3. **Get your OpenAI API Key**:
   - Sign up at [OpenAI](https://platform.openai.com/)
   - Go to API Keys section and create a new secret key
   - Copy your API key (you'll need it in the next step)

## 🎮 How to Use

1. **Launch the application**:
   ```bash
   streamlit run ai_chess_agent.py
   ```

2. **Configure the game**:
   - Enter your OpenAI API key in the sidebar
   - Set the number of turns (5-10 is recommended for testing)
   - Click "Start Game" to begin

3. **Understanding the interface**:
   - The main window shows the current chess board
   - The sidebar contains configuration options
   - The game progress and agent moves are displayed in the terminal/console

4. **Game controls**:
   - **Start Game**: Begins a new game
   - **Reset Game**: Clears the current game and resets the board
   - **Max Turns**: Set how many moves each player will make before the game ends

## 🏆 Game Features

### Watching the AI Play
- The game features two AI players: GrandMaster (White) and DeepThinker (Black)
- Each AI will analyze the board and make strategic moves
- The game automatically alternates between the two players

### Understanding the Output
- In the terminal, you'll see the conversation between the AI agents
- Each move is validated before being executed
- The board updates automatically after each move
- Move history is displayed below the board

### Troubleshooting
- If you see an error about the API key, ensure it's correctly entered in the sidebar
- For connection issues, check your internet connection and OpenAI API status
- If the game freezes, try reducing the number of turns or restarting the application


