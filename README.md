# Jinhee Mok (목진희)

**AI Engineer (Agents & Automation)** at StyleSeller, a Korean social-commerce platform that matches influencer sellers with brands for time-limited group buys.

I designed, built, and run the company's internal AI systems solo, from Dec 2025 to now. I write code with Claude Code. Architecture, rules, verification, and rollout decisions are mine.

## What I run in production (private repos, org: styleseller-co-kr)

- **Vendor support agent on KakaoTalk.** Personal chats have no official API, so collectors on staff PCs feed a grounded answer loop. Improved auto-replies are in staged rollout in a test room.
- **SS work tool (brand-tool).** An internal web app for staff. It started as a replacement for a spreadsheet price sheet. It now covers proposals, catalog parsing, sales-partner matching, seller discovery, and personalized KakaoTalk campaigns.
- **Spark · Work OS.** A company assistant over four databases with read-only roles, cited answers, and a Tool Registry. The registry defaults to dry run and runs only approved actions.
- **Email agent and knowledge hub.** Reply drafts are checked by rule validators and critics. Its LightRAG workspaces are shared by the other systems.
- **Staff PC tools.** One-line installers, sha256-versioned auto-update, and per-device keys, so no database key lives on a PC. 11 PCs registered (as of 2026-09-16).

Case studies: **[jin-tonix.github.io](https://jin-tonix.github.io)** · English: [jin-tonix.github.io/en](https://jin-tonix.github.io/en)

## How I build

- Project rules in CLAUDE.md and hooks. Examples: a pre-commit guard for hand-rolled Windows zips, and no deploy without verification.
- Every claim is checked against the code. The portfolio numbers come from a fact ledger re-run with git.
- I review AI output with a second model from a different source before merging risky changes.

## Open-source base

- The KakaoTalk tooling is a fork of an MIT-licensed KakaoTalk CLI (kakaocli). My 81 commits add delivery confirmation, duplicate-send guards, and window-detection retries. The fork is private because it contains company integration code.

## Contact

jinheemok815@gmail.com · [Résumé (EN)](https://jin-tonix.github.io/resume/Resume_Jinhee_Mok.pdf) · [경력기술서 (KO)](https://jin-tonix.github.io/resume/Career_Jinhee_Mok_KO.pdf)
