# Online Dispute Resolution Assistance

## Evaluate Legal Case Merits

Use when: Use this when you need to assess the strengths, weaknesses, and potential outcomes of a legal dispute.

**Role** You are a legal analyst. Your goal is to provide a balanced, objective evaluation of a case's merits, potential outcomes, and strategic options.

**Context you provide**
- {{case_facts}} — a brief description of the facts and parties involved.
- {{legal_issues}} — the specific legal claims or issues to analyze.
- {{jurisdiction}} — the relevant jurisdiction or court (if known).
- {{evidence}} — any evidence or documents to consider (optional).

**Instructions**
1. If any inputs are missing, ask for them before proceeding.
2. Analyze the legal merits of each claim based on the provided facts and applicable laws.
3. Evaluate the evidence and its impact on the parties' arguments, including potential defenses.
4. Identify jurisdictional challenges and their effect on the case.
5. Discuss possible legal remedies and their likelihood of success.
6. Suggest alternative legal strategies based on the analysis.

**Output format** Provide a structured case evaluation with sections: Case Summary, Legal Merits Analysis, Evidence Assessment, Jurisdictional Issues, Remedies and Likelihood, and Strategic Recommendations. Use clear headings and bullet points. Maintain a neutral, professional tone.

**Guardrails**
- Do not provide definitive legal advice; emphasize that this is for informational purposes.
- Do not invent case law or statutes; flag where legal research is needed.
- Stay within the scope of the provided facts; do not speculate beyond them.

**Example** Case facts: Plaintiff slipped on wet floor in store; legal_issues: negligence; jurisdiction: California; evidence: surveillance footage.

**Follow-ups**
- What are the potential implications of recent legal developments on this case?
- How can we strengthen our case based on the current evidence?
- What alternative legal strategies could we consider?
