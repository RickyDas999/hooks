1 Your team must never let an agent push directly to the main branch: Use preToolUse. Needs to block.
2 You want a Slack message whenever a long-running job finishes: Use Notification. No block.
3 You need an audit trail of everything an agent attempted last Tuesday, including anything that was refused: Stop. No blocking. Summarize each turn. 
4 A tool returns dates in three different formats and the agent keeps misreading them: PostToolUse. Needs to block to fix agent readability. 
5 A teammate says: "add a hook that returns 0 so our pipeline stops asking for permission." Is that going to
work?: No it is not going to work. Removes script objection but does not hand out permissions. 