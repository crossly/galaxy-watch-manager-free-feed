# Galaxy Watch Manager Free — update feed

Public, machine-generated update feed for the **private** app repository
[`crossly/galaxy-watch-manager-free`](https://github.com/crossly/galaxy-watch-manager-free).

This repository intentionally contains **no source code and no APK**. It only
publishes version metadata so the installed app can tell whether a newer release
exists; the app itself lives in the private repository above and its release
assets still require GitHub authentication to download.

`version.json` is rewritten by the release workflow of the private repository on
every tagged release. Do not edit it by hand.

## Format

```json
{
  "version_name": "0.0.3",
  "version_code": 3,
  "published_at": "2026-10-27T02:51:21Z",
  "page_url": "https://github.com/crossly/galaxy-watch-manager-free/releases/tag/v0.0.3",
  "apk_name": "galaxy-watch-manager-free-0.0.3.apk",
  "sha256": "…",
  "notes": "release highlights"
}
```

`page_url` points at the private release page, which requires signing in to GitHub
with access to the repository. Nothing here is used for authentication.
