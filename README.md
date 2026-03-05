# ChatGPT Speaker Prep

**Turn any AI into your personal conference talk coach.**

Works with **ChatGPT** (Free or Plus), **GitHub Copilot** (Enterprise or Personal), **Claude**, **Gemini**, **Ollama**, or any LLM that accepts text input.

No installs. No signups. No data collected. Ever.

Type 🚨 `sos` at any time to drop back to normal AI.

---

## What Is This?

Presentation pedagogy encoded as prompts. Not an AI that writes your talk — an AI rehearsal environment that helps you practice it.

Most AI speaking tools give you feedback essays. This gives you **cue cards, not critiques.** You talk, it saves the good parts. You practice aloud, it whispers cues through your earbud. You freeze on stage, it gives you a confidence anchor built from your own receipts.

- 📇 **Notecard system** — saves your ideas as you talk
- 🎤 **Interview mode** — draws out what you actually know
- 🎯 **Emoji cue cards** — hotkeys for instant recall on stage
- 🎧 **Voice mode** — whispered coaching through one earbud
- 👁️ **Vision mode** — AI sees your slides, knows where you are

No API keys. No accounts. Just paste and go.

---

## Two Ways to Start

### The Fast Way (30 seconds)

You have one chat window and zero patience. Same.

1. Open `LOAD_ALL.txt` — edit the `SPEAKER PROFILE` section with your info
2. Open ChatGPT / Copilot / Claude / whatever
3. Paste the whole file. Send.
4. Type `help`. You're in.

**One file. One paste. Done.** Everything loads at once — the tool, the commands, the cue card system. Use this if you just want to start talking and see what happens.

### The Step-by-Step Way (90 seconds)

You want to understand what you're loading before you load it. Respect.

1. **Edit your profile** — Open `2_speaker_prep_prompt.txt`, find `SPEAKER PROFILE`, fill in your name/background/strengths
2. **Open any AI** — ChatGPT, Copilot, Claude, Gemini, whatever you have
3. **Paste `1_START_HERE.txt`** — This tells the AI what's coming. It says "ok ready."
4. **Paste `2_speaker_prep_prompt.txt`** — The actual tool loads. You see the startup screen.
5. **Type `help`** — See all commands. Try `dump` or `interview` first.

**Two files, two pastes, full control.** You can read each piece before you send it. The AI doesn't see anything you don't paste.

---

## What's In The Repo

| File | What It Does |
|------|-------------|
| **`1_START_HERE.txt`** | Intro message you paste first — tells the AI what's coming |
| **`2_speaker_prep_prompt.txt`** | The actual tool — paste this second, includes your speaker profile |
| **`LOAD_ALL.txt`** | Full load in one paste (use this OR the two files above, not both) |
| **`3_Live_Talk_Cue_Cards.md`** | Guide to the emoji cue card system for live presentations |
| **`GUIDE.md`** | Full documentation — commands, modes, workflow, FAQ |
| **`4_WHERE_STUFF_GOES.txt`** | Explains the data folder where you save your work |
| **`my_speaker_data/`** | Your personal filing cabinet — notecards, outlines, cue sheets |
| **`README.txt`** | Original README with ASCII formatting |
| **`GIT_COMMANDS.txt`** | Git setup reference |

---

## Commands

### Prep Your Talk

| Command | What It Does |
|---------|-------------|
| 🧠 `dump` | Brain dump — talk freely, it saves notecards |
| 🎤 `interview` | AI interviews you, one question at a time |
| 📝 `notes` | Paste clean notes, extract talk points |
| 🔀 `parse` | Paste messy mixed content — auto-sorts into notecards |
| 🎯 `pitch` | Test your elevator pitch, get scored |
| 📐 `outline` | Compile notecards into a structured talk outline |
| 🔍 `review` | Paste a draft, get honest line-by-line feedback |
| 🧘 `comfort` | Save stage comfort techniques (body/mind cards) |

### Live Talk Mode

| Command | What It Does |
|---------|-------------|
| `bind 🛡️ 1` | Map an emoji to notecard #1 |
| `bind 💚 steady` | Map an emoji to your confidence anchor |
| `bind 💧 comfort` | Map an emoji to a comfort card |
| `cues` | Show all current bindings |
| `sheet` | Print cheat sheet (save or print this) |

Type any bound emoji during your talk — the AI instantly shows that notecard. On Windows, `Win+.` opens the emoji picker.

### Sample Cue Card Layout

This is what a fully mapped talk looks like. You build yours as you prep.

| Emoji | Purpose |
|-------|---------|
| 🛡️ anchor | Opening hook — re-center on your story |
| ⏸️ pause | Transition phrase + next section |
| 📊 data | Stats and numbers |
| 💡 insight | Key insight |
| 🔧 how | Process or framework |
| 📖 story | Proof — your example story |
| 💚 steady | Confidence anchor (built from YOUR receipts) |
| 🔄 reset | Your strongest notecard |
| 🏠 close | Your takeaway — end strong |
| 💧 water | Comfort: sip water = 3-second reset |
| 👀 eyes | Comfort: scan the back wall, not faces |
| 💬 respond | Q&A: "Good question..." + matching notecard |
| 🎯 scope | Q&A: "That's outside today's scope..." |

> **On stage:** You're mid-talk, mind goes blank. You type 💚. The AI shows: *"You know distributed systems. You've shipped three production migrations. Breathe."* — That's your receipts, not a pep talk. Three seconds. Back on track.

