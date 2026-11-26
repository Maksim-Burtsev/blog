---
date: 2026-11-26
url:
media: text
---

Teams adopt coding agents to ship faster. Almost nobody spends time optimizing their GitLab or GitHub CI.

On one of my last four projects, tests dropped from 12–15 minutes to 90 seconds. And there is no rocket science behind it.

Tests:
- parallelize runs
- Postgres template DBs and transaction rollbacks
- profile and rewrite the slowest
- delete useless ones

Builds:
- fix missing caches
- use multi-stage builds
- pick slim images where you can
- switch to a Rust package manager (like uv) for faster installs

Five teams, a few releases a day: around 1,000 engineering hours saved a year. No more waiting 15 minutes, hitting one flaky test, and waiting 15 more

Tests and linters are basic DX for the team and the baseline checks for coding agents. Better agents mean more work getting done and more CI jobs running. Tuning your jobs matters just as much as tuning your agent harness or CI becomes a bottleneck really fast.

What else has worked for you to speed up CI and improve DX? Curious what works for others and what kind of new tricks I can use.
