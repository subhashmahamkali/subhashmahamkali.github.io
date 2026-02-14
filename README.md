<p align="center">
  <img src="assets/logo-sm-dna.svg" alt="SM DNA logo" width="760">
</p>

# Sai Subhash Mahamkali - Portfolio Website

A research-driven portfolio focused on plant genomics, quantitative genetics, and computational biology.

Live site: [https://subhashmahamkali.github.io](https://subhashmahamkali.github.io)

## Core Structure

| Area | File / Folder | Purpose |
|---|---|---|
| Site config | `_config.yml` | Theme, plugins, global defaults |
| Navigation | `_data/navigation.yml` | Top menu links |
| Global style | `assets/css/main.scss` | Custom design, responsive layout, cards, media grids |
| Home page | `index.md` | Landing content and profile highlights |
| Journey page | `pages/journey.md` | Timeline plus undergrad/masters/CTRI visual story |
| Projects page | `pages/projects.md` | Project summaries |
| CV page | `pages/cv.md` | CV download link |
| Contact page | `pages/contact.md` | Public contact details |
| Videos page | `pages/videos.md` | Embedded and linked video content |
| Media guide | `assets/media/README.md` | Rules for media uploads |
| Favicon | `assets/favicon.svg` | Browser tab icon |
| Brand logo | `assets/logo-sm-dna.svg` | Project identity mark |

## Content Folders

| Type | Location | Notes |
|---|---|---|
| Undergraduate photos | `assets/media/photos/under_grad/` | Used in Journey page |
| Master's photos | `assets/media/photos/masters/` | `.jpg` preferred for web |
| CTRI photos | `assets/media/photos/CTRI/` | Fieldwork visuals |
| Web videos | `assets/media/videos/` | `.mp4` preferred |
| CV PDF | `cv/Subhash_CV.pdf` | Linked from CV page |

## Workflow

1. Add/update media under `assets/media/`.
2. Reference new files in `pages/journey.md` or `pages/videos.md`.
3. Adjust layout/design in `assets/css/main.scss` if needed.
4. Commit and push to `main` to deploy via GitHub Pages.

## Brand Notes

- Primary mark: `assets/logo-sm-dna.svg`
- Tab icon: `assets/favicon.svg`
- Theme direction: clean scientific identity, modern typography, high readability.
