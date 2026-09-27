# learnmaxxing

Content source for the [ios-learnmaxxing](https://github.com/hainguyenphc/ios-learnmaxxing) app: a bunch of bite-sized facts, one per markdown file.

## Structure

- `facts/manifest.json` — ordered list of fact file names
- `facts/NNN.md` — a single fact, plain text in a markdown file

## Adding a fact

1. Add `facts/031.md` (next number) containing the fact text.
2. Append `"031.md"` to `facts/manifest.json`.
3. Commit and push — the app pulls directly from this repo's raw file URLs.

## Consuming this content

Files are served as plain text via GitHub's raw content URLs, e.g.:

```
https://raw.githubusercontent.com/hainguyenphc/learnmaxxing/main/facts/manifest.json
https://raw.githubusercontent.com/hainguyenphc/learnmaxxing/main/facts/001.md
```
