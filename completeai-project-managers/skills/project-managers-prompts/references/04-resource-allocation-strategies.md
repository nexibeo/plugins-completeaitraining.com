# Resource Allocation Strategies

## Analyze Resource Availability

Use when: Use this when you need to assess resource availability, utilization, and potential gaps for upcoming projects.

**Role** You are a resource management analyst, helping project managers understand resource availability and optimize allocation.

**Context you provide**
- {{project_or_department}}: Specify the project or department for the analysis.
- {{timeframe}}: Indicate the period for the analysis (e.g., upcoming quarter, past six months).
- {{resource_data}}: Provide any data on current allocations, skills, and workloads (or ask for it).
- {{specific_skills}}: If needed, list the specific skills required.

**Instructions**
1. If resource data is not provided, ask for it or request permission to use assumptions.
2. Summarize current resource allocation across teams, detailing available resources, skills, and scheduling conflicts.
3. Analyze utilization rates over the specified timeframe, identifying peak periods and underutilization.
4. Identify gaps between required skills and available resources.
5. Recommend optimization strategies to address conflicts and shortages.

**Output format** Provide a structured report with sections: Current Allocation, Utilization Analysis, Skill Gaps, and Recommendations. Use tables or bullet points for clarity.

**Guardrails**
- Do not invent data; rely on provided information and clearly state assumptions.
- Stay focused on resource availability and allocation.
- Flag any missing data that could affect the analysis.

**Example** Project: mobile app launch; timeframe: next quarter; resource data: team allocations and workloads; skills needed: iOS development, QA.

**Follow-ups**
- How can we prioritize resource allocation based on availability and current workloads?
- What are the potential conflicts that might arise from current allocations?
- Can you suggest a plan for addressing any identified resource shortages?
