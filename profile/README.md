# Leafcroft

A free, open-source notes platform. Your notes are plain markdown files on your own device. A small core app reads them, and plugins, themes and starter kits do the rest.

A leaf is a page. A croft is a small plot of land a family works themselves, next to land everyone shares. Your notes are your croft. The plugins and kits are the commons.

## Where things stand

October 2026: the research is done, the name is chosen, and nothing is built yet. This page will say so until that changes.

The first piece of code is a test, not a feature. Open a folder of real notes, save them, and prove that not one byte changed. Everything else waits on that.

## What we promise

- You never pay. No paid tier, no paid sync, no paid plugins from us.
- Your notes stay plain files that open in any text editor.
- The folder format is a public spec with test files, so anyone can build an app for it.
- No ads, no tracking, no network connection you did not ask for.
- The license stays open, and we will not relicense.

The full version, including how the project is paid for and what happens if we stop, is in [the charter](CHARTER.md).

## How it will be built

- Markdown files are the true copy. A relational database can be a plugin that keeps its own file in the notes folder.
- A tiny core plus WordPress-style plugins, themes and starter kits. A starter kit sets up a whole use case, like a bank ledger or a club roster, in one step.
- Tauri 2 for Mac, Windows, Linux, iPhone and Android. No Electron.
- Sync launches with WebDAV plus "point any sync tool at the folder". Other backends are plugins.
- Plugins declare what they touch before you install them. AI will write many of them, so the platform assumes plugin code might be wrong.

## Follow along

- Bluesky: [@leafcroft.org](https://bsky.app/profile/leafcroft.org)
- Email: hello@leafcroft.org
- Code and discussion will appear in this organization as they exist.
