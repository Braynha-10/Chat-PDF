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
```
## 🛠️ Etapas do Projeto (Passo a Passo)
Upload dos PDFs
- Usuário faz upload de um ou mais arquivos PDF
- Textos são extraídos de forma estruturada
- Geração de Embeddings
- Cada trecho dos PDFs é convertido em vetor semântico
- Utiliza-se modelos como text-embedding-ada-002 da OpenAI
- Indexação
- Os vetores são armazenados em uma base vetorial (ex: FAISS)
- Interação via Chat
- Usuário envia uma pergunta
- Sistema busca os trechos mais relevantes
- Um LLM (modelo de linguagem) gera a resposta com base nesses dados

## 💬 Exemplo de Uso (Simulado)
Pergunta: "Qual a principal vantagem de um motor V8 em relação ao V6?"
Resposta simulada:

"Motores V8 tendem a entregar mais potência e torque, sendo preferidos em veículos de alto desempenho. Em contrapartida, são menos eficientes em termos de consumo de combustível em comparação com motores V6."

## 🚧 Desafios Enfrentados
Acesso limitado a serviços como OpenAI, Pinecone, LangChain Cloud

Algumas APIs cobram por tokens, o que inviabiliza testes longos

Alternativas gratuitas possuem limite de uso diário ou baixa performance

## ✅ Conclusão
Apesar das limitações técnicas, estudei toda a estrutura necessária para a construção de um sistema inteligente de análise de PDFs com IA generativa.
Esse projeto me permitiu explorar:

Pré-processamento de documentos

Criação de pipelines de IA com foco em embeddings

Fundamentos de busca semântica e indexação vetorial

Geração de respostas contextuais com LLMs

💡 Assim que possível, pretendo revisitar este projeto com acesso total às ferramentas e implementá-lo na prática para fortalecer ainda mais meu portfólio.
