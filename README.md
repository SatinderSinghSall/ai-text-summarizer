# 🧠 AI Text Summarizer (Transformer-Based)

<p align="center">
  <b>End-to-End NLP Web Application using HuggingFace T5 + FastAPI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi" />
  <img src="https://img.shields.io/badge/HuggingFace-Transformers-yellow" />
  <img src="https://img.shields.io/badge/PyTorch-DeepLearning-red?logo=pytorch" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
  <img src="https://img.shields.io/badge/License-MIT-blue" />
</p>

---

## 📌 Overview

This project is a **full-stack AI-powered Text Summarization system** that leverages a **fine-tuned T5 Transformer model** to generate concise summaries from conversational text.

It demonstrates the **complete ML lifecycle**, from training to deployment:

- Data preprocessing
- Transformer fine-tuning
- Model checkpointing
- API deployment
- Frontend integration

---

## 🖼️ Demo Preview

![App UI](https://via.placeholder.com/900x400.png?text=Text+Summarizer+UI)

> 💡 Replace this with your actual screenshot (`index.html` UI)

---

## ⚙️ How It Works

```
User Input (Browser)
        ↓
Frontend (HTML + JS + CSS)
        ↓
FastAPI Backend
        ↓
Text Preprocessing
        ↓
T5 Transformer Model
        ↓
Generated Summary
        ↓
Response → UI
```

---

## ✨ Features

### 🧠 Machine Learning

- Fine-tuned **T5 Transformer**
- Dialogue summarization
- Beam search decoding
- HuggingFace tokenizer

### ⚡ Backend (FastAPI)

- REST API (`/summarize`)
- Model inference pipeline
- Pydantic validation
- Auto device selection (CPU/GPU)

### 🌐 Frontend

- Responsive UI
- Real-time summarization
- Error handling
- Fetch API integration

### 🚀 Deployment Ready

- Modular structure
- Static file serving
- Easy cloud deployment

---

## 🗂️ Project Structure

# File Tree: Text Summarizer [Minor Project]

**Generated:** 4/10/2026, 10:23:18 PM
**Root Path:** `e:\Artificial Intelligence and Machine Learning Projects\Text Summarizer [Minor Project]`

```
├── 📁 Text Summarizer App
│   ├── 📁 saved_summary_model
│   │   ├── ⚙️ config.json
│   │   ├── ⚙️ generation_config.json
│   │   ├── 📄 model.safetensors
│   │   ├── ⚙️ tokenizer.json
│   │   └── ⚙️ tokenizer_config.json
│   ├── 📁 static
│   │   ├── 📄 script.js
│   │   └── 🎨 style.css
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── 🐍 app.py
│   └── 🌐 index.html
├── 📁 Text Summarizer [Minor Project]
│   ├── 📁 .ipynb_checkpoints
│   │   ├── 📄 samsum-test-checkpoint.csv
│   │   └── 📄 text-summarizer-checkpoint.ipynb
│   ├── 📁 .virtual_documents
│   │   └── 📄 text-summarizer.ipynb
│   ├── 📁 Lecture Notes
│   │   ├── 🖼️ Screenshot (3164).png
│   ├── 📁 Project Code
│   │   ├── 📁 Summarizer-HF-main
│   │   │   └── 📁 Summarizer-HF-main
│   │   │       ├── 📝 README.md
│   │   │       ├── 🐍 app.py
│   │   │       └── 🌐 index.html
│   │   └── 📄 text_summarizer.ipynb
│   ├── 📁 Project Dataset
│   │   ├── 📄 samsum-test.csv
│   │   ├── 📄 samsum-train.csv
│   │   └── 📄 samsum-validation.csv
│   ├── 📁 anaconda_projects
│   │   └── 📁 db
│   │       └── 📄 project_filebrowser.db
│   ├── 📁 results
│   │   ├── 📁 checkpoint-1000
│   │   │   ├── ⚙️ config.json
│   │   │   ├── ⚙️ generation_config.json
│   │   │   ├── 📄 model.safetensors
│   │   │   ├── 📄 optimizer.pt
│   │   │   ├── 📄 rng_state.pth
│   │   │   ├── 📄 scheduler.pt
│   │   │   ├── ⚙️ trainer_state.json
│   │   │   └── ⚙️ training_args.bin
│   │   ├── 📁 checkpoint-1500
│   │   │   ├── ⚙️ config.json
│   │   │   ├── ⚙️ generation_config.json
│   │   │   ├── 📄 model.safetensors
│   │   │   ├── 📄 optimizer.pt
│   │   │   ├── 📄 rng_state.pth
│   │   │   ├── 📄 scheduler.pt
│   │   │   ├── ⚙️ trainer_state.json
│   │   │   └── ⚙️ training_args.bin
│   │   ├── 📁 checkpoint-2000
│   │   │   ├── ⚙️ config.json
│   │   │   ├── ⚙️ generation_config.json
│   │   │   ├── 📄 model.safetensors
│   │   │   ├── 📄 optimizer.pt
│   │   │   ├── 📄 rng_state.pth
│   │   │   ├── 📄 scheduler.pt
│   │   │   ├── ⚙️ trainer_state.json
│   │   │   └── ⚙️ training_args.bin
│   │   ├── 📁 checkpoint-2500
│   │   │   ├── ⚙️ config.json
│   │   │   ├── ⚙️ generation_config.json
│   │   │   ├── 📄 model.safetensors
│   │   │   ├── 📄 optimizer.pt
│   │   │   ├── 📄 rng_state.pth
│   │   │   ├── 📄 scheduler.pt
│   │   │   ├── ⚙️ trainer_state.json
│   │   │   └── ⚙️ training_args.bin
│   │   ├── 📁 checkpoint-3000
│   │   │   ├── ⚙️ config.json
│   │   │   ├── ⚙️ generation_config.json
│   │   │   ├── 📄 model.safetensors
│   │   │   ├── 📄 optimizer.pt
│   │   │   ├── 📄 rng_state.pth
│   │   │   ├── 📄 scheduler.pt
│   │   │   ├── ⚙️ trainer_state.json
│   │   │   └── ⚙️ training_args.bin
│   │   └── 📁 checkpoint-500
│   │       ├── ⚙️ config.json
│   │       ├── ⚙️ generation_config.json
│   │       ├── 📄 model.safetensors
│   │       ├── 📄 optimizer.pt
│   │       ├── 📄 rng_state.pth
│   │       ├── 📄 scheduler.pt
│   │       ├── ⚙️ trainer_state.json
│   │       └── ⚙️ training_args.bin
│   ├── 📁 saved_summary_model
│   │   ├── ⚙️ config.json
│   │   ├── ⚙️ generation_config.json
│   │   ├── 📄 model.safetensors
│   │   ├── ⚙️ tokenizer.json
│   │   └── ⚙️ tokenizer_config.json
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── 📄 samsum-test.csv
│   ├── 📄 samsum-train.csv
│   ├── 📄 samsum-validation.csv
│   └── 📄 text-summarizer.ipynb
└── 📝 README.md
```

---

_Generated by FileTree Pro Extension_

```
Text Summarizer App/
│
├── app.py                  # FastAPI backend
├── index.html              # Frontend UI
├── static/
│   ├── script.js
│   └── style.css
│
├── saved_summary_model/    # Trained T5 model
├── Project Dataset/        # SAMSum dataset
├── results/                # Training checkpoints
└── text-summarizer.ipynb   # Training notebook
```

---

## 📊 Dataset

- **Dataset:** SAMSum (Dialogue Summarization)
- Format:

```
dialogue → input text
summary → target output
```

Example:

**Input:**

```
John: Are we meeting tomorrow?
Alice: Yes, at 10 AM.
```

**Output:**

```
John and Alice confirm a meeting at 10 AM.
```

---

## 🧠 Model Details

- Model: **T5 (Text-to-Text Transformer)**
- Framework: HuggingFace Transformers

### ⚙️ Training

- Sequence-to-sequence learning
- Cross-entropy loss
- Multiple checkpoints saved

### ⚡ Inference

```
max_length = 150
num_beams = 4
early_stopping = True
```

---

## 🔌 API Usage

### Endpoint:

```
POST /summarize/
```

### Request:

```json
{
  "dialogue": "Your text here"
}
```

### Response:

```json
{
  "summary": "Generated summary"
}
```

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install fastapi uvicorn transformers torch jinja2
```

---

## ▶️ Run the App

```bash
uvicorn app:app --reload
```

Open:

```
http://127.0.0.1:8000
```

---

## 📸 Example

**Input:**

```
Emma: Did you finish the report?
Liam: Yes, I sent it.
```

**Output:**

```
Liam confirms he sent the report and Emma acknowledges it.
```

---

## 🎯 Learning Outcomes

- Transformer architectures (T5)
- NLP preprocessing pipelines
- Model fine-tuning (HuggingFace)
- API development (FastAPI)
- Full-stack AI deployment

---

## ⚠️ Known Issues

- Typo in CUDA check:

```python
torch.cuda.is_availanle()  ❌
torch.cuda.is_available()  ✅
```

---

## 🔮 Future Improvements

- Multi-language support
- File upload (PDF/DOCX)
- Docker deployment
- Cloud deployment (AWS/GCP)
- Streaming responses

---

## 👨‍💻 Author

**Satinder Singh Sall**

🔗 GitHub: https://github.com/SatinderSinghSall
🔗 LinkedIn: https://www.linkedin.com/in/satinder-singh-sall-b62049204/
🌐 Portfolio: https://satinder-portfolio.vercel.app/

---

## ⭐ Acknowledgements

- HuggingFace Transformers
- PyTorch
- FastAPI

---

## 📄 License

MIT License

---

# 📄 Text Summarizer App (HuggingFace Transformer)

# AI / ML: Deep Learning – GenAI - Transformers

A full-stack **Text Summarization Web Application** built using **Transformer models (T5)** from HuggingFace, deployed with **FastAPI** and a simple **HTML/CSS/JavaScript frontend**.

This project demonstrates end-to-end implementation of:

- NLP model fine-tuning
- Model serving via API
- Frontend-backend integration
- Deployment-ready architecture

---

# AI Text Summarizer

### Transformer-based Dialogue Summarization using HuggingFace T5 and FastAPI

An end-to-end **AI-powered text summarization system** that fine-tunes a **Transformer model (T5)** on conversational data and deploys it through a **FastAPI backend with an interactive web interface**.

The system takes long dialogue text as input and generates concise summaries using a trained neural sequence-to-sequence model.

This project demonstrates the complete **Machine Learning lifecycle**, including:

- Data preprocessing
- Transformer fine-tuning
- Model checkpointing
- Model deployment
- API development
- Frontend integration
- Full-stack AI application deployment

---

# Project Overview

Large volumes of conversational text (such as chat logs or discussions) are difficult to read and analyze quickly. This project addresses that problem by building a **neural text summarization system** that compresses dialogue into meaningful summaries.

The model is trained on the **SAMSum dataset**, which contains real conversational dialogues paired with human-written summaries.

After training, the model is exported and integrated into a **production-style FastAPI service**, enabling users to input dialogue and receive summaries instantly through a modern web interface.

---

# Key Features

### Machine Learning

- Transformer-based summarization
- Fine-tuned **T5 sequence-to-sequence model**
- Dialogue summarization capability
- Tokenization using HuggingFace tokenizer
- Beam search generation

### Backend

- FastAPI REST API
- Model loading and inference
- Input validation using Pydantic
- Automatic device selection (CPU / CUDA / MPS)

### Frontend

- Clean responsive UI
- Text input and real-time summary generation
- Error handling modal
- Asynchronous API communication using Fetch API

### Deployment Ready

- Static file serving
- Template rendering with Jinja2
- Modular code structure
- Local or cloud deployment compatible

---

# Project Architecture

```
User Input (Browser)
        │
        ▼
Frontend Interface (HTML + JS + CSS)
        │
        ▼
Fetch API Request
        │
        ▼
FastAPI Backend
        │
        ▼
Text Cleaning & Tokenization
        │
        ▼
Fine-tuned T5 Transformer
        │
        ▼
Generated Summary
        │
        ▼
JSON Response
        │
        ▼
Displayed in Browser
```

---

# Dataset

This project uses the **SAMSum Dialogue Summarization Dataset**.

Dataset files:

```
samsum-train.csv
samsum-validation.csv
samsum-test.csv
```

Each dataset record contains:

```
dialogue → conversation text
summary → human written summary
```

Example:

Dialogue:

```
John: Are we meeting tomorrow?
Alice: Yes, at 10 AM.
John: Great, see you then.
```

Summary:

```
John and Alice confirm their meeting for tomorrow at 10 AM.
```

---

# Machine Learning Pipeline

## 1. Data Preprocessing

The dialogue text is cleaned before being passed to the model.

Steps include:

- Removing HTML tags
- Removing extra whitespace
- Lowercasing text
- Normalizing line breaks

This ensures cleaner input for the tokenizer and improves model performance.

---

## 2. Tokenization

The text is converted into token IDs using the **T5 tokenizer**.

Key parameters:

```
max_length = 512
padding = max_length
truncation = True
```

Tokenization converts natural language text into numerical representations suitable for neural networks.

---

## 3. Model Training

The model used is:

```
T5ForConditionalGeneration
```

T5 is a **sequence-to-sequence Transformer** architecture designed for text-to-text tasks.

Training involves:

- Encoding dialogue input
- Predicting target summaries
- Minimizing sequence cross-entropy loss

During training, checkpoints are saved periodically.

Example:

```
checkpoint-500
checkpoint-1000
checkpoint-1500
checkpoint-2000
checkpoint-2500
checkpoint-3000
```

After training completes, the final model is saved to:

```
saved_summary_model/
```

---

# Model Inference

During deployment, the trained model is loaded and used to generate summaries.

Generation parameters:

```
max_length = 150
num_beams = 4
early_stopping = True
```

Beam search helps improve summary quality by exploring multiple candidate outputs.

---

# Backend API (FastAPI)

The application backend is built using **FastAPI**.

Key components:

- Model loading
- Dialogue preprocessing
- Summarization function
- REST API endpoint

The summarization endpoint:

```
POST /summarize/
```

Request body:

```
{
  "dialogue": "input text"
}
```

Response:

```
{
  "summary": "generated summary"
}
```

The backend loads the trained model and performs inference on each request.

---

# Frontend Interface

The UI allows users to interact with the summarization model easily.

Interface features include:

- Large text input area
- Summary display panel
- Responsive layout
- Error handling modal

The interface is built with standard web technologies:

```
HTML
CSS
JavaScript
```

The HTML layout defines the UI structure.

JavaScript handles API communication with the backend.

CSS provides styling, layout, animations, and responsiveness.

---

# Project Structure

```
Text Summarizer App
│
├── app.py
├── index.html
├── static/
│   ├── script.js
│   └── style.css
│
├── saved_summary_model/
│   ├── config.json
│   ├── tokenizer.json
│   ├── tokenizer_config.json
│   └── model.safetensors
│
├── Project Dataset/
│   ├── samsum-train.csv
│   ├── samsum-test.csv
│   └── samsum-validation.csv
│
├── results/
│   └── training checkpoints
│
└── text-summarizer.ipynb
```

---

# Installation

Clone the repository:

```
git clone https://github.com/your-username/text-summarizer.git
cd text-summarizer
```

Create a virtual environment:

```
python -m venv venv
```

Activate environment:

Windows

```
venv\Scripts\activate
```

Mac / Linux

```
source venv/bin/activate
```

Install dependencies:

```
pip install fastapi uvicorn transformers torch jinja2
```

---

# Running the Application

Start the FastAPI server:

```
uvicorn app:app --reload
```

Open your browser:

```
http://127.0.0.1:8000
```

You will see the text summarizer interface.

---

# Example Usage

Input dialogue:

```
Emma: Did you finish the report?
Liam: Yes, I sent it this morning.
Emma: Perfect, thanks!
```

Generated summary:

```
Liam confirms he finished and sent the report, and Emma thanks him.
```

---

# Technologies Used

### Machine Learning

- HuggingFace Transformers
- PyTorch
- T5 Model

### Backend

- FastAPI
- Pydantic
- Uvicorn

### Frontend

- HTML5
- CSS3
- JavaScript

### Development Tools

- Python
- Jupyter Notebook
- VS Code

---

# Learning Outcomes

This project demonstrates understanding of:

- Transformer architectures
- Text summarization techniques
- HuggingFace model fine-tuning
- NLP preprocessing pipelines
- API development with FastAPI
- Frontend–backend integration
- Machine learning model deployment

---

# Future Improvements

Potential enhancements include:

- Support for multiple summarization models
- Deployment using Docker
- Cloud deployment (AWS / GCP / Azure)
- HuggingFace Hub integration
- Streaming responses
- Long-document summarization

---

# Author

**Satinder Singh**

GitHub
[https://github.com/SatinderSinghSall](https://github.com/SatinderSinghSall)

LinkedIn
[https://www.linkedin.com/in/satinder-singh-sall-b62049204/](https://www.linkedin.com/in/satinder-singh-sall-b62049204/)

Portfolio
[https://satinder-portfolio.vercel.app/](https://satinder-portfolio.vercel.app/)

---

# License

This project is released under the MIT License.

---

## 🚀 Project Overview

This application takes user-input text (dialogue or paragraph) and generates a concise summary using a fine-tuned **T5 Transformer model**.

The system includes:

- 🧠 Transformer-based summarization model
- ⚡ FastAPI backend for inference
- 🌐 Interactive web UI for user input/output

---

## 🧱 Tech Stack

### 🔹 Machine Learning

- HuggingFace Transformers (T5)
- PyTorch

### 🔹 Backend

- FastAPI
- Pydantic
- Jinja2 Templates

### 🔹 Frontend

- HTML5
- CSS3
- JavaScript (Fetch API)

---

## 📂 Project Structure

```
├── app.py                # FastAPI backend (model inference)
├── index.html           # Frontend UI
├── saved_summary_model/ # Fine-tuned T5 model
├── README.md            # Project documentation
└── notebook.ipynb       # Training & preprocessing pipeline
```

---

## ⚙️ How It Works

### 1. Input Processing

User enters text in the UI → sent to backend via POST request.

### 2. Data Cleaning

Text is cleaned before processing:

- Removes extra spaces
- Removes HTML tags
- Converts to lowercase
  (Implemented in backend)

### 3. Tokenization

- Uses T5 tokenizer
- Max length: 512 tokens
- Applies padding & truncation

### 4. Model Inference

- Fine-tuned T5 model generates summary
- Beam search used for better output quality:
  - `num_beams=4`
  - `max_length=150`

### 5. Output

- Decoded summary returned as JSON
- Displayed dynamically on frontend

---

## 🧠 Backend Details (FastAPI)

The backend is implemented using FastAPI :

### Key Features:

- Loads trained T5 model from local directory
- Device selection:
  - Apple MPS / CUDA / CPU

- REST API endpoint:
  - `POST /summarize/`

- Web route:
  - `GET /` → serves UI

### API Example

```json
POST /summarize/

{
  "dialogue": "Your input text here"
}
```

Response:

```json
{
  "summary": "Generated summary text"
}
```

---

## 🎨 Frontend Details

The frontend UI is built using HTML, CSS, and JavaScript .

### Features:

- Clean and responsive UI
- Text input area for content
- Real-time API interaction
- Loading & error handling
- Dynamic summary display

### Workflow:

1. User submits text
2. JS sends request via Fetch API
3. Backend processes input
4. Summary is displayed instantly

---

## 🧪 Model Details

- Model: **T5 (Text-to-Text Transfer Transformer)**
- Fine-tuned for **text summarization task**
- Stored locally: `./saved_summary_model`

### Generation Parameters:

- `max_length=150`
- `num_beams=4`
- `early_stopping=True`

---

## ▶️ Running the Project

### 1. Install Dependencies

```bash
pip install fastapi uvicorn transformers torch jinja2
```

---

### 2. Start the Server

```bash
uvicorn app:app --reload
```

---

### 3. Open in Browser

```
http://127.0.0.1:8000/
```

---

## 📸 Features Demonstrated

- End-to-end NLP pipeline
- Transformer fine-tuning
- API deployment
- Frontend-backend integration
- Real-time inference system

---

## 📌 Learning Outcomes

From this project, the following concepts were implemented:

- Data preprocessing for NLP
- Tokenization using T5 tokenizer
- Fine-tuning transformer models
- Model saving & loading
- FastAPI-based deployment
- REST API design
- Frontend integration using JavaScript

---

## ⚠️ Known Issues / Improvements

- Minor typo in CUDA check:

  ```python
  torch.cuda.is_availanle()
  ```

  → should be `is_available()`

- Add:
  - Input validation limits
  - Streaming responses for long text
  - Docker deployment
  - Better UI/UX enhancements

---

## 🔮 Future Enhancements

- Support for multiple languages
- Upload files (PDF, DOCX)
- Summarization modes (short / detailed)
- Deploy on cloud (AWS / GCP / Render)
- Add authentication

---

## 👨‍💻 Author

**Satinder Singh Sall**
AI/ML Practitioner

---

## 📄 License

This project is for academic and educational purposes.

---

## ⭐ Acknowledgements

- HuggingFace Transformers
- PyTorch
- FastAPI Framework
- Apna College AI/ML Program

---
