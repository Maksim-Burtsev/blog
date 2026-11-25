---
date: 2026-11-18
url: https://www.linkedin.com/feed/update/urn:li:activity:7528790307123961856/
media: text
---

An agent always comes back saying everything works, so code review gets stuck on trust until the agent brings proof.

Trust moves when the agent shows you instead of stopping at code and tests. It starts the app, clicks through the feature and everything the change could touch, and records a before-and-after screencast.

I still read the code, but I do it calmly, knowing what was already verified instead of debugging every line in my head.

We took over a codebase and turned on the strictest linters: type checks, bans on many language constructs, and a huge number of error classes. Fixing everything flipped the whole project upside down across 200 files, +15,000 and −15,000 lines. With green tests, the agent went through every main flow, I checked the whole diff, we merged, and nothing broke.

The one real investment is explaining to the agent which flows are key and how to test them in the app. After that, keeping it up is cheap, and large changes ship without rollbacks.
