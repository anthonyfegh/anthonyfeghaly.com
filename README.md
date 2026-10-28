# anthonyfeghaly.com — the AI for Founders workbooks (GitHub Pages)

Only the workbooks live here. `index.html` is the shelf; each `session-N/` has a small download page (`index.html`)
and the workbook itself as `workbook.bin`. The `.bin` extension is deliberate: GitHub Pages serves unknown types as
`application/octet-stream`, so the browser downloads it instead of rendering it, and the page's download button
renames it to its real name (`WorkbookSkills.html`, `WorkbookConnectors.html`). The workbook must run from the
student's computer: that is where it keeps the venture and the progress.

Update a workbook: copy the new build over `session-N/workbook.bin`, fix the size in `session-N/index.html` if it
changed a lot, commit, push. Pages rebuilds in about a minute.

- `session-3/`: the routines workbook (7 Oct 2026), downloads as WorkbookRoutines.html.
- `session-4/`: the build workbook (28 Oct 2026), downloads as WorkbookBuild.html (2.1 MB: seven published skills are embedded). No iPad copy: Codex and Claude Code need a laptop.

- `revive/`: Revive Wrapped 2026 demos for Revive (23 Oct 2026): after the password, a chooser between the member Wrapped and the coach Wrapped. Both pages (and the chooser labels) are one AES-GCM encrypted bundle (PBKDF2-SHA256, 600k rounds); the plain pages never enter this repo. Not linked from the shelf; `noindex`.
