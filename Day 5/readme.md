# 🏆 Capstone Project Guidelines

# Program Theme: Agentic AI & RAG Applications using Gemini API + ChromaDB/FAISS

# 1. Objective
```
To design and implement an end-to-end AI application using concepts from Deep Learning, Transformers, Generative AI, Prompt Engineering, and Retrieval-Augmented Generation (RAG).

By the end of this project, each team/individual should demonstrate:

Effective use of Gemini API for LLM-based tasks

Integration of vector databases (ChromaDB / FAISS) for retrieval

A working prototype deployed via Streamlit in Colab (with Ngrok if external access needed)
```
# 2. Suggested Project Themes
```
Teams can choose from the suggested themes or propose their own:

Legal Q&A Assistant (RAG-based)

Upload legal/policy PDFs → system answers user queries with Gemini + FAISS.

Code Debugging & Explanation Agent

AI assistant that explains/debugs code snippets + retrieves best practices from a knowledge base.

Healthcare / Clinical Trial Agent

Summarize and retrieve insights from clinical trial or medical guideline documents.

Financial Report Summarizer

AI agent to analyze financial statements and provide structured summaries.

Smart Knowledge Base Assistant (Individual Project)

RAG-powered personal assistant that answers from uploaded documents (general domain).
```
# 3. Project Workflow
```
Step 1 – Problem Definition

Clearly state the problem and why RAG/Agentic AI is suitable.

Define expected input/output.

Step 2 – Data Preparation

Collect relevant documents (PDF, text, CSV).

Perform preprocessing (chunking, cleaning).

Step 3 – Embedding & Storage

Use Gemini Embeddings API for vector representation.

Store embeddings in ChromaDB or FAISS.

Step 4 – RAG Pipeline Implementation

User query → Retrieve top-k documents → Pass context + query to Gemini → Generate response.

Implement fallback/retry logic for failed queries.

Step 5 – Application Layer

Build a Streamlit app for interaction.

UI requirements:

File upload (PDF/text)

Query input box

AI-generated answer display

Optional: sources shown for transparency

Step 6 – Testing & Evaluation

Evaluate response quality with metrics:

Relevance (BLEU/ROUGE scores on sample Q&A)

Correctness (manual/human evaluation)

Fairness (avoid bias in answers)

Compare FAISS vs ChromaDB retrieval quality.

Step 7 – Deployment

Deploy app in Colab + Streamlit, accessible via Ngrok.
```
# 4. Deliverables
```
Each team/individual must submit:

Project Report (PDF):

Problem statement

System architecture diagram

Methodology (pipeline explanation)

Results & evaluation

Challenges & improvements

Working Prototype: Streamlit app demo in Colab

Source Code Repository (GitHub/Drive)

Presentation (10 mins per team)
```
# 5. Evaluation Criteria

```
| Criteria                                      | Weightage |
| --------------------------------------------- | --------- |
| Problem Definition & Relevance                | 10%       |
| Technical Implementation (RAG + LLM)          | 30%       |
| Use of Gemini API & Vector DB (Chroma/FAISS)  | 20%       |
| Application/Prototype Quality (UI, usability) | 20%       |
| Evaluation & Insights                         | 10%       |
| Presentation & Documentation                  | 10%       |

```
# 6. Team Structure

Team Projects (4 projects): Groups of 3–4 engineers

Individual Project (1 project): Solo assignment (smaller scope but full pipeline)
