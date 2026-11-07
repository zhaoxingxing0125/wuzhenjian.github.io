# zhaoxingxing0125/wuzhenjian.github.io

Bilingual academic homepage for Zhenjian Wu. The website opens in English by default at `/`, and a complete Chinese mirror page is available at `/zh/`.

## Deployment

This checkout publishes to `zhaoxingxing0125/wuzhenjian.github.io`. Enable GitHub Pages from branch `main` and directory `/(root)`.

English: https://zhaoxingxing0125.github.io/wuzhenjian.github.io/

Chinese: https://zhaoxingxing0125.github.io/wuzhenjian.github.io/zh/

The project-site prefix is configured through `baseurl` in `_config.yml`.

## Structure

- `_pages/about.md`: English single-page homepage
- `_pages/about-zh.md`: Chinese mirror homepage
- `_data/profile.yml`: bilingual profile, education, experience, awards, and research-interest data
- `_publications/`: publication entries and working papers
- `_projects/`: research projects, data resources, methods, and collaboration topics
- `_data/navigation.yml`: bilingual anchor navigation and language switch targets
- `publications.html`, `projects.html`, `zh/*.html`, `en/*.html`: compatibility redirects to single-page anchors

## Maintenance

- Keep English and Chinese pages structurally aligned.
- Update publications, working papers, and research resources through structured entries first.
- Keep the public repo free of `个人材料/`, private attachments, `cv.pdf`, and any maintenance-only files such as `AGENTS.md`.

## Local Preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000`.
