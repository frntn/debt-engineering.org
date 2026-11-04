# Debt Engineering

Public site for the DEBT Framework (Debt Engineering & Bet Tracking): [debt-engineering.org](https://debt-engineering.org).

The site is English and French. It is a [Jekyll](https://jekyllrb.com/) site published with GitHub Pages.

## Run locally

Ruby and Bundler are required. The `Gemfile` pins Jekyll and the plugins to the versions GitHub Pages builds with.

```bash
bundle install
bundle exec jekyll serve
```

Open [http://127.0.0.1:4000/](http://127.0.0.1:4000/). French: [http://127.0.0.1:4000/fr/](http://127.0.0.1:4000/fr/).

`jekyll serve` previews with canonical URLs pointed at localhost. `bundle exec jekyll build` uses `https://debt-engineering.org` from `_config.yml`, which is what GitHub Pages publishes.

## License

Text and site content are [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
