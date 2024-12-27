# SparshGPT

SparshGPT is an AI-powered chat model that allows users to interact with a conversational agent based on OpenAI's GPT models. The project uses Streamlit for a simple web interface and integrates with OpenAI's API to generate responses based on user inputs.

This project is designed to allow users to quickly interact with an AI model in an easy-to-use web interface, making it ideal for personal projects or for showcasing GPT-based conversational agents.

---

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Project Description

SparshGPT provides an interface to interact with an AI chatbot powered by GPT-4. This app allows users to input text, which is sent to an AI model through OpenAI's API. The model responds with a generated answer, providing an engaging user experience.

The app also has a sidebar for easy navigation to the user's profiles on social media platforms like GitHub, LinkedIn, Instagram, and a link to a Discord server. The sidebar also includes a contact section with an email and phone number.

---

## Features

- **Interactive AI Chat**: Users can input a query, and SparshGPT will provide a response generated by OpenAI's GPT model.
- **Sidebar Navigation**: Access to social media profiles and email directly from the sidebar.
- **Responsive Layout**: Optimized layout for smooth interaction with the chatbot.
- **Customizable**: Simple to extend with new features or modify for personal use.

---

## Installation

To get started with SparshGPT on your local machine, follow these steps:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/sparshgpt.git
2. **Navigate to the project directory**:
   ```bash
   cd sparshgpt
3. **Install required dependencies: Make sure you have `pip` installed, then run:**
   ```bash
   pip install -r requirements.txt
4. **Set up environment variables: Create a `.env` file in the project directory to store your OpenAI API key:**
   ```bash
   touch .env
   ```
   In the `.env` file, add your OpenAI API key like this:
   ```makefile
   api_key = your_openai_api_key
   ```

---

## Usage

1. After installing the dependencies, run the Streamlit app:
   ```bash
   streamlit run app.py
2. The app will open in your default web browser, where you can interact with the AI model by entering a Query

---

## Deployment

Since ChatGPT is already deployed on **Streamlit Cloud**, you can access it through the following URL: 
[SparshGPT - Streamlit](https://sparshgpt.streamlit.app/)

## Technology Used

- **Streamlit**: Used for building the interactive web interface.
- **OpenAI GPT-4**: Powers the chatbot's natural language processing.
- **Python**: The primary programming language for the app
- **dotenv**: For managing environment variables securely.
- **Requests**: For making HTTP requests to interact with the OpenAI API.

---

