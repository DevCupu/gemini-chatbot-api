# Gemini AI Chatbot

A simple, clean, and modern web-based chatbot application powered by Node.js and the Google Gemini API. This project provides a responsive chat interface where users can interact with Google's generative AI in real-time.

![Chatbot Screenshot](https://user-images.githubusercontent.com/your-username/your-repo/assets/screenshot.png) <!-- It's a good practice to add a screenshot of your app here -->

## ✨ Features

- **Modern UI**: Clean and responsive chat interface built with vanilla HTML, CSS, and JavaScript.
- **Real-time AI Interaction**: Get instant responses from the `gemini-1.5-flash` model.
- **Node.js Backend**: A lightweight and efficient backend server using Express.js.
- **Secure API Key Handling**: Uses `dotenv` to keep your Google Gemini API key safe and out of the source code.
- **Easy to Set Up**: Get the chatbot running locally with just a few commands.

## 🛠️ Technology Stack

- **Frontend**:
  - HTML5
  - CSS3
  - Vanilla JavaScript (with `fetch` for API calls)
- **Backend**:
  - Node.js
  - Express.js
- **AI**:
  - Google Gemini API (`@google/generative-ai`)
- **Environment**:
  - dotenv for environment variable management

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js (which includes npm) installed on your system.
- A **Google Gemini API Key**. You can get one from Google AI Studio.

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/gemini-chatbot-ai.git
    cd gemini-chatbot-ai
    ```

2.  **Install backend dependencies:**
    ```sh
    npm install
    ```

3.  **Set up your environment variables:**
    - Create a new file named `.env` in the root of your project directory.
    - Open the `.env` file and add your Google Gemini API key as follows:
      ```
      GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
      ```
    - Replace `"YOUR_GEMINI_API_KEY"` with your actual key.

4.  **Run the server:**
    ```sh
    node index.js
    ```

5.  **Open the application:**
    - Open your web browser and navigate to `http://localhost:3000`.
    - You should now see the chatbot interface and can start a conversation!

## 📁 Project Structure

```
gemini-chatbot-ai/
├── public/
│   ├── index.html      # Main HTML file for the chat interface
│   ├── script.js       # Frontend JavaScript for chat logic
│   └── style.css       # All styles for the application
├── .env                # Stores environment variables (API key)
├── index.js            # The main Express.js server file
├── package.json        # Project metadata and dependencies
└── README.md           # You are here!
```