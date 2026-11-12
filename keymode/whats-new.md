---
title: What's new in Keymode
---

# What's new in Keymode

## 1.0.1 (12 November 2026)

- Undo works as it does in Vim: one `u` undoes a whole command, or everything typed in one insert,
  including after `o`, `O` and `c`.
- Search and replace use Vim's own pattern syntax, so word boundaries, groups and alternatives work as
  Vim users expect. `:set pcre` switches to JavaScript patterns if you prefer them.
- New commands: `:t` and `:copy`, `:m` and `:move`.
- Fixed: `:j` with a range, indenting leaving empty lines empty, the ampersand in a replacement, and the
  whitespace pattern matching a line break.
- New in Settings: Advanced, with Vim's own settings as switches: ignore case, smartcase, scrolloff and
  cursor line. Each change is saved in `.keymoderc`, and you can still edit that file by hand.
- A long command or search wraps upwards, so you can see what you are typing, and the command-line key
  row has more symbols.
- Help has a Copy address button, for writing to support from any email service, and notes on closing
  panels by touch and on search patterns. Support is now at robertfb-apps@posteo.uk.

## 1.0.0 (9 November 2026)

The first release.

- A vim-style editor for iPhone: normal, insert and visual mode, counts, text objects, registers,
  macros, search and replace, and folding.
- Its own keyboard with Esc and Ctrl, and a key row that changes with the mode. In normal mode it
  starts with the digits for counts, and each swipe stops in the same place.
- Files edited where they live: Keymode's own folder, iCloud Drive, or other apps through the
  Files app. Nothing is copied, and unsaved changes are kept as drafts.
- Find and replace across all files, word completion, and a Markdown preview.
- Syntax colours for 28 languages, six colour themes, and six fonts.
- Works with Bluetooth keyboards and VoiceOver.
- A 14-day free trial, then a one-off unlock. No subscription, no adverts, and no data collected.
