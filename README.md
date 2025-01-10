
# Java Final Project: Twitch Game

## Purpose of Project
This project is an interactive game designed for Twitch streamers to play with their viewers in real-time. The game allows viewers to participate by typing specific messages in the chat, and based on these inputs, the game tracks the frequency of different messages. At the end of the entry period, the game determines the most frequent message and displays it.

## Version and Date
**Version**: 0.0.1  
**Date**: 2025-01-10

## How to Start This Project
To start this project, follow the steps below:

1. **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/ChristianDenniss/twitch-game.git
    ```
   
2. **Install Java** if you haven't already. This project is built using Java, so ensure you have Java JDK 8 or above installed. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

3. **Open the project in your preferred IDE** (e.g., IntelliJ IDEA, Eclipse).

4. **Run the application**:
    - Make sure you replace the `OAUTH_TOKEN` and `NICKNAME` in the code with your own Twitch OAuth token and username.
    - Run the `TwitchChatProcessor` class.

5. **Start the game**:
    - The application will prompt you to enter a Twitch channel name.
    - Press "Start Entry Period" to begin collecting messages from the chat.
    - Viewers can send messages "1", "2", "3", or "4" in the Twitch chat.
    - After 15 seconds, the game will display the most frequent message and highlight the result.

## Authors
- **Christian Dennis**

## User Instructions
1. Open the game interface.
2. Enter the Twitch channel name you want to use (e.g., your own Twitch channel).
3. Press "Start Entry Period" to begin the game.
4. During the entry period (15 seconds), viewers can send messages "1", "2", "3", or "4" in the chat.
5. After the entry period ends, the game will display the message that was sent most frequently by viewers.
6. The interface will color-code the results based on their rank (Gold for the highest, Silver for second, etc.).
