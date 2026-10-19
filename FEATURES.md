# Built-in features for modforge-os

Purpose: game modding

1. **prepare racing and game notes** — run modforge-os-workspace. It creates ~/Documents/modforge-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run modforge-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/modforge-os-session-plans/.
3. **check game and controller readiness** — run modforge-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/modforge-os-workspace features/modforge-os-plan features/modforge-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for game modding:

1. **Prism Launcher** — org.prismlauncher.PrismLauncher
2. **Godot Engine** — org.godotengine.Godot
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for game modding:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **VLC** — review media files (org.videolan.VLC)
3. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
4. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
5. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
6. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
7. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
10. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **RetroArch** (org.libretro.RetroArch) — organize and run compatible retro-game emulator cores.
2. **Dolphin Emulator** (org.DolphinEmu.dolphin-emu) — run compatible GameCube and Wii homebrew or legally obtained game files.
3. **PPSSPP** (org.ppsspp.PPSSPP) — run compatible PSP homebrew or legally obtained game files.
4. **PCSX2** (net.pcsx2.PCSX2) — run compatible PlayStation 2 homebrew or legally obtained game files.
5. **MAME** (org.mamedev.MAME) — run compatible arcade software using lawful game files.
6. **Protontricks** (com.github.Matoking.protontricks) — apply compatibility fixes to Steam Proton prefixes.
7. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
8. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **GNOME Extensions** (org.gnome.Extensions) — manage GNOME desktop extensions.
11. **GNOME Papers** (org.gnome.Papers) — read project and reference PDFs.
12. **GNOME Weather** (org.gnome.Weather) — check local weather conditions.
13. **GNOME Contacts** (org.gnome.Contacts) — organize partner and team contacts.
14. **GNOME Sound Recorder** (org.gnome.SoundRecorder) — capture voice and field notes.
15. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **ScummVM** (org.scummvm.ScummVM) — run supported classic adventure games when you provide lawful game data files.
2. **KPatience** (org.kde.kpat) — play a collection of solitaire card games.
3. **KMines** (org.kde.kmines) — play a Minesweeper-style puzzle game.
4. **KNights** (org.kde.knights) — study and play chess against a person or engine.
5. **KSudoku** (org.kde.ksudoku) — practice Sudoku and number-placement puzzles.
6. **KMahjongg** (org.kde.kmahjongg) — play a tile-matching solitaire game.
7. **KShisen** (org.kde.kshisen) — play a Mahjong-tile matching puzzle.
8. **Kapman** (org.kde.kapman) — play a maze arcade game inspired by Pac-Man.
9. **KGoldrunner** (org.kde.kgoldrunner) — solve platform puzzles by collecting gold and avoiding enemies.
10. **KJumpingCube** (org.kde.kjumpingcube) — play a territory-control strategy puzzle.
11. **KFourInLine** (org.kde.kfourinline) — play four-in-a-row against a person or computer.
12. **KDiamond** (org.kde.kdiamond) — solve a three-in-a-row matching puzzle.
13. **KNetWalk** (org.kde.knetwalk) — solve network-routing logic puzzles.
14. **Klickety** (org.kde.klickety) — clear matching-color puzzle boards.
15. **Naval Battle** (org.kde.knavalbattle) — play a Battleship-style strategy game.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for game modding. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Bomber** (org.kde.bomber) — Play a compact single-player arcade bombing game.
2. **Bovo** (org.kde.bovo) — Play a two-player five-in-a-row strategy game.
3. **KBounce** (org.kde.kbounce) — Capture board space in an arcade puzzle game.
4. **KBreakOut** (org.kde.kbreakout) — Break brick formations in an arcade game.
5. **Kollision** (org.kde.kollision) — Avoid moving balls in a reflex and timing game.
6. **KReversi** (org.kde.kreversi) — Play Reversi and plan captures on a board.
7. **KSnakeDuel** (org.kde.ksnakeduel) — Compete in a two-player snake arena.
8. **Konquest** (org.kde.konquest) — Plan a turn-based interplanetary strategy game.
9. **KsirK** (org.kde.ksirk) — Play turn-based world-conquest strategy.
10. **Atlantik** (org.kde.atlantik) — Play a networked property trading board game.
11. **Picmi** (org.kde.picmi) — Solve nonogram picture-logic puzzles.
12. **LSkat** (org.kde.lskat) — Play a trick-taking card game for two players.
13. **GNOME Mines** (org.gnome.Mines) — Solve a classic hidden-mine logic puzzle.
14. **GNOME Sudoku** (org.gnome.Sudoku) — Generate and solve Sudoku puzzles with notes and hints.
15. **Tetravex** (org.gnome.Tetravex) — Match numbered tile edges in a timed logic puzzle.
