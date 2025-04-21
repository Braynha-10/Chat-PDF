# 🚀 Chatbot Inteligente Baseado em PDFs com IA Generativa

> **⚠️ Aviso Importante:**  
> Infelizmente, por limitações na minha assinatura de estudante, não consegui acesso a certos recursos necessários para a execução prática deste projeto, como a utilização de serviços de embeddings, vetorização e armazenamento em nuvem, que são funcionalidades avançadas e geralmente associadas a planos pagos.  
> Além disso, tentei utilizar versões gratuitas ou de teste de algumas plataformas, porém elas apresentaram restrições técnicas ou financeiras que inviabilizaram o desenvolvimento completo da solução.  
> Mesmo assim, busquei compreender toda a lógica do projeto e apresento abaixo um plano detalhado de como ele seria desenvolvido.

---

## 🎯 Objetivo

O projeto consiste em construir um **chat interativo baseado no conteúdo de arquivos PDF**, utilizando conceitos de:

- Inteligência Artificial Generativa (LLMs)
- Embeddings semânticos
- Buscas vetoriais
- Extração e organização de conteúdo a partir de documentos

---

## 🧠 Cenário

Imagine que sou um estudante em fase de desenvolvimento de TCC, lidando com diversos artigos científicos em PDF. A ideia é criar um sistema capaz de **entender o conteúdo desses documentos e responder perguntas** com base no material estudado.

Neste caso hipotético, os PDFs são relacionados ao tema **“Motores V8”**, mas a aplicação pode ser adaptada para qualquer área do conhecimento.

---

## 📚 Tecnologias e Ferramentas Envolvidas

Caso tivesse acesso completo, usaria as seguintes tecnologias:

| Recurso | Descrição |
|--------|-----------|
| **Python** | Linguagem principal do projeto |
| **LangChain** | Para orquestrar a lógica de IA generativa |
| **FAISS ou ChromaDB** | Para indexação e busca vetorial |
| **OpenAI API / Hugging Face** | Para geração de embeddings e respostas |
| **PyPDF2 ou pdfplumber** | Para leitura dos arquivos PDF |
| **Streamlit ou Gradio** | Interface web simples e interativa |

---

## 🔧 Estrutura do Projeto (Planejamento)

```bash
chatbot-pdf-v8/
├── app.py                  # Código principal com a interface
├── pdfs/                   # Pasta com arquivos PDF
├── utils/
│   └── pdf_reader.py       # Função para extrair texto dos PDFs
│   └── embedder.py         # Função para gerar embeddings
│   └── vector_search.py    # Função para busca vetorial
├── requirements.txt        # Dependências do projeto
└── README.md               # Documentação (este arquivo)
