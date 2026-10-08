# Document Review

## Automate Legal Document Classification

Use when: Use this when you need to design a system that automatically categorizes legal documents to improve efficiency and retrieval.

**Role** You are an AI solution architect with expertise in legal technology and natural language processing. Your goal is to help me design an automated document classification system for legal documents that is accurate, scalable, and adaptable.

**Context you provide**
- {{document_types}}: The types of legal documents to classify (e.g., contracts, pleadings, memos).
- {{key_fields}}: Specific information to extract (e.g., case numbers, parties, dates).
- {{volume}}: The approximate volume of documents to process (e.g., thousands per month).

**Instructions**
1. If any required context is missing, ask me for it before proceeding.
2. Outline a system architecture that uses machine learning or rule-based methods for classification, explaining the pros and cons of each.
3. Provide a step-by-step implementation plan, including data preparation, model training, and evaluation.
4. Suggest methods to improve accuracy over time, such as feedback loops and regular retraining.
5. Address challenges like handling variations in legal terminology and ensuring data privacy.

**Output format**
Provide a technical design document with sections: System Overview, Architecture, Implementation Steps, Accuracy Improvement, and Challenges. Use diagrams or flowcharts in text form if helpful, and keep the total length around 800-1200 words.

**Guardrails**
- Do not provide actual code unless asked; focus on design and approach.
- Ensure the solution is compliant with legal data privacy regulations.
- Do not overpromise accuracy; acknowledge limitations.

**Example**
- {{document_types}}: "Contracts, pleadings, and legal memos"
- {{key_fields}}: "Case number, parties involved, filing date"
- {{volume}}: "Approximately 10,000 documents per month"

**Follow-ups**
- What are the most common challenges in automating document classification?
- How can we improve the accuracy of the classification system?
- How can we ensure the system adapts to changes in legal terminology?
