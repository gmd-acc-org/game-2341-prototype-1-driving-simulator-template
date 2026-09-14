# Prototype 1: Driving Simulator

**GAME-2341 — Game Scripting**  
**Unity:** Unity 6 LTS (6000.x)  
**Due:** Sunday, September 27, 2026, 11:59 PM

This is a **blank Unity 6 starter project** for Prototype 1. Build the Create
with Code (CwC) Unit 1 Driving Simulator in this repository, not in a separate
local project.

Learning path: [CwC Unit 1: Player Control](https://learn.unity.com/course/create-with-code/unit/unit-1-driving-simulation?version=6.0)

## One-time setup (Windows or Mac)

Run these in **PowerShell** (Windows) or **Terminal** (Mac). Every command in
this README works in both.

| | Windows | Mac |
|---|---|---|
| Git and GitHub CLI | `winget install Git.Git GitHub.cli` | `xcode-select --install`, then `brew install gh` ([Homebrew](https://brew.sh) first if you don't have it) |
| Unity | Unity Hub, then Unity 6 LTS | Unity Hub, then Unity 6 LTS |

Then, on either system:

```bash
gh auth login
gh extension install foundation50/gh-student
```

When Unity Hub says the project's editor version (6000.3.6f1) is missing,
install that version, or open with a newer Unity 6 LTS and accept the upgrade.

**Windows:** clone into a short folder such as `C:\dev`. Your `Documents` and
`Desktop` folders are often synced by OneDrive, which breaks Unity projects,
and long paths break Unity's `Library` folder. Also run once:
`git config --global core.longpaths true`

Line endings are handled by the repository's `.gitattributes`, so the same
project opens cleanly on both systems. Don't change it.

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

After you push, also run `gh student submit` from inside this repository.
It's optional for now, but please do it: later assignments will use it, and
it gives you a timestamped receipt.

Use [SUBMISSION-CHECKLIST.md](SUBMISSION-CHECKLIST.md) before the deadline.
