# CV LaTeX Source

This directory contains the LaTeX source code for Luiz Augusto Fidalgo's CVs.

## Files

- `LuizAugustoFidalgo_cv_simple.tex` - Simple one-page CV
- `LuizAugustoFidalgo_cv.tex` - Full CV with profile picture
- `profile.png` - Profile picture for the full CV

## Automated Workflow

Both CVs are automatically compiled to PDF using GitHub Actions whenever changes are pushed to this directory.

### How it works:

1. **Edit**: Make changes to either `.tex` file
2. **Commit & Push**: Push your changes to GitHub
3. **Auto-compile**: GitHub Actions automatically compiles both LaTeX files to PDF
4. **Auto-update**: The compiled PDFs are automatically committed to the `downloads/` folder

### Workflow file:

`.github/workflows/compile-cv.yml`

### Manual trigger:

You can also manually trigger the workflow from the Actions tab in GitHub.

## Local compilation (optional)

If you want to compile locally:

```bash
cd cv
pdflatex LuizAugustoFidalgo_cv_simple.tex
```

Note: You'll need a LaTeX distribution installed (e.g., MacTeX for macOS).
