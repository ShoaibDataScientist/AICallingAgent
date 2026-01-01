# AI Calling Agent using twilio and openai

The AI Calling Agent is an innovative solution designed to automate both inbound and outbound calling processes, currently tailored as a mental health consultant. This project leverages a combination of cutting-edge technologies including Twilio for call handling, OpenAI for intelligent conversation, Pinecone for vector database services, and MongoDB for data persistence.

## Features

- **Inbound and Outbound Calls:** Handles both incoming and outgoing calls efficiently using Twilio.
- **AI-Powered Conversations:** Integrates OpenAI to provide responsive and context-aware interactions.
- **Data Handling:** Utilizes MongoDB for robust data management and Pinecone for querying capabilities.
- **Real-Time Response:** Employs Text-to-Speech (TTS) and Speech-to-Text (STT) for real-time communication.

## Usage

After starting the server, the application will be available on `http://localhost:5000/`. Use the following endpoints to interact with the AI calling agent:

- **GET /** - Test the connection and retrieve API status.
- **POST /voice** - Handle incoming calls.
- **GET /make_call?phone_number=+1234567890** - Initiate an outbound call to the specified number.
- **POST /handle_speech** - Process user speech from an ongoing call.

