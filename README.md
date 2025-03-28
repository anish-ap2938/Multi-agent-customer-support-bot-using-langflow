# Multi-agent-customer-support-bot-using-langflow


# Customer Agent Chat using Langflow

This project provides an interactive customer support chat interface built with Streamlit. It leverages a Langflow-powered API to simulate a conversational agent that answers customer queries by tapping into pre-defined FAQ data and structured customer support information. The app is designed to deliver a smooth chat experience with conversation history, easy-to-use messaging, and clear instructions for users.

---

## Project Overview

- **Conversational AI Integration:**  
  Uses Langflow’s API to process user messages and return responses from a virtual customer support agent. The agent can answer FAQs, provide order details, and address common customer queries.

- **Interactive Web Interface:**  
  Built with Streamlit, the UI features a two-column layout: one for message input and one for displaying the chat history. The design is clean and responsive, suitable for desktop and mobile browsers.

- **Data-Driven Responses:**  
  The project includes supporting files such as CSVs for sample products and orders, a PDF containing company FAQs, and JSON files with customer support data. These assets help the agent provide accurate and contextually relevant answers.

- **Environment & Security:**  
  Environment variables (loaded via python-dotenv) securely store API tokens and configuration settings required to authenticate requests to the Langflow API.

- **Extensibility:**  
  The code is modular and designed for easy customization. Users can modify the API endpoint, update conversation logic, and adjust the UI as needed.

---
Langflow : 
![image](https://github.com/user-attachments/assets/39854ab9-cc84-4c95-a332-b25eea4f071d)

Application UI: 
![image](https://github.com/user-attachments/assets/48d8bcfd-7902-439f-8fa0-2d16f2a9b7ce)

Customization
API Endpoint & Token:
Modify the constants in main.py (e.g., BASE_API_URL, LANGFLOW_ID, FLOW_ID, APPLICATION_TOKEN, ENDPOINT) to point to a different Langflow instance or to update authentication credentials.

User Interface:
Update the Streamlit layout, sidebar instructions, and chat history formatting in main.py to tailor the user experience.

Supporting Data:
You can replace or update the sample CSV, PDF, and JSON files with your own data to further customize the responses provided by the agent.

Extending Functionality:
The project is modular and can be extended with additional features, such as saving conversation history to a database, adding more sophisticated NLP processing, or integrating with external CRM systems.
