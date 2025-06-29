# RightHomeAI – Dynamic AI Chatflow

RightHomeAI is an intelligent real estate chatbot interface built with **React.js**, **JavaScript**, and **Tailwind CSS**. It allows users to interact with an AI-powered assistant to find property recommendations based on their needs. The chatbot integrates with **ChatGPT (OpenAI)** for natural language conversations and fetches **real property listings** from a database of scraped listings, presenting them in a highly personalized and user-friendly way.

## 🧠 Features

- **ChatGPT-Powered AI Assistant**  
  Engage users in dynamic, natural conversations to understand their preferences.

- **Real-Time Property Listings**  
  Fetches actual real estate properties from our database (scraped data) and displays them based on user requirements.

- **Smart Property Suggestions**  
  GPT reformats and enhances the presentation of properties, making them more contextual and easier to browse.

- **Interactive Chat Suggestions**  
  When users start chatting, they get clickable suggestion buttons to continue the conversation with ease.

- **Modern UI**  
  Built using **React.js** and **Tailwind CSS** to deliver a clean, fast, and mobile-friendly user experience.

## 🔧 Tech Stack

- **Frontend**: React.js (JavaScript)
- **Styling**: Tailwind CSS
- **AI Integration**: OpenAI (ChatGPT API)
- **Backend (optional)**: Connects to a database with real, scraped property listings

## 🚀 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/righthomeai-chatflow.git
   cd righthomeai-chatflow

2. **Install dependecies**
   ```bash
   npm install

3. **Configure environment variables**
   Create a .env file and add your OpenAI API key and backend API URL:

   ```env
   VITE_OPENAI_API_KEY=your_openai_key
   VITE_BACKEND_API_URL=https://your-api-url.com

4. **Run the project**
   npm run dev
