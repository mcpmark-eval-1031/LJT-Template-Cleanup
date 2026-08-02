---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This repository is a cleaned-down fork of the [Academic Pages template](https://github.com/academicpages/academicpages.github.io), reworked into a concise **template-cleanup report** rather than a full personal homepage. Only identity fields that are backed by memory are shown; every demo page, collection, navigation entry, and sidebar link that is not supported by memory has been removed or hidden.

## Profile

- **Name:** Junteng Liu
- **Affiliation:** Ph.D. candidate, HKUST NLP Group, Hong Kong University of Science and Technology (HKUST)
- **Research areas:** natural language processing and machine learning, including:
  - LLM reasoning and reinforcement learning
  - Hallucination in vision-language models (VLMs)
  - LLM truthfulness and interpretability
- **Contact:**
  - Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
  - GitHub: [Vicent0205](https://github.com/Vicent0205)
  - Google Scholar: [scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
  - X (Twitter): [@junteng88716710](https://x.com/junteng88716710)

## Removed from template

The following academicpages demo pages, collections, and workflows were removed (or hidden) because they are not supported by memory:

- **Publications workflow** — `_pages/publications.html`, the `_publications/` collection, the `publication_category` configuration block, and the `markdown_generator/` notebooks and CSV/TSV data used to generate publication pages.
- **Talks** — `_pages/talks.html`, `_pages/talkmap.html`, the `_talks/` collection, and the talk-map tooling (`talkmap.py`, `talkmap.ipynb`, `talkmap_out.ipynb`, `talkmap/`).
- **Teaching** — `_pages/teaching.html` and the `_teaching/` collection.
- **Portfolio** — `_pages/portfolio.html` and the `_portfolio/` collection.
- **Blog** — `_pages/year-archive.html`, all demo posts in `_posts/` and `_drafts/`, the category/tag archive pages, and the demo comment data in `_data/comments/`.
- **CV** — `_pages/cv.md`, `_pages/cv-json.md`, `_data/cv.json`, and the CV conversion scripts in `scripts/`.
- **Demo and guide pages** — the template Markdown guide, the archive-layout demo, the non-menu-page demo, the terms page, and the page/collection archive demos.
- **Navigation entries** — every demo entry in `_data/navigation.yml` (Publications, Talks, Teaching, Portfolio, Blog Posts, CV, Guide).
- **Demo identity fields and links** — the placeholder name, bio, employer, and location, plus the demo ORCID, PubMed, Bluesky, and other sidebar links in `_config.yml`; the demo entries in `_data/authors.yml`; and the demo attachments in `files/`.

## Kept for this site

- The Jekyll / Minimal Mistakes theme infrastructure (`_layouts/`, `_includes/`, `_sass/`, `assets/`) that renders the site.
- `_config.yml`, updated with memory-backed identity fields only: name, HKUST Ph.D. affiliation, research summary, email, GitHub, Google Scholar, and X.
- The author sidebar (`_includes/author-profile.html`), which now shows only Junteng Liu's name, HKUST NLP Group affiliation, and the memory-backed contact links.
- This single landing page (`_pages/about.md`), structured as the cleanup report above.
- Standard repository files (`LICENSE`, `Gemfile`, `.gitignore`, `_pages/404.md`, `_pages/sitemap.md`).
