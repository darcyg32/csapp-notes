# Computer Systems (CS:APP) — Study Notes & Flashcards

![License](https://img.shields.io/badge/License-MIT-green)
![Language](https://img.shields.io/badge/Notes-Markdown-blue)
![GitHub Repo](https://img.shields.io/badge/GitHub-CSAPP-orange)

This repository contains my personal study notes and Anki flashcards based on  
**_Computer Systems: A Programmer’s Perspective (3rd Global Edition)_**  
by Randal E. Bryant and David R. O’Hallaron.

All notes are written in Markdown (for use with **Obsidian**) and all flashcards are made in **Anki**.  
This repo is a **work-in-progress**. New sections and cards will be added as I continue through the book.

---

## Purpose

This repo documents my journey to deeply understand computer systems and C++ fundamentals.  
It serves both as a personal study resource and as a public learning resource for others who want to explore computer systems concepts.

---

## Quick Links

- [Repository Structure](#repository-structure)
- [Requirements](#requirements)
- [Viewing Notes](#viewing-the-notes-in-obsidian)  
- [Using the Flashcards](#using-the-flashcards-in-anki)  
- [Updating Flashcards](#updating-the-flashcards-adding-new-cards-without-losing-progress)  
- [Cloning the Repo](#cloning-and-updating-the-repo)  
- [Recommended Workflow](#recommended-workflow)  
- [Contributing](#contributing)

---

## Repository Structure

```
csapp-notes/
├── Notes/
│   ├── Attachments/
│   │   └── Figure_1.2.png
│   ├── Part 1 - Program Structure and Execution/
│   │   └── 2. Representing and Manipulating Information/
│   │       └── 2.0 - Introduction.md
├── Flashcards/
│   └── Computer_Systems.apkg
└── README.md
```

**Notes/**  
- Contains all textbook notes, organised by part and chapter.  
- Each note is an Obsidian-compatible `.md` file.  
- Images and diagrams are stored under `Notes/Attachments/`.

**Flashcards/**  
- Contains a single Anki `.apkg` deck (`Computer_Systems.apkg`) that covers the entire textbook.  
- The deck will be periodically updated with new cards as notes expand.

---

## Requirements

You’ll need:
- [Obsidian](https://obsidian.md): for viewing and navigating the Markdown notes.  
- [Anki](https://apps.ankiweb.net): for importing and studying the flashcards.  
- (Optional) [Git](https://git-scm.com): for cloning and syncing updates.

---

## Viewing the Notes in Obsidian

1. Install and open **Obsidian**.  
2. Click **Open Folder as Vault**.  
3. Select the `Notes/` folder from this repository.  
4. Explore the notes via the left sidebar. Chapters and parts are clearly named.  

---

## Using the Flashcards in Anki

The flashcards are stored in `Flashcards/Computer_Systems.apkg`. It's a single deck to cover the entire textbook.

### First-Time Import
1. Open **Anki**.  
2. Go to **File → Import**.  
3. Select `Computer_Systems.apkg` from the repo’s `Flashcards/` folder.  
4. The deck will appear as **“Computer Systems (CS:APP)”**.

---

## Updating the Flashcards (Adding New Cards Without Losing Progress)

Whenever the deck in this repo is updated with new cards, you should be able to safely re-import it without resetting your review history.

**To update:**
1. Download the latest `.apkg` file from `Flashcards/`.  
2. Open **Anki → File → Import**.  
3. Select the new `.apkg` file.  
4. When prompted:
   - Ensure **“Update existing notes if note type and field match”** is checked.  
   - Keep the deck name the same (e.g., *Computer Systems (CS:APP)*).  

Anki will merge new or modified cards into your existing deck and retain your learning progress.

> Do not rename the deck locally. Otherwise, Anki won’t detect it as the same deck during import.

---

## Cloning and Updating the Repo

If you’d like to keep a local copy that you can update easily:

```bash
git clone https://github.com/<yourusername>/csapp-notes.git
cd csapp-notes
```

To fetch new chapters, figures, or deck updates later:

```bash
git pull
```

---

## Recommended Workflow

1. Clone/download the repo.  
2. Open the `Notes/` folder in Obsidian as a vault.  
3. Import `Computer_Systems.apkg` into Anki.  
4. Periodically pull updates from GitHub and re-import the deck when new cards are released.

---

## Contributing

This is a personal study project; contributions, suggestions, and corrections are welcome:
- Open a **pull request** for fixes or improvements.
- Open an **issue** for suggestions or discussion.

---

## License & Attribution

- Notes and flashcards © 2025 Darcy Geyer.  
- Textbook © Randal E. Bryant & David R. O’Hallaron.  
- Shared under the **MIT License** (see `LICENSE`).  
- This material is intended for educational use only and is not a substitute for the textbook.

---
