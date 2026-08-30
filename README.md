# NaruBase™ — Installer Downloads

This repository hosts **installer downloads** for the NaruBase™ product
suite. Each product has its own folder, its own version manifest, and its
own tagged releases, so updates to one product never affect another.

| Product | Info | Latest release |
|---|---|---|
| **FlowReach** — local-business lead research | [flowreach/README.md](flowreach/README.md) | [Releases](https://github.com/louisbyun/narubase-install/releases?q=flowreach) |

More NaruBase™ products will be added here as they move to this
distribution repo.

## Structure

Each product's install materials live under `<product>/`:

```
<product>/
  README.md       product page (description, screenshots)
  version.json     update-check manifest the app polls
  logo.png
  ...screenshots
```

Releases are tagged `<product>-vX.Y.Z` (e.g. `flowreach-v1.0.0`) so tags
never collide across products.

## Source

Application source for each NaruBase™ product is maintained in its own
private repository. Bug reports and questions: open an
[issue](../../issues) here.

---

© 2026 narubox. NaruBase™ is a trademark of its respective owner.
