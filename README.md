# George Xiang Li — No-Code Portfolio CMS

This repository is a GitHub Pages + Jekyll website with Pages CMS as the editing layer.

## What changes for editors

After the one-time setup, normal content updates do **not** require editing HTML or CSS.

Editors can use Pages CMS to:
- edit homepage text
- change the logo
- add/edit projects
- upload cover images and galleries
- edit project sections in a rich-text editor
- choose which projects appear on the homepage

## One-time setup

1. Upload all files in this package to the root of `george-xiang-li.github.io`, replacing the old website files.
2. Wait for GitHub Pages to rebuild.
3. Go to `https://app.pagescms.org`.
4. Sign in with GitHub.
5. Install/authorize the Pages CMS GitHub App for the `george-xiang-li.github.io` repository.
6. Open the repository in Pages CMS. The `.pages.yml` file will automatically create the editing interface.

## Daily editing workflow

### Change homepage
Open **Website Home** → edit fields → Save.

### Edit a project
Open **Projects** → select the project → change text/images → Save.

### Add a project
Open **Projects** → New → fill in fields → Save.

### Add images
Use the image picker inside a project, or the media library. Images are stored in `assets/images`.

## Safe editing design

Project deletion and renaming are disabled in Pages CMS to reduce accidental breakage. A technical administrator can still make structural changes in GitHub when necessary.

## Site structure

- `_data/site.yml` — homepage content
- `_projects/` — project content
- `_layouts/` — fixed page templates
- `assets/images/` — all images and logo
- `assets/css/` — styling (normally not touched by editors)
- `.pages.yml` — Pages CMS editor configuration

## Important content rule

Only publish project claims, technical details, results, and student contributions that are supported by George's original materials. Website design support and project authorship should remain clearly distinguishable.
