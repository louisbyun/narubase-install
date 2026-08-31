# NaruBase™ — Installer Downloads

This repository hosts **installer downloads** for the NaruBase™ product
suite. Each product has its own folder, its own version manifest, and its
own tagged releases, so updates to one product never affect another.

| Product | Info | Latest release |
|---|---|---|
| **Wireless** — local Wi-Fi/BLE security monitoring | [wireless/README.md](wireless/README.md) | [Releases](https://github.com/louisbyun/narubase-install/releases?q=wireless) |
| **Probe** — local network/DNS/TLS diagnostics | [probe/README.md](probe/README.md) | [Releases](https://github.com/louisbyun/narubase-install/releases?q=probe) |
| **FlowReach** — local-business lead research | [flowreach/README.md](flowreach/README.md) | [Releases](https://github.com/louisbyun/narubase-install/releases?q=flowreach) |
| **Cloud** — SSH server management with AI assistance | [cloud/README.md](cloud/README.md) | [Releases](https://github.com/louisbyun/narubase-install/releases?q=cloud) |

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
