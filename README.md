# PDF Chatting DeepSeek-R1

The DeepSeek API and local Ollama LLM provide a powerful way to build AI chatbots that can process documents and answer queries efficiently. 
By running the model locally, you ensure greater control over data privacy and reduce dependency on cloud services. 
Whether you’re building an AI assistant for research, education, or business applications, this setup offers a great starting point.


# Setting Up the AI Chatbot Locally with Ollama LLM

## Install Required Dependencies

Before running the code,

To download and use DeepSeek-R1 locally with Ollama, run the following command:

<code> ollama pull deepseek-r1 </code>

This will download the DeepSeek-R1 model onto your local machine for use with Ollama.

And then install the necessary Python libraries using the following command:

<code> pip install streamlit langchain_community langchain_text_splitters langchain_core langchain_ollama pdfplumber </code>

## Running the Chatbot

To launch the chatbot application, run the following command:

<code> streamlit run rag_chat.py </code>

This will open a local web interface where users can upload PDFs and ask questions based on the document content.

# Output

![image](https://github.com/user-attachments/assets/ec315d79-7d17-496b-b605-1202ac63aea1)

![image](https://github.com/user-attachments/assets/b5f8fcca-beb5-4cd8-a9dd-aad9dfc53f6d)

