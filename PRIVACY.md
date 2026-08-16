# Privacy Policy — CSS themes

_Last updated: 16 August 2026_

> **Disclaimer.** This policy may be updated from time to time. The current
> version is the one published in this document.

This policy describes how this repository (the "CSS themes") handles data.
The short answer: **the CSS themes are plain, static stylesheets. They collect
nothing, store nothing and transmit nothing.** There is no code in this
repository — only CSS — and therefore no mechanism by which any data could be
collected, processed or transmitted.

## 1. What this repository is

This repository contains **original CSS theme files** for personal user-interface
styling:

- `pear-music-theme/dark.theme.css` — a dark theme for the YouTube Music web
  interface, applied on your own device via a user-style browser extension
  (e.g. Stylus);
- `Vencord/translucent.theme.css` and `Vencord/padelle.theme.css` — themes for
  Discord client modifications (Vencord/BetterDiscord).

These are **demonstrative and educational** files (see DISCLAIMER.md). They are
provided to illustrate CSS customization techniques. They contain no JavaScript,
no executables, no trackers and no data-collection logic of any kind.

## 2. Data processed

**None.** The CSS themes:

- do **not** collect personal data;
- do **not** read, store or transmit any of your data;
- do **not** use cookies, `localStorage`, `sessionStorage`, IndexedDB or any
  other form of persistent storage;
- do **not** run scripts of any kind;
- request **no permissions**.

A stylesheet only restyles the visual appearance of the host application's
interface (colors, layout, fonts). It cannot, and does not, inspect or access
your content, your messages, your viewing history or any other data.

## 3. Network access

The CSS files themselves perform no network requests. The only network
reference in the repository is a single `@import` inside
`Vencord/padelle.theme.css`:

```
@import url("https://raw.githubusercontent.com/padelle2603/css-themes/main/Vencord/translucent.theme.css");
```

If you apply this theme, your browser (or client) fetches the companion base
theme `translucent.theme.css` from **this repository's own GitHub
raw-content CDN** (`raw.githubusercontent.com`) — i.e. from the project itself,
not from any third party. This loads a stylesheet from the same project and
contains no data about you. As with any request to a web host, GitHub's servers
may observe routine connection data (such as your IP address) under GitHub's
own privacy practices.

No other network requests are made by any file in this repository.

## 4. The host applications

The CSS themes are applied **on top of third-party applications** — YouTube
Music (via a user-style extension) and Discord (via client modifications).
Those applications are **not operated by the author of this repository**, and
this repository has no interaction with them beyond styling their interface in
your browser. Their own network activity, data collection and privacy policies
are entirely their own and are **not** influenced by, nor the responsibility
of, this project. Refer to Google's and Discord's own privacy policies for how
they handle your data.

## 5. Permissions

The CSS themes request **no permissions** from your browser, operating system
or host application. They are pure presentation rules.

## 6. Backups and data export

The CSS themes create no backups, exports or copies of any data. They have no
data to back up.

## 7. Children's privacy

The CSS themes collect no personal data from anyone, including children.

## 8. Good faith

This repository is published in good faith:

- the themes are **original works** that contain no third-party copyrighted
  assets and no proprietary code from Google/YouTube or Discord;
- they contain **no code intended to circumvent access controls, protections
  or monetization** of any service;
- they are provided for **demonstrative and educational purposes** only;
- they **do not collect or transmit personal data** and do not process
  personal information in any way.

For the legal assessment of these themes, see **[LEGAL.md](LEGAL.md)** and
**[DISCLAIMER.md](DISCLAIMER.md)**.