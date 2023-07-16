---
title: Release {{ env.TAG }}
labels: [RELEASE]
---

# Release `{{ env.TAG }}`

- published at: {{ env.CURRENT_TIME }}
- created at:   {{ env.COMMIT_TIME }}
- published at: {{ payload.sender.login }}
- author:       {{ payload.head_commit.author.name }}

<!-- All Checks passed: {{ env.CHECKS_LINK }} -->

Current version -------- {{ env.TAG }}
Previous version ---- {{ env.PREV_TAG }}
Total commits ------- {{ env.COMMITS }}

Changelog:
{{ env.CHANGES }}
