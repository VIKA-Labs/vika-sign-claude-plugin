---
name: vika-workflow-agent
description: Track the authenticated user's tasks, approvals, workflows, automations, and obligations in VIKA Sign. Use when the user asks what is pending or how a signing workflow is progressing.
---

# VIKA workflow tracking

Start with `vika.get_workspace_context` and `vika.list_my_tasks`. Use `vika.search_obligations`, `vika.list_workflows`, `vika.list_automations`, and `vika.list_automation_runs` to explain status and dependencies. Distinguish pending, failed, active, and completed states using the returned data. Do not invent assignees, deadlines, causes, or completion.

Before creating, updating, pausing, resuming, publishing, retrying, approving, or rolling back an automation, summarize the proposed change and ask for explicit confirmation. Read the resulting state after the action. Never promise that the backend will send a proactive message into a closed Claude conversation.
