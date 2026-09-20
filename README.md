# Zixuan Chen — Academic Homepage

Academic homepage using the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.
The theme is vendored locally (upstream commit `1ea07f39518ac44644406380c83da6f89037c4fc`), so GitHub Pages does not need to fetch a remote theme.

## Editing

- `_config.yml`: name, position, affiliation, photo, contact links and site URL.
- `index.html`: biography, research interests, news, honors, services and internships.
- `_data/publications.yml`: all 17 selected publications, grouped by year; HTML emphasis in authors and venue is supported.
- `assets/css/custom.css`: small layout adjustments layered over Minimal Light.
- `images/new.jpg`: original profile photo.

## Preview

Install Ruby and Bundler, then run `bash run_server.sh`.
Open <http://127.0.0.1:4000/homepage/>.
For a production build, run `bundle exec jekyll build`.

## GitHub Pages

The site targets <https://chenzixuan99.github.io/homepage/> with `baseurl: /homepage`.
Publish the repository root using the existing GitHub Pages branch configuration.
When moving to a root user site or custom domain, update `url` and set `baseurl: ""`.
The `/about/` and `/about.html` redirects and existing section anchors are preserved.
The existing citation crawler workflow remains unchanged.

## Credits

Minimal Light is MIT licensed; see `LICENSE-minimal-light`.
Original AcadHomepage licensing is retained in `LICENSE`.
