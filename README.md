# sak-content

Content for the [sak](https://github.com/Th3Kr4t3) app that is updated without an app release. The app downloads `catalog.json` from this repo at most every 12 hours and keeps a bundled copy for when it's offline.

Only words live here, never code or anything about users.

## Format

```json
{
  "schema": 1,
  "version": 1,
  "recovery": [
    {"id": "recovery-001", "tags": ["general"], "en": "…", "es": "…"}
  ]
}
```

- `schema`: the format. The app ignores a catalog whose schema it doesn't know. Change it only together with an app release that reads the new format.
- `version`: **raise it on every change**. The app only replaces its catalog with a higher version.
- Sections are named by where the app uses them. `recovery` holds the phrases shown after the user says what got in the way of a habit.
- `id`: unique and stable. The app remembers which ids it already showed, so changing an id shows that phrase again.
- `tags`: `general` (any answer) or a barrier: `capability`, `opportunity`, `motivation`, `phone`. The app goes through the barrier's phrases plus the general ones in file order, without repeating until all were shown.
- `en`, `es`: the text in each language, at most 200 characters. A missing language falls back to English.

## Writing guidelines

From the scientific foundation behind sak: neutral and kind, a lapse is information and not a failure, support the person's sense that they can do it, no guilt, no medical or mental-health claims, no promises like "a habit takes 21 days".

## Updating

1. Edit `catalog.json` and raise `version`.
2. Check that it's valid JSON and that every id is unique.
3. Merge to `main`. Phones pick it up within about 12 hours.
4. Copy the same file to `app/src/main/assets/catalog.json` in the app repo before the next release, so new installs start from it.
