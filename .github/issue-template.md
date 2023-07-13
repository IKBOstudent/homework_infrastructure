---
title: Release {{ env.TAG }}
labels: [RELEASE]
---

sent on:    {{ date | date('YYYY-MM-DD hh:mm:ss ZZ') }}
created at: {{ env.COMMIT_TIME }}
sender:     {{ payload.sender.login }}
author:     {{ payload.head_commit.author.name }}

this is release text
