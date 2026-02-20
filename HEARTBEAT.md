# HEARTBEAT.md - Pending Tasks

Tasks listed here will be executed during heartbeat cycles (autonomous mode).

## Format

- [ ] Task description (include context needed to complete it)

## Recurring Tasks

### Daily at 7:00 AM Pacific
- [x] **GitHub Trending Summary**: Fetch https://github.com/trending, summarize the top trending repositories as a markdown table (repo, description, language, stars today, total stars) with a short "Themes & Takeaways" section, and append/update it in today's journal at `memory/YYYY-MM-DD.md` under a `## GitHub Trending Repositories` heading. Each repository name in the table must be a clickable markdown link to its GitHub page (e.g. `[owner/repo](https://github.com/owner/repo)`).

### Daily
- [x] **LocalGPT New Tag Check**: Fetch https://github.com/localgpt-app/localgpt/tags and check for new tags. Compare against `Last known tag` in MEMORY.md. If a new tag exists, alert the user immediately. Update MEMORY.md with the new tag and check date.

## Current Tasks

(No pending tasks)
