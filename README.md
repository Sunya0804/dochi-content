# Dochi Keyboard — learning content

`phrasebook.json` is downloaded by the Dochi Keyboard app's Learn screen (at most once a day) to add
phrasebook situations and quiz material without an app update.

- Format: `{"version": n, "situations": [{"id", "title", "phrases": [{"ko", "en"}]}]}`
- Raise `version` every time you publish: the app only replaces its copy with a higher version.
- `romaja` per phrase is optional; the app romanizes Korean itself. Keep the file under 2 MB.
