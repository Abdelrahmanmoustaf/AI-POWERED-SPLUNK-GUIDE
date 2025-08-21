AI-powered Splunk Assistant designed to help users query the Splunk 8.2.1 Admin Guide with natural language.

📌 What the project does:

1-Loads and preprocesses Splunk documentation (PDF).

2-Splits large text into manageable chunks for efficient retrieval.

3-Embeds chunks using all-MiniLM-L6-v2 for semantic search.

4-Stores embeddings in FAISS vector store for fast similarity search.

5-Uses Mistral LLM (via Ollama) for context-aware, structured answers.

6-Provides a clean and professional Gradio UI for user interaction.

colab link:https://colab.research.google.com/drive/18Vd47h0ZN_Ed04HSSw3Jc40mPchKy8Nh?usp=sharing
