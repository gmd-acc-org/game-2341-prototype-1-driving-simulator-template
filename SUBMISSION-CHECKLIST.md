# Prototype 1 submission checklist

Complete this in your cloned project before your final push.

## Unity check

- [ ] `Assets/Scenes/Prototype1_DrivingSimulator.unity` opens in Unity 6 LTS.
- [ ] A vehicle sits on a road, with obstacles in the way.
- [ ] The vehicle moves forward and responds to arrow-key/WASD input.
- [ ] Movement uses `Time.deltaTime`, so it doesn't depend on frame rate.
- [ ] The camera follows the vehicle.
- [ ] I pressed Play and saw no compiler errors or missing-script messages.
- [ ] **Edit > Project Settings > Editor** still shows Force Text and Visible
      Meta Files.

## Repository check

```bash
git status --short
git add Assets ProjectSettings Packages README.md reflection.md ai-use.md screenshot.png
git status --short
```

- [ ] The staged list includes my scene, my scripts, and their `.meta` files.
- [ ] It includes `ProjectSettings/`, `Packages/manifest.json`, and
      `Packages/packages-lock.json`.
- [ ] It includes completed `reflection.md`, `ai-use.md`, and `screenshot.png`.
- [ ] It does **not** include `Library/`, `Temp/`, `Logs/`, `Build/`, a
      `.unitypackage`, or files from a Synty or other asset pack.

## Final push

```bash
git commit -m "Complete Prototype 1"
git push origin main
```

- [ ] The push succeeded, and I can see the commit on my repository page.
- [ ] I ran `gh student submit` (optional, but please do it), and it printed a
      submission time and a link.
