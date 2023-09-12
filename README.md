# About this Repo

This is the Git repo of a custom build of Odoo maintained by OmnidApps. The Docker image is hosted [here](https://registry.hub.docker.com/r/omnidapps/odoo).

# Derivative Work

This image is built on a fork of the [official Odoo image](https://hub.docker.com/_/odoo).

## Changes

1. Added `master` tag pointing to latest Odoo dev nightly build.
2. Removed 14/15/16 tags for now until/if we maintain a fork of those or any other upstream tags.

# Build

If you'd like to build a local copy, you can run:

```bash
docker build . -t omnidapps/odoo:master # or see .github/workflows/build.yml
```

