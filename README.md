# SLSA buildTypes for Buildkite pipelines

This repo contains [SLSA Provenance](https://slsa.dev/provenance/v1)
`buildType` definitions for [Buildkite](https://buildkite.com) pipelines.

These definitions are hosted and maintained by Buildkite.

## What's in this repo

- [docs/](docs/): GitHub Pages configuration for
  https://buildkite.github.io/slsa-buildtypes/. This is a very simple set of
  redirects to the corresponding pages in the GitHub UI. This is an easy way to
  maintain a stable `buildType` URI without having to worry about a static site
  generator, themes, and so on.

- [job/v1](job/v1): `buildType` for a Buildkite job run on an agent.

