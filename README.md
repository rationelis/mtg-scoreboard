# MTG Scoreboard

A dedicated scoreboard for Magic: The Gathering Commander games.

## Overview

Design document in `docs/design-document.tex` describing a 4-screen device for tracking life totals and commander damage.

## Building

Requires a TeX distribution with TikZ (TeX Live, MiKTeX, or MacTeX).

```bash
cd docs
pdflatex design-document.tex
```

Alternatively, PDFs are built automatically on each push—download from the Actions tab.

## Installation

**Linux:** `sudo apt install texlive-base texlive-pictures`

**Windows:** Install [MiKTeX](https://miktex.org/download) with "Install missing packages on-the-fly"

**macOS:** `brew install --cask mactex`

## License

MIT