# ```Gemini Chat Application```

## Index
1. [Project Overview](#project-overview)
2. [Folder Structure](#folder-structure)
3. [File Descriptions](#file-descriptions)
    - [Root Files](#root-files)
    - [Source Folder](#source-folder)
    - [Components Folder](#components-folder)
    - [Config Folder](#config-folder)
    - [Context Folder](#context-folder)
4. [Running the Project](#running-the-project)

## Project Overview
The Gemini Chat Application is a React-based web application that interacts with Google's Generative AI API to provide conversational AI features. The app consists of a sidebar for navigation and a main area for displaying chat results.

## Folder Structure
Below is the structure of the project's files and folders:
```
GeminiChatApp/
│
├── public/
│
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Main.jsx
│   │   ├── Sidebar.jsx
│   │   ├── Main.css
│   │   ├── Sidebar.css
│   ├── config/
│   │   └── gemini.js
│   ├── context/
│   │   └── Context.jsx
│   ├── App.jsx
│   └── index.js
│
├── package.json
│
└── README.md
```

## File Descriptions

### Root Files
- package.json: This file contains metadata about the project and its dependencies, including scripts to run the project.

### Source Folder
- src/: The main source folder containing all the application code.

### Components Folder
- Main.jsx: This file defines the Main component which contains the main chat interface, displaying results or prompt suggestions.
- Sidebar.jsx: This file defines the Sidebar component which provides navigation and displays recent prompts.
- Main.css: This file contains the CSS styles for the Main component.
- Sidebar.css: This file contains the CSS styles for the Sidebar component.

### Config Folder
- gemini.js: This file contains the configuration for interacting with the Google Generative AI API. It includes API keys and functions for sending prompts and receiving responses.

### Context Folder
- Context.jsx: This file defines a context for managing global state across the application, such as user inputs, recent prompts, and results.

### App.jsx
- App.jsx: This file is the entry point of the application. It sets up the Sidebar and Main components.

### index.js
- index.js: This file renders the App component into the DOM.

## Running the Project

### Prerequisites
- Node.js and npm installed on your machine.

### Steps
1. Clone the Repository:
   ```sh
   git clone <repository-url>
   cd GeminiChatApp
   ```

2. Install Dependencies:
   ```sh
   npm install
   ```

3. Add API Key:
   Open the `src/config/gemini.js` file and replace the placeholder API key with your Google Generative AI API key.

4. Start the Development Server:
   ```sh
   npm start
   ```

5. Access the Application:
   Open your browser and navigate to `http://localhost:3000`.

By following these steps, you will be able to run and interact with the Gemini Chat Application.
