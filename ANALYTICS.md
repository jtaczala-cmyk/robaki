# Analytics (GoatCounter – enabled)

SNEAKY BUGS counts visits with GoatCounter, cookie-free and anonymous. Site code: `GC_CODE` in `index.html`
(`'jtaczala-games'` -> https://jtaczala-games.goatcounter.com; set to `''` to turn it off).

`count.js` is self-hosted (unmodified copy of https://gc.zgo.at/count.js, ISC licence, same file as in the
Stop60 games); nothing is loaded from gc.zgo.at. The only external request is the hit sent to
`https://jtaczala-games.goatcounter.com/count`. It records:
- one page view per visit of the game: path `/robaki/` (Polish) or `/robaki/en/` (English, chosen language at load),
- page views of `/robaki/informacje/`, `/robaki/prywatnosc/`, `/robaki/en/info/`, `/robaki/en/privacy/`,
- events `robaki-start` (a round starts), `robaki-finish` (end screen) and `robaki-share` (the player actually shared or copied the end-screen result). `robaki-share` is not sent when the postcard is only shown, when the share sheet is cancelled, or when the menu button shares the game link. Events are sent with a random 0–15 s delay, or immediately when the page is hidden/closed so they are not lost. The shared text itself is not sent.

GoatCounter sets no cookies, stores nothing in the browser and stores no IP address or personal data
(IP + user agent are only kept in memory for up to 8 hours to count unique visits). Legal basis given on the
privacy pages (`/robaki/prywatnosc/`, `/robaki/en/privacy/`): legitimate interest, Art. 6(1)(f) GDPR.
