# Saved Video Links: Tasks & Ideas

Date: 2026-11-25

**What this is based on:** I couldn't open any of the links. Facebook and YouTube are blocked from this environment, and Facebook reels need a login anyway. Everything below comes from the **titles and creator names you pasted**. Where I say what a video "probably" covers, that's a guess from its title and you should check it. Nothing in the titles is about 3D printing, so if some of the reels were 3D-printing videos, they aren't covered here (see the last section).

---

## 1. Jarvis project (high value: keep these ideas)

| Source title | Idea / task |
|---|---|
| Cursor/Claude Code hacks I wish I knew earlier | **Task:** Add a `CLAUDE.md` to the Jarvis repo (architecture, conventions, commands). Use plan mode for big changes, custom slash commands or skills for repeated workflows, and hooks for auto-lint/test. |
| Free AI Certification from Claude | **Task:** Take Anthropic's free courses (Anthropic Academy), especially the Claude API, tool use and MCP ones. MCP is the natural way to plug Jarvis into calendar, email, files and home devices. |
| Install DeepSeek in VS Code in 30 Seconds | **Idea:** A local/offline model tier for Jarvis. Run Ollama with an open model for cheap, private tasks (classifying, summarizing) and send hard tasks to a frontier API. |
| Why Developers Love Docker / Docker Image vs Container | **Task:** Run Jarvis's parts (agent, local LLM, scheduler, DB) under one `docker compose` file so the system can be rebuilt on any machine. Image = blueprint, container = running instance. |
| DIY E-Ink Productivity Dashboard / I Built My Dream E-Ink Productivity Display | **Project:** A Jarvis "ambient display": a Raspberry Pi with an e-paper panel showing today's calendar, tasks, weather and Jarvis briefings. Open-source starting points to evaluate: Inkycal, MagInkDash. **Ties to 3D printing:** print the enclosure or stand. |
| Ultimate Web Scraper chrome extension | **Idea:** Data ingestion for Jarvis. For anything recurring, prefer a scripted scraper (Playwright) Jarvis can run on a schedule over a manual browser extension. |
| Comment "Erase"… ChatGPT wipe your… | **Task (privacy):** Review and prune what ChatGPT/Claude memory stores about you. Decide what Jarvis itself is allowed to remember. (The video itself is a comment-for-prompts engagement funnel; nothing else to keep.) |
| 5 Interesting Open Source Projects / "This GitHub repo is ACTUALLY goated" / 5 GitHub Repos to Save Money | I can't tell which repos from the titles. Commonly featured ones worth bookmarking for Jarvis: `public-apis/public-apis` (free APIs to integrate) and `ripienaar/free-for-dev` (free hosting/tiers). |
| tech stack I use to make money as a solo developer | **Task:** Write down Jarvis's stack decision once (language, hosting, DB, auth) and stop re-deciding it. |
| STOP building TODO APPS / Claude prompt to build amazing coding projects / ChatGPT prompt for staff-level projects | **Takeaway:** Jarvis *is* the impressive portfolio project. Give it a clean README, an architecture diagram and a demo video. |

### The 3 YouTube links (titles from YouTube oEmbed; transcripts blocked by YouTube's bot check)

| Link | Title / creator | Idea / task |
|---|---|---|
| watch?v=OUbEeJOxjyw | *Give Me 13 Minutes and I'll Make You Disgustingly Good With Claude* (Duncan Rogoff) | **Keep / watch once.** The most relevant video in the whole list for Jarvis. Expect overlap with the Claude Code hacks task above. |
| shorts/z0BHjqFYwWg | *How 137 AI Agents Run an Entire Company* (ReStructure AI) | **Idea:** multi-agent design for Jarvis, meaning specialized sub-agents (email, calendar, research) under one orchestrator. Start with one agent and split only when a single prompt gets unwieldy. The "137 agents" framing is hype. |
| shorts/S7eDSJz3erA | *Coding Project To Get Into FAANG* (Erik Cupsa) | Career content; see section 4. Safe to delete. |

## 2. PC & mobile use optimization

