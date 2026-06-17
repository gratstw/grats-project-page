# GRATS Website Draft (Anonymous Review Version)

This folder contains an anonymized static website draft for the GRATS Dataset Project.

## Files

- `index.html`: main website page.
- `assets/style.css`: website styling.
- `audio/`: placeholder folder for example audio clips.
- `files/`: optional folder for PDFs, README files, or access documents.

## How to preview locally

Open `index.html` directly in a web browser.

## What was changed for anonymous review

- Removed direct author names.
- Removed institutional affiliations.
- Removed identifying email addresses.
- Replaced final citations with anonymous placeholders.
- Added an `Example Audio` section with five speaking-rate placeholders.
- Updated the visual design to look more polished and professional.

## Audio placeholder filenames

The current HTML expects these example files:

- `audio/example1_0.5x.wav`
- `audio/example1_0.75x.wav`
- `audio/example1_1.0x.wav`
- `audio/example1_1.25x.wav`
- `audio/example1_1.5x.wav`

You can duplicate the example block in `index.html` if you want more than one example sentence.

## Suggested anonymous-review practice

- Use audio-only examples during review.
- Avoid identity-revealing video samples on the anonymous page.
- Remove any metadata that might contain speaker or author identities.
- Restore final author/contact/citation details only after review.

## How to deploy later

When the review stage is over, update the following:

1. Replace the anonymous contact placeholder.
2. Replace the anonymous citation placeholders with final BibTeX entries.
3. Replace the access-form placeholder with the real access form or official request link.
4. Add the final project URL when safe to do so.
5. Optionally add video or more examples after acceptance.

## Dataset version note

The website distinguishes between:

- Original paper version: 25 speakers × 60 prompts × 5 speaking rates = 7,500 utterances.
- Expanded corpus: original 7,500 utterances + additional 7,500 utterances = 15,000 utterances.
- Important: describe this as two 25-speaker × 60-prompt × 5-rate subsets, not as a fully crossed 50-speaker × 120-prompt × 5-rate corpus.
