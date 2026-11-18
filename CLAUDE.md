# Endless Trek — notes for Claude

## Always link the app

End every chat in this repo with a link to the live app:
**https://claude.ai/artifact/BVmtRPfnyDkFBa29kfKerH**

When `index.html` changes, republish that same artifact (pass the URL above as `url` and read it first) so the link always shows the latest version. The artifact copy is `index.html` with the outer `<!DOCTYPE>`, `<html>`, `<head>`, `<body>` tags and the charset/viewport metas removed (the artifact host adds its own), plus `color-scheme:dark` on `:root`.

## Testing

Append `?debug` to the URL to expose `window.__trek` (state plus `sim(seconds)`, `jump(x)`, `force(activity)` and friends) for headless testing.
