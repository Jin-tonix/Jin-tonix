# Jinhee Mok (목진희)

**AI Engineer (Agents & Automation)** at StyleSeller, a Korean social-commerce company. I moved from law and teaching into development in 2024. Since Nov 2025 I have led AI and automation work, moving repeated staff work into AI agents and internal tools. I run what I build.

I write most code with Claude Code. I decide what to build, what to turn on in production, and I check the results. The systems only propose; staff confirm.

## What I run (private repos)

- **Status board and ledger.** Merges KakaoTalk rooms, shared mailboxes, Slack, and emailed order sheets into one dated calendar per counterpart (400+ partners). Records are linked by fixed rules, not an LLM. Anything it cannot match goes to a staff queue.
- **Vendor support agent.** Answers only when tagged, only for a matched vendor, and checks every amount in a draft against sources before it is sent.
- **Internal work tool.** Price calculation ported from a spreadsheet, catalog parsing, partner matching, personalized KakaoTalk campaigns with an approval gate.
- **Email agent and knowledge hub.** Grounded reply drafts that land in the owner's Gmail drafts; staff send them. Unsupported claims are rewritten, then dropped.
- **Agent platform and Spark.** A Paperclip fork with a tool gate, one-time approvals, a hard daily spend cap, and a skill router for the sub-agents that Hermes assigns work to: BM25 search pulls candidates from all shared skills, a judge model (Jev) checks gating and fit, and Gemini makes the final pick. Gemini now reviews 5 skills instead of 115, and the router scored 90.15% on a 132-case evaluation.
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

- Email: jinheemok815@gmail.com
- Phone: +82 10-9030-2888 (010.9030.2888)
- Site: [jin-tonix.github.io](https://jin-tonix.github.io)
- Location: Yeoksam-dong, Gangnam-gu, Seoul (서울시 강남구 역삼동)

Documents:
[Résumé (EN)](https://jin-tonix.github.io/resume/Resume_Jinhee_Mok.pdf) ·
[이력서 (KO)](https://jin-tonix.github.io/documents/%EB%AA%A9%EC%A7%84%ED%9D%AC_%EC%9D%B4%EB%A0%A5%EC%84%9C.pdf) ·
[Career description (EN)](https://jin-tonix.github.io/files/career-description-en.pdf) ·
[경력기술서 (KO)](https://jin-tonix.github.io/files/career-description-ko.pdf) ·
[Portfolio (EN)](https://jin-tonix.github.io/files/portfolio-en.pdf) ·
[포트폴리오 (KO)](https://jin-tonix.github.io/files/portfolio-ko.pdf)
