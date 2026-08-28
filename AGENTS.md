# Programme planner: repository facts

- This repository contains the public export of the HU programme planner.
- The maintained builder is `Projects/Programme Explorer/build-prototype.py` in Freek's private Work-Files repository. Pass `--publish-dir` with this checkout's absolute path to refresh the public files.
- Keep edits to course data and shared behaviour in the source project. Regenerate the public copy before a publishing commit.
- Publish only `index.html`, `.nojekyll`, `sources/`, and these repository documents. Keep design feedback, private notes, and student data out of this repository.
- GitHub Pages serves `https://freekmetsch.github.io/hu-programme-planner/` from `/` on `codex/publish-programme-planner`. Read the Pages API for build status.
- The site is static and has no authentication or health endpoint. After deployment, check the root page, all three views, course filters, matching-code marks, phase credit totals, Remaining only, browser persistence, English/Spanish teaching separation, and source links in a logged-out browser.
- Roll back by reverting the affected commit and pushing the revert. Do not force-push.
