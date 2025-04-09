# 🧠 IntelliBank – Seu Segundo Cérebro Digital com IA Integrada

O **IntelliBank** é uma aplicação web (e futuramente mobile) criada para ser sua **base de conhecimento pessoal inteligente**, onde você pode **registrar, organizar, explorar e conversar com o seu próprio conhecimento**.

O objetivo é transformar o caos de informações soltas em uma biblioteca estruturada, conectada e pesquisável — com apoio de **Inteligência Artificial** para sugerir tags, criar resumos, identificar relações entre ideias e responder perguntas com base nas suas próprias notas.

> “Uma mente organizada pensa melhor.”  
> O IntelliBank ajuda você a pensar com clareza, guardar o que importa e explorar melhor o que já sabe.

---

## 🚀 Funcionalidades

✅ **Criação e organização de notas**
- Notas com título, conteúdo, tags e links entre elas

🔎 **Busca inteligente**
- Busca textual e semântica com similaridade de conteúdo

🏷️ **Sugestão automática de tags**
- A IA analisa o conteúdo e sugere tags relevantes

🧠 **Resumo automatizado**
- Gere resumos breves e claros com base em textos longos

🕸️ **Visualização em grafo**
- Veja conexões entre suas ideias em um mapa interativo

💬 **Chatbot pessoal**
- Faça perguntas em linguagem natural e receba respostas com base no seu próprio conteúdo

📱 **App mobile (em desenvolvimento)**
- Capture ideias a qualquer momento, mesmo offline

---

## 🛠️ Tecnologias Utilizadas

| Camada | Tecnologias |
|--------|-------------|
| **Frontend Web** | React.js, Axios, Styled Components |
| **Backend API** | Node.js, Express.js |
| **Banco de Dados** | PostgreSQL + tsvector |
| **IA / NLP** | OpenAI API, sentence-transformers (via Python ou JS) |
| **Busca Semântica** | FAISS ou ChromaDB |
| **Mobile** | React Native (Expo) |

---

## 📷 Demonstrações (em breve)

- [ ] Tela de criação de notas  
- [ ] Busca com destaque de resultados  
- [ ] Gráfico de conexões entre ideias  
- [ ] Chatbot com respostas baseadas nas notas  

> *Imagens e vídeos serão adicionados assim que as interfaces forem concluídas.*

---

## 📦 Instalação (em desenvolvimento)

> **Pré-requisitos**:
- Node.js 16+
- PostgreSQL
- Yarn ou npm
- Python 3.8+ (para módulos de IA opcionais)

```bash
# Clonar o projeto
git clone https://github.com/seu-usuario/intelli-bank.git
cd intelli-bank

# Backend
cd backend
npm install
npm run dev

# Frontend
cd ../frontend
npm install
npm start
