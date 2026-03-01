# meetpan
> AI Meeting Intelligence Platform

An AI-powered meeting assistant that turns recordings into structured knowledge — transcripts, action items, summaries, and a searchable archive of everything discussed.

## What is this?

meetpan solves the problem of meetings being information black holes. Feed it a recording and it uses Whisper-based speech-to-text to generate an accurate transcript, then extracts action items and decisions automatically using GPT-4o. Every meeting gets embedded into a vector database, so you can semantically search across all your past conversations — ask "what did we decide about the API redesign?" and get a real answer.

The backend is built on FastAPI for async performance, with CI/CD pipelines, analytics tracking, and production-grade monitoring baked in from the start.

## Core Features

- [ ] Audio upload and Whisper-based transcription
- [ ] Automatic action item and decision extraction
- [ ] Meeting summaries with key highlights
- [ ] Semantic search across all past meetings
- [ ] Vector database integration
- [ ] Analytics and usage tracking
- [ ] CI/CD pipelines with production monitoring

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Tailwind CSS |
| Backend | FastAPI (Python) |
| AI | OpenAI Whisper, GPT-4o, embeddings |
| Vector DB | Pinecone or pgvector |
| Database | PostgreSQL |
| Infra | Docker, AWS, GitHub Actions |
