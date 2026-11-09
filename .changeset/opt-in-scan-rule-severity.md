---
"react-doctor": patch
"@react-doctor/core": patch
---

Run opt-in security-scan rules when `doctor.config` pins them to a severity, for example `"rules": { "react-doctor/agent-tool-capability-risk": "error" }`. Category-wide severity overrides still leave those rules dormant.
