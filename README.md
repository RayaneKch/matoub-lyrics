The full discography of **Matoub Lounès** (1956–1998), Kabyle singer, poet, and activist: 223 songs across 28 albums from 1978 to 1998, each available as plain text and as time-synced `.lrc`.

## Structure

```
matoub-lyrics/
+-- plain lyrics/
¦   +-- <year> - <album>/
¦       +-- <song>.txt
+-- synced lyrics/
    +-- <year> - <album>/
        +-- <song>.lrc
```

Both folders mirror each other, so every song has a `.txt` and a `.lrc` with the same name.

- **plain lyrics/**: raw lyrics, no timestamps
- **synced lyrics/**: [LRC](https://en.wikipedia.org/wiki/LRC_(file_format)) files with per-line timestamps, usable in most music players.

Albums are named `<year> - <title>` and sort chronologically. Titles use Kabyle Latin orthography, so make sure your tools handle UTF-8.

## Contributing
Spotted a typo, a transliteration inconsistency, or a timing issue in an `.lrc`? PRs and issues are welcome. Please include the song and album, and a source if you have one.

## Copyright

The lyrics belong to Matoub Lounès and his rights holders. This repo exists for cultural preservation and personal/educational use.