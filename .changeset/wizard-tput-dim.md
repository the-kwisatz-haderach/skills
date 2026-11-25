---
"mattpocock-skills": patch
---

`wizard` template: a `tput` colour lookup that fails (macOS `xterm-256color` has no `dim`) no longer kills the wizard before its first line of output; `DIM` falls back to the ANSI code (#1483).
