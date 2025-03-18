# LangChain Search Engine Chat

A powerful search engine chat application built with LangChain, Streamlit, and Groq. This application combines multiple search tools (Arxiv, Wikipedia, and DuckDuckGo) to provide comprehensive answers to your questions.

## 🌟 Features

- Real-time chat interface using Streamlit
- Integration with multiple search tools:
  - Arxiv for academic papers
  - Wikipedia for general knowledge
  - DuckDuckGo for web search
- Powered by Groq's Llama3-8b-8192 model
- Streaming responses with real-time agent thoughts
- Secure API key management
- Beautiful and intuitive UI

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Search_Engine_LangChain.git
cd Search_Engine_LangChain
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your API keys:
```env
GROQ_API_KEY="your_groq_api_key"
LANGCHAIN_API_KEY="your_langchain_api_key"
LANGCHAIN_PROJECT="your_project_name"
```

### Running the Application

1. Start the Streamlit app:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the URL shown in the terminal (typically http://localhost:8501)

## 💡 Usage

1. Enter your question in the chat input field
2. The application will:
   - Search across multiple sources (Arxiv, Wikipedia, DuckDuckGo)
   - Process the information using the Groq LLM
   - Display the results in real-time
   - Show the agent's thought process

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) - For the web interface
- [LangChain](https://www.langchain.com/) - For building the search agent
- [Groq](https://groq.com/) - For the LLM backend
- [Arxiv](https://arxiv.org/) - For academic paper search
- [Wikipedia](https://www.wikipedia.org/) - For general knowledge
- [DuckDuckGo](https://duckduckgo.com/) - For web search

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 👤 Author

**Vedanth Nayak**

- GitHub: [@vedanthnyk25](https://github.com/vedanthnyk25)

## 🙏 Acknowledgments

- Thanks to the LangChain team for their excellent framework
- Groq for providing the LLM capabilities
- All the open-source tools and libraries used in this project 
