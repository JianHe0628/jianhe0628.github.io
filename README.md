# jianhe0628.github.io

Personal academic website of Low Jian He, built with Jekyll and served by GitHub Pages at <https://jianhe0628.github.io>.

## Where things live

| To change…                         | Edit                                  |
| ---------------------------------- | ------------------------------------- |
| Name, role, links, interests       | `_config.yml`                         |
| Bio paragraph                      | `_includes/bio.md`                    |
| News                               | `_data/news.yml` (newest first)       |
| Education & industry experience    | `_data/cv.yml`                        |
| Publications                       | `_publications/*.md` (one per paper)  |
| Page structure                     | `index.html`, `_layouts/default.html` |
| Styling                            | `assets/css/style.css`                |

### Adding a publication

Create `_publications/<year>-<short-name>.md`:

```yaml
---
title: "Paper title"
authors: JH Low, A Coauthor, R Bowden     # "JH Low" is highlighted automatically
venue: Full venue name
venue_short: CVPR 2026                    # shown in the tag
type: conference                          # conference | journal | preprint
date: 2026-06-01                          # used for ordering
presentation: Oral                        # optional (Oral, Spotlight, …)
award: Best Paper Award                   # optional, also highlights the entry
paper: https://…                          # optional
arxiv: https://arxiv.org/abs/…            # optional
code: https://github.com/…                # optional
---

Abstract (optional, shown behind the "Abstract" toggle).
```

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
