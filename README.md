<p align="center">
  <img src="assets/icon.png" width="96" alt="AAE PO Suite">
</p>

<h1 align="center">AAE PO Suite</h1>

<p align="center">
  Desktop application that turns customer purchase-order PDFs into finished PO documents.
</p>

<p align="center">
  <a href="https://github.com/Dry1ceD7/poex-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Dry1ceD7/poex-releases?label=latest&color=2f6feb"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-555">
</p>

<p align="center">
  <a href="https://github.com/Dry1ceD7/poex-releases/releases/latest"><strong>Download the latest version</strong></a>
</p>

---

## Overview

AAE PO Suite reads purchase orders received as PDF files, checks every order
against your vendor list and price list, and produces your company's PO form in
Excel and PDF. Orders that need attention are held for review with the reason
shown. Finished POs are emailed from your Microsoft 365 mailbox when you click
Send.

This repository hosts the installers and the update feed the app checks. The
source code is maintained privately.

## Features

- Import PO PDFs by drag and drop, from a watched folder, or from Outlook (approved senders only)
- Read scanned PDFs and images on your computer
- Split a PDF that holds several orders into one document per order
- Match vendors and prices, including prices with a start date
- Hold orders that need a person: totals that do not add up, revised or cancelled orders, unknown parts, unexpected ship-to addresses
- Produce the PO form in Excel and PDF, preview it in the Forms tab, and get one combined spreadsheet per run
- Email from your Microsoft 365 mailbox with a saved subject and message; nothing is sent until you click Send
- Keep every version of your price and vendor lists and compare any two
- Daily summary, full history and four appearance styles

## Download

Get the file for your system from the
[latest release](https://github.com/Dry1ceD7/poex-releases/releases/latest).

| System                | File                                                            |
| --------------------- | --------------------------------------------------------------- |
| Windows (installer)   | `AAE-PO-Suite-Setup-<version>.exe`                              |
| Windows (portable)    | `AAE-PO-Suite-<version>.exe`                                    |
| macOS (Apple silicon) | `AAE-PO-Suite-<version>-arm64.dmg`                              |
| Linux                 | `AAE-PO-Suite-<version>.AppImage` or `poex_<version>_amd64.deb` |

## Installation

The builds are not yet code-signed, so your system asks for confirmation the
first time.

**Windows.** Run the installer. If SmartScreen shows "Windows protected your
PC", select **More info**, then **Run anyway**.

**macOS.** Open the `.dmg` and drag AAE PO Suite into Applications. Open the
app; if macOS blocks it, go to **System Settings > Privacy & Security** and
select **Open Anyway**.

**Linux.** Make the AppImage executable (`chmod +x`) and run it, or install
the package with `sudo apt install ./poex_<version>_amd64.deb`.

Each release includes SHA-256 checksum files (`SHA256SUMS-*.txt`) for
verifying a download.

## System requirements

| Component | Requirement                                                             |
| --------- | ----------------------------------------------------------------------- |
| Windows   | Windows 10 or 11, 64-bit                                                |
| macOS     | Apple silicon (M1 or later), macOS 12 or later                          |
| Linux     | 64-bit x86; the `.deb` package targets Debian and Ubuntu                |
| Email     | A Microsoft 365 work account. Your administrator approves the app once. |

## Updates

The app checks this repository for a new release at startup and every six
hours. Depending on your system it installs the update the next time you quit,
or shows a link to download it here and install it over the current version.
What changed in each version is listed on the
[releases page](https://github.com/Dry1ceD7/poex-releases/releases).

## Roadmap

| Status  | Item                                                            |
| ------- | --------------------------------------------------------------- |
| Next    | Signed Windows and macOS builds, so every system updates itself |
| Planned | Highlighting of values read from scanned pages during review    |

## License

AAE PO Suite is proprietary software. All rights reserved.
