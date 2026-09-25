# Argus

<img src="logo.png" alt="Argus" width="160">

A voice-first assistant for your Mac. It reads your own files, mail and
calendar, answers from them, and can place a call for you. Everything it
keeps stays on your Mac.

This repository holds **releases only**. There is no source code here.

## Download

Get the latest `Argus-<version>.dmg` from
[Releases](https://github.com/shauryavatwani/Argus-Releases/releases/latest).

Requires macOS 26 or later on Apple silicon.

## Install

1. Open the DMG and drag **Argus** onto **Applications**.
2. The first time, right-click Argus in Applications and choose **Open**, then
   **Open** again. Argus is signed ad hoc, not notarized, so macOS asks once.
3. Sign in (or create an account) and follow the setup.

Argus updates itself: Settings → Updates shows a new version and installs it
when you click.

## Your data

Every account on your Mac has its own folder in
`~/Library/Application Support/Argus`: settings, keys, memory, conversation
and caches. Updates never touch it.

Only what a feature you use needs leaves your Mac, to the service behind it:

- **The AI provider you choose** in Settings → Brain: your questions, and what
  Argus read to answer them.
- **Web search:** your search, to the SearXNG instance you run and the search
  engines it queries, or to Brave Search if you add a Brave key.
- **ElevenLabs**, only if you add an ElevenLabs key: your recordings to
  transcribe, and the text Argus speaks.
- **Calls:** a call's audio goes through a Cloudflare tunnel to the person you
  call.
- **GitHub:** Argus checks this releases page for updates and downloads them
  from it.

None of it is sent to the developer.

## Uninstall

Quit Argus, drag it from Applications to the Bin, and delete
`~/Library/Application Support/Argus` if you also want your data gone.

## Licence

Copyright © 2026 Shaurya Vatwani. All rights reserved.

Argus is proprietary software, licensed, not sold. You may install and use
the copies published here. You may not copy, modify, distribute, sell,
reverse engineer, decompile or disassemble it, or create derivative works
from it, except as the copyright owner expressly permits in writing. The full
terms are in [LICENSE](LICENSE).

Third-party components included with Argus are subject to their respective
licences, listed in Settings → About and in `Contents/Resources/Licenses`.
