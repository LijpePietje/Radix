# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This repository contains no application source code. It only holds the public **privacy policy** for "Radix", a horoscope app (the app's own code lives elsewhere). The policy is in `index.md` at the repository root. The file was renamed from `Privacy Policy` to `index.md`, which suggests it is served as a static page (e.g. via GitHub Pages) and linked from the app's store listing.

There is no build, lint or test tooling: edits are plain Markdown changes to `index.md`.

## Content constraints

The policy must stay consistent with what the Radix app actually does. When editing, keep these facts in sync with the app (ask the user if a change to the app's behaviour is implied):

- Data collected: location (only with permission) and birth data entered by the user.
- All data is stored locally on the device; nothing is sent to external servers.
- Only permission requested: optional location access.
- Third parties: Swiss Ephemeris (astronomical calculations) and Google Play Services (location).
- The contact address at the bottom of the policy is the maintainer's public contact for privacy questions.

## Formatting notes

- `index.md` is written as plain text with numbered section headings and `•` bullets, not Markdown headings or lists, and has no blank lines between lines. When rendered as Markdown, consecutive lines merge into one paragraph. Keep this in mind if asked to improve the rendered output.
- Section 7 contains a literal `\n` (`7. Contact\n`), which renders as visible text.
