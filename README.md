# Argus

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

Everything Argus writes — your account, settings, keys, memory, conversation
and caches — lives in `~/Library/Application Support/Argus` on your Mac.
Nothing is uploaded except what you send to the AI provider you choose in
Settings → Brain. Updates never touch this folder.

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
