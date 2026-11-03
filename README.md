# AIRSHIP Lab

AI Reasoning for Scientific Hypotheses, Inferences, and Predictions.

Website: https://airship-lab.github.io/

A static website hosted by GitHub Pages from the root of the `main` branch.
No package installation or build step is required. `.nojekyll` disables Jekyll processing.

## Pages

- `index.html`: lab introduction and original logo.
- `members/index.html`: core members and profile links.
- `research/index.html`: selected publications.
- `styles.css`: shared layout, header, typography, and responsive styling.
- `assets/airship-logo.png`: original lab logo.

The header is shared markup in each HTML page; update all three pages when changing navigation.
To preview locally, run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

## Member portraits

Portraits are copied from the members’ own or university profile pages:

- James Unwin: https://jamesunwin.github.io/assets/img/prof_pic.jpg
- Richard Cavanaugh: https://phys.uic.edu/wp-content/uploads/sites/276/2018/07/cavana-profile-157x180.jpg
- Laura Schaposnik: https://lauraschaposnik.com/assets/img/prof_pic.jpg
- Lev Reyzin: https://www.levreyzin.com/assets/img/lev-optimized.jpg

The estimated July 2025 appearance date for “Cross-Validation Error Dynamics in Smaller Datasets” is based on its MOSS 2025 workshop version (the workshop was held on 19 July 2025): https://sites.google.com/view/moss2025/accepted-papers. It remains last in the publication list by request.

## Stylesheet caching

All three pages use a versioned stylesheet URL so browsers do not combine a new page layout with cached CSS. Whenever `styles.css` changes, update the `?v=` value in each page to the first 12 characters of the CSS file’s SHA-256 hash. The logo also has a small intrinsic display size as a fallback while CSS loads.

## Partner symbols

- Equitech Futures: official site icon from https://www.equitechfutures.com/ — https://cdn.prod.website-files.com/67a498f10e7c0758d8cd4650/67b301ec422dbb33bcb63e93_fav%20EF.png
