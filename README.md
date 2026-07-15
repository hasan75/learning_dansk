# Danish Language Learning Journal

A personal, Claude-powered Danish course — built for an absolute beginner (A0) preparing to study Computer Science and Engineering at DTU (Technical University of Denmark). This repo is both the curriculum and the running record of every lesson, correction, and homework submission along the way.

Claude acts as the teacher, following the structured methodology and correction rules defined in [`CLAUDE.md`](CLAUDE.md), and persists everything here so no lesson or vocabulary word is ever lost between sessions.

## How it works

Custom slash commands drive the workflow:

| Command | What it does |
|---|---|
| `/new-lesson [focus]` | Spaced revision of past material, then a full new lesson (vocabulary, pronunciation, grammar, reading, listening, speaking, writing, exercises, homework) |
| `/review` | A standalone spaced-repetition quiz, no new material |
| `/homework <lesson>` | Reviews a completed submission in `homework/`, corrects it, updates `progress.md` |
| `/progress-report` | Summarizes CEFR level, lessons completed, and vocabulary/grammar coverage |

Progress follows the CEFR scale: A0 → A1 → A2 → B1 → B2, and a lesson is never skipped ahead until the material is understood.

## Repository structure

```
danish_lang/
├── CLAUDE.md          # Teaching methodology & rules Claude follows
├── curriculum.md       # Overall curriculum plan
├── routine.md          # Lesson workflow / routine notes
├── progress.md         # Cumulative CEFR progress and lesson log
├── lessons/            # Full content of each lesson (lesson-XXX.md)
├── vocabulary/         # New words introduced per lesson (lesson-XXX.md)
├── grammar/             # Grammar notes per lesson (lesson-XXX.md)
├── homework/            # Homework assignments & submissions (lesson-XXX.md)
└── notes/               # Freeform notes (recurring mistakes, weak spots, etc.)
```

## Focus areas

The curriculum prioritizes practical, everyday Danish over formal textbook language, covering:

- **Daily life** — greetings, shopping, transport, healthcare, banking, housing, government offices (CPR, MitID)
- **University (DTU)** — talking with professors and classmates, lectures, group projects, emails, presentations
- **Part-time jobs** — restaurants, retail, warehouses, customer service, and other common student jobs
- **Professional & technical Danish** — software engineering, IT terminology, meetings, interviews

## Status

See [`progress.md`](progress.md) for the current CEFR level and lesson history.

## License

Licensed under the [MIT License](LICENSE).
