
# Chat with PDF using Gemini

## Abstract
This project is a Streamlit-based web app that allows users to upload PDF files and ask questions about the contents using Google's Gemini model for conversational AI. By processing the PDFs, it extracts text, divides it into manageable chunks, and stores it in a vector database. The app then allows users to ask detailed questions, retrieving relevant information from the uploaded PDFs using embeddings and a conversational AI model.

## Key Features
- **PDF Upload**: Users can upload multiple PDF files for processing.
- **Google Gemini Integration**: Uses Google's Gemini model for conversational AI to answer user questions.
- **FAISS Vector Store**: Efficiently stores and retrieves text chunks for similarity search.
- **Streamlit Interface**: Simple and interactive interface to chat with the uploaded PDFs.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/dineshramv13/PDF-ChatBot-with-GEMINI-AI
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
3. Set up environment variables:

   Create a .env file and add your Google API key:
   ```bash
   GOOGLE_API_KEY=your_google_api_key

4. Run the Streamlit app:
   ```bash
   streamlit run app.py

## **How It Works**
- Upload PDF files using the sidebar.
- The app extracts text from the PDFs, splits it into chunks, and stores them in a FAISS vector store using Google Generative AI embeddings.
- Users can ask questions about the content of the PDFs.
- The app retrieves relevant chunks using similarity search and answers the questions using the Google Gemini conversational AI model.

## **Future Enhancements**
- Improve the conversational experience by fine-tuning prompts and optimizing text chunking.
- Expand functionality to support additional document types beyond PDFs.
- Integrate real-time document updates and more advanced question-answering capabilities.
   

