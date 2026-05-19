<h1 align="center"> 📄 RAG </h1>
<p align="center">

<img width="800" height="400" alt="8AE94339-2C08-4041-A43B-B1B1755B1D18" src="https://github.com/user-attachments/assets/a1f485e2-e8b0-4758-994f-3fa4459812f6" />
</p>

## 💻 Linguagem usada no projeto
<img loading="lazy" src="https://img.shields.io/badge/Python-darkblue"/>      <img loading="lazy" src="https://img.shields.io/badge/LangChain-grey"/>      <img loading="lazy" src="https://img.shields.io/badge/Ollama-purple"/>      <img loading="lazy" src="https://img.shields.io/badge/Milvus-red"/>

---

## 📌 Sobre

Este projeto foi desenvolvido como parte das atividades do curso **Alura – LangChain: Técnicas Avançadas de RAG**.

O objetivo do projeto foi aprofundar o entendimento sobre arquiteturas de **Retrieval-Augmented Generation (RAG)**, explorando técnicas capazes de melhorar a recuperação de informações e a qualidade das respostas geradas por modelos de linguagem.

Durante o desenvolvimento, foi construído um pipeline responsável por:

- carregar documentos em PDF
- processar e dividir textos em chunks
- gerar embeddings semânticos
- armazenar informações em um banco vetorial
- recuperar contexto relevante para geração de respostas

O sistema utiliza:

- LangChain para orquestração do pipeline
- Ollama para execução local do LLM e geração de embeddings
- Milvus como banco de dados vetorial

Além disso, foram exploradas técnicas avançadas de recuperação de contexto, como **HyDE (Hypothetical Document Embeddings)**, utilizada para melhorar a busca semântica através da geração de respostas hipotéticas.

---

## 🧠 Conceitos Fundamentais Praticados

Durante o desenvolvimento deste projeto, foram aplicados conceitos importantes relacionados à IA generativa e sistemas RAG, incluindo:

- Carregamento e processamento de documentos com `DirectoryLoader`
- Divisão de documentos em chunks utilizando `CharacterTextSplitter`
- Geração de embeddings semânticos
- Armazenamento e busca vetorial utilizando Milvus
- Uso de modelos locais com Ollama
- Construção de pipelines com LangChain
- Implementação de técnicas avançadas de retrieval como HyDE
- Estruturação de prompts e chains
- Integração entre LLMs, embeddings e bancos vetoriais

---

## 🔄 Fluxo do sistema

```text
PDFs → Chunking → Embeddings → Milvus → Retrieval → LLM → Resposta Gerada
```

---

## ▶️ Como executar o projeto

1. Clone este repositório:
```bash
git clone https://github.com/StellaLeoni2008/tecnicas_rag.git
```
2. Crie um ambiente virtual:
```bash
python -m venv venv
```
3. Ative o ambiente virtual:

Windows
```bash
venv\Scripts\activate
```
macOS/Linux
```bash
source venv/bin/activate
```
4. Instale as dependências:
```bash
pip install -r requirements.txt
```
5. Execute o notebook ou script principal do projeto.

<br>



## Autores 
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/237313711?v=4" width=115><br><sub>Stella Leoni</sub>](https://github.com/StellaLeoni2008) | 
| :---: |


<p align="right">
25/03/2026
