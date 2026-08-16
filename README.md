# piv-pivot-screenshots-public

**Public image host** for Connections / HED UI visual-proof screenshots so they render
inline (`![](raw-url)`) in GitHub PR descriptions, Jira, and Confluence.

- **Images only** — no code, tests, or credentials. The tooling that generates these
  lives in the private `piv-pivot-screenshots` repo and the `hed-ui-visual-proof` skill.
- Layout: `shots/<TICKET>/<name>.png`.
- Inline reference (renders anywhere):
  `![nav-on](https://raw.githubusercontent.com/nomuto-collegeboard/piv-pivot-screenshots-public/main/shots/<TICKET>/<name>.png)`

> Only commit non-sensitive UI screenshots here (this repo is world-readable).
