# **🌳 Sandalwood Knowledge System**  
A cutting-edge AI-powered platform to preserve and access traditional knowledge about sandalwood cultivation in Karnataka, India. This system combines **Automatic Speech Recognition (ASR)** and a **Question-Answering (QA) system** to make indigenous wisdom easily searchable and accessible.  


---


### **🌟 Key Features**  
- **Kannada Speech Recognition**: Optimized for colloquial and informal speech patterns.  
- **Real-Time Translation**: Converts Kannada to English for wider accessibility.  
- **Semantic Search**: Retrieval-Augmented Generation (RAG) architecture ensures contextually relevant results.  
- **Time-Aligned Audio Retrieval**: Retrieves specific audio segments matching user queries.  
- **Interactive Query Interface**: Supports both text and voice inputs for intuitive use.  


---


### **🏗️ System Architecture**  

#### **1) Training and Development Phase**  

**Data Preprocessing**  
- Preprocessed audio files to remove noise and unrelated segments.  
- Transcribed audio into text to build a meaningful and labeled dataset.  

**Model Selection and Fine-Tuning**  
- Compared multiple ASR models to identify the best-performing one for colloquial Kannada.  
- Integrated LangChain-powered Gemini for accurate Kannada-to-English translation.  

**Vector Database Creation**  
- Generated text embeddings using Sentence Transformers tailored for semantic understanding.  
- Built a GPU-accelerated FAISS database to index and retrieve vectorized data efficiently.  

**Question-Answering System Development**  
- Implemented Retrieval-Augmented Generation (RAG) architecture.  
- Combined retrieved segments with a language model to generate context-aware responses.  


---


#### **2) Runtime Phase**  

**User Interaction**  
- Users can input voice or text queries in Kannada or English.  

**Query Processing**  
1. **Speech-to-Text Conversion**:  
   - Processes Kannada speech using the fine-tuned ASR model to transcribe queries in real-time.  
2. **Translation and Search**:  
   - Translates Kannada queries into English if needed.  
   - Retrieves relevant audio/text segments from the FAISS database based on semantic search.  
3. **Contextual Response Generation**:  
   - Combines retrieved data and user queries to generate responses using the RAG model.  

**Response Delivery**  
- Outputs responses in text or synthesized speech for user clarity.  


---


### **📊 Dataset**  
- Source: YouTube content on sandalwood cultivation.  
- Characteristics: Colloquial Kannada, informal speech, background noise, and diverse dialects.  


---


### **🎯 Achievements**  
- Successfully handles colloquial Kannada despite language barriers.  
- Precise time alignment using innovative chunking techniques.  
- Seamless integration of state-of-the-art ASR and QA technologies.  


---


### **🚀 Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/sandalwood-knowledge-system.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd sandalwood-knowledge-system  
   ```  

3. Create a virtual environment:  
   ```bash  
   python -m venv venv  
   ```  

4. Activate the virtual environment:  
   - Linux/Mac: `source venv/bin/activate`  
   - Windows: `venv\Scripts\activate`  

5. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

---
