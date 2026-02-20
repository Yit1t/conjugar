# Conjugar

A Spanish verb conjugation practice app for A1–A2 learners. Built for Chinese and English speakers with bilingual interface, audio pronunciation, and offline-ready PWA support.

**Live → [conjugar.vercel.app](https://conjugar.vercel.app)**

---

## Features

**Practice**
- 158 verbs across 8 categories: daily verbs, food & drink, shopping, professions, hobbies, health, studying, transport
- 6 tenses: Present, Pretérito Perfecto, Pretérito Indefinido, Near Future, Reflexive Present, Imperative
- Irregular forms highlighted in orange
- Audio pronunciation via Web Speech API (Spanish TTS)
- Tap to reveal conjugation, tap again for next card
- Keyboard shortcuts: Space / Enter to flip, ← → to navigate, S to speak

**Filters**
- Filter by category, tense, pronoun, and vocabulary level (A1 / A2)
- Regular only / irregular only / all forms

**Grammar Reference**
- Full conjugation rules for all 6 tenses with irregular form tables
- Reflexive verbs and imperative mood explained
- Bilingual (Chinese / English)

**Settings & Persistence**
- Dark mode
- Bilingual interface: Chinese / English
- All settings saved automatically and restored on next visit
- Progress tracking: today's cards, total cards, daily streak

**PWA**
- Installable on iOS (Safari → Add to Home Screen) and Android (Chrome → Install)

---

## Tech Stack

Vanilla HTML / CSS / JavaScript — no framework, no build step. Single `index.html` + `verbs.json` data file, deployed on Vercel.

---

## File Structure

```
conjugar/
├── index.html       # App (UI + logic)
├── verbs.json       # Verb database (158 verbs)
├── manifest.json    # PWA manifest
└── README.md
```

