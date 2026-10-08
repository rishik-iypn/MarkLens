<p align="center">
<img src="https://github.com/user-attachments/assets/ccada4ee-1c6e-48c6-9533-3977e5fc8e92" width="128 alt="MarkLens icon">
</p>

<h1 align="center">MarkLens</h1>

<p align="center">
A calm Markdown editor for macOS 26, built with SwiftUI and Liquid Glass.<br>
Write in rich text, keep plain Markdown underneath.
</p>

<p align="center">
<a href="https://github.com/TheCommandPrompt-Mac/MarkLens/releases/latest"><b>Download MarkLens 1.7.1</b></a> ·
<a href="changelogs.md">What’s new</a>
</p>

<p align="center">
<img alt="macOS 26+" src="https://img.shields.io/badge/macOS-26%2B-black?logo=apple">
<img alt="Swift" src="https://img.shields.io/badge/Swift-SwiftUI-orange?logo=swift&logoColor=white">
<img alt="Version" src="https://img.shields.io/badge/version-1.7.1-6E56CF">
</p>

---

## Why MarkLens

Most Markdown apps make you choose between pretty and plain. MarkLens edits like a document and saves like a text file, so your notes stay yours and open anywhere.

## Features

**Write**

- Live editing that looks like the finished page, plus a raw Coding mode and a clean Viewing mode
- Math (`$…$`, `$$…$$`), Mermaid diagrams, footnotes, `[TOC]`, `==highlights==` and callouts
- Tags with `#anything`, snippets like `;date`, emoji with `:smile`, and smart paste from the web
- Focus Mode, Typewriter scrolling, folding headings, word goals and a focus timer
- Command palette on ⇧⌘P

**Read & share**

- Reading mode and full-screen Present mode from `---` sections
- Export to styled PDF, HTML, RTF and Markdown, or copy as rich text
- Kanban view for any checklist
- Publish to GitHub Pages or pull a document back from your repo

**Library**

- Pins, favourites, archive, Smart Groups and folders from your Mac
- Covers, icons, templates and daily notes
- Search every document at once, with tag and date filters
- Import from Notion, Bear, Obsidian and Apple Notes, plus daily backups

**Mac**

- Touch ID locks (tied to this Mac) and password locks (open on any Mac)
- A Now Playing island for Music and Spotify, with a beat-synced visualiser
- Spotlight, Shortcuts, Services, a menu bar extra and Quick Look previews
- Themes that follow the time of day, shareable `.mltheme` files

## Install

1. Download **MarkLens-1.7.1.dmg** from [Releases](https://github.com/TheCommandPrompt-Mac/MarkLens/releases/latest).
2. Open it and run **Install MarkLens**.
3. The first time, right-click the installer → **Open** → **Open** (the app is not notarised yet).

Requires **macOS 26 Tahoe** or later.

## Project layout

| Folder | What’s inside |
| --- | --- |
| `MarkLens/App` | App entry, windows, menus, startup screen |
| `MarkLens/Editor` | Rich editor, code editor, toolbar, tables, writing aids |
| `MarkLens/Library` | Library window, sidebar, grid, inspector, search |
| `MarkLens/Markdown` | Parser, preview and math/diagram rendering |
| `MarkLens/Models` | Documents, themes, shortcuts, export, app info |
| `MarkLens/System` | Locks, Spotlight, Shortcuts, Now Playing |
| `MarkLens/Settings` | Settings and theme galleries |
| `Shared` | Markdown to HTML, shared with Quick Look |
| `QuickLook` | Finder preview extension |
| `Installer` | The Install MarkLens app |
| `Tools` | Installer script and DMG artwork |
| `docs` | Website (GitHub Pages) |

## Privacy

Your documents stay on your Mac. MarkLens only talks to the network when you check for updates, publish to GitHub, or load a Spotify cover. Music control and the visualiser ask for permission first and never record anything.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/TheCommandPrompt-Mac/MarkLens/issues).

<p align="center"><sub>Made with care for macOS by Rishik.</sub></p>

