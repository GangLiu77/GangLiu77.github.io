# Gang Liu's homepage

The homepage contains About, News, Publications, Education, and Miscellaneous on one page.

- `_pages/about.md`: biography, education entries, and miscellaneous interests.
- `_news/`: news entries, displayed by month.
- `_bibliography/papers.bib`: publications, displayed as a numbered text list in file order.
- `_data/socials.yml`: navbar contact links.
- `assets/img/prof_pic.jpg`: profile photograph.
- `assets/img/iirl-logo.png`: lab logo from its official website.
- `assets/img/nd-logo.png`: Notre Dame tab icon from static.nd.edu.
- `assets/pdf/Gang_Liu_CV.pdf`: downloadable CV.

`_layouts/about.liquid`, `_layouts/bib.liquid`, and `_includes/header.liquid` control the homepage layout. `_config.yml`, `Gemfile`, the package files, and `.github/workflows/deploy.yml` support the site build and deployment.

`_unused/` stores template examples, unused pages, sample assets, documentation, and development tools in their original directory structure. It is excluded from the site build.
