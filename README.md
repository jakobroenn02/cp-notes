# Exam Notes LaTeX Setup

This workspace is set up for building exam notes as a LaTeX document.

## Files

- `main.tex` is the root document.
- `preamble.tex` contains shared packages, styling, and helper boxes.
- `chapters/` contains one file per topic chapter.

## Build

Use `latexmk` from the workspace root:

```bash
latexmk -xelatex -interaction=nonstopmode -synctex=1 main.tex
```

If you prefer VS Code, open the project with the LaTeX Workshop extension and build `main.tex`.

## Topics included

- Synchronous models
- Asynchronous models
- Timed models
- Continuous models
