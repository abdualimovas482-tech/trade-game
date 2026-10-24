# TRADE WAR — Global Trade Challenge (Case Study Edition)

Interactive classroom game built with React, Vite, Tailwind CSS, Framer Motion and Lucide React. Four teams, three rounds, no backend, saved game state, leaderboard, timers, fullscreen, printable winner certificates.

## Run on Windows

1. Extract this ZIP and open the **trade-war-v2** directory in VS Code. Verify `package.json` is in your current terminal directory (`dir package.json`).
2. Run `npm.cmd install` and `npm.cmd run dev` from that directory (not from `C:\`).
3. Open the localhost URL displayed by Vite.

## Game rules

- Start with 100 points and three units of each team's own product.
- Round 1: Exchange one owned product for one owned product. Three distinct product types: +30, two: +20, one: +10. Note: a team has three total units, so three types is the attainable maximum.
- Round 2: 2018 US–China tariff war inspired scenario. A: 40% tariffs (+5), B: free trade with investment (+20), C: negotiate (+30).
- Round 3: WTO DS267 US–Brazil cotton subsidies inspired scenario. A: import ban (+5), B: WTO consultations (+30), C: direct negotiation (+25).
- Decisions are recorded by the host; points and explanations are revealed after all teams decide. Joint winners are allowed.

These are simplified hypothetical classroom points, not universal economic or legal judgments. Case studies are inspired by historical events, not verbatim reconstructions.
