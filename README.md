<div align="center">

# OS Concepts Flashcards

**580+ exam questions from *Operating System Concepts*. Pick chapters, press 1-5, see what you got wrong.**

A single-page quiz app for the 10th edition of Silberschatz, Galvin and Gagne's *Operating System Concepts*,<br>
with chapter presets for the end-term, a "review wrong only" mode and progress saved in your browser.

**[Open it](https://sulte4.github.io/os-concepts-flashcards/)**

![HTML](https://img.shields.io/badge/single%20file-index.html-E34F26?logo=html5&logoColor=white)
![Questions](https://img.shields.io/badge/questions-580%2B-2E3192)
![Chapters](https://img.shields.io/badge/chapters-17-2D6A4F)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-222222?logo=githubpages&logoColor=white)

</div>

---

## Why

The book's test bank is the best practice for the exam, but it's a wall of text. This turns it into flashcards you can drill on your phone between classes. It remembers what you got wrong, so the last evening before the exam goes to the questions that matter.

## How it works

```
 index.html  (everything inline: questions, styles, script)
     │
     ▼
 Home:  quick pick or chapters  ──►  type (MC / T-F)  ──►  difficulty  ──►  mode
        Endterm, Memory, ...         381 MC, 202 T/F       Easy/Med/Hard     book order │ shuffle │
                                                                              review wrong only
     │
     ▼
 Study:  question ──► pick ──► Check answer ──► correct / wrong ──► Next
     │
     ▼
 localStorage: seen, correct, wrong, bookmarks, the session to resume
```

## Features

- **The whole test bank.** 17 chapters, from Introduction to Protection, as multiple choice and true/false.
- **Quick picks.** The Endterm preset covers chapters 9, 10 and 13-16. There are also Memory, File systems, Security and "Not yet tested" presets.
- **Filters.** Combine any chapters, question types and difficulties.
- **Review wrong only.** Drill just the questions you missed.
- **Resume anytime.** Progress and the current session are saved in your browser.
- **Question library.** Browse every question and tap to reveal its answer, filtered by type and difficulty.
- **Keyboard first.** Answer and move on without touching the mouse.
- **Light and dark.** Follows your system theme and works on phones.
- **No build, no server.** One HTML file.

## Keyboard

| Key | Action |
|---|---|
| `1`-`5` or `A`-`E` | Pick an option (multiple choice) |
| `T` / `F` | True / False |
| `Enter` | Check the answer, then go to the next question |
| `Space` | Skip, or go to the next question after checking |
| `→` | Next question |
| `B` | Bookmark the question |
| `Esc` | Close the dialog |

## Chapters

| # | Chapter | # | Chapter |
|---|---|---|---|
| 1 | Introduction | 10 | Virtual Memory |
| 2 | Operating-System Structures | 11 | Mass-Storage Structure |
| 3 | Processes | 12 | I/O Systems |
| 4 | Threads & Concurrency | 13 | File-System Interface |
| 5 | CPU Scheduling | 14 | File-System Implementation |
| 6 | Synchronization Tools | 15 | File-System Internals |
| 7 | Synchronization Examples | 16 | Security |
| 8 | Deadlocks | 17 | Protection |
| 9 | Main Memory | | |

## Run locally

```bash
git clone https://github.com/SULTE4/os-concepts-flashcards.git
xdg-open os-concepts-flashcards/index.html     # or just double-click it
```

To edit questions, change the `QUESTIONS` array in `index.html`. Each entry has `chapter`, `type` (`mc` or `tf`), `difficulty`, `section`, `question`, `options` and `answer`.

## Roadmap

- [ ] Explanations for the answers
- [ ] Spaced repetition instead of plain "wrong only" review
