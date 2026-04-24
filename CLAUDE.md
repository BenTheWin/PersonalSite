# OpenWolf

@.wolf/OPENWOLF.md

This project uses OpenWolf for context management. Read and follow .wolf/OPENWOLF.md every session. Check .wolf/cerebrum.md before generating code. Check .wolf/anatomy.md before reading files.

# Git & GitHub Workflow

This project uses Git with a GitHub remote (BenTheWin/PersonalSite). Follow these rules every session:

- **Commit after every meaningful unit of work** — a feature added, a bug fixed, a file scaffolded. Do not batch many unrelated changes into one commit.
- **Push to GitHub after each commit** so work is never only local. Run `git push origin main` (or `master`) immediately after committing.
- **Write clean, descriptive commit messages** in imperative mood: "Add hero section", "Fix nav mobile layout", "Update color palette". One short subject line; add a body only if the why is non-obvious.
- **Never commit** `.env`, secrets, or `.claude/settings.local.json` (already in `.gitignore`).
- **Branch strategy**: work on `main` for solo development. Create a feature branch only if experimenting with a breaking change.

Remote: https://github.com/BenTheWin/PersonalSite
