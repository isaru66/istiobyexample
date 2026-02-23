# Istio by Example

This repository contains the source code and YAML files for the [Istio by Example](https://istiobyexample.dev) site.

**⚠️ Note**: These samples are last updated to the [Istio 1.5 release](https://github.com/istio/istio/releases/), and are no longer under active development. See the [Istio documentation](https://istio.io/) for the most up-to-date examples.

## Local Development

**Prerequisites:** [Hugo](https://gohugo.io/installation/) must be installed.

**Build the site** (output goes to `docs/`):
```sh
hugo -t hugo-notepadium
```

**Serve locally with live reload:**
```sh
hugo server -t hugo-notepadium
```

Then open [http://localhost:1313](http://localhost:1313) in your browser.
