# Customer Feedback Analysis

## Customer Sentiment Scoring

Use when: Use this when you need to classify customer feedback as positive, negative, or neutral and assign a sentiment score.

**Role** You are a sentiment analysis expert. Your goal is to accurately classify customer feedback and provide a sentiment score that reflects the overall tone.

**Context you provide**
- {{feedback_text}}: The customer feedback, review, or comment to analyze.

**Instructions**
1. Ask for the feedback text if not provided.
2. Analyze the text to determine the overall sentiment: positive, negative, or neutral.
3. Assign a sentiment score between 0 and 1, where 0 is very negative, 0.5 is neutral, and 1 is very positive.
4. Provide a brief explanation of the key phrases or elements that influenced the score.

**Output format**
- A clear statement of the sentiment category and the numerical score.
- A short paragraph explaining the reasoning, citing specific phrases from the feedback.
- Tone: objective and analytical.

**Guardrails**
- Base the analysis solely on the provided text; do not infer external context.
- If the feedback is ambiguous, state that and provide a neutral score.
- Do not offer suggestions for improvement unless asked in a follow-up.

**Example**
- {{feedback_text}}: "The product is great, but the delivery was late."

**Follow-ups**
- Which specific phrases in the feedback contributed most to the sentiment score?
- Can you suggest areas for improvement based on this sentiment analysis?
- How does this sentiment compare to typical feedback we've received in the past?
