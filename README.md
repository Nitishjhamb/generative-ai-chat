# Google Generative AI Chat Application

This project demonstrates a simple chat application using **Google Generative AI**. It includes two components:
1. **Command-Line Chat (index.js)**: A command-line interface that allows users to interact with Google Generative AI in real-time.
2. **Web-Based Chat Server (server.js)**: A web server that serves an HTML page for users to interact with the AI through a browser.

## Features
- **Command-Line Interface** (CLI): Real-time AI chat in the terminal.
- **Web Interface**: Users can interact with the AI via a web browser.
- **Safety Settings**: Prevents harmful content like harassment, hate speech, explicit content, and dangerous content.
- **AI Configuration**: Control AI response behavior using parameters like `temperature`, `topK`, `topP`, and `maxOutputTokens`.

## Installation

### Prerequisites
- Node.js installed
- Google Generative AI API Key (You can obtain it from Google Cloud).

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/generative-ai-chat.git
   cd generative-ai-chat
2. Install the required dependencies:

npm install

3.Update your API Key and Model Name in both index.js and server.js:

const API_KEY = "//enter-your-Api-key";
const MODEL_NAME = "// Example Ai-Model"; // Example: "gemini-1.0-pro"
