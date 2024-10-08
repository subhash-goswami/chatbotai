# ChatBot AI

This project implements a Retrieval-Augmented Generation (RAG) chatbot using FastAPI. It allows users to upload PDF documents, which are processed to generate text embeddings and stored in Pinecone. The chatbot, powered by OpenAI GPT-4, leverages these embeddings to retrieve relevant sections from the documents, providing users with contextually enriched responses.

The frontend, built with Next.js and TypeScript, delivers a seamless interface for interacting with the chatbot. Users can upload documents, engage in conversations, and view messages in real time. The design, styled with Tailwind CSS, ensures a responsive and modern user experience.

---


# Docker Compose - ChatBotAI Application

## Running Both Services Together

To run both the server and client services together using Docker Compose:

1. **Build and Start Containers:**

   ```bash
   docker-compose up --build
   ```

2. **Access Services:**

   - **Frontend:** `http://localhost:3000`
   - **Backend:** `http://localhost:8000`

## Cleaning Up

To stop and remove containers:

```bash
docker-compose down
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
