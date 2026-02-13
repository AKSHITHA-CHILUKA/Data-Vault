# 🔐 Data Vault – Secure File Storage and Intelligent Document Management

Data Vault is an AI-powered secure cloud document management platform that combines multi-layer encryption, intelligent document analysis, controlled sharing workflows, and trust-based monitoring.

---

## 🚀 Key Features

- 🔐 Secure file upload with AES encryption
- 🤖 AI document analysis using Google Gemini API
- 🔗 Controlled sharing with permissions and OTP verification
- 💬 RAG chatbot for document interaction
- 📊 Trust score analytics dashboard

---

# 🏗️ High-Level System Architecture

![High Level Architecture](docs/images/high-level-architecture.png)

The system follows a layered architecture:

- Streamlit UI
- Python Backend Controller
- Security Module
- AI Intelligence Module
- MongoDB Database
- Vector Database (Chroma)

---

# 📄 File Upload & Processing Flow

![File Upload Flow](docs/images/file-upload-flow.png)

Workflow:

1. User uploads document
2. Content extraction
3. Gemini AI analysis
4. Category detection & event extraction
5. User confirmation
6. Password protection + AES encryption
7. Secure storage

---

# 🔐 Security Authentication Flow

![Security Flow](docs/images/security-auth-flow.png)

Multi-layer security approach:

- Password verification
- Decryption key validation
- OTP authentication
- Temporary decryption
- Secure viewing/download

---

# 💬 RAG Chatbot Architecture

![RAG Chatbot Flow](docs/images/rag-chatbot-flow.png)

Steps:

1. User query
2. Query embedding
3. Vector database similarity search
4. Context injection
5. Gemini AI response generation

---

# 🔗 File Sharing & Trust Score Workflow

![File Sharing Flow](docs/images/file-sharing-trust-flow.png)

Features:

- Permission-based sharing
- OTP-secured access
- Action tracking (view/download/reshare)
- Trust score updates
- Analytics dashboard

---

# ⚙️ Technology Stack

## Frontend
- Streamlit

## Backend
- Python

## Database
- MongoDB
- Chroma Vector Database

## APIs
- Google Gemini AI API
- Tavily API
- Ngrok API

---

# 🔐 Security Design

- AES encryption
- Password-protected files
- OTP-based authentication
- Zero plain-text storage

---

# 🤖 AI Capabilities

- Automatic document categorization
- Event extraction
- RAG-based chatbot interaction
- Context-aware AI responses

---

# 👩‍💻 Author

Akshitha Chiluka
