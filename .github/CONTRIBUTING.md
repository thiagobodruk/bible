# Contributing

Thanks for helping improve this dataset! Contributions of any size are welcome:
reporting errors, requesting new versions, or improving the docs.

By participating you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

- **Report a text error** — a missing verse, a wrong chapter count, broken
  characters, or mismatched XML/JSON. Use the *Text error* issue template and
  include the file, book, chapter, and verse.
- **Request a version or language** — use the *Version request* template and
  tell us the language, the version name, and its abbreviation.
- **Improve the documentation** — fixes to the README and its translations
  are very welcome (see [README translations](#readme-translations)).

## Repository layout

| Path | Contents |
| --- | --- |
| `json/<lang>_<code>.json` | One Bible version per file |
| `xml/<lang>_<code>.xml` | The same version in XML |
| `json/index.json` | Index of languages and versions |

Every version must exist in **both** formats, and must be listed in
`json/index.json` and in the README table (sorted by language name).

## Pull requests

1. Fork the repository and create a branch from `master`.
2. Keep each pull request focused on one change (one version, one fix).
3. For a new version, check that:
   - it has all 66 books, with no empty chapters;
   - the JSON and XML files have the same content;
   - `json/index.json`, the README table, and the version/language counts in
     the README (headline and badge) are updated;
   - the license of the text allows redistribution.
4. Open the pull request and fill in the template.

## README translations

`README.md` is the default (English). Translations live in
`README.<code>.md`. When you change the English README, please mention in the
pull request which translations need the same update. Each translation lists
its own language first in the language menu.

## Questions

Open an issue — there are no silly questions.
