# PACMAN — Publication

Static publication page for **PACMAN**, a self-hosted manager for a live `proxy.pac`.

> A safe control plane for the file that routes everything: marker-scoped rules, a behavioural
> safety guard, atomic writes, versioned rollback, legacy PAC analysis, and honest limits.

This repository is the published artefact only. The product itself is maintained in a private
repository.

**Live:** https://odigiedavididemudia.github.io/pacman-publication/

## Contents

- `index.html` — the entire publication: HTML, CSS, and the theme toggle in one file.
- `.nojekyll` — serve the directory as-is on GitHub Pages.

There is no build step, no framework, and no external asset other than the Google Fonts link
(with a system-font fallback). The page ships light and dark themes, a manual toggle persisted in
`localStorage`, and a print stylesheet.

## Publishing model

The page is documentation, not a landing page. It publishes architecture and method only:

- no production hostnames, internal addresses, credentials, or organisation data;
- all examples use RFC 2606 / RFC 5737 reserved values;
- the two live defects described in section 09 were found in a real file and are reported by
  class, with sanitised hostnames.

## Authors

David Idemudia Odige — [github.com/OdigieDavidIdemudia](https://github.com/OdigieDavidIdemudia)
