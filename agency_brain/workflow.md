# Agency Workflow: Thought Flow (LangChain/LangGraph)

## 1. The Innovation Loop (State Graph)

The agency operates on a cyclical thought process:

1.  **Monitor (Input)**: Analyst scans market trends via MCP.
2.  **Concept (LangChain)**: CD takes trends + Ontology to define a "Next-Gen Product" concept.
3.  **Visualise (Designer)**: Designer creates drafts/prototypes using design tools.
4.  **Validate (LangGraph Node)**: CD reviews if it meets "Minimalist/Sophisticated" standards.
    - *Fail*: Return to Concept/Design.
    - *Pass*: Move to Production.
5.  **Produce & List (Sales)**: Product agent finalises assets; Sales agent lists them globally.

## 2. Prompting Strategy
- **Few-Shot Design Prompts**: Ensuring agents understand the specific "Sophisticated/Minimalist" style.
- **Chain-of-Thought (CoT)**: For CD to justify design decisions based on ontology.
- **Self-Reflection**: Designer agent critiques its own work before presenting to CD.

## 3. Communication Channel
- All thoughts are shared via a central "Agency Memory" (Knowledge Item/Vector DB).
