# Project Management Plan

**Business Sustainability Management Platform** — Software Project Management · Group Project PMP document.

## Group Members

| Name | Student ID | Role |
| ------ | ----------- | ------ |
| Liu Haopu (刘昊普) | | |
| Yao Tianren (姚天任) | | |
| Gong Zhijian (龚知健) | | |
| Li Sihang (李思航) | | |

## Repository Structure

```text
.
├── README.md
├── .gitignore
└── report/
    ├── main.tex          ← LaTeX source (edit this)
    └── figures/
        ├── pmp_header.png              ← decorative header image
        └── project_team_structure.png  ← org chart (replace with yours)
```

## How to Compile

You need a LaTeX distribution installed (e.g. [TeX Live](https://tug.org/texlive/) or [MiKTeX](https://miktex.org/)).

```bash
cd report
pdflatex main.tex   # first pass
pdflatex main.tex   # second pass (updates TOC & cross-references)
```

The output is `report/main.pdf`.

> **Tip (macOS/Linux):** Install `latexmk` and run `latexmk -pdf main.tex` inside `report/` — it handles the multi-pass compilation automatically.

## Editing Guidelines

- **Grey italic text** inside `\instr{...}` is placeholder instruction text. Replace it with your own content and delete the `\instr{}` wrapper when done.
- **Tables** already have the correct structure. Fill in the empty cells.
- **Org chart** — replace `figures/project_team_structure.png` with your group's actual org chart image.
- **Title page** — fill in `\instr{Project Name}`, `\instr{Group Number}`, and `\instr{Author Names}` in `main.tex` (around line 98–102).

## Contribution Workflow

```bash
# Before starting work
git pull

# After editing
git add report/main.tex
git commit -m "Section X: describe your change"
git push
```

Avoid committing `.aux`, `.log`, `.out`, `.toc` files — they are listed in `.gitignore`.

## Section Owners (assign as needed)

| Section | Owner |
| ------- | ----- |
| 1. Executive Summary | |
| 2. Integration Management | |
| 3. Scope Management | |
| 4. Schedule Management | |
| 5. Cost Management | |
| 6. Quality Management | |
| 7. Process Improvement Plan | |
| 8. Human Resource Management | |
| 9. Procurement Management Plan | |
| 10. Communications Management | |
| 11. Risk Management | |
| 12. References | |
