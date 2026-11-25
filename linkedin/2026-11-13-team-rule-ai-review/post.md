---
date: 2026-11-13
url: https://www.linkedin.com/feed/update/urn:li:activity:7526918950593667073/
media: text
---

My team has one rule about AI code review: keep yours to yourself.

Nobody forwards their agent's review to anyone else, whatever kind of review it is.

Does it work, does it solve the task, are there bugs? The author's agent has already checked that locally. Security, dependencies, code style and so on? Those are CI jobs, and they run on every branch automatically. Running all of that again on your machine makes no sense.

Top-tier models have been good enough for a while now that one review is all you need. A second one gives you the same findings in other words, cases that can't happen, or nitpicks made up to have something to say.

By the time a pull request is open, agents have reviewed it twice: with the author and in CI. In the comments, people talk to people.
