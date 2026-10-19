---
title: Keymode support
---

# Keymode support

Keymode (on the App Store as "Keymode: Vim-Style Editor") is a keyboard-driven, vim-style text
editor for iPhone. It is an editor only: it does not compile, run or debug code.

## Contact

The easiest way is from Keymode itself: open Help, and at the end tap **Get help or report a
problem**. It opens an email to keymode@posteo.uk with a few questions to answer, and Keymode's
version, the iOS version and the keyboard setting already filled in. Nothing from your files is
added, and you see the whole email before sending it.

You can also write to **keymode@posteo.uk** directly. It helps to include:

- the app's version and build, shown in Keymode under About (for example 1.0.0 (10));
- your iPhone model and iOS version;
- which keyboard you use: Keymode's own, the iPhone's, or a Bluetooth keyboard;
- what you did, what you expected, and what happened instead. A screenshot helps.

Please do not send text or files you would not want read. Replies come from the same address.

## Questions and answers

### What Keymode is

**Does Keymode run or compile code?** No. Keymode is an editor only: it edits text and code and
saves them, but it does not run, compile or debug anything. Use it alongside the tools that do.

**Is it the same as Vim?** No. Keymode follows Vim's way of working (normal, insert and visual
mode, counts such as 3j, text objects such as ciw, registers, macros, :s and :%s), but it is not
Vim itself, and not every Vim command is there. Help lists what is.

**Can I use it on an iPad, or with the phone turned sideways?** Not yet. Keymode 1.0 is for
iPhone, upright. Both may come later.

**Where is the list of commands?** In Keymode, open Help. Its Export button saves the same list as
a file, "Keymode help.md", to keep beside your work.

### Files

**Where are my files?** In the Files app, under On My iPhone, Keymode. A file you opened from
elsewhere (iCloud Drive, another app's folder) stays where it is and is saved back there.

**Are my files backed up?** Keymode's own folder is part of your iPhone's normal backups (iCloud
Backup, or a backup to a computer), as other apps' documents are. Files you open from elsewhere
are backed up wherever they live. Unsaved changes are kept as a draft, so closing Keymode loses
nothing.

**Does Keymode sync between devices?** Not by itself. Open a file from iCloud Drive (in Keymode,
tap the file name at the top, then Open from Files) and Keymode edits it where it lives, so iCloud
keeps it in step on your other devices. The same works for other apps that offer their files to
the Files app, such as Working Copy for Git.

**A file says it is "being downloaded from iCloud".** iCloud had removed the file from the iPhone
to save space. Keymode has asked for it back; open it again in a moment.

**A save says the file changed elsewhere.** Another app changed the file since Keymode opened it.
:w! saves your version over theirs; :e! loads theirs (u undoes that).

### Keyboards

**How do I leave insert mode without an Esc key?** Press Ctrl-[ (Control and the left square
bracket), or tap the mode name (INSERT or VISUAL) at the bottom left.

**Can I use a Bluetooth keyboard?** Yes. Keep the Keyboard setting on Keymode keyboard and put
Keymode's keyboard away with its hide key; a tap on the text brings it back. Keyboards vary, and
not every key on every keyboard can be promised.

**Can I use the iPhone's own keyboard?** Yes: Settings, Keyboard, iPhone keyboard. It has no Esc
or Ctrl key, so the answer above about leaving insert mode applies.

### Settings

**Can I keep my own settings, as in a .vimrc?** Yes. A file named .keymoderc in Keymode's folder
is read at start-up. It can hold :set, :syntax, map and unmap lines. Help, under Start-up file,
explains it.

### The trial and the unlock

**How do the trial and the unlock work?** Every feature works for 14 days from the moment you
start the free trial. Afterwards your files can still be opened, read, searched, copied and
shared, and editing and saving need the unlock: a single purchase, not a subscription. Nothing is
collected, and there are no adverts. The price is the one the App Store shows.

**I have a new iPhone, or I reinstalled Keymode.** Open Settings in Keymode, then the trial and
unlock panel, and tap Restore purchases. The trial and the unlock belong to your Apple Account.

**How do I get a refund?** Refunds are handled by Apple, not by the developer:
<https://reportaproblem.apple.com/>.

## Privacy

Keymode collects no data. See the [privacy policy](privacy).
