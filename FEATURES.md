# Built-in features for stockroom-studio-os

Purpose: retail inventory and content

1. **prepare a creative project** — run stockroom-studio-os-workspace. It creates ~/Documents/stockroom-studio-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run stockroom-studio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/stockroom-studio-os-session-plans/.
3. **check project and export readiness** — run stockroom-studio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/stockroom-studio-os-workspace features/stockroom-studio-os-plan features/stockroom-studio-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for retail inventory and content:

1. **GNOME Calendar** — org.gnome.Calendar
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
