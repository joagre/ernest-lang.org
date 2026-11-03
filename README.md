# ernest-lang.org

The site at https://ernest-lang.org, one page: what Ernest is and where it is read. `site/` is what the server serves, as it stands; nothing is built.

| File | What it is |
|---|---|
| `site/index.html` | the page |
| `site/404.html` | what a missing address answers |
| `site/style.css` | the stylesheet |
| `site/ernest-combined-light.svg`, `site/ernest-combined-dark.svg` | Ernest's logo, from the release's `share/doc/ernest/assets/` |

The server is [ernest-httpd](https://github.com/joagre/ernest-httpd); its `deploy/README.md` says how the site is put on the machine: the files of `site/` copied under `/home/httpd/ernest-httpd/site/`.

This page is served until the site generated in Ernest's repository, `make site` there, goes live with the shell page among its pages; then this repository goes.
