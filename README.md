# Jinhee Mok (목진희)

**AI Engineer (Agents & Automation)** at StyleSeller, a Korean social-commerce company. I moved from law and teaching into development in 2024. Since Nov 2025 I have led AI and automation work, moving repeated staff work into AI agents and internal tools. I run what I build.

I write most code with Claude Code. I decide what to build, what to turn on in production, and I check the results. The systems only propose; staff confirm.

## What I run (private repos, org: styleseller-co-kr)

- **Status board and ledger.** Merges KakaoTalk rooms, shared mailboxes, Slack, and emailed order sheets into one dated calendar per counterpart (352 brands, vendors, and sellers). Records are linked by fixed rules, not an LLM. Anything it cannot match goes to a staff queue.
- **Vendor support agent.** Answers only when tagged, only for a matched vendor, and checks every amount in a draft against sources before it is sent.
- **Internal work tool.** Price calculation ported from a spreadsheet, catalog parsing, partner matching, personalized KakaoTalk campaigns with an approval gate.
- **Email agent and knowledge hub.** Grounded reply drafts that land in the owner's Gmail drafts; staff send them. Unsupported claims are rewritten, then dropped.
- **Agent platform and Spark.** A Paperclip fork with a tool gate, one-time approvals, a hard daily spend cap, and a router (Jev) that hints at shared skills while the worker chooses.
- **Content autopilot.** Reels requests to rendered video to approval, driven by a state machine with publishing off by default.
- **Staff PC rollout.** One-line installs and per-device keys on 11 Mac and Windows PCs.

Case studies: **[jin-tonix.github.io](https://jin-tonix.github.io)** · [English](https://jin-tonix.github.io/en)

## How I work

- Rules live in CLAUDE.md and hooks, not in my head.
- Every number in my write-ups was checked against code or logs.
- Risky changes get a second review from a different model before merge.

## Open source

- Fork of the MIT-licensed KakaoTalk CLI (kakaocli): change detection, wrong-room guards, image sends, hang timeouts, delivery confirmation. Private, because it holds company integration code.

## Contact

jinheemok815@gmail.com · [Résumé (EN)](https://jin-tonix.github.io/resume/Resume_Jinhee_Mok.pdf) · [Career description (EN)](https://jin-tonix.github.io/files/career-description-en.pdf) · [경력기술서 (KO)](https://jin-tonix.github.io/files/career-description-ko.pdf)
