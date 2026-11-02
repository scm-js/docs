# docs

The published copy of the [scmJS](https://github.com/scm-js/scm-js) documentation, served at
[docs.scmjs.dev](https://docs.scmjs.dev).

Nothing here is written by hand. The guides are the Markdown files under `docs/` in the
editor's repository, and that is where to read, change or report them. The editor's
`docs.yml` workflow builds them into the site with `npm run build:docs` and force-pushes
the result to this repository's `gh-pages` branch as a single commit. It runs on each
release, and by hand when a guide is fixed between releases.

The site has:

- the map maker's guide and the install guide
- the trigger reference and the TrigScript guides
- the plugin author's guide and the plugin API reference
- how maps are opened and saved, and the CHK format reference
- where the game data comes from
- the development guide
