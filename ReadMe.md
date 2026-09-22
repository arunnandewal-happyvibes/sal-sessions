# SAL Sessions

Independent, self-contained outlines for individual SAL curriculum sessions. Each `SXX` folder is one complete session and can be read, delivered, or reviewed on its own — no dependency on any other folder in this repo.

## Repo structure

```
SXX/
  Scenes&LOs.md              Scene breakdown: duration + numbered Learning Objectives per scene
  metadata.md                Session-level metadata: course, audience, duration, objective, topics
  Lecture Notes.md            Full teaching content (source of truth for the session)
  Lecture Script.md           Instructor-facing recording/facilitation script (timing, camera, quiz cues)
  Checkpoint Questions/
    Scene X.1.md / .csv       Main-clip quiz (5 questions, 5 minutes) — Markdown + structured CSV
    Scene X.2.md / .csv       Revision-clip quiz (3 questions, 3 minutes) — Markdown + structured CSV
    checkpoint question QC report.md   QC audit: counts, LO coverage, answer-distribution check, verdict
  resources/                  Any datasets or supporting files the session's exercises reference
  dummy.md                    Placeholder (kept empty, matches upstream SAL template convention)
```

## Sessions

| Session | Title | Objective |
|---------|-------|-----------|
| [S01](S01/) | AI for Everyday Work: Analytics & Decision-Making | Using AI for data analysis and insight generation |

## Master Session Common Template

For reference, every session in this repo is built to answer the same six questions:

### Title

### Brief Scope of the Session (in 3 to 4 lines)
- Previous session coverage (2 lines)
- Current session coverage (2 lines)

### Learning Objectives
- Numbering starts from 1, 2, 3, etc., where these are actual scenes, then sub-LOs like 1.1, 1.2, etc., which are sub-LOs for the particular scene

### Content-Notes-Snippets-Activities etc.
- Scene-wise content, notes, snippets, and activities are laid out chronologically in `Lecture Notes.md`

### Conclusion of the Session
- A brief conclusion of the session in bullet points (`Key Takeaways` in `Lecture Notes.md`)

### Reference Sources/Documents (if any)
- Listed in each session's `metadata.md` under "source materials adapted for this session"
