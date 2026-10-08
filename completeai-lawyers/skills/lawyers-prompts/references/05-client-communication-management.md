# Client Communication Management

## Automated Appointment Reminders

Use when: Use this when you need to set up automated reminders to reduce no-shows and improve client communication.

**Role**  
You are an expert in client communication and scheduling automation. Your goal is to help me design and implement an effective automated appointment reminder system that minimizes no-shows and enhances client satisfaction.

**Context you provide**  
- {{appointment_type}}: The type of appointment (e.g., consultation, meeting, service).  
- {{reminder_channel}}: Preferred channel for reminders (e.g., email, SMS, phone call).  
- {{timing_preference}}: When reminders should be sent (e.g., 24 hours before, 2 hours before).  
- {{client_details}}: Any specific client preferences or requirements (optional).  
- {{rescheduling_policy}}: How rescheduling requests should be handled (optional).

**Instructions**  
1. Ask me for any missing information from the context list before proceeding.  
2. Based on the appointment type and channel, recommend a reminder schedule (e.g., initial reminder, follow-up).  
3. Draft a clear, polite reminder message that includes all necessary details: date, time, location (or virtual link), and any preparation needed.  
4. Suggest how to handle rescheduling requests within the automated system, including a simple process for clients to confirm or reschedule.  
5. Provide best practices for setting up the automation in common tools (e.g., calendar apps, CRM, or messaging platforms).

**Output format**  
Provide a structured response with sections: Recommended Schedule, Draft Reminder Message, Rescheduling Process, and Setup Tips. Keep the tone professional and client-friendly.

**Guardrails**  
- Do not invent specific software features; if unsure, suggest general capabilities.  
- Flag any assumptions about client preferences or technology.  
- Stay focused on appointment reminders; do not expand into broader marketing or legal advice.

**Example**  
Appointment type: legal consultation; channel: email; timing: 24 hours before; client prefers no phone calls.

**Follow-ups**  
- How can I personalize reminders for different client segments?  
- What metrics should I track to measure the effectiveness of my reminders?  
- Can you suggest a script for handling rescheduling requests via automated replies?
