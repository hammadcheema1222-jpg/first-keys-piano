# First Keys — Personal Piano Studio

A playable piano and beginner learning app, with a guided first hour and Practice Lab.

## Play

Download `index.html` and open it in your browser. No install, API key or subscription is needed. Touch, mouse, computer keys and supported USB MIDI keyboards work. MIDI may require HTTPS or localhost. A touchscreen helps with notes and rhythm; physical keys are needed for piano technique.

## Included

- Six guided first-hour lessons and a simplified Ode to Joy melody.
- Polyphonic piano-like synthesis, metronome and adjustable tempo.
- Treble/bass notation, hand selection, phrase loops and chord-onset checking.
- Informal sight-reading drills and a browser-local practice journal.

## Source and tests

`First-Keys-Source.zip` contains the complete modular source, unit tests, lesson checks and a GitHub Actions workflow. Extract it into a directory, then run:

```
npm run check
npm test
npm run build
```

No npm dependencies are required. The repository workflow extracts the source and runs those same checks. `index.html` is the self-contained playable build of that source.

## Learning and limitations

The in-app Method page cites Faber Piano Adventures, ABRSM and a pitch-feedback study. The app is evidence-informed, not experimentally validated. An hour aims at a short melody, not piano fluency. Wait-mode feedback does not grade posture, fingering, dynamics, held-note duration or omissions against a fixed performance clock. Reading drills are not a standardised assessment.

Original implementation inspired by general interactive-practice features in flowkey and Piano Marvel. No proprietary code, paid song libraries or assessments were copied. Traditional/public-domain melodies use simplified original practice arrangements.
