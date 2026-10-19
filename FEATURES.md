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
