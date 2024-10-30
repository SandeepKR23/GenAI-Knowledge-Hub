# GENAI-KNOWLEDGE-HUB
A comprehensive toolkit for working with various databases and knowledge graph implementations, featuring integrations with AstraDB, MongoDB, and web crawling capabilities.

# 🌟 Features


**Web Crawling**

- Graph-based HAL (Hypertext Application Language) scraping
- Automated data extraction and processing

**Knowledge Graphs**

- Healthcare-specific langchain implementation
- Customizable graph structures for domain-specific applications


**MongoDB Integration**

- Basic MongoDB operations and RAG implementation
- Pinecone integration with real-time RAG pipeline
- Two-phase pipeline implementation for enhanced performance

**AstraDB RAG Integration**

- Implementation of Retrieval-Augmented Generation (RAG) with AstraDB
- Optimized stack operations for efficient data retrieval

**Finetune**

- Finetune llama 2
- Finetune Distillbert
- Quantization


# 📋 Prerequisites

- Python 3.8+
- AstraDB account and credentials
- MongoDB installation
- Pinecone API access
- Required Python packages (see requirements.txt)

# 🚀 Getting Started

1. Clone the repository:
```
git clone https://github.com/SandeepKR23/GenAI-Knowledge-Hub.git
cd GENAI-KNOWLEDGE-HUB
```
2. Created a environment and activate it
```
conda create -p venv python==3.11
conda activate venv/
```

3. Install dependencies:
```
pip install -r requirements.txt
```
4. Configure your environment variables in .env file:
```
ASTRADB_TOKEN="your_token"
MONGODB_URI="your_mongodb_uri"
PINECONE_API_KEY="your_pinecone_key"
```

# 📁 Project Structure
```
GENAI-KNOWLEDGE-HUB/
├── AstraDB_RAG/
│   └── RAGStack.ipynb
├── Knowledge Graphs/
│   └── Knowledge Graph-HealthCare_Langchain.ipynb
├── MongoDB/
│   ├── RAG_MongoDB.ipynb
│   └── MongoDB_Pinecone/
│       ├── Mongodb_with_Pinecone_Realtime_RAG_Pipeline_1.ipynb
│       └── Mongodb_with_Pinecone_Realtime_RAG_Pipeline_2.ipynb
├── Webcrawler/
│   └── ScrapeGraphHAL_Guide.ipynb
└── README.md
```
# 📝 License
This project is licensed under the MIT License- see the LICENSE file for details.

# 🙏 Acknowledgments

Special thanks to:

- LangChain documentation and community for RAG implementation insights
- AstraDB team for their vector database documentation
- MongoDB documentation for database integration knowledge
- Pinecone documentation for vector search implementation
- CS50AI course materials for knowledge graph concepts
- Personal hands-on implementation and experimentation

Project created and maintained by  **Sandeep Kasinampalli Rajkumar**

## Connect with Me
* [LinkedIn](https://www.linkedin.com/in/sandeep-k-rajkumar/)
* [Medium](https://medium.com/@sandeepkrajkumar)
