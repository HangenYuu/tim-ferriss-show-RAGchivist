# The Tim Ferriss Show Archivist
This is my final project for DataTalk.Club LLM Zoomcamp.
- [The Tim Ferriss Show Archivist](#the-tim-ferriss-show-archivist)
- [Progress](#progress)
- [Points](#points)
- [Problem Statement](#problem-statement)
- [Workflow](#workflow)
- [How to Run the App](#how-to-run-the-app)
- [Development Details](#development-details)
- [FAQs](#faqs)


# Progress
- [x] 1. Scrape the data.
- [x] 2. Chunk the data.
- [x] 3. Tokenize the data.
- [x] 4. Ingest the data into an ElasticSearch Docker
- [x] 5. Perform RAG trial with Groq API & Phi-3 (Ollama)
- [x] 6. Build an UI for the app
- [ ] 7. Perform Evaluations with GPT-4o
- [ ] 8. Build a dashboard for evalution
- [ ] 9. Best practices: Hybrid search, Document re-ranking
- [ ] 10. Cloud deployment: HuggingFace Space (no monitoring)

# Points
To save you the trouble of looking for the project criteria, I put my marks here. You can double-check while reading through the repo and running it.

Problem description
- [ ] 2 points: The problem is well-described and it's clear what problem the project solves

RAG flow
- [ ] 2 points: Both a knowledge base and an LLM are used in the RAG flow

Retrieval evaluation

    0 points: No evaluation of retrieval is provided
    1 point: Only one retrieval approach is evaluated
    2 points: Multiple retrieval approaches are evaluated, and the best one is used

RAG evaluation

    0 points: No evaluation of RAG is provided
    1 point: Only one RAG approach (e.g., one prompt) is evaluated
    2 points: Multiple RAG approaches are evaluated, and the best one is used

Interface
- [ ] 2 points: UI (e.g., Streamlit), web application (e.g., Django), or an API (e.g., built with FastAPI)

Ingestion pipeline
- [ ] 2 points: Automated ingestion with a Python script or a special tool (e.g., Mage, dlt, Airflow, Prefect)

Monitoring

    0 points: No monitoring
    1 point: User feedback is collected OR there's a monitoring dashboard
    2 points: User feedback is collected and there's a dashboard with at least 5 charts

Containerization
- [ ] 2 points: Everything is in docker-compose

Reproducibility
- [ ] 2 points: Instructions are clear, the dataset is accessible, it's easy to run the code, and it works. The versions for all dependencies are specified.

Best practices
- [ ] Hybrid search: combining both text and vector search (at least evaluating it) (1 point)

# Problem Statement
While I am not a regular follower of Tim Ferriss' podcast (which supposedly is one of the most famous right now), I sometimes check out the episode transcript, especially if the guest is someone I admire (e.g., Derek Sivers). But after 10 years and over 700 episodes, the content can be intimidating to read, and the gems hard to search for. That's when retrieval-augmented generation can help. Semantic vector search can help looks for relevant passages, and LLMs can process the different passages into appropriate answer.

# Workflow

# How to Run the App

# Development Details

# FAQs