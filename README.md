# 🌌 Website Explorer AI

### AI-Powered Website Analysis Using RAG and Semantic Search

## 📌 Project Description

Website Explorer AI is an AI-powered web application that extracts information from a public website URL, generates summaries, and answers user questions based on the website content.

It uses Retrieval-Augmented Generation (RAG), semantic search, vector embeddings, and FAISS to retrieve relevant information and generate meaningful answers. The application features a modern midnight blue and cyan user interface built with Gradio.

## 🚀 Features

- Website content extraction
- Automatic website summarization
- Semantic search based on meaning and context
- AI-powered question answering
- Retrieval-Augmented Generation (RAG)
- Text splitting and embedding generation
- FAISS vector database for similarity search
- Display of extracted website content
- Display of retrieved context
- Interactive Gradio interface
- Midnight blue and cyan theme

## 🛠️ Technologies Used

- Python
- Gradio
- Groq API
- LangChain
- Hugging Face
- Sentence Transformers
- FAISS
- BeautifulSoup
- Requests

## 🧠 How It Works

1. The user enters a public website URL.
2. Requests retrieves the webpage HTML.
3. BeautifulSoup extracts the readable website content.
4. The extracted text is divided into smaller chunks.
5. Hugging Face embeddings convert the text into numerical vectors.
6. FAISS stores the vectors and enables similarity search.
7. Groq generates an AI-powered summary of the website.
8. The user asks questions about the analyzed webpage.
9. Semantic search retrieves the most relevant text chunks.
10. The language model uses the retrieved context to generate an answer.

## 🔍 Semantic Search

Semantic search finds information based on meaning rather than matching only exact keywords.

**Example:**

- Search question: "How can I save money?"
- Website content: "Tips to reduce monthly expenses."

The system can identify the related content because the two sentences express similar ideas.

## 📚 Retrieval-Augmented Generation (RAG)

RAG combines information retrieval with text generation.

In this project, FAISS retrieves relevant website content, and the Groq language model uses that content to answer the user's question.

This helps ground answers in the analyzed webpage rather than relying only on the model's general knowledge.

## 💻 Installation

Install the required Python libraries:

```bash
pip install gradio requests beautifulsoup4 langchain-groq langchain-core langchain-text-splitters langchain-huggingface langchain-community faiss-cpu sentence-transformers
```

## 🔑 API Configuration

A Groq API key is required to generate summaries and answers.

The application prompts the user to enter the API key when it starts.

**Security:** Do not upload your API key or other secrets to your GitHub repository.

## ▶️ How to Run

1. Save the Python code in a file named `app.py`.
2. Install all required dependencies.
3. Enter your Groq API key when prompted.
4. Run the Python application.
5. Enter a public website URL.
6. Click **Analyze Website**.
7. Read the generated summary and extracted details.
8. Enter a question and click **Get Answer**.

## 📁 Project Structure

```text
Website-Explorer-AI/
│
├── app.py
├── README.md
└── requirements.txt
```

## ⚠️ Limitations

- Some websites block automated access.
- Websites that require JavaScript may not expose all their content.
- Answers depend on the available website text and retrieved context.
- The application analyzes the submitted webpage rather than crawling the entire website.
- AI-generated answers may occasionally contain errors.

## 🔮 Future Enhancements

- PDF document analysis
- Multiple webpage analysis
- Chat history
- Multilingual support
- Downloadable summaries
- Improved source citations
- Support for JavaScript-rendered webpages

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Artificial Intelligence
- Natural Language Processing
- Semantic Search
- Retrieval-Augmented Generation
- Vector Embeddings
- Vector Database Management
- Web Scraping
- Large Language Model Integration
- Interactive AI Application Development

## 👩‍💻 Author

**Name:** Your Name

## 📄 License

This project is developed for educational and learning purposes.
