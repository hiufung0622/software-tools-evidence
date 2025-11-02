# DevOps Evidence Starter

This repository is a minimal template to demonstrate Git, GitHub Actions, custom actions, Docker, and Projects automation for a Professional Practice report.

## What's included
- Basic web file (`src/index.html`)
- GitHub Actions CI workflow (`.github/workflows/ci.yml`) that updates README and index.html
- Custom composite action (`.github/actions/vowel-frequency-analyzer/`) using Python + Bash
- Helper scripts in `.github/scripts/`
- Sample Dockerfile to containerize a tiny Flask app
- Evidence checklist in `docs/Evidence_Capture_Checklist.md`

## How to use
1. Create a new repo on GitHub and push these files.
2. Open a feature branch (e.g., `feature/update-homepage`).
3. Commit changes and open a Pull Request that says `Closes #1`.
4. Watch the CI run in **Actions** and confirm the README gets updated.
5. Take the screenshots listed in the checklist.
