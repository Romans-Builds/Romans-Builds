# Labi Roman · Testy911cody

I ship web products on **[housegames.club](https://housegames.club)** — one Next.js site that hosts multiplayer party games *and* embedded standalone apps: AAC for nonspeaking kids, ride booking, voice rooms, retro social profiles.

Everything below is a live URL. The House Games repo itself is private, so I link the running product rather than a clone command.

## Open these

| Product | What it is | Live |
|---------|------------|------|
| **House Games** | Neon arcade — rooms, guest play, Jeopardy / Taboo / Codenames / DrawGuess / Werewolf and more | [housegames.club](https://housegames.club) |
| **Talk Board** | Picture-and-voice AAC; record real voices for dialects with no computer TTS | [/amoory/](https://housegames.club/amoory/) · [source](https://github.com/Testy911cody/amoory-app) |
| **GoFleet** | Taxi / limo / truck booking with fare estimates and dispatch | [/gofleet/book](https://housegames.club/gofleet/book) |
| **PityParty** | Supportive voice rooms — join from a link, no account | [/pityparty/](https://housegames.club/pityparty/) |
| **Mychillplace** | Retro profiles, top friends, bulletins, profile song | [/mychillplace/](https://housegames.club/mychillplace/) |
| **Women ↔ Men Translator** | Voice-first phrase interpreter and warmer rephrase | [/apps/women-men-translator](https://housegames.club/apps/women-men-translator) |

Full catalog: **[housegames.club/apps](https://housegames.club/apps)**

## Stack I use for real

`TypeScript` · `React` · `Next.js 16 (App Router)` · `Expo / React Native Web` · `Tailwind CSS` · `Supabase` · `Cloudflare Pages` · `Pages Functions / Hono` · `Node + Express` · `PWA` · `GitHub Actions`

## A few things I care about

- **Guest-first.** House Games rooms and PityParty campfires work with no account. Sign-in adds persistence; it is not a gate at the door.
- **One domain, two kinds of app.** `/games` is the Next.js arcade. `/apps` is a catalog of separate codebases exported to static files and served from the same origin — one deploy, no cross-origin auth juggling.
- **Deliberate releases.** CI runs QA on every push; the production Cloudflare upload is opt-in (an explicit marker or a manual dispatch), so previews stay cheap and releases stay intentional.
- **Accessibility that fits the user.** Talk Board exists because commercial AAC has no voice for Sudanese and Juba Arabic. Community-recorded audio fills the gap that TTS cannot.

## Public source

[`amoory-app`](https://github.com/Testy911cody/amoory-app) — Talk Board, the AAC PWA. Most other product repos are private; the live demos above are the honest version of "go look at my work."

---

## Contact

- LinkedIn: [linkedin.com/in/labi-roman](https://www.linkedin.com/in/labi-roman)
- GitHub (live until rename): [github.com/Testy911cody](https://github.com/Testy911cody)
- Portfolio (GitHub Pages): [testy911cody.github.io/RomanProjects](https://testy911cody.github.io/RomanProjects/)
- Live products: [housegames.club](https://housegames.club)

*Portfolio: [RomanProjects](https://github.com/Testy911cody/RomanProjects) on GitHub Pages.*
