---
title: Inputrc support
---

# Inputrc support

Inputrc is a keyboard-driven text editor for iPhone, worked with Ctrl and Meta keys. It is an
editor only: it does not compile, run or debug code.

## Contact

The easiest way is from Inputrc itself: open Help, and at the end tap **Get help or report a
problem**. It opens an email to robertfb-apps@posteo.uk with a few questions to answer, and
Inputrc's version and the iOS version already filled in. Nothing from your files is added, and you
see the whole email before sending it.

If the button opens no email (for example, no mail account is set up on the iPhone), write from
any email service to **robertfb-apps@posteo.uk**; the address is shown under the button, and
**Copy address** beside it copies it. The
address is the same for all of the developer's apps, so please say the email is about Inputrc.
It helps to include:

- the app's version and build, shown in Inputrc under About (for example 1.0.0 (17));
- your iPhone model and iOS version;
- which keyboard you use: Inputrc's own, the iPhone's, or a Bluetooth keyboard;
- what you did, what you expected, and what happened instead. A screenshot helps.

Please do not send text or files you would not want read. Replies come from the same address.

## Questions and answers

### What Inputrc is

**Does Inputrc run or compile code?** No. Inputrc is an editor only: it edits text and code and
saves them, but it does not run, compile or debug anything, and it does not run scripts of its
own. Use it alongside the tools that do.

**How is it worked?** With keys: C-f means hold Ctrl and press f; M-f means hold Meta (on a
Bluetooth keyboard, the Alt key, which Apple's keyboards call Option) and press f, or press Esc and
then f. Moving, searching, the mark and region,
cutting and pasting with a kill ring, undo, buffers and files are all on Ctrl and Meta, and
M-x runs any command by its name. Help, in Inputrc, lists every key.

**Can I use it on an iPad, or with the phone turned sideways?** Not yet. Inputrc 1.0 is for
iPhone, upright.

**Where is the list of commands?** In Inputrc, open Help (or C-h C-h). Its Export button saves the
same list as a file to keep beside your work.

### Files

**Where are my files?** In the Files app, under On My iPhone, Inputrc. A file you opened from
elsewhere (iCloud Drive, another app's folder) stays where it is and is saved back there.

**Are my files backed up?** Inputrc's own folder is part of your iPhone's normal backups (iCloud
Backup, or a backup to a computer), as other apps' documents are. Files you open from elsewhere
are backed up wherever they live. Unsaved changes are kept as a draft, so closing Inputrc loses
nothing.

**Does Inputrc sync between devices?** Not by itself. Open a file from iCloud Drive (in Inputrc,
tap the buffer name at the top, then Open from Files) and Inputrc edits it where it lives, so
iCloud keeps it in step on your other devices.

**A save says the file changed elsewhere.** Another app changed the file since Inputrc opened it.
C-x C-s then asks whether to save anyway; M-x revert-buffer loads the other version instead (C-/
undoes that).

**How do I close a file?** C-x k closes its buffer; the file is never deleted. If it has unsaved
changes, Inputrc asks first: yes, no, or save and then close.

### Keyboards

**Can I use a Bluetooth keyboard?** Yes, and it is the quickest way to work. Meta is the Alt key
(Option on Apple's keyboards). On keyboards that need that key for characters, such as # on a UK
Apple keyboard, Inputrc's Settings, Right Option key, can make the right one type characters while
the left one stays Meta. The iPhone can also make Caps Lock a second Ctrl key, in the iPhone's
Settings app: General, Keyboard, Hardware Keyboard, Modifier Keys. Keyboards vary, and not every
key on every keyboard can be promised.

**My keyboard has no Esc key.** C-[ (Ctrl and the left square bracket) is Esc.

**Can I use the iPhone's own keyboard?** Yes: in Inputrc's Settings, Keyboard, iPhone keyboard. It has no Ctrl
or Meta keys, so Inputrc's commands then need a Bluetooth keyboard.

**How do I close Help or Settings without a keyboard?** Tap Close at the top right. On a Bluetooth
keyboard, q, C-g or Esc closes them too.

### The trial and the unlock

**How do the trial and the unlock work?** Every feature works for 14 days from the moment you
start the free trial. Afterwards your files can still be opened, read, searched, copied and
shared, and editing and saving need the unlock: a single purchase, not a subscription. Nothing is
collected, and there are no adverts. The price is the one the App Store shows.

**It says READ ONLY at the top.** The free trial has not been started, or it has ended without the
unlock. Tap READ ONLY (or M-x unlock-inputrc) to start the trial, unlock, or restore a purchase.

**I have a new iPhone, or I reinstalled Inputrc.** Open Inputrc's Settings, then Trial and unlock,
and tap Restore purchases. The trial and the unlock belong to your Apple Account.

**How do I get a refund?** Refunds are handled by Apple, not by the developer:
<https://reportaproblem.apple.com/>.

## Privacy

Inputrc collects no data. See the [privacy policy](privacy).
