# Free Anki decks with audio

Free, ready-to-import Anki decks for Spanish, French, German and Portuguese
learners, published by [AnkiWordBank](https://ankiwordbank.com). Each card shows an
English sentence on the front. The back has the same sentence in the target
language, with an audio clip.

Every file here is the exact package we ship, or a cut of one. Each deck folder
also has a plain-text `words.tsv`, so you can see every card before you download.

| Deck | Language | Notes | What it is |
|---|---|---|---|
| [Spanish Top 1000: first 100](decks/spanish-top-1000-first-100/) | Spanish | 100 | Ranks 1–100 of our paid [Spanish Top 1000](https://ankiwordbank.com/decks/spanish-top-1000-most-common-words) deck (rebuilt Oct 2026), plus the [full ranked word list](decks/spanish-top-1000-first-100/spanish-top-1000-words.tsv) |
| [French Top 1000: first 100](decks/french-top-1000-first-100/) | French | 100 | Ranks 1–100 of our paid [French Top 1000](https://ankiwordbank.com/decks/french-complete-1000-most-common-words-audio) deck (rebuilt Oct 2026), plus the [full ranked word list](decks/french-top-1000-first-100/french-top-1000-words.tsv) |
| [Spanish verbs](decks/spanish-verbs-50/) | Spanish | 52 (51 after import) | 51 common verbs in example sentences. Next: [300 Spanish verbs](https://ankiwordbank.com/decks/spanish-most-common-verbs-300) |
| [German verbs](decks/german-verbs-50/) | German | 50 | 50 common verbs in example sentences. Next: [300 German verbs](https://ankiwordbank.com/decks/german-most-common-verbs-300) |
| [Portuguese verbs](decks/portuguese-verbs-50/) | Portuguese (Brazil) | 54 | 30 core verbs and 24 everyday verb phrases. Next: [Portuguese Top 1000](https://ankiwordbank.com/decks/portuguese-top-1000-most-common-words-native-audio) |

## What's on a card

- **Front:** an English sentence ("I want pizza and a salad for dinner.")
- **Back:** the target-language sentence, usually with the target word in bold
  ("Quiero pizza **y** una ensalada para cenar."), plus audio of the sentence.
- One card per note, with no reverse cards.

**Audio** is AI-generated, not recordings of people. The two Top 1000 samples use
ElevenLabs AI voices cloned from native speakers (Spain for Spanish, France for
French); the verb decks use neural text-to-speech. Every note in every deck here
has an audio file. We checked that no reference is missing or empty.

## How to import

1. Download the `.apkg` file from a deck folder. On the file page, click "Download raw file".
2. Open it with Anki (desktop, AnkiMobile or AnkiDroid), or use File → Import.

## The two samples and the full decks

The Spanish and French samples keep the paid deck's note type, note IDs and
deck name. If you buy the full deck later and import it, Anki adds the other 900
notes to the same deck and keeps your progress on these 100. We tested this
with Anki 26.9: it reported 0 conflicts, and reviewed cards kept their scheduling.

The full decks cost $5 each, as a one-time purchase with a 30-day money-back
guarantee. You don't need to buy anything to use the decks in this repository.

## How these decks were made

The two Top 1000 decks start from a published frequency list: the Wiktionary
Spanish subtitle list (Buchmeier, 27.4M words) and Lexique 3.83's film-subtitle
frequencies for French, grouped by dictionary form with names, interjections and
swear words removed. Each deck folder links the full ranked list. Every word gets
one A1–A2 context sentence, reviewed card by card, with region-specific audio:
Spain Spanish, France French, Germany German and Brazilian Portuguese.

## License

[CC BY-NC 4.0](LICENSE). You may share and adapt these decks for non-commercial
use, with attribution to AnkiWordBank (https://ankiwordbank.com).

Found an error? Open an issue.
