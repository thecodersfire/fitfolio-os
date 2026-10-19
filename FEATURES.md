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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for fitness tracking:

1. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
2. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
3. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
4. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
5. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
6. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
7. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
2. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
3. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
4. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
5. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
6. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
7. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
8. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
9. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
10. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
13. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
14. **Zotero** (org.zotero.Zotero) — manage research sources and citations.
15. **Anki** (net.ankiweb.Anki) — create spaced-repetition study decks.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
2. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
3. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
4. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
5. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
6. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
7. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
8. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
9. **Ark** (org.kde.ark) — open and create common project archive files.
10. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
11. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
12. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
13. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
14. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
15. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.
