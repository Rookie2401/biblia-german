# Biblia — Deutsch

The German Bible (Schlachter 1951) in Biblia, read through GoLearn: every word can be tapped for its meaning and grammar, and, when you sign in with your GoLearn
account, what you look up is recorded under your German enrolment for review in GoReview.

Live at https://rookie2401.github.io/biblia-german/

This repository holds only the built site. It is built from the go-v0 source (`packages/biblia`, `npm run biblia:build-standalone-de`);
each commit names the source commit it was built from.

## Licences

- **Text:** Die Schlachter-Bibel 1951 — translated by Franz Eugen Schlachter; revised 1951 by the Genfer Bibelgesellschaft.
  Copyright © 1951 Genfer Bibelgesellschaft (Geneva Bible Society). Licensed under the
  [Creative Commons Attribution 4.0 licence](https://creativecommons.org/licenses/by/4.0/), as stated by eBible.org.
  Source: [eBible.org (deu1951)](https://ebible.org/deu1951/), source files dated 2025-12-12.
  Changes: the verse wording is unchanged; the German verse numbers the source prints in brackets inside verses where its numbering differs
  from the English, e.g. “(03-2)”, are not shown, nor Matthew 21:44, which the source leaves empty; the verses are laid out by Biblia. These
  changes are not endorsed by the original licensor (see `data/de/SOURCES.json`).
- **Type:** EB Garamond, under the SIL Open Font License 1.1 (licence text in `fonts/`).
