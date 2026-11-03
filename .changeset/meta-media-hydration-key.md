---
"@tanstack/redact": patch
---

Match `<meta>` by `media` as well during document hydration, so a same-name tag inserted before hydration (for example an active `theme-color`) is left alone and the server-rendered light and dark tags are adopted without mismatches.
