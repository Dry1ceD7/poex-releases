# AAE PO Suite releases

AAE PO Suite (formerly POex) is a desktop app for teams that receive customer
purchase orders as PDF files and need to turn them into their own PO documents.
It reads each PO, checks it against your vendor list and price list, holds
anything doubtful for a person with a plain reason, produces your PO form as
Excel and PDF, and emails it from your Microsoft 365 mailbox when you click
Send.

This repository hosts the installers and the update feed the app checks. The
source code is private.

**[Download the latest release](https://github.com/Dry1ceD7/poex-releases/releases/latest)**

## Features

- **Bring POs in your way:** drag and drop, a watched folder, or pick them up
  from Outlook, only from the senders you list. Scanned PDFs and images are
  read on your computer. A PDF holding several POs is split into one document
  per PO.
- **Checks before anything goes out:** vendor and price-list matching
  (including prices with start dates), totals that must add up, revised or
  cancelled orders, parts missing from the price list and unexpected ship-to
  addresses. A PO that needs a look waits in Work with the reason.
- **Your PO form, ready to send:** Excel and PDF output, a Forms tab that
  previews the result, and one combined spreadsheet per run. Clean POs can be
  produced unattended, limited to the vendors you choose.
- **Email from your own mailbox:** POs go from your Microsoft 365 account with
  your saved subject and message, and a copy stays in Sent Items. Nothing is
  sent until you click Send.
- **Master data history:** every price list and vendor list version is kept,
  and any two can be compared and exported to Excel.
- **Daily summary, history and four appearance styles.**

## Install

Pick the file for your computer from the
[latest release](https://github.com/Dry1ceD7/poex-releases/releases/latest).
Each release also lists SHA-256 checksums (`SHA256SUMS-*.txt`).

| System                    | File                                                            |
| ------------------------- | --------------------------------------------------------------- |
| Windows 10 or 11 (64-bit) | `AAE-PO-Suite-Setup-<version>.exe` (installer)                  |
| Windows, no install       | `AAE-PO-Suite-<version>.exe` (portable)                         |
| macOS on Apple silicon    | `AAE-PO-Suite-<version>-arm64.dmg`                              |
| Linux (64-bit)            | `AAE-PO-Suite-<version>.AppImage` or `poex_<version>_amd64.deb` |

The builds are not yet code-signed, so the first launch asks for confirmation:

- **Windows:** if SmartScreen says "Windows protected your PC", choose
  **More info**, then **Run anyway**.
- **macOS:** open the app once; when macOS blocks it, go to
  **System Settings > Privacy & Security** and choose **Open Anyway**.

Emailing needs your organization's Microsoft 365 administrator to approve the
AAE PO Suite sign-in once. Until then, everything else works and emails wait.

## Updates

The app checks this repository for a newer release when it starts and every
six hours, and tells you when one is available. Depending on your system it
either installs the update the next time you quit, or links you here to
download it and install it over the current version.

What changed in each version is in the notes of each
[release](https://github.com/Dry1ceD7/poex-releases/releases).

## Roadmap

- **Next:** signed Windows and macOS builds, so updates install themselves on
  every system and the first-launch confirmation goes away.
- **Later:** values read from scanned pages highlighted for review.
