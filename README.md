# 📝Project Description 
Pizza Review Q&A System | Python, LangChain, Ollama, Chroma

Built a retrieval-augmented generation (RAG) system that answers natural-language questions about a pizza restaurant using real customer reviews. Integrated LangChain, Ollama, and Chroma to create a fully local AI pipeline capable of retrieving, embedding, and reasoning over review data.

Implemented semantic search using Ollama embeddings and Chroma vector storage.

Developed a custom retrieval-augmented prompt chain to feed top-matched reviews into LLaMA 2 for context-aware answers.

Enabled offline operation by running both the embedding model and LLM locally via Ollama.

Built an interactive CLI that allows users to ask open-ended questions about menu items, ingredients, or restaurant feedback.

Structured and indexed 1,000+ reviews with metadata (rating, date) for future filtering and analysis.
