# Xiaoyu Ye · 冶晓宇

Academic homepage of Xiaoyu Ye, Ph.D. student at CUHK-Shenzhen, working on spatial intelligence, multimodal LLMs, and 3D scene reconstruction and generation.

- [Homepage](https://victor-xiaoyu-ye.github.io/)
- [Latest CV](https://victor-xiaoyu-ye.github.io/uploads/resume.pdf)
- [Publications](https://victor-xiaoyu-ye.github.io/#papers)
- [Research projects](https://victor-xiaoyu-ye.github.io/projects/)

## Editing and deployment

The website uses Hugo Blox with Hugo Extended 0.126.3. GitHub Actions builds and deploys pushes to `main` to GitHub Pages.

- Biography, education and experience: `content/authors/admin/_index.md`
- Publication pages and downloadable citations: `content/publication/`
- Combined BibTeX: `publications.bib`
- Research projects: `content/project/`
- Latest CV: `static/uploads/resume.pdf`
- Navigation and SEO settings: `config/_default/`

Conference submission and acceptance status is written explicitly on each publication page. Page dates control listing order; they are separate from the conference year. Template sample pages are retained as drafts and are not published.

## Search indexing

Hugo generates `sitemap.xml`; `layouts/robots.txt` advertises it. The Google verification file is published from `static/google565ff4fce33a07d6.html` at the site root, and `marketing.verification.google` contains only the verification token.

After deployment, use the verified URL-prefix property in Google Search Console to submit the sitemap and inspect/request indexing for the homepage. Search Console reports the actual indexing status; a successful deployment or ownership verification does not guarantee search inclusion.
