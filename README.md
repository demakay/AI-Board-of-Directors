# AI Board of Directors — Executive Boardroom

A self-contained, single-file boardroom that convenes a simulated Board of Directors (Warren Buffett as Chair; Aliko Dangote; Femi Otedola; Apostle Joshua Selman; Pastor E. A. Adeboye; John D. Rockefeller; Robert Kiyosaki) to review strategic decisions through a 5-phase process: context review, independent member reviews, board debate, consensus, and a Chairman's Report with decision/risk/alignment scores and 30/90-day plans.

**Live tool:** https://demakay.github.io/AI-Board-of-Directors/

## How to use

1. Open the page and choose an engine in the Board Engine panel:
   - **Claude API key** — enter your own key from console.anthropic.com; the Board runs live in your browser. Your key is stored only in your browser and sent only to api.anthropic.com.
   - **Offline copy/paste** — no key needed; copy the generated Board instructions into any capable AI chat, paste the JSON reply back, and the boardroom renders it.
2. Describe your decision, set the live assumptions (time horizon, risk tolerance, capital in USD, reversibility, custom assumptions), and convene a Quick Take or Full Board Session.
3. Change any assumption and re-convene to see the Board's updated view. Scenarios save automatically in your browser.

## Notes

- This repository contains no API keys, and the page never embeds one. Each user supplies their own key in their own browser.
- Board members are perspectives modeled on public records — not the actual individuals. Output is decision support, not legal, financial, or professional advice.
