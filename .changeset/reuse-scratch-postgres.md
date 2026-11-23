---
'@pikku/cli': patch
---

`pikku db` commands boot the embedded Postgres scratch database once per process and wipe it between uses, instead of booting a new one each time.
