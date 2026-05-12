# Medical-Chatbot

# Build a Complete Medical Chatbot with LLMs, LangChain, Pinecone, Flask & AWS

## How to Run?

### STEP 1: Clone the Repository

```bash
git clone https://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```

---

### STEP 2: Create a Conda Environment

```bash
conda create -n medibot python=3.10 -y
conda activate medibot
```

---

### STEP 3: Install the Requirements

```bash
pip install -r requirements.txt
```

---

### STEP 4: Create a `.env` File

Create a `.env` file in the root directory and add your credentials:

```env
PINECONE_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

---

### STEP 5: Store Embeddings in Pinecone

```bash
python store_index.py
```

---

### STEP 6: Run the Application

```bash
python app.py
```

Now open your browser and go to:

```bash
http://localhost:5000
```

---

# Tech Stack Used

- Python
- LangChain
- Flask
- OpenAI
- Pinecone
- AWS
