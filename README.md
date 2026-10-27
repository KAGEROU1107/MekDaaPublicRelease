# MekDaa Public Release — official site

This repository hosts the **public information site only** for MekDaa: home, support, privacy policy, and terms of use. **It is not the MekDaa session database**. ChatGPT session records live in each user's selected Google Drive workspace.

The public source has a clean, independent history and must never be populated by forking, mirroring, or directly pushing branches/commits from the private MekDaa development repository.

## Website

GitHub Pages can publish this site from `main` → `/ (root)`.

Expected URL **after Pages is enabled and independently verified**: `https://kagerou1107.github.io/MekDaaPublicRelease/`.

## Support

Use [public GitHub Issues](https://github.com/KAGEROU1107/MekDaaPublicRelease/issues). Never submit private session content, Google Drive folder IDs/links, passwords, credentials, or tokens in public issues.

## Publishing/security

- Commit with your GitHub-provided `noreply` email; inspect the raw commit metadata after every first/public push.
- Do not import Git history from the private repository.
- Do not commit secrets, user data, credentials, installation configurations, or Drive documents.
- Keep `main` branch protected with an applicable ruleset and prevent force pushes or deletion.
- Avoid adding workflows with broad `GITHUB_TOKEN` permissions, unreviewed third-party GitHub Actions, or external scripts.
- Published files: static HTML/CSS and a packaged public icon; no analytics, forms, login, server code or session storage.

Publisher: KAGEROU. MekDaa is free to use.