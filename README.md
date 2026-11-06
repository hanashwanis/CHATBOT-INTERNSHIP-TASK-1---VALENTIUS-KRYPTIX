🤖 Gemini AI Chatbot

Overview

Gemini AI Chatbot is an intelligent, web-based conversational application powered by Google's Gemini API. It enables users to interact with an AI assistant through natural-language conversations while maintaining context across multiple messages.

The application provides a seamless chat experience with multi-conversation support, token-based context management, and persistent chat history.

✨ Key Features

- **AI-Powered Conversations:** Generates intelligent and informative responses using Google Gemini.
- **Multi-Turn Conversation Memory:** Retains previous messages to understand follow-up questions and maintain conversational context.
- **Token-Based Context Management:** Uses Gemini's token-counting API to monitor input size and manage conversation history efficiently.
- **Multiple Chat Sessions:** Allows users to create new conversations and switch between existing chats.
- **Persistent Chat History:** Stores conversations and messages in an SQLite database, preserving them even after application restarts.
- **Conversation Management:** Supports automatically generated chat titles and deletion of individual conversations.
- **Error Handling:** Handles API failures, temporary service unavailability, and quota-exceeded errors.

🛠️ Technology Stack

| Technology | Usage |
|---|---|
| Python | Backend development |
| Flask | Web application framework |
| Google Gemini API | AI-powered response generation |
| SQLite | Persistent conversation storage |
| HTML5 | Webpage structure |
| CSS3 | User interface styling |
| JavaScript | Frontend functionality |

⚙️ How It Works

1. Users enter messages through the web-based chat interface.
2. The Flask backend receives and processes the requests.
3. Previous conversation messages are retrieved from the SQLite database.
4. Token counting is used to manage the conversation context.
5. The prepared conversation is sent to the Gemini API.
6. Gemini generates a context-aware response.
7. Both user messages and AI responses are saved in SQLite.
8. The response is displayed in the chat interface.



🎯 Project Objective

The primary objective of this project is to develop a conversational AI application that goes beyond basic question-and-answer interactions by incorporating contextual understanding, conversation management, and persistent storage.

It demonstrates the practical integration of Generative AI APIs with full-stack web development and database management.

<img width="652" height="477" alt="image" src="https://github.com/user-attachments/assets/d39b01a7-874d-4cc8-ae71-2251b42b99ac" />

---

⭐ If you find this project useful, consider giving it a star!
