Offline copy of https://www.wpdcoins.com/  (WPD CHAIN)  — captured 2026-08-02

HOW TO VIEW  (important):
This is a React single-page app (Vite build), so it must be opened through a
small local web server — opening index.html directly with a double-click will
only show the header/footer (the page body needs a served origin to route).

1. Open a terminal in this folder.
2. Run:   python3 -m http.server 8000
   (or any static server, e.g.  npx serve .)
3. Open   http://localhost:8000/   in your browser.

Everything then works fully offline: Home, PCSM Coins, LEEA Coins, Whitepaper,
Tokenomics, Governance, Partnerships, plus both background videos and the coin
imagery — all stored locally in assets/.

Contents:
  index.html                      App shell
  assets/                         All JS, CSS, images, fonts, wallet chunks
  vid1.mp4, vid2.mp4              Hero background videos
  logo.png                        Logo / video poster
  WPD_Chain_Whitepaper.pdf       Downloadable whitepaper
  WPD_CHAIN_Enhanced_Final.html  Full HTML whitepaper page
  telegram-web-app.js            Telegram web-app script (localized)

Note: live blockchain actions (Connect Wallet, on-chain price/RPC calls) still
need internet — the rest of the site is fully offline.
