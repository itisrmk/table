---
'@tanstack/table-core': patch
---

Retry memoized table computations after they throw, instead of caching the failed dependency tuple and returning the previous result
