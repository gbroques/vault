To be idempotent, only the state of the server is considered. The response returned by each request may differ: for example, the first call of a DELETE will likely return a 200, while successive ones will likely return a 404. Another implication of DELETE being idempotent is that developers should not implement RESTful APIs with a delete last entry functionality using the DELETE method.

**Source:** https://developer.mozilla.org/en-US/docs/Glossary/Idempotent

---
tags:
  - web-api
  - rest
  - idempotence
---
