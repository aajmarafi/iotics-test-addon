# Iotics test add-ons

Home Assistant add-on repository for **Iotics test builds**.

Add this repository in Home Assistant (Settings → Apps → Add-on store → ⋮ → Repositories):

```
https://github.com/aajmarafi/iotics-test-addon
```

It contains only the add-on settings (`iotics_test/config.json`, changelog, docs, icons). No source code. The add-on runs the private Docker image `aliajmarafi/iotics-test`, so Home Assistant needs Docker Hub registry credentials to install it.

This repository is updated automatically by the build workflow after every test build.
