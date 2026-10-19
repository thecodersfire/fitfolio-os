# Built-in features for fitfolio-os

Purpose: fitness tracking

1. **organize a personal routine** — run fitfolio-os-workspace. It creates ~/Documents/fitfolio-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run fitfolio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/fitfolio-os-session-plans/.
3. **check routine readiness** — run fitfolio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/fitfolio-os-workspace features/fitfolio-os-plan features/fitfolio-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for fitness tracking:

1. **GIMP** — org.gimp.GIMP
2. **Foliate** — com.github.johnfactotum.Foliate
3. **Audacity** — org.audacityteam.Audacity

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
