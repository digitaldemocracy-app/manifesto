🌐 English · [中文](zh/CONTRIBUTING.md) · [हिन्दी](hi/CONTRIBUTING.md) · [Español](es/CONTRIBUTING.md) · [العربية](ar/CONTRIBUTING.md) · [Français](fr/CONTRIBUTING.md) · [বাংলা](bn/CONTRIBUTING.md) · [Português](pt/CONTRIBUTING.md) · [Русский](ru/CONTRIBUTING.md) · [Bahasa Indonesia](id/CONTRIBUTING.md)

# Contributing

This manifesto belongs to no one: it is a starting point. Correct it, translate it, improve it.

Everything here happens in the open, in this repository. There is no mailing list, no private channel. Issues and pull requests are the record.

## Ways to contribute

| I want to… | Do this |
|---|---|
| Sign the manifesto | Follow [SIGNATURES.md](SIGNATURES.md) |
| Fix a typo or a broken link | Open a pull request directly |
| Suggest a change to the wording or the ideas | Open an issue with the **Text suggestion** template |
| Translate, or review a translation | Open an issue with the **Translation or review** template, then a pull request |
| Ask a question or raise an objection | Check [FAQ.md](FAQ.md) first; if it is not there, open an issue with the **Text suggestion** template and label it `question` |

## The official text

- The official text is the English version in [README.md](README.md).
- The Portuguese text in [pt/README.md](pt/README.md) is the author's original and the reference of meaning for all translations.
- Substantive changes to the official text (anything beyond typos, grammar or links) must start as an issue, so the reasoning is public before any edit. The author and maintainers decide; the discussion stays on record.
- Every change goes through a pull request reviewed by at least one maintainer. The `main` branch is protected; nothing is pushed to it directly, including by maintainers.

## Translations

1. Check [TRANSLATIONS.md](TRANSLATIONS.md) for the status of your language. If someone is already working on it, join their issue instead of opening a new one.
2. Open an issue with the **Translation or review** template. Say which language, whether you are a native speaker, and whether you are translating or reviewing.
3. Translate from the English text. When a sentence is ambiguous, use the Portuguese original to decide the meaning. Keep the same headings and the same number of paragraphs; do not add, remove or reorder sections.
4. Put the file at `<code>/README.md`, in a folder named with the two-letter ISO 639-1 code (`es`, `fr`, `zh`, …); the companion documents go in the same folder as `PRINCIPLES.md`, `FAQ.md`, `NEUTRALITY.md`, `CONTRIBUTING.md`, `SIGNATURES.md` and `LICENSE` (the official Creative Commons translation, when one exists). If a language needs a regional variant, use a hyphen and the region code (`pt-PT`, `zh-TW`).
5. Right-to-left languages (Arabic, Urdu, Persian, Hebrew): wrap the whole text in `<div dir="rtl">` … `</div>` with a blank line after the opening tag and before the closing tag. See [ar/README.md](ar/README.md).
6. Open a pull request. A translation is marked **Reviewed** after at least one other native speaker approves it in the pull request.

Translations into languages beyond the ten listed are welcome. The ten are a starting point, not a limit.

## Style

- Short sentences. Plain words. The manifesto is meant to be read aloud and repeated.
- Keep the tone: inviting, not accusing. We accuse the distance, not people.
- No party, candidate, government or country is endorsed or attacked, in any language.

## Behaviour

Debating is not fighting. Arguments have sides, and sides have arguments. Disagree with ideas, not with people. Maintainers will close discussions that become personal, and may block accounts that insist.

## Licence

By contributing you agree that your contribution is published under the same licence as the manifesto, [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Translators are credited in the translation file and in the git history.
