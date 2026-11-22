# 172-lecture-notes

Handwritten-style lecture notes for **Math 172: Precalculus & Trigonometry** at Santa Ana College. Each set is built from a guided-notes handout. Students try each part, then open a hint or the answer.

One repo, one Netlify site. Every set lives in its own folder.

## What's here

| Folder | Notes | Book section |
|---|---|---|
| `te4/` | Solving Right Triangles (TE4) | 4.3.1 |
| `te5/` | Law of Sines and Law of Cosines (TE5) | 4.3.2 |
| `te6/` | Applications of Trigonometry (TE6) | 4.3.3 |
| `te1/` | Trigonometric Identities (TE1) | 4.4.1 |
| `te2/` | Verifying Trigonometric Identities (TE2) | 4.4.2 |
| `te3/` | Solving Trigonometric Equations (TE3) | 4.4.3 |
| `pr3/` | Graphs of Polynomial Functions (PR3) | 5.1.1 |
| `pr4/` | Polynomial Long Division (PR4) | 5.2.1 |
| `pr6/` | Rational Equations (PR6) | 5.3.1 |

Each folder holds:
- `index.html`: the notes page (single file, works offline)
- `XXX_Lecture_Notes.pdf`: the tagged PDF version, linked from the page

The root `index.html` is the landing page that lists every set.

## Links

With the site at `https://<site>.netlify.app`:
- Landing page: `https://<site>.netlify.app/`
- A set of notes: `https://<site>.netlify.app/te3/`
- A PDF: `https://<site>.netlify.app/te3/TE3_Lecture_Notes.pdf`

## Adding a new set

1. Create a folder named for the section code in lowercase, such as `pr4/`.
2. Put the notes page in it as `index.html`, with its PDF next to it.
3. Add a line for it to the root `index.html` under the right chapter.
4. Add a row to the table above.
5. Merge to `main`. Netlify publishes it automatically.

## Workflow for each set

Solve the handout → verification packet audited externally (ChatGPT) → revise → HTML → review → tagged PDF.

## Accessibility

Each notes page is built for WCAG 2.1 AA:
- think-first reveals that work by keyboard and screen reader
- a font toggle between handwriting and standard text
- graphs with full text descriptions
- reflow at 320px and at 200% text

The PDFs are tagged, with headings, page language, and figure alt text. Formal compliance certification is done separately.

## History

These notes used to live in separate repos (`172te1notes` … `172te6notes`), one Netlify site each. They were combined here in November 2026.
