# tools.juliakrylova.com

Ready-to-serve files of the interactive widgets used on pages of juliakrylova.com.

Everything here is build output. The files are generated from a private source repository and
copied here by its publish script, so do not edit them by hand: the next publish overwrites them.

- `mol-tools.js`: the widgets, one script without dependencies. It sends nothing anywhere and by
  default keeps nothing in the browser.
- `assets/fonts/`: Lora and Inter, loaded by the script from the same address. Both are under the
  SIL Open Font License, the license texts are next to the font files.
- `index.html`, `robots.txt`: an empty page, and a request to search engines to index nothing.

The repository root is published with GitHub Pages by `.github/workflows/deploy.yml` on every
push to `main`.
