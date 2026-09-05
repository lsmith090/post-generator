# Post Generator

Mock social-media post + chat generator for Tamara's middle-school classroom (history/ELA assignments: "what would Lincoln post"). Inspiration: zeoob.com, minus ads/watermark-paywall. Classroom use only.

## Shape
- One static `index.html`, no build, no backend, no deps. Same approach as `~/repos/emoji-picker`.
- Devices: school Chromebooks + Windows (Chromium). Safari not a target.
- Export: DOM → SVG foreignObject → canvas → PNG. Download or copy-to-clipboard (kids paste into Docs/Slides).
- Every card carries a tiny "mockup" stamp. Keep it.
- Repeating content (comments, messages) = one textarea, one item per line. No add/remove-row UI.

## Priorities (from Tamara)
1. Post generators: Instagram, X, Facebook — done first pass. TikTok / Snapchat / YouTube maybe later.
2. Chat generators, iMessage first — done first pass. WhatsApp / Messenger / Snapchat / Instagram DM later.

## Hosting
- Hosting: GitHub Pages from `main:/`, public repo, https://posts.thornology.com (CNAME → lsmith090.github.io, DNS-only in Cloudflare, same as emoji-picker).

## Open
- Dark mode, save/restore work (localStorage), images inside chat bubbles — only if asked.
