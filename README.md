ClickUp Completed / Deployed Tasks → Daily Google Sheet AccumulatorThis automation:
• Triggers when a ClickUp task status changes to "deployed" or "completed"
• Fetches full task details
• Formats each task nicely (• Task Name + Created/Start/End in PKT / Asia/Karachi timezone)
• Accumulates completed tasks per member per day in Google Sheets column "Completed Tasks"
• Increases "No_of_Completed_Tasks" counter
• Prevents duplicate entries if the same task triggers the webhook multiple timesPart of a consistent set of daily productivity trackers used for different teams and different task lifecycle stages (devops, backend, frontend, QA, AI, etc.).Integrations
ClickUp (webhook trigger + get task)
Google Sheets (lookup → append or update row by unique_key = memberId_date)
JavaScript nodes (PKT date formatting + duplicate detection logic)
Great for sprint retros, weekly reports, individual performance tracking, or seeing who is actually shipping work.
