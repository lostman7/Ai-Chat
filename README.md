# AI Chat Application

## Overview
This is an AI chat application that allows users to interact with a language model via a web interface. The application includes features such as:
- A chat window for displaying messages.
- Input field and send button for sending messages.
- Voice input toggle for speaking messages.
- Model status indicator showing whether the model is loaded.
- Memory usage indicator showing how much memory is being used.
- Text-to-speech functionality that can be toggled on or off.

## Setup

### Prerequisites
1. **Node.js**: Ensure you have Node.js installed on your machine.
2. **LM Studio**: Ensure LM Studio is running and accessible at `http://localhost:1234`.

### Steps to Run the Application

1. **Clone the Repository** (if not already done):
   ```sh
   git clone <repository-url>
   cd ai-chat-app
   ```

2. **Install Dependencies**:
   ```sh
   npm install --save-dev vite
   ```

3. **Start the Development Server**:
   ```sh
   npm run dev
   ```

4. **Open the Application**:
   - The application will be available at `http://localhost:3000` (or another port if specified).

## Features

### Chat Interface
- **Chat Window**: Displays messages sent by the user and responses from the AI.
- **Input Field**: Allows users to type messages.
- **Send Button**: Sends the typed message to the AI.
- **Voice Input Button**: Allows users to speak messages, which are then converted to text.

### Model Status Indicator
- Shows whether the model is loaded using a green or red dot:
  - Green: Model is loaded and ready for interaction.
  - Red: Model is not loaded.

### Memory Usage Indicator
- Displays the current memory usage and the maximum allowed memory (500MB).

### Text-to-Speech Toggle
- Allows users to enable or disable text-to-speech functionality.

## Notes
- Ensure that LM Studio is running and accessible at `http://localhost:1234` before starting the application.
- The application uses IndexedDB for long-term storage of chat logs when memory usage reaches 500MB.
