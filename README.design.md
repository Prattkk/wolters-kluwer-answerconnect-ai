# Design Notes – CCH AnswerConnect AI Prototype

## Architecture Overview
The system follows a modular, feature-based React architecture.
Core components include:
- Drafting Workspace (AI-assisted writing + citations)
- Workflow Orchestrator (multi-step research pipelines)
- External Legal Data APIs
- LLM-powered AI services

## Frontend
- React + Vite
- Feature-based folder structure
- Drafting and workflow modules isolated for scalability

## AI Layer
- Gemini LLM for text generation and reasoning
- Retrieval logic for grounding responses
- Citation services ensure explainability

## External Data Sources
- CourtListener API
- Federal Register API
- GovInfo API

## Limitations
- Prototype-level error handling
- Mocked API responses in some flows
- Not production hardened

## Future Enhancements
- Role-based access control
- Production-grade audit logs
- Model confidence scoring
