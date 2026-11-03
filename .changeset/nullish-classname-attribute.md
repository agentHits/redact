---
"@tanstack/redact": patch
---

Remove the `class` attribute when `className` is null or undefined instead of writing an empty `class=""`, so `[class]` selectors match the same elements as in React.
