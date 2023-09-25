# Chat With Multiple PDFs 

A Streamlit web application that allows you to chat with a model using questions related to multiple PDF documents. This application utilizes natural language processing (NLP) and document retrieval to provide answers to user queries.

## Getting Started

### Prerequisites

Before running the application, make sure you have the necessary dependencies installed. You can install them using `pip`:

```bash
pip install streamlit python-dotenv PyPDF2 langchain streamlit_embedcode
Running the Application
To run the application, use the following command:

bash
Copy code
streamlit run app.py
This will start the Streamlit app, and you can access it in your web browser.

How It Works
Upload PDF Documents:

Click on the "Your documents" section in the sidebar.
Upload one or more PDF documents that you want to extract text from and ask questions about.
Ask a Question:

In the main application section, you can type a question related to the uploaded documents in the text input field.
Get Answers:

After asking a question, the application will provide answers based on the content of the PDF documents.
The responses will be displayed as a conversation between the user and the model.
Conversation History:

The conversation history is maintained, allowing you to continue the conversation with follow-up questions.
Application Components
PDF Text Extraction: The application extracts text content from the uploaded PDF documents using the PyPDF2 library.

Text Chunking: The extracted text is divided into smaller chunks to facilitate processing.

Text Embeddings: The chunks of text are encoded into vector representations using OpenAI embeddings.

Conversational Retrieval: A conversational retrieval chain is created using Langchain, enabling the model to answer user questions based on the embedded text.

Dependencies
Streamlit: For creating the web application interface.
python-dotenv: For loading environment variables from a .env file.
PyPDF2: For extracting text from PDF documents.
Langchain: For text splitting, embeddings, vector storage, and conversation management.
Acknowledgments
This application leverages various libraries and tools to enable document-based conversational interactions. Special thanks to the developers of Streamlit, PyPDF2, and Langchain for their contributions.

License
This project is licensed under the MIT License - see the LICENSE file for details.

vbnet
Copy code

You can copy and paste this README into your GitHub repository's README.md file. Don't forget to include relevant license and usage information in your project repository.



