# lintlab

**Pay-per-result tools that check web pages, sites, sitemaps and PDFs and return what is there or wrong, as JSON records.**

Four run on Apify, priced per result and charged only for completed results. One is a GitHub Action, [Visual Regression Check](https://github.com/lintlab/visual-regression-action), that diffs a pull request's preview against production. Every tool lists its limits next to its features.

## Live tools

All tools, with API examples: **https://lintlab.dev**

| Tool | What it does | Price |
|---|---|---|
| [Website Screenshot & Visual Regression Diff](https://apify.com/lintlab/screenshot-diff) | Full-page, viewport or element screenshots with an optional pixel diff against a baseline | $0.004 per capture, $0.002 per diff |
| [Broken Link Checker & Technical SEO Audit](https://apify.com/lintlab/seo-site-qa) | HTTP-only technical SEO audit: titles, meta, headings, canonicals, robots, internal links, duplicates | $0.004 per audited page; failed pages free |
| [PDF to Markdown & Text Extractor](https://apify.com/lintlab/pdf-to-markdown) | Public PDF URLs to page-aware Markdown or text with links, simple tables and metadata (no OCR) | $0.003 per processed PDF; failures free |
| [XML Sitemap Checker, Validator & URL Extractor](https://apify.com/lintlab/sitemap-doctor) | Finds sitemaps via robots.txt, validates every file (XML, gzip, indexes), extracts URLs with lastmod, diffs runs, optional status checks | $0.001 per sitemap file, $0.0003 per URL, $0.0005 per status check |
| [Visual Regression Check (GitHub Action)](https://github.com/lintlab/visual-regression-action) | Runs the screenshot diff on your PR preview against production and posts a pass/fail summary | Free action; $0.006 per compared page in Apify events |

Apify prices are Free-plan rates with platform usage included; paid Apify plans pay less per event. You (or your AI agent) pay only for results.

Support: hello@lintlab.dev
