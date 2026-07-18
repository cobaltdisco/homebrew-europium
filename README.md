# Homebrew tap for Europium

[Europium](https://github.com/cobaltdisco/europium) — a macOS build of ungoogled-chromium
where no browser extension can put items into your right-click menus.

```bash
brew tap cobaltdisco/europium
brew install --cask europium
```

Update with `brew upgrade --cask europium`.

**Apple Silicon only.** There is no Intel build — Homebrew will refuse to install on Intel
rather than give you an app that cannot run.

**No auto-updater**: this browser never updates itself, so `brew upgrade` is the update
path. A browser you don't update is a security risk.
