# Heroku Buildpack: Git Submodule Init

This buildpack ensures that Git submodules are properly initialized during a Heroku deployment.

This buildpack fixes that by running:

```bash
git submodule update --init --recursive
```
