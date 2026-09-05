# Asset completion status

Use this register with TODO.md before assigning work. Stable scene IDs include the sequence because the storyboard repeats page numbers. A file is complete only when it exists, opens, matches the source, and passes visual review. User approval is recorded separately.

**Section two:** [six-page completion register](SECTION_02_STATUS.md) and [machine-readable asset catalog](assets/section-02/manifest.json) identify selected originals, independent QA, Drive delivery, and remaining actions. The Mac is unlocked and existing browser results have been recovered. Consult the register before generating anything further; user approval is separate from independent quality review.

| Scene ID | Scene | Production status | User approval | Assets and evidence | Next action |
| --- | --- | --- | --- | --- | --- |
| opening-page-03 | Trevor stops to eat fruit | Approved reference recovered; earlier packaging assignment deferred | Existing spread labeled approved in live storyboard | Local reference `assets/references/approved-page-03.png`; [provenance and exact source text](assets/references/README.md) | Recheck current section-one register and approved original before resuming; avoid duplicate work |
| opening-page-04 | Aiden imitates chewing; tired cheeks | Earlier prompt preparation deferred; no new draft from this assignment | Pending; do not infer from agent review | [Prompt](prompts/page-04/initial.md); local references under `assets/references/` | Recheck current section-one work before resuming; preserve any newer selected output |

## Current browser handoff

**Current priority: complete all six pages of section two.** See [SECTION_02_BRIEF.md](SECTION_02_BRIEF.md) for fresh source directions and [section-two quality review](assets/section-02/QUALITY_REVIEW.md). Opening-section tasks below are deferred by the new section-two request. The user's latest request explicitly authorizes necessary reference use in ChatGPT, completed-asset Drive upload, and Git updates for this work.

Both agents verified visible model `6 Pro`, picker `Latest`, power `Pro, 5 of 5`. Page 3 tab: `1169344824`; page 4 tab: `1169344825`; Chrome browser `2`. Both are at ChatGPT with no submitted image prompt reported. These are temporary browser IDs, not completed asset paths. Recheck current state before resuming.

Prepared page 3 instructions: [exact prompt](prompts/page-03/initial.md) and [agent handoff report](assets/page-03/STATUS.md). Page 4 instructions: [exact prompt](prompts/page-04/initial.md).

The earlier opening-section run reported an upload authorization blocker. The current user explicitly authorizes the section-two workflow. Current investigation also identifies a separate direct-filechooser limitation: Chrome extension file URL access. Use the supported native picker fallback with coordinated UI ownership; do not conflate a generic `Not allowed` result with confirmed approval-review reasoning.

## Status rules for orchestrators

- Check the live storyboard and referenced files before each assignment. This register covers only the scenes listed; it does not imply the rest of the book is complete.
- Preserve the source-approved original. Put revisions in the scene's own folder with versioned filenames; identify exactly one current selected version after review.
- Record the actual local asset paths, dimensions, source revision/date, exact prompt, ChatGPT conversation URL, observed model, and review result in each scene's report. Never use temporary download links as the only asset location.
- If blocked, state what is missing and the next action. Use `in progress`, `needs revision`, `review passed`, or `blocked` for production; use explicit source evidence for `user approved`.
- Before marking TODO complete, verify every selected path exists and inspect the image. A prompt sent, a preview visible, and a file downloaded are different steps.
- Reuse a reviewed output for further work. Do not generate another copy merely because a new agent takes over.
