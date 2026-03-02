# LinguaCapture

A voice-to-flashcard language learning prototype. Record any conversation, meeting, or idea — it transcribes it and generates lesson cards in your target language.

## How it works

1. Select your target language (Spanish, French, Japanese, etc.)
2. Hit record and talk
3. Hit stop — it transcribes your speech and pulls out key vocabulary and phrases
4. Flip through the generated cards to see real translations

Translations are powered by the [MyMemory API](https://mymemory.translated.net/) — free, no API key required.

## The idea behind it

Most language learning apps teach you generic vocabulary ("the cat is on the table"). This app learns *your* vocabulary — the words and phrases that actually come up in your daily life — and teaches you those in your target language.

It's a prototype exploring a broader concept: interest- and context-based language learning, where your personal life is the curriculum.

## Usage

Open `linguacapture-prototype.html` in **Chrome or Edge** (required for the Web Speech API). No install, no build step, no dependencies.

## Stack

- Vanilla HTML/CSS/JS
- Web Speech API (transcription)
- MyMemory Translation API (free tier)
