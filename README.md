# Vancouver Hospice Society conference article

A standalone static webpage prepared for the `/conference` path. It uses relative links for its local stylesheet, logo, and article photos, so it can be opened directly from `index.html` or served as a directory.

For a local preview from the repository root:

```sh
python -m http.server 8000 --directory outputs/website
```

Then open <http://localhost:8000/>. The YouTube players and Google Fonts need an internet connection; the article text, navigation, logo, and photos are local.
