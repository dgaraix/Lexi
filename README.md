# Lexi 🦊

**An offline-friendly, multilingual early-literacy trainer for kids.**
Numbers, words, and phonics sounds — and (planned) spelling — in **English, French, and
Spanish**, with a Practice mode and a speak-aloud Test mode. Built as a single
self-contained web page.

🔗 **Play it:** https://dgaraix.github.io/Lexi/

---

## What it is

Lexi is a reading-practice game for young children (roughly ages 4–9). A grown-up sets the
language, what's being drilled, and the difficulty; the child reads/says each card out loud.
It was built for a bilingual household and treats French and Spanish as first-class, not
afterthoughts.

Everything runs in the browser from one `index.html` file — no server, no build step, no
accounts, no data collection. Voice output uses the device's built-in text-to-speech; the
Test mode's answer-checking uses the device's built-in speech **recognition**. Both are
engine-based and cost zero storage.

## Features at a glance

- **Three game modes** (soon four):
  - 🔢 **Numbers** — 1–100, with counting icons; number words + speech in the chosen language.
  - 🔠 **Words** — hundreds of real words per language across 16 topic categories, filtered
    by length.
  - 🗣️ **Sounds** — phonics graphemes / syllables (French *sons du CP*, Spanish *sílabas*,
    English digraphs & vowel teams), each with an example word.
  - ✍️ **Spell** — *(planned)* see/hear a word, build it from letters.
- **Two play modes:** 🏋️ Practice (explore freely, with a Back button) and 🎓 Test
  (10/20/30 questions, speak the answer, scored, anti-cheat).
- **Global language** with a flag in the header; switching language rules every mode.
- **Smart filters** — length × topic options grey out when empty, with a plain-language hint.
- **Learning-science built in** — shuffle-bag randomization, Leitner-style review of misses,
  immediate feedback, fireworks for passing a test.
- **Pictures as a reward, not a crutch** — show / tap-to-reveal / hide the icon in Words mode.

## A note on the microphone

Test mode listens to the child's spoken answer, which needs a microphone — and browsers only
allow mic access over **https** (which the hosted link above provides). Practice mode works
everywhere, including a plain offline file open. When speech recognition isn't available
(offline, or an unsupported browser), Test mode falls back to a grown-up tapping ✓ / ✗ — a
technical glitch is never scored against the child.

## License

Public domain (The Unlicense) — see `LICENSE`.
