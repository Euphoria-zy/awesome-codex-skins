# Spider Terminal — credits and usage notice

This working theme is an unofficial, non-commercial Spider-Man fan project for the owner's personal use. It is not affiliated with or endorsed by Marvel, Sony Pictures, the performers, photographers, or the source publishers. Spider-Man and related film imagery remain the property of their respective rights holders.

## Active personal-use cinematic assets

The following WebP files are cropped, color-graded, or softly composited derivatives of the listed private design references. They must not be submitted to the upstream public repository or redistributed in a `.codexskin` without permission from the relevant rights holders and acceptance by the upstream maintainer.

| Theme asset | Reference and source | Credit |
|---|---|---|
| `assets/guardian-home-cinematic-v2.webp` | [`bnd-set-reddit-hawke2321-02.jpg`](https://www.reddit.com/r/Spiderman/comments/1tk15gj/bnd_set_photos/) | Hawke2321 / bex__pix |
| `assets/guardian-task-cinematic-v2.webp` | [`bnd-set-reddit-hawke2321-04.jpg`](https://www.reddit.com/r/Spiderman/comments/1tk15gj/bnd_set_photos/) | Hawke2321 / bex__pix |
| `assets/intro-city-v2.webp` | [Brand New Day trailer frame](https://www.youtube.com/watch?v=8TZMtslA3UY) | Marvel Entertainment / Sony Pictures |
| `assets/card-homecoming-v2.webp` | [Homecoming editorial still](https://www.gamesradar.com/entertainment/marvel-movies/spider-man-homecoming-2017-interviews/) | Sony / Marvel Studios via GamesRadar |
| `assets/card-far-from-home-v2.webp` | [Far From Home VFX still](https://image-engine.com/film/spider-man-far-from-home/) | Image Engine |
| `assets/card-no-way-home-v2.webp` | [No Way Home official still](https://www.marvel.com/movies/spider-man-no-way-home) | Marvel |
| `assets/card-brand-new-day-v2.webp` | [Brand New Day trailer frame](https://www.youtube.com/watch?v=8TZMtslA3UY) | Marvel Entertainment / Sony Pictures |

The full private source inventory and original URLs are kept outside the theme package in `spider-reference/sources.csv`.

## Generated structural artwork

The Manhattan wall, abstract fallback intro, console frames, selector pill, navigation glyphs, crest, watermark, workspace marks, and dual-state filament launcher were generated with OpenAI image generation tools and processed locally into WebP assets. Their prompts and processing record are stored in `studio/prompts/spider-terminal-imagegen.md`.

## Public-PR replacements

Original generated replacements for the reference-derived cards and characters are retained in:

- `studio/generated/spider-terminal-public-cards/`
- `studio/generated/spider-terminal-public-characters/`

Before an upstream pull request, restore those generated assets, remove the active cinematic derivatives from `skins/spider-terminal/`, take a real running-Codex preview, record the actually verified Codex version, and pass the repository's pack gate.
