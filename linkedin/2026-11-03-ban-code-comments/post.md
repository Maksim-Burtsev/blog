---
date: 2026-11-03
url: https://www.linkedin.com/feed/update/urn:li:activity:7523441973891072000/
media: text
---

Comments don’t change how code runs. Yet deleting them from my Rust project took almost two weeks.

About a third of them were the only record of why the code was built this way and not another. Strip that note, and the next agent “fixes” the code without knowing why and breaks something somewhere else. So it wasn’t just clearing out about 10,000 lines of comments. It meant refactoring and fixing the bad design decisions they were covering for.

That’s the reason people at conferences give when they say their teams have banned comments. People write them to add context or explain a decision. Agents write them to justify a bad one.

Now about six projects I work on have the same rule.
