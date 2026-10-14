# Third-party notices

The game code and content of SNEAKY BUGS are © 2026 Stop60, all rights reserved (see `LICENSE`).
The game is a single `index.html` without third-party code libraries; the only third-party script is
GoatCounter `count.js` (self-hosted, unmodified, file `count.js`, ISC licence, © Martin Tournoij) for cookie-free visit statistics.

Fonts (self-hosted in `fonts/`: unmodified WOFF2 files, latin + latin-ext subsets, as distributed by
Google Fonts; no requests to Google are made at runtime):

| Font | Files | Licence | Copyright |
|---|---|---|---|
| Oswald (variable, 400–700) | `fonts/oswald-latin*.woff2` | SIL Open Font License 1.1 | © 2016 The Oswald Project Authors |
| Anton | `fonts/anton-latin*.woff2` | SIL Open Font License 1.1 | © 2020 The Anton Project Authors |
| Racing Sans One | `fonts/racing-sans-one-latin*.woff2` | SIL Open Font License 1.1 | © 2012 Pablo Impallari, Rodrigo Fuenzalida, Reserved Font Name "Racing Sans" |

The full licence texts are included as `fonts/OFL-Oswald.txt`, `fonts/OFL-Anton.txt` and `fonts/OFL-RacingSansOne.txt`.

Online services: online leaderboard via Supabase (supabase.com, EU region, Ireland), accessed with plain
`fetch` to its REST API; no Supabase library is loaded. Anonymous, cookie-free visit statistics via GoatCounter (goatcounter.com);
the `count.js` script is served from this site, not from gc.zgo.at. Hosting: GitHub Pages.

## QR code

The QR code in the menu and on the end screen is a static inline SVG generated offline (no external QR service, no tracking); it encodes only `https://stop60.no/robaki/`. QR Code is a registered trademark of DENSO WAVE INCORPORATED.

## ISC License (GoatCounter count.js)

Permission to use, copy, modify, and/or distribute this software for any purpose with or without
fee is hereby granted, provided that the above copyright notice and this permission notice appear
in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS
SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE
AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT,
NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF
THIS SOFTWARE.
