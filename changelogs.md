# Changelog

All notable changes to MarkLens. Requires macOS 26 Tahoe or later.

## 1.1 · September 2026

### New

- **Flow.** Turn on Settings → Themes → Flow and your library theme's colours rise slowly through the window, like a living glow. A slider sets the speed from 0.25× to 2.5×. Flow pauses when MarkLens isn't the front app and stays still with Reduce Motion.
- **Sync editor with library.** Let the editor use your library theme's colours and accent. You choose its fonts and text size under Customize or in Settings. Your editor themes are hidden, not deleted, and come back when you turn sync off.
- **A new app icon.** A layered Liquid Glass icon that follows your macOS icon style: Default, Dark, Clear or Tinted.
- **Find themes fast.** The Themes window has a search bar. Type a name to jump to it, press Return for the next match, or use the back button to return. Swipe sideways on the search bar and it turns into a scrubber for flicking through themes.
- **Haptic feedback.** A light tap on your Force Touch trackpad or Magic Trackpad as each theme snaps into place. Settings → General → Trackpad has an on/off switch and a five-step intensity slider. It's greyed out on Macs whose trackpad can't do haptics.
- **Clean up images.** Settings → General → Storage shows how much space images use and can move images that no document uses to the Trash.

### Improved

- Pasted and large dropped images are saved in a smaller format when they have no transparency, and the same image is never stored twice.
- Flow fades in and out smoothly when you turn it on or off.
- Flow, the theme gallery's 3D swipe and other animations automatically ease off in Low Power Mode or when the Mac is running hot.
- The theme gallery swipes and scrubs smoothly. Card previews are drawn far more efficiently and the background no longer re-blurs on every step.
- With sync on, each library theme shows a small preview of how the editor will look, in the gallery, in Customize and in Settings.
- The light/dark preview switch matches the search bar's height and Liquid Glass style.
- Every editor theme adapts to light and dark mode, including Midnight and themes you create.
- The Themes window follows your Mac's appearance instead of always being dark.
- New Document, More and the inspector button now sit together at the top right of the library.
- Typing in long documents, searching and the inspector preview are faster and use less power.
- Theme cards have lighter frames, and the Settings carousel no longer cuts off the first card.
- Image drag and paste checks are much lighter, so dragging over the editor stays smooth.

### Fixed

- Text could appear dark on a dark editor theme.
- Locked documents moved to the Trash disappeared from view.
- Erase All Content could remove files that were opened from Finder. It now only touches the MarkLens library, and also signs out of GitHub.
- Themes could reset to the defaults after an update. A backup is now kept if a theme file can't be read.
- Undo could get confused after a numbered list renumbered itself.
- Documents with front matter, comments or nested indentation now open in Coding mode so nothing is rewritten.
- Publishing to a branch that doesn't exist yet now creates it instead of writing to the default branch.
- Switching repositories quickly in the publish window could pick a branch from the wrong repository.
- A locked document could still be typed into while hidden behind the lock screen.
- Temporary copies made for sharing a locked document are now deleted when the vault locks.
- Saving files opened from Finder is more reliable.

## 1.0 · September 2026

The first release.

- **Live editing** that looks like the finished page, plus Coding and Viewing modes.
- **Theme gallery** with editor and library themes: accents, backgrounds, fonts and sizes.
- **Table designer** with header, stripe, border, spacing and rounded-corner styles.
- **Encrypted locks.** Locked documents are encrypted on disk with AES-256 and open with Touch ID. The Trash needs Touch ID too.
- **Publish to GitHub.** Send a document and all of its images to a repository in one commit.
- **Custom keyboard shortcuts** with conflict warnings.
- **Export** to PDF, HTML, Rich Text and Markdown, with images included.
- **Groups** with any name, colour and SF Symbol.
- **Code blocks** in 20 languages with auto-detect and Xcode-style or accent colours.
- **Images** by drag and drop or ⌘V, and .md files you can drop in.
- **Quick Look** previews and MarkLens as your default Markdown app, with an Opened Files section for files from Finder.
- **Installer app and DMG**, update checks against GitHub Releases, and a What's New window.