| Source title | Idea / task |
|---|---|
| My Linux Ubuntu Setup for Software Development | **Decide:** Use WSL2 on Windows or dual-boot Ubuntu for dev. WSL2 is the low-friction choice and gives Docker/Linux tooling without a reboot. |
| Install DeepSeek in VS Code | Same local-model idea as above. Doubles as free AI autocomplete in your editor. |
| Ultimate Office Desk Hack (IKEA DIY) / "Do you know about the ikea desk hack?" | The usual version (verify): two IKEA Alex drawer units with a Karlby countertop on top. A cheap, large, solid desk. |
| Take a tour of my updated desk setup / Top Desk Accessories | Common upgrades: monitor arm, under-desk cable tray, a single USB-C dock, a desk mat. **3D-print candidates:** cable clips, headphone hook, under-desk mounts for a power strip or PC. |
| Submitting my app to the Play Store #reactnative | **If Jarvis gets a phone app:** a Play Console account costs a one-time $25. New personal accounts must run a closed test with a set number of testers for about 14 days before going public. The rule has changed before, so check the current numbers. React Native or Expo lets one codebase target Android and iOS. |
| Mobile optimization (general) | None of the titles cover phone optimization directly. If one of the reels did, I couldn't see it. |

## 3. 3D printing

Nothing in the titles is explicitly about 3D printing. Print ideas that come out of the other videos:
- E-ink dashboard enclosure or stand (from section 1)
- Desk cable clips, headphone hook, under-desk mounts (from section 2)
- Space-saving organizers (from "Five of my favorite space saving apartment hacks")

## 4. Coding career (only if you're job-hunting; otherwise safe to delete)

Most of these give the same advice: **ship real, deployed projects instead of grinding LeetCode, and present them well.**
- How I Optimize My LinkedIn / Do THIS With Your Coding Projects / GitHub Repositories That Get You Hired / Recruiters are tired of your trash projects / give me 49 seconds… / Backend Coding Project for Big Tech / I STOPPED Leetcode and STARTED shipping: pin 2–3 deployed projects, give each a README with a demo GIF, and link them on LinkedIn.
- 3 Google Tools You MUST Use After Publishing Your Website: probably Google Search Console, PageSpeed Insights and Google Analytics. Only matters if you publish a site.
- 5 Coding Tips I'd Kill To Tell My 18 Y/O Self / How To Learn AI/ML For Free: low priority, generic.
- Going from $0 to $2000/month on the EASIEST App / "I only work on ideas that CANNOT fail": motivational, no concrete tasks.
- AI tutorial (×2): titles too vague to extract anything.

## 5. Personal / lifestyle (safe to delete, one-line takeaways)

- **You need EVENING ROUTINES / How to Rewire Your Brain with a 5-Year Plan:** possible Jarvis feature: an evening check-in and quarterly goal review pushed to the e-ink display or your phone.
- **4 Simple Ways to Strengthen Your Marriage:** personal; nothing for me to extract.
- **5 Affordable Home Upgrades That Look Expensive / Space saving apartment hacks / Hermès Grand Paddock case / Motivational Hub:** no project tasks.

---

## Consolidated action list

1. Add `CLAUDE.md`, custom commands and hooks to the Jarvis repo.
2. Take Anthropic's free API/MCP courses, then define Jarvis integrations as MCP servers.
3. Containerize Jarvis with `docker compose`.
4. Prototype a local-model tier (Ollama) alongside the cloud API.
5. Build the e-ink Jarvis dashboard (Pi + e-paper) and 3D-print its enclosure.
6. Audit AI assistant memory/privacy settings; write Jarvis's own memory policy.
7. Decide WSL2 vs dual-boot Ubuntu for the dev setup.
8. Optional: desk upgrade with the IKEA hack plus 3D-printed cable management.
9. Optional: a Jarvis mobile companion app. Check current Play Store testing rules first.

## Before you delete the links

- The ~41 Facebook reels and 3 YouTube links weren't watched. If your pasted titles are the titles of those links, this summary covers them.
- If you remember any reel being specifically about **3D printing or phone optimization**, check it before deleting, or paste its caption here and I'll add it.
