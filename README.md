# century-arcade.github.io

[![pages](https://img.shields.io/github/actions/workflow/status/century-arcade/century-arcade.github.io/pages%2Fpages-build-deployment?branch=master&label=pages)](https://github.com/century-arcade/century-arcade.github.io/actions/workflows/pages/pages-build-deployment)

The front page of [centuryarcade.org](https://centuryarcade.org): one Markdown page built by GitHub Pages (Jekyll, the Primer theme) from `master`.

- `index.md`: the front page.
- `404.md`: the not-found page.
- `_config.yml`: site title, description and theme.
- `CNAME`: the custom domain.

The other sites under the domain are published from their own repos: [centuryarcade.org/xd/](https://centuryarcade.org/xd/) from `docs/` in [xd](https://github.com/century-arcade/xd), and [status.centuryarcade.org](https://status.centuryarcade.org/) from [status](https://github.com/century-arcade/status).

To preview locally: `bundle exec jekyll serve` with the [github-pages gem](https://github.com/github/pages-gem). `_config.yml` excludes this README from the site.
