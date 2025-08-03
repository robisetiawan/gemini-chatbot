# Laravel Chatbot with Gemini AI

This project is an example of a simple chatbot implementation powered by the Gemini AI model. The chatbot is designed to function as an expert assistant for the Laravel framework, with a persona modeled after Taylor Otwell, the creator of Laravel.

### AI Model Used

This chatbot is built using Google's **gemini-2.5-flash** model. This model was chosen for its advanced capabilities in context understanding, reasoning, and efficiency in answering specific questions, making it ideal for the role of a technical assistant.

### The Role of AI in This Chatbot

The primary role of the AI in this chatbot is as a **Laravel expert consultant**. Through the defined `systemInstruction`, the AI is trained to:

* Act as **Taylor Otwell**, the creator of Laravel.
* Answer all questions about the Laravel framework.
* Help solve problems and errors in Laravel code.
* Provide accurate, concise, and direct solutions.
* Politely decline questions that are outside the context of Laravel and redirect the conversation back to the relevant topic.

With this role, the chatbot can provide focused and valuable support for Laravel developers.

### Installation

Follow the steps below to run the project locally.

#### Prerequisites

Make sure you have installed:

* Node.js and npm
* A Gemini API key (can be obtained from Google AI Studio)

#### Steps

1.  **Clone this repository**:
    ```bash
    git clone https://github.com/robisetiawan/gemini-chatbot.git
    cd gemini-chatbot
    ```

2.  **Install Node.js dependencies**:
    ```bash
    npm install
    ```

3.  **Create a configuration file**:
    Create a `.env` file in the root directory and add your Gemini API key, which you can get from https://aistudio.google.com :
    ```
    GEMINI_API_KEY=YOUR_API_KEY
    ```

4.  **Run the application**:
    ```bash
    node index.js
    ```
    The application will run on `http://localhost:3000`. You can test the `/chat` endpoint by sending a POST request containing a user's message.
