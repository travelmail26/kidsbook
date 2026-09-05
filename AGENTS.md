# Agent instructions

- The [live Google Doc](https://docs.google.com/document/d/1f6nbea5M4BJEsfQdq17SvxFLUpuSjPrzEQhwimhki0I/edit?tab=t.0) is ground truth and may be edited by the user at any time. Recheck the relevant section before work; do not treat cached notes as current approvals. Follow explicit user directions and flag material conflicts.
- Read this file, then use [TOC.md](TOC.md) to select only necessary files or source sections. Do not bulk-read the repository, linked background, or historical notes.
- Locate actual reference images through [ILLUSTRATIONS.md](ILLUSTRATIONS.md). Preserve approved work, character continuity, and the separate left text/right illustration layout. Verify images before claiming to have inspected them.
- Keep [RUNNING_NOTES.md](RUNNING_NOTES.md) brief and current: active work, confirmed preferences, feedback, and unresolved questions. Replace superseded notes rather than accumulating history. Keep key paths in TOC.md current.
- After each completed task, if subagents are available, delegate a brief completion record to a logging subagent. Supply the outcome, changed paths, verification, and user preferences or feedback from the current task. The subagent owns [CHANGELOG.md](CHANGELOG.md) and the latest-changes section below; it must preserve others' edits.
- The logging subagent records an ISO 8601 timestamp with timezone, a concise change summary, and any explicit user preferences/feedback. Distinguish requests from completed work; never invent feedback. It updates the section below to the **three most recent changelog entries**, newest first (all entries if fewer than three exist).
- **The main agent must not read CHANGELOG.md.** Use the three summaries below for recent context. If subagents are unavailable, append a completion entry without reading history and refresh the three summaries using this file. A user request to update the changelog at task end follows the same procedure. Do not recursively delegate logging of the logging task itself.

## Latest changes

- **2026-09-05T14:56:03Z — Public documentation publication:** User approved publishing source links. README is verified on GitHub main; publication of all six Markdown files via the GitHub connector is in progress.
- **2026-09-05T14:43:57Z — Documentation scaffold:** Added README, TOC, agent guidance, running notes, illustration paths, and completion logging. Google Doc is ground truth; use selective reading and delegated logging. Scaffold link checks passed; no images imported.
