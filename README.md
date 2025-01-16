# Multi-Agent Chatbot with LangGraph and Astra DB  

## 📜 Project Description  
This project implements a multi-agent chatbot utilizing LangGraph and Astra DB. The system consists of two agents:  
1. **Wikipedia Search Agent**: Performs a search on Wikipedia to provide relevant information.  
2. **VectorDB Agent**: Retrieves detailed information stored in a VectorDB from research paper URLs, optimizing responses based on context.  

The chatbot uses **prompt engineering** to improve the quality of responses and decides whether to fetch information from the VectorDB or fallback to Wikipedia based on the query content. This enables efficient querying of stored research paper data or general knowledge from Wikipedia.

---

## 🚀 Getting Started  

### 🛠 Prerequisites  
Ensure you have the following installed:  
- Python 3.8+  
- Astra DB credentials  
- Required libraries (see `requirements.txt`)  

### 📥 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/multi-agent-chatbot.git
   cd multi-agent-chatbot
### 🛠 IMP Note  
Pls provide your own secre keys:
- AstraDB Application Token
- AstraDB ID