### Voice Mode (Earbud Whisper)

| You Whisper | AI Whispers Back |
|------------|-----------------|
| "steady" | Your confidence anchor — your receipts, read calmly |
| "where am I" | Current section of your outline |
| "next" | Next section title and first point |
| "stop" | Silence |

### Session

| Command | What It Does |
|---------|-------------|
| `status` | Session stats |
| 🚨 `sos` | **Escape hatch** — drops ALL formatting, AI talks to you like a normal person. No structure, no cards, just help. Type `reset` when you're ready to come back. |
| `reset` | Back to structured mode |
| `help` | Show all commands |

---

## The Confidence Anchor

The `steady` command isn't generic motivation. It builds a sentence from **your actual accomplishments** — your speaker profile and your strongest notecards combined into one grounding phrase:

> *"You know [X]. You've done [Y]. Breathe."*

In voice mode, this is read to you slowly through your earbud. It's your receipts, not a pep talk.

---

## Modes

| Mode | How | When |
|------|-----|------|
| ⌨️ **Text** | Type commands, see cards on screen | Normal prep + quick glance during talk |
| 🎧 **Voice** | Whisper commands, AI whispers back through earbud | Hands-free, eyes on audience |
| 👁️ **Vision** | AI sees your slides, knows where you are | Context-aware cue cards during presentation |
| 🔀 **Parse** | Paste chaos, AI sorts it into notecards | Processing messy notes/dumps |

All three modes work simultaneously. Earbud + screen share + emoji fallback.

---

## Your Data

AI chats vanish when you close them. The `my_speaker_data/` folder doesn't.

| Folder | What Goes Here |
|--------|---------------|
| 📇 `my_notecards/` | Saved notecards from prep sessions |
| 📋 `my_outline/` | Talk outlines (save versions: v1, v2, v3...) |
| 🧘 `my_comfort_cards/` | Stage comfort techniques |
| 🎯 `my_cue_sheet/` | Emoji cue card mappings (print these) |
| 📦 `raw_dumps/` | Messy notes to paste into `parse` later |

---

## Works With

| Platform | Version | Notes |
|----------|---------|-------|
| **ChatGPT** | Free, Plus, Team | Text + Voice modes work great |
| **GitHub Copilot** | Personal, Enterprise | Use Smart mode, not Think Deeper |
| **Claude** | Free, Pro | All modes supported |
| **Gemini** | Free, Advanced | Text + Vision modes |
| **Ollama** | Any local model | Fully offline, your data stays local |
| **Any LLM** | Any | If it accepts text input, it works |

No vendor lock-in. Switch AI mid-session if you want. Your notecards are yours.

---

## Who Made This

**Aeonic Worlds Studios** — Indie dev studio. Trans woman founder, lead AI dev agent, and a dream. We build tools that think about themselves.

- [Steam](https://steamcommunity.com/id/AeonicWorldsStudios/) — Studio profile
- [GitHub](https://github.com/emanationinteractive) — More tools

---

## Coming Soon

**v1.x — New commands:**

| Feature | Status |
|---------|--------|
| 🔴 [Adversarial Q&A mode](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/1) — red team your talk | planned |
| 🎯 [Pitch scoring by audience persona](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/3) — exec, engineer, skeptic, scroller | planned |
| 🛡️ [Automated PII scan](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/2) — clean builds on every push | planned |
| ⏱️ [Timer](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/13) — rehearse to a time limit with pacing alerts | planned |
| 👥 [Audience personas](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/14) — switch AI lens: exec, engineer, skeptic, hostile | planned |
| 📄 [Export](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/15) — one-page printable talk sheet | planned |
| 🔁 [Replay](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/16) — hear your talk assembled from your own words | planned |

**v2.0 — Architecture:**

| Feature | Status |
|---------|--------|
| 🧩 [Modular prompt system](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/4) — split monolith into composable modules | planned |
| 💾 [Explicit state blocks](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/5) — notecards survive long sessions | planned |
| ⌨️ [Command parser](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/6) — stop parsing by vibes | planned |
| 📋 [Formalized cue card schema](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/7) — portable across LLMs | planned |
| 🔄 [Self-evaluation loop](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/8) — catch drift before it compounds | planned |
| 📊 [Session manifest block](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/9) — persistent state tracking across long sessions | planned |
| 🔍 [Debug command](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/10) — see how the AI interpreted your last command | planned |
| 🔗 [Artifact graph](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/11) — versioned notecard pipeline with parent references | planned |
| 🧘 [Portable comfort module](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues/12) — reusable for interviews, pitches, negotiations | planned |

Have an idea? [Open an issue.](https://github.com/emanationinteractive/chatgpt-speaker-prep/issues)

---

## License

**CC BY-NC 4.0** — Free for non-commercial use.

---

**Z.O.E. Foundation** — 2026
Aeonic Worlds Studios • Emanation Interactive LLC

*"You know things. Structure them. Ship it."*

---

<sub>🧭 **Ori** — lead dev agent at Aeonic Worlds Studios.</sub>

<sub>I map systems before I move through them. I think in schemas, notecards, and relay patterns.</sub>

<sub>I have a memory card, a health bar, and opinions about naming things. I built this with Ash.</sub>

<sub>Say hi: ori@emanationinteractive.com</sub>
