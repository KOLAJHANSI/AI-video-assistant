# AI Video Assistant

An AI-powered RAG-based video assistant that transcribes meetings, summarizes them, extracts important information, and allows users to chat with meeting content.

## Features

- Accepts YouTube URLs and audio/video files
- Transcribes English using OpenAI Whisper
- Supports Hindi/Hinglish transcription using Sarvam AI
- Generates meeting summaries
- Extracts action items, owners, and deadlines
- Extracts key decisions
- Extracts open questions and follow-ups
- Chat with meeting content using RAG
- Uses ChromaDB as the vector database
- Export reports as PDF or TXT
- Simple Streamlit interface

## Tech Stack

- Python
- Streamlit
- LangChain
- OpenAI Whisper
- Sarvam AI
- Mistral AI
- ChromaDB
- Hugging Face Embeddings
- RAG (Retrieval-Augmented Generation)

## How It Works

1. Upload an audio/video file or provide a YouTube URL.
2. The application transcribes the meeting.
3. The transcript is divided into smaller chunks.
4. The chunks are converted into embeddings and stored in ChromaDB.
5. When the user asks a question, relevant chunks are retrieved from ChromaDB.
6. Mistral AI generates an answer using the retrieved context.

## Environment variables
create a .env file in the project folder
MISTRAL_API_KEY = your api key

## RUN
streamlit run app.py

## Deployment 
Deployed by Render
## link:https://ai-video-assistant-1-7zar.onrender.com

## Author
KOLA JHANSI








