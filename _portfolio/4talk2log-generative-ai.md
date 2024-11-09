---
title: "Log Analytics: using AI to transform complex log files in engaging narratives"
permalink: /portfolio/talk2log
excerpt: ""
header:
  teaser: /assets/images/talk2log_th.png
sidebar:
  - title: ""
    image: /assets/images/talk2log_logo.png
    image_alt: "logo"
  - title: "Project goal"
    text: "To design an AI-powered solution that translates complex industrial control system logs into clear, accessible summaries for diverse stakeholders. The tool aimed to improve understanding, response times, and decision-making by making dense log data understandable to operators, managers, and executives."

---

![alt]({{ site.url }}{{ site.baseurl }}/assets/images/talk2log.png)

📅 October, 2024

### Project Description
As the principal developer, I created Talk2log, an AI system using Retrieval-Augmented Generation (RAG) and reranking techniques to interpret technical log data. The tool leverages machine learning to generate human-friendly summaries, bridging the gap between raw machine data and actionable insights. I was responsible for system architecture, embedding setup, and vector database integration, ensuring that Talk2log could process dense industrial data and produce valuable insights. Key challenges included handling data sparsity and aligning log information with meaningful, plain-language summaries, which I addressed through rigorous data preprocessing and embedding.

### Tools and Technologies Used
- **Streamlit**: Used for building the interactive interface, making the tool accessible to users.
- **Python (pandas, SentenceTransformer)**: Essential for data handling and generating embeddings for log data.
- **Qdrant (vector database)**: Chosen for efficient, scalable storage of embeddings, allowing rapid retrieval during the RAG process.
- **Cohere API**: Employed for reranking and generating summaries based on log data.
- **Retrieval-Augmented Generation (RAG)**: Combined information retrieval with language generation to produce contextually relevant summaries.

These technologies enabled a streamlined, user-friendly application capable of transforming complex data into actionable insights.

### Statistical and Analytical Techniques
- **Sentence Embeddings**: Provided by SentenceTransformer, allowing for semantic search and enhanced matching of log tags with descriptions.
- **Data Reranking**: Used to prioritize relevant data points and refine the summaries for clarity and impact.


**See it in action:**

[Talk2log](https://talk2log.streamlit.app/)
