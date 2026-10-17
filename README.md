<div align="center">

<img src=".github/assets/logo.png" width="112" alt="AAE PO Suite">

# AAE PO Suite

Turn customer purchase-order PDFs into checked, ready-to-send PO documents.

[![Release](https://img.shields.io/github/v/release/Dry1ceD7/poex-releases?style=flat-square&label=release&color=2f81f7)](https://github.com/Dry1ceD7/poex-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Dry1ceD7/poex-releases/total?style=flat-square&color=2f81f7)](https://github.com/Dry1ceD7/poex-releases/releases)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-555?style=flat-square)
![License](https://img.shields.io/badge/license-proprietary-555?style=flat-square)

[![Download](https://img.shields.io/badge/Download-latest_version-2f81f7?style=for-the-badge)](https://github.com/Dry1ceD7/poex-releases/releases/latest)

</div>

## Features

<table>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/inbox.svg" width="28" alt=""><br>
      <b>Flexible intake</b><br>
      Drag and drop, up to five watched folders, saved Outlook emails, or Outlook pickup from approved senders.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/file-search.svg" width="28" alt=""><br>
      <b>Sorts out what is not a PO</b><br>
      Drawings, invoices, quotations and other files are set aside with a reason, and your allow and block rules decide.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/scan-text.svg" width="28" alt=""><br>
      <b>Reads scans</b><br>
      Scanned PDFs and images are read on the computer, in English, Thai and Chinese. Multi-order PDFs are split.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/shield-check.svg" width="28" alt=""><br>
      <b>Checks every order</b><br>
      Vendor and price matching, totals, revisions and ship-to, with a clear reason when something needs review. Item tables drawn as a grid are read twice.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/badge-check.svg" width="28" alt=""><br>
      <b>Proven before it skips review</b><br>
      A PO skips review only when the POs you checked prove each of its fields right, at the error limit you choose.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/list-checks.svg" width="28" alt=""><br>
      <b>Optional checks</b><br>
      Compare POs with your quote register or with TE order files from SupplyOn, and check scans by reading them as pictures. All off until you turn them on.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/text-search.svg" width="28" alt=""><br>
      <b>Parts by description</b><br>
      When a part number is missing or not on the price list, Review suggests parts whose description fits. Nothing is filled in until you choose.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/history.svg" width="28" alt=""><br>
      <b>Change orders</b><br>
      When a customer changes a PO, Review lists every change, and Apply changes produces it again as Rev 2, linked to the original.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/layout-template.svg" width="28" alt=""><br>
      <b>Templates for any supplier</b><br>
      Drafted from a PO you checked, tested on it, and checked against earlier POs before it is saved.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/file-spreadsheet.svg" width="28" alt=""><br>
      <b>Your PO form</b><br>
      PDF output from your own template, signed with your company certificate if you wish, with an Excel copy and one combined spreadsheet per run as options.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/mail.svg" width="28" alt=""><br>
      <b>Microsoft 365 email</b><br>
      Formatted messages with your logo, signature, Cc and Bcc, sent from your mailbox only when you click Send.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/package.svg" width="28" alt=""><br>
      <b>Order book</b><br>
      Every line you send is tracked as open, part shipped, shipped, late or cancelled, with on-time-in-full for each customer.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/layout-dashboard.svg" width="28" alt=""><br>
      <b>Dashboard</b><br>
      Order value, top parts, price changes and turnaround at a glance, with a warning when a customer's regular order is late.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/fingerprint-pattern.svg" width="28" alt=""><br>
      <b>Tamper-evident records</b><br>
      Every history entry is sealed, so a change made outside the app shows. Every price list and vendor list version is kept.
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/icons/languages.svg" width="28" alt=""><br>
      <b>English, Thai and Chinese</b><br>
      Every screen in English, ไทย or 简体中文, chosen in Settings or on first run.
    </td>
  </tr>
</table>

## Download

| Platform              | File                                                            |
| --------------------- | --------------------------------------------------------------- |
| Windows               | `AAE-PO-Suite-Setup-<version>.exe`                              |
| Windows (portable)    | `AAE-PO-Suite-<version>.exe`                                    |
| macOS (Apple silicon) | `AAE-PO-Suite-<version>-arm64.dmg`                              |
| Linux                 | `AAE-PO-Suite-<version>.AppImage` or `poex_<version>_amd64.deb` |

All files are on the [latest release](https://github.com/Dry1ceD7/poex-releases/releases/latest), with SHA-256 checksums.

## Installation

The Windows builds are not code-signed, and the Mac build is signed with the company's own certificate rather than one from Apple, so the first launch asks for confirmation.

- **Windows:** run the installer. On the SmartScreen prompt, select **More info**, then **Run anyway**.
- **macOS:** drag the app into Applications and open it. If it is blocked, go to **System Settings > Privacy & Security** and select **Open Anyway**.
- **Linux:** run the AppImage after `chmod +x`, or install with `sudo apt install ./poex_<version>_amd64.deb`.

## Requirements

| Platform | Requirement                                                     |
| -------- | --------------------------------------------------------------- |
| Windows  | Windows 10 or 11, 64-bit                                        |
| macOS    | macOS 12 or later on Apple silicon                              |
| Linux    | 64-bit x86, Debian or Ubuntu for the `.deb`                     |
| Email    | Microsoft 365 work account, approved once by your administrator |

## Updates

The app checks for a new version at startup and every six hours. The installed Windows app, the Mac app and the Linux builds download it in the background and install it when you quit or click **Restart to update**. The portable Windows copy links you to the download instead. A copy older than 1.3.0 needs the latest version installed by hand once; later versions arrive on their own.

After an update, a short "What's new" screen lists what changed, with an optional guided tour. The [release notes](https://github.com/Dry1ceD7/poex-releases/releases) have the details.

## License

Proprietary. All rights reserved.
