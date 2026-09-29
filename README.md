# Liu Liu Academic Website v3

A Quarto faculty-job-market website focused on quantitative methodology, measurement, educational statistics, and social-science methods.

## What is new in v3

- Added a top-level **Projects** section.
- Added five mature methodological project pages:
  - Bayesian variance priors in multilevel models
  - Variance-prior selection / translation / reporting tutorial
  - Sparse ordinal CFA and fit calibration
  - Bayesian prior calibration across measurement models and software
  - Longitudinal dyadic modeling with limited numbers of dyads
- Each project page includes the scholarly structure expected on a methods faculty site: project overview / abstract, paper status, supplement, code, design or workflow, and key findings or research questions.
- Public links are included only where a DOI or public URL is available. Non-public accepted manuscripts and code are labeled transparently rather than linked to placeholders.
- Homepage and publication entries now link directly to project pages.

## Render locally

Install Quarto, then run:

```bash
quarto preview
```

or

```bash
quarto render
```

## Publish with GitHub Pages

1. Create a GitHub repository for the site.
2. Replace `https://YOUR-USERNAME.github.io` in `_quarto.yml` with the final site URL.
3. Commit and push the project.
4. Use Quarto's GitHub Pages publishing workflow.

## Files to add later

The project pages intentionally do not invent links to manuscripts, supplements, or code that have not yet been made public. When those materials are ready, add them to the relevant project page and replace the current availability note with a direct link.
