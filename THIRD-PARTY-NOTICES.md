# Third-party notices

The game code and content of SNEAKY BUGS are © 2026 Jacek Mariusz Taczała, all rights reserved (see `LICENSE`).
The game is a single `index.html` without third-party code libraries.

Fonts (self-hosted in `fonts/`: unmodified WOFF2 files, latin + latin-ext subsets, as distributed by
Google Fonts; no requests to Google are made at runtime):

| Font | Files | Licence | Copyright |
|---|---|---|---|
| Oswald (variable, 400–700) | `fonts/oswald-latin*.woff2` | SIL Open Font License 1.1 | © 2016 The Oswald Project Authors |
| Anton | `fonts/anton-latin*.woff2` | SIL Open Font License 1.1 | © 2020 The Anton Project Authors |
| Racing Sans One | `fonts/racing-sans-one-latin*.woff2` | SIL Open Font License 1.1 | © 2012 Pablo Impallari, Rodrigo Fuenzalida, Reserved Font Name "Racing Sans" |

The full licence texts are included as `fonts/OFL-Oswald.txt`, `fonts/OFL-Anton.txt` and `fonts/OFL-RacingSansOne.txt`.

Online services: online leaderboard via Supabase (supabase.com, EU region, Ireland), accessed with plain
`fetch` to its REST API; no Supabase library is loaded. No analytics. Hosting: GitHub Pages.

## QR code

The QR code in the menu and on the end screen is a static inline SVG generated offline (no external QR service, no tracking); it encodes only `https://stop60.no/robaki/`. QR Code is a registered trademark of DENSO WAVE INCORPORATED.
