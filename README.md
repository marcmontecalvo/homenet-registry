# HomeNet registry

The default add-on registry for [HomeNet](https://github.com/marcmontecalvo/homenet). `registry.json` lists add-ons by id; each entry points at that add-on's manifest (`addons/<id>.json`).

To add an add-on, open a pull request that adds its manifest under `addons/` and an entry to `registry.json`. See HomeNet's `docs/addons.md` for the manifest and registry formats.

HomeNet fetches `registry.json` from `https://raw.githubusercontent.com/marcmontecalvo/homenet-registry/main/registry.json`.
