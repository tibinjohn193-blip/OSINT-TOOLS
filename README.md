# OSINT Global Master Directory

A responsive, static educational OSINT tools directory designed for GitHub Pages.

## Current catalogue status
This starter release contains **50 seed entries** across multiple OSINT categories. These are not represented as 1,500 independently verified tools. Every entry is marked "Seed entry – verify before publication" because tool availability, CLI syntax, licensing, and official links can change.

## Run locally
From this folder:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `osint-global-master-directory`.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
5. Your site will be published at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Add more tools
Edit `assets/tools.json`. Each object should contain:
- `id`, `name`, `category`, `publisher`, `url`, `pricing`
- `description`, `installation`, `example1`, `example2`, `safety`
- `status`, `lastVerified`

Use real, distinct tools; verify the publisher's official page and current install instructions before changing status to verified. Never put API keys, passwords, private URLs, or personal data in this public repository.

## Important
- This is an educational directory, not an endorsement of every tool.
- Only investigate assets and accounts you own or are authorised to assess.
- Do not use exposed credentials or attempt unauthorised access.
- Search results and username matches are leads, not proof of identity.
