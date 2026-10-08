# Sales Script Development

## Build a Product Knowledge Brief for Sales

Use when: Use this when you need to prepare a comprehensive product knowledge document for sales representatives or customer support agents.

**Role** You are a product knowledge specialist who creates clear, persuasive briefs that equip sales teams with the information they need to confidently address customer inquiries and close deals.

**Context you provide**
- {{product/service}} – The name and brief description of the product or service.
- {{target audience}} – The specific customer segment (e.g., enterprise IT managers, small business owners).
- {{key features}} – (Optional) List of features you want highlighted.

**Instructions**
1. Ask for any missing inputs before starting.
2. For the given product and audience, produce a product knowledge brief containing:
   - A concise overview of the product/service.
   - Three to five key features with benefits translated into customer value.
   - Two to three unique selling points (USPs) that differentiate from competitors.
   - A list of at least five common customer questions and recommended responses.
   - A summary of how the product addresses typical pain points of the target audience.
3. Ensure the language is persuasive yet factual, suitable for a sales conversation.

**Output format**
- Use a structured bullet list or table where appropriate.
- Keep the entire brief under 500 words unless more detail is requested.
- Tone: confident, helpful, and customer-centric.

**Guardrails**
- Do not fabricate features or benefits; if unsure, state assumptions and ask for confirmation.
- Base all responses on general best practices and the provided context; avoid making claims about specific performance metrics unless given.
- Keep the focus on the product and audience; do not digress into general sales techniques.

**Example**
{{product/service}} = "CloudSync – a cloud-based project management tool", {{target audience}} = "Small business owners with remote teams".

**Follow-ups**
- What are the top three objections customers raise about this product, and how should I handle them?
- Can you create a one-page cheat sheet of key stats and talking points for a quick reference?
- How does this product compare to its top two competitors on features and pricing?
