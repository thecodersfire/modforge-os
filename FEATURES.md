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
