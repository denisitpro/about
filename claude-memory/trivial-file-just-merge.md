---
name: trivial-file-just-merge
description: "A non-code file (LICENSE, copy, docs) is copied, PR'd and merged without test runs, gate hunting or a long report"
metadata:
  node_type: memory
  type: feedback
  originSessionId: 089a64c6-cd07-455f-a702-052c314270b7
  modified: 2026-10-21T07:59:09.973Z
---

For a non-code change such as adding a LICENSE file: copy it, open the PR, merge it, report in one line. Do not try to run `make check`, look for CI, or explain why tests could not run.

**Why:** 2026-10-21 the owner was angry that adding lux-l7's LICENSE turned into a test run attempt (Go missing), a CI investigation and a long caveat list ("тесты ради тестового файла").

**How to apply:** test gates are for code changes. For text/legal/asset files, skip them silently and keep the status report short: what changed, merged, link.
