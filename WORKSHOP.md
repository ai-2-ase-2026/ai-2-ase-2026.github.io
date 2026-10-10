# AI2ASE 2026 Hugo source

Website: https://ai-2-ase-2026.github.io/

The `hugo-source` branch stores the editable workshop source. The `master` branch in `ai-2-ase-2026/ai-2-ase-2026.github.io` stores the generated static website used by GitHub Pages. Source changes do not publish automatically.

## Build

Use Hugo **0.95.0 extended**, the version installed on the original maintainer's machine and verified to reproduce the published 2026 homepage, call for papers, dates, schedule, and papers pages byte for byte. The legacy Netlify configuration retains its original 0.87.0 setting. Keep `go.mod` and `go.sum` pinned to the existing Wowchemy revision.

From this source directory:

```sh
hugo
hugo server --disableFastRender --i18n-warnings
```

`hugo` generates the static site in `public/`. Review the result before copying it into a separate checkout of the `master` branch and committing/pushing. Preserve historical files in that checkout; do not use a copy command with deletion enabled. Never merge `master` into `hugo-source` or vice versa.

## Content

- `content/home/title.md`: workshop title.
- `content/home/theme.md`: introduction, date, venue, theme.
- `content/home/speakers.md`: speakers section.
- `content/authors/`: people and portraits.
- `content/home/organizing_comittee.md`: organizer section.
- `content/cop/_index.md`: call for papers.
- `content/dates/_index.md`: deadlines.
- `content/schedule/_index.md`: program.
- `content/papers/_index.md`: accepted papers.
- `config/_default/menus.yaml`: navigation and earlier editions.
- `config/_default/config.yaml`: base URL and Hugo configuration.

This is a historical copy of the matching 2026 source. Its base URL points to the 2026 archive. The published archive also preserves all historical static files from the original repository. Do not sync future main-site content into the archive.
