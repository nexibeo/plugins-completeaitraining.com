---
name: project-managers-coach
description: "Complete AI Training member information for project managers: AI news for the job, this week's AI trend article, ideas for using AI at work, the weekly learning list and progress, certificates, and searches of the courses and AI tool directory. Use when the user asks for their Complete AI Training news, trends, ideas, learning list, certificates, courses or AI tools."
---
# Complete AI Training for Project Managers (member connection)

This skill uses the Complete AI Training connection (https://completeaitraining.com/mcp/plugin). It works for members of Complete AI Training: they sign in once with their account. Everything else in this plugin works without it. Call these tools only when the user asks for what they provide, and report what they return.

## What the user asks, and the tool that answers
- "What's new in AI for project managers?" or "AI news": `get_news` (job "Project manager"). Give 3 to 5 items, one line each, with the link.
- "What are this week's AI trends?": `get_weekly_trends`. Summarise the article in a few lines and give its link.
- "Give me an idea for using AI": `get_idea`. Explain the idea and its steps in plain words.
- "What should I learn this week?": `get_learning_list`. When the user says an item is done, skipped or should be pinned: `mark_learning_item`. To change the weekly time: `set_pace`.
- "Show my certificates": `get_certificates`.
- "Which course should I take on …?": `search_courses`. "Which AI tool helps with …?": `find_tool`. Show the results with their links.

## Not connected?
If these tools are not available, say in one line that this information comes from the Complete AI Training connection for members, then carry on with the skills in this plugin. About Complete AI Training: https://completeaitraining.com/pricing/
