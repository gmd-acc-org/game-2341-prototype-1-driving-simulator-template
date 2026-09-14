# Prototype 1: Driving Simulator

**GAME-2341 — Game Scripting**  
**Unity:** Unity 6 LTS (6000.x)  
**Due:** Sunday, September 27, 2026, 11:59 PM

This is a **blank Unity 6 starter project** for Prototype 1. Build the Create
with Code (CwC) Unit 1 Driving Simulator in this repository, not in a separate
local project.

Learning path: [CwC Unit 1: Player Control](https://learn.unity.com/course/create-with-code/unit/unit-1-driving-simulation?version=6.0)

## Start here

1. In Classroom 50, accept **Prototype 1: Driving Simulator** and copy the
   clone URL of the private repository it creates.
2. Clone it into a local development folder — not Google Drive, OneDrive, or
   Dropbox:

   ```bash
   git clone "https://github.com/YOUR-CLASSROOM50-REPOSITORY.git" GAME2341-Prototype1
   ```

3. In Unity Hub choose **Add > Add project from disk**, select the
   `GAME2341-Prototype1` folder, and open it in Unity 6 LTS.
4. Open `Assets/Scenes/Prototype1_DrivingSimulator.unity`.
5. When CwC Lesson 1.1 tells you to create a new project, **use this project
   instead**. When it gives you the Unit 1 starter files, import them into this
   project (**Assets > Import Package > Custom Package**).

The project already uses **Force Text** serialization and **Visible Meta
Files** (**Edit > Project Settings > Editor**). Leave both settings as they are.

## What goes in this repository

| File | What it is |
|---|---|
| `Assets/`, `Packages/`, `ProjectSettings/` | Your Unity project |
| `reflection.md` | About 300 words: what was hard, what was easy, what you added |
| `ai-use.md` | The five AI-use questions (a no-AI answer can earn full credit) |
| `hygiene-check.md` | Week 4 bridge assignment, **due Sunday, September 20, 2026, 11:59 PM** |
| `screenshot.png` | Your running game, from the first 5 seconds of play |

**Asset packs (Synty and others) stay out of Git.** The `.gitignore` excludes
the usual Synty import folders. Name the pack you used, and where you got it,
in `reflection.md`. Never commit an exported `.unitypackage`.

## Commit and submit

```bash
git status --short
git add Assets ProjectSettings Packages README.md reflection.md ai-use.md hygiene-check.md screenshot.png
git status --short
git commit -m "Prototype 1 progress"
git push origin main
```

**Your `git push` is the submission.** Grading reads this repository. Push
early and often; I grade the latest commit pushed on time.

`gh student submit` is optional. It pushes your work too and gives you a
timestamped receipt. Use it if you want that record.

Use [SUBMISSION-CHECKLIST.md](SUBMISSION-CHECKLIST.md) before the deadline.
