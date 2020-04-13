---
title: Someone just pushed without rebasing
assignees: Rotemcyber, {{ payload.sender.login }}
labels: bad-push
---
Someone just pushed but did not ask for rebase, oh no! Here's who did it: {{ payload.sender.login }}.

{{ date | date('dddd, MMMM Do HH:mm') }}

in workflow
