---
date: 2026-11-19
url: https://www.linkedin.com/feed/update/urn:li:activity:7529188281658318848/
media: text
---

Everything that breaks now gets blamed on AI slop. On production systems with real users I saw the opposite: we deliver more, and incidents dropped dramatically.

I compared our work before coding agents, and when the first weak ones appeared, against what we shipped this fall. Every branch now has far more tests. At the start of the year many were junk, and an agent told to fix a bug would just edit the test to pass; over the last quarter that barely happened. We also have capacity for more linters and code rules.

The bigger surprise came after release. Nights spent debugging are much rarer, and hotfixes fell once agents started testing the whole application, not only local tests. Bugs from a typo or a wrong method disappeared. Errors still happen, mostly in corner cases.

Once you put a little work into configuring agents for testing and verification, the payoff is huge. Quality climbs sharply, bugs fall, and you ship faster and more often. When agents take on the checks that used to cost engineer time, confidence in every release goes up.
