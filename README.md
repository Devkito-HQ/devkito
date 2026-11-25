<div align="center">

<img src="assets/icon.png" width="96" height="96" alt="Devkito icon">

# Devkito

**Every small dev tool you keep googling, in one app.**

120+ formatters, encoders, converters, generators and network checks behind one shortcut.<br>
They run on your machine, so they work offline and what you paste stays with you.

[**Download**](https://devkito.com/download) · [Website](https://devkito.com) · [All tools](https://devkito.com/tools) · [Changelog](https://devkito.com/changelog) · [Pricing](https://devkito.com/pricing)

macOS (Apple silicon and Intel) · Windows 10/11 · Linux (AppImage, .deb, .rpm)

<br>

<img src="assets/screens/app.webp" alt="The Devkito window with the JWT Parser open" width="900">

</div>

## Why Devkito

- **Your data stays on your machine.** Tokens, keys and customer data never go through someone else's website. Network tools only contact the host you point them at.
- **One shortcut away.** Press <kbd>⌥</kbd><kbd>⌘</kbd><kbd>K</kbd> (<kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>K</kbd> on Windows and Linux) from any app to bring Devkito forward with search open. You can change the shortcut in Settings.
- **Opens what you copied.** Copy a token, JSON, SQL or a URL and press the shortcut: when it is clearly one thing, its tool opens with it filled in; otherwise the matches are listed first in search. Copied text stays in memory and is never saved.
- **Keyboard all the way.** <kbd>⌘</kbd><kbd>↵</kbd> presses a tool's Run or Generate button and <kbd>⇧</kbd><kbd>⌘</kbd><kbd>C</kbd> copies its result (<kbd>Ctrl</kbd> on Windows and Linux).
- **Picks up where you left off.** Inputs, favourites and recent tools are remembered between sessions, and settings can be exported to another machine.
- **Made to sit next to your editor.** Keep it always on top or in a compact window, zoom the whole app with <kbd>⌘</kbd><kbd>=</kbd> / <kbd>⌘</kbd><kbd>−</kbd>, and hide the tools you never use.
- **A real desktop app.** Native window, tray icon, light and dark themes, English and Vietnamese, and automatic updates. Some tools only a desktop app can offer, such as seeing which process holds a port and stopping it, or HTTP requests without CORS.

## See it in action

<table>
  <tr>
    <td width="50%">
      <img src="assets/clips/palette.gif" alt="Pasting a token into search opens the JWT Parser">
      <p><b>Paste into search, get the right tool.</b> Put a token, JSON, URL or cron line into <kbd>⌘</kbd><kbd>K</kbd> and Devkito suggests the tool that reads it.</p>
    </td>
    <td width="50%">
      <img src="assets/clips/search.gif" alt="Typing part of a tool name and pressing Enter">
      <p><b>Find any tool in a few keystrokes.</b> Type part of a name and press Enter. Output updates as you type, with no Convert button.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="assets/clips/smart-paste.gif" alt="Pasting with no tool selected">
      <p><b>Paste without choosing a tool.</b> Devkito recognises what you copied and offers to open it in the matching tool.</p>
    </td>
    <td width="50%">
      <img src="assets/clips/themes.gif" alt="Switching between light and dark themes and languages">
      <p><b>Light or dark, English or Vietnamese.</b> Switch from the toolbar; Devkito remembers your choice.</p>
    </td>
  </tr>
</table>

## A few of the tools

<table>
  <tr>
    <td width="50%"><img src="assets/screens/json-viewer.webp" alt="JSON Viewer"><p align="center">JSON Viewer</p></td>
    <td width="50%"><img src="assets/screens/regex-tester.webp" alt="Regex Tester"><p align="center">Regex Tester</p></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screens/jwt-parser.webp" alt="JWT Parser verifying a signature"><p align="center">JWT Parser</p></td>
    <td width="50%"><img src="assets/screens/curl-to-code.webp" alt="cURL to Code"><p align="center">cURL to Code</p></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/screens/port-viewer.webp" alt="Port &amp; Process Viewer"><p align="center">Port &amp; Process Viewer</p></td>
    <td width="50%"><img src="assets/screens/color-shades.webp" alt="Color Shades Generator"><p align="center">Color Shades Generator</p></td>
  </tr>
</table>

## What's inside

120+ tools in 10 groups. Each one has its own page on [devkito.com/tools](https://devkito.com/tools).

<details>
<summary><b>Development</b></summary>

.env Sorter, Chmod Calculator, Code Formatter, Crontab Generator, cURL to Code, Docker Run to Compose, Email Normalizer, Git Cheat Sheet, Gitignore Generator, ID Decoder, JSON Schema Generator, JSON Schema Validator, JSON to Code, JSON Viewer, JSON ⇄ CSV Converter, License Generator, Random Port Generator, Regex Tester, Semver Checker
</details>

<details>
<summary><b>Web</b></summary>

Basic Auth Generator, Bookmarklet Generator, Color Contrast Checker, Color Shades Generator, CSS Box Shadow Generator, CSS Gradient Generator, Device Information, HTML to JSX, HTML WYSIWYG Editor, HTTP Client, HTTP Header / Cookie Parser, HTTP Status Codes, JSON Diff, JWT Generator, JWT Parser, Keycode Info, Meta Tag Generator, MIME Types, OTP Code Generator, Safelink Decoder, Slugify String, Tailwind CSS Converter, URL Encoder / Decoder, URL Parser, User Agent Parser
</details>

<details>
<summary><b>Converter</b></summary>

Base64 / Base32 / Base58 Converter, Base64 Image Encoder, Byte Unit Converter, Case Converter, Color Converter, CSS Unit Converter, Gzip / Brotli Compressor, Integer Base Converter, List Converter, Markdown ⇄ HTML Converter, MessagePack / CBOR Decoder, Roman Numeral Converter, Text to Binary, Text to NATO Alphabet, Text to Unicode, Timestamp Diff, Timezone Converter, TOML / YAML / JSON Converter, Unix Timestamp Converter, XML / JSON Converter
</details>

<details>
<summary><b>Crypto</b></summary>

Bcrypt / Argon2 Hash, BIP39 Mnemonic Generator, Certificate Decoder, Encryption / Decryption, Hash Text & File Checksum, HMAC Generator, Password Strength Analyser, PEM / JWK Converter, PGP Encrypt / Decrypt / Sign / Verify, RSA Key Pair Generator, SSH Key Generator, Token Generator, UUID / ULID Generator
</details>

<details>
<summary><b>Text</b></summary>

ASCII Text Drawer, Diff Viewer, Emoji Picker, Line Tools, List Comparer, Lorem Ipsum Generator, Markdown Table Generator, Numeronym Generator, Regex Library, String Escape / Unescape, String Obfuscator, String Similarity, Text Statistics, Unicode Inspector
</details>

<details>
<summary><b>Images & Videos</b></summary>

EXIF Viewer & Remover, Favicon Generator, Image Compressor, Image Format Converter, Image Generator, QR Code Generator, QR Code Reader, SVG Optimizer, SVG Placeholder Generator
</details>

<details>
<summary><b>Network</b></summary>

CIDR Matcher, DNS Lookup & WHOIS, IPv4 Address Converter, IPv4 Subnet Calculator, IPv6 ULA Generator, MAC Address Generator, Port & Process Viewer, TLS / SSL Checker
</details>

<details>
<summary><b>Data</b></summary>

CSV Viewer / Editor, IBAN Validator, JSON Expression Eval, Mock Data Generator, Phone Parser
</details>

<details>
<summary><b>Math</b> and <b>Measurement</b></summary>

Aspect Ratio Calculator, ETA Calculator, Math Evaluator, Percentage Calculator, Benchmark Builder, Chronometer, Temperature Converter
</details>

## Install

Get the installer for your system from [devkito.com/download](https://devkito.com/download) or the [latest release](https://github.com/Devkito-HQ/devkito/releases/latest).

| System | File |
| --- | --- |
| macOS, Apple silicon | `Devkito_<version>_aarch64.dmg` |
| macOS, Intel | `Devkito_<version>_x64.dmg` |
| Windows 10/11, 64-bit | `Devkito_<version>_x64-setup.exe` |
| Linux | `.AppImage`, `.deb` (Debian, Ubuntu) or `.rpm` (Fedora, RHEL) |

The installers are not code-signed yet, so your system asks before opening Devkito the first time. You only do this once ([step-by-step guide](https://devkito.com/download#first-launch)):

- **macOS:** open Devkito once and click **Done** when macOS says it can't verify it. Then go to **System Settings → Privacy & Security**, click **Open Anyway** next to the message about Devkito, and confirm. (On macOS 14 or earlier, right-clicking Devkito in Applications and choosing **Open** also works.) If macOS says the app is damaged, run `xattr -cr /Applications/Devkito.app` and try again.
- **Windows:** if Edge warns that the installer isn't commonly downloaded, choose **Keep**, then **Keep anyway**. When SmartScreen appears, click **More info**, then **Run anyway**.
- **Linux (AppImage):** `chmod +x Devkito_*.AppImage`, then run it.

After that, Devkito updates itself: it checks this repository for new releases and asks before installing one.

## Pricing

Try every tool free for 7 days, with no account or card. After that, a one-time licence keeps Devkito working forever and includes a year of updates:

| Computers | Price |
| --- | --- |
| 1 | $10 |
| 2 | $15 |
| 5 | $30 |

Buy on [devkito.com/pricing](https://devkito.com/pricing). Move a licence to another computer from Settings whenever you need.

## Privacy

Every tool except the network ones (DNS, WHOIS, TLS and HTTP requests) runs entirely on your machine, and clipboard detection never sends or saves what you copied. Devkito only goes online for licence checks, update checks and, if you leave them on, anonymous crash reports, which never include what you type into tools. Details in the [privacy policy](https://devkito.com/privacy).

## Feedback and support

- Found a bug or want a tool Devkito doesn't have? [Open an issue](https://github.com/Devkito-HQ/devkito/issues).
- Licence and billing questions: [support@devkito.com](mailto:support@devkito.com).

Including your Devkito version (Settings) and your operating system helps us answer faster.

---

This repository hosts Devkito's releases and issue tracker. The app's source code is not public.
