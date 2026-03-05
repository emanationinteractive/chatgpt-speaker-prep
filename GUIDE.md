# Speaker Prep v1.0 — Full Guide

## What Is This?

A text prompt you paste into any AI that turns it into a structured speaker coaching tool. You talk, it saves notecards. You say `outline`, it compiles your talk. That's it.

It works with ChatGPT, GitHub Copilot, Claude, Gemini, Ollama, or any LLM. No installs. No accounts beyond what you already have.

---

## Who Is This For?

- Knows their stuff but hasn't organized it into a talk yet
- Learns by doing, not by outline-first planning
- Wants a thinking partner, not a ghostwriter
- Has imposter syndrome about public speaking (most people do)
- Has a work laptop with Copilot and nothing else

**What it is NOT:** This is not AI writing your talk. The tool saves YOUR words, asks YOU follow-up questions, and compiles YOUR ideas into structure. The talk that comes out is yours.

---

## Getting Started

### Step 1 — Open Your AI

Any AI assistant you have access to. Copilot on your work laptop, ChatGPT on your phone, Claude in a browser tab. Doesn't matter.

### Step 2 — Pick Your Load Method

| Method | File | When to Use |
|--------|------|-------------|
| **Fast** | `LOAD_ALL.txt` | One paste, everything loads. Best for repeat use. |
| **Step-by-step** | `1_START_HERE.txt` then `2_speaker_prep_prompt.txt` | Two pastes. Read each piece first. Best for first time. |

Open the file. Select all. Copy. Paste into the AI chat. Send.

### Step 3 — Edit Your Speaker Profile

Before or after pasting, edit the `SPEAKER PROFILE` section:

```
name=YOUR NAME
background=YOUR BACKGROUND
strength_1=YOUR FIRST STRENGTH
strength_2=YOUR SECOND STRENGTH
strength_3=YOUR THIRD STRENGTH
goal=YOUR GOAL
style=YOUR LEARNING STYLE
```

This is your character sheet. The tool uses it to build your confidence anchor and tailor feedback.

### Step 4 — Set Up Your Data Folder

The `my_speaker_data/` folder is where YOU save your work. AI chats expire when you close them. Your files don't. See `4_WHERE_STUFF_GOES.txt` for the full map.

---

## Prep Commands

Use these during talk preparation sessions (5-30 min each).

### `dump` — Brain Dump

Just talk. Say whatever's in your head. The tool saves good parts as notecards and asks one follow-up question.

**Best for:** Early discovery. Getting ideas out.

### `interview` — Self-Interview

The tool asks YOU one question at a time. When you answer, good parts get saved as notecards. It pulls the talk out of you.

**Best for:** Discovering what you actually know.

### `notes` — Clean Notes

Paste organized notes. The tool extracts 3-5 notecards.

**Best for:** Meeting notes, organized thoughts.

### `parse` — Raw Dump Sorting

Paste ANYTHING — messy Discord convos, email chains, random notes, multiple topics jumbled together. The tool detects thread boundaries, sorts by relevance, and files each piece as a notecard. Off-topic stuff gets flagged but not deleted.

**Best for:** Messy input, mixed sources, clipboard dumps.

> **Tip:** Save your raw dump to `my_speaker_data/raw_dumps/` BEFORE pasting. If the AI session dies, you still have the source.

### `pitch` — Elevator Pitch Test

Give your talk in 2 sentences. Get scored on clarity, hook, and specificity. Verdict: SHIP IT, REWORK, or SCRAP.

### `outline` — Compile Talk Structure

Compiles all your notecards into a structured outline with sections (Hook, Problem, Insight, How, Proof, Takeaway) and time estimates.

**Best for:** After you have 10+ notecards.

### `review` — Draft Feedback

Paste draft text. Get honest line-by-line feedback. Lines tagged as VAGUE, WEAK, or STRONG. Overall score out of 10.

### `comfort` — Stage Techniques

Save physical and mental techniques for stage presence. These are body notecards, not content:

- "Sip water = 3-second reset button"
- "Scan the back wall, not individual faces"
- "Look toward a light source — natural reason to pause"
- "Pick up your laptop and gesture with it — movement kills freeze"

### `sos` — Normal AI Mode

Drop all structured formatting. The AI talks to you like a normal assistant. Type `reset` when you're ready to go back.

**Best for:** When you're stuck and need a real conversation.

---

## Live Talk Features

Keep your AI open on your laptop while you present.

### Cue Cards — Emoji Shortcuts

Before your talk, map your best notecards to emoji. During the talk, type an emoji to instantly pull up a notecard.

**On Windows:** `Win+.` opens the emoji picker. Type the emoji name, hit Enter. The AI shows your notecard. Takes about 3 seconds.

| Command | What It Does |
|---------|-------------|
| `bind [emoji] [notecard#]` | Map an emoji to a notecard |
| `bind [emoji] steady` | Map emoji to confidence anchor |
| `bind [emoji] comfort` | Map emoji to a comfort card |
| `cues` | Show all current bindings |
| `sheet` | Print cheat sheet (save or print this) |

### Suggested Cue Card Layout

| Emoji | Purpose |
|-------|---------|
| 🛡️ anchor | Opening hook — re-center on your story |
| ⏸️ pause | Transition phrase + next section |
| 📊 data | Stats and numbers |
| 💡 insight | Key insight |
| 🔧 how | Process/framework |
| 📖 story | Proof/example story |
| 💚 steady | Confidence anchor (auto-built from YOUR receipts) |
| 🔄 reset | Your strongest notecard |
| 🏠 close | Your takeaway — end strong |
| 💧 water | Comfort: sip water, reset |
| 👀 eyes | Comfort: scan back wall |
| 💬 respond | Q&A: "Good question..." + notecard |
| 🎯 scope | Q&A: "Outside today's scope..." |

---

### Voice Mode

Use Speaker Prep hands-free with one earbud. The AI becomes a coach whispering in your ear.

**Setup:**
1. Plug in ONE earbud (audience won't notice — normal in 2026)
2. Click the voice/microphone button in your AI
3. Whisper commands. AI whispers back. 15 words max.

| You Whisper | AI Whispers Back |
|------------|-----------------|
| "steady" | Your confidence anchor, spoken slowly |
| "where am I" | Current section of your outline |
| "next" | Next section title and first point |
| "stop" | Goes silent |
| "continue" | Resumes where it left off |
| "repeat" | Says the last thing again |
| any card name | Reads that notecard aloud, brief |

The audience sees a speaker with an earbud. Every presenter checks notes. Yours just talk back.

### Vision Mode

If your AI supports screen sharing, it can watch your slides in real time and give context-aware help.

**Setup:**
1. Turn on screen sharing or vision mode in your AI
2. The AI can now see your slides
3. It tracks which section of your outline you're on automatically

| You Say | AI Does |
|---------|---------|
| "where am I" | Matches visible slide to your outline |
| any cue card | Pulls notecard matching current slide |
| "stuck" | References what's on screen + matching notecard |
| "next" | Knows what slide comes next |

**Voice + Vision combined:** The AI watches your slides and whispers what's coming next through your earbud before you even ask.

---

## Signals The Tool Gives You

| Signal | Meaning |
|--------|---------|
| `[NOTECARD SAVED]` | You said something worth keeping |
| `[VAGUE — be specific]` | You're hand-waving. Give a real example. |
| `[WEAK]` | This section needs work |
| `[STRONG]` | This is good. Keep it. |
| `[YOU KNOW MORE THAN THAT]` | You're underselling yourself |
| `[SHIP IT]` | Your pitch is ready |
| `[MAYBE]` | Borderline relevant — kept but flagged |
| `[COMFORT]` | Stage technique, not content |

---

## Recommended Workflow

**Week 1-2: Discovery**
Use `dump` and `interview`. Don't organize yet. Just get ideas out. 5-minute sessions whenever you have a thought. Save notecards to your data folder.

**Week 2-3: Structure**
Run `notecards` to see what you've collected. Run `outline` to see your talk taking shape. Use `pitch` to sharpen your description. Use `parse` to process any meeting notes.

**Week 3-4: Draft and Refine**
Write sections from your outline. Paste them back with `review` for feedback. Iterate until sections score well.

**Day Before: Prep for Live**
Set up cue cards. Save comfort cards. Run `sheet` and print your cheat sheet or save it to your phone.

**Show Day: Go Live**
Open your AI. Paste the prompt. Load your notecards. Turn on voice and vision if available. Minimize the window. Put in your earbud. Go.

---

## Starting a New Session

Every time you open a new AI chat, you need to reload:

1. Paste `LOAD_ALL.txt` (or `1_START_HERE.txt` + `2_speaker_prep_prompt.txt`)
2. Paste your saved notecards back in using `notes` or `parse`
3. Continue where you left off

This is why you save to the data folder. The AI forgets. Your files don't.

---

## Your Data Folder

| Folder | What Goes Here |
|--------|---------------|
| `my_speaker_data/my_notecards/` | Notecards copied from AI sessions |
| `my_speaker_data/my_outline/` | Talk outlines (save versions: v1, v2, v3) |
| `my_speaker_data/my_comfort_cards/` | Stage techniques (body/mind cards) |
| `my_speaker_data/my_cue_sheet/` | Emoji bindings for live talks (print these) |
| `my_speaker_data/raw_dumps/` | Raw messy notes BEFORE pasting into `parse` |

---

## FAQ

**Does this store my data anywhere?**
No. Everything lives in the AI chat session. When you close the chat, it's gone. Save notecards to your data folder to keep them.

**Can my IT department see what I type?**
If you're using Copilot on a work laptop, your organization's data policies apply. Speaker Prep is just text — it adds no external connections.

**What if the AI stops following the format?**
Type `reset`. Short sessions (5-15 min) hold format best. If it's really broken, start a new chat and paste the prompt again.

**Do I need to pay for anything?**
No. If you have access to any AI assistant (including free tiers), this works.

**Can I use voice mode during my talk?**
Yes. One earbud. Whisper commands. AI whispers back. Audience sees a speaker with an earbud. Normal.

**What if I paste a huge mess of notes?**
Use `parse`. It sorts everything by relevance. Save the raw text to your data folder first.

**Can the AI see my slides?**
If you turn on screen sharing or vision mode, yes. It tracks which slide you're on and gives context-aware help.

---

## Privacy

Speaker Prep is a text prompt. It does not install software, collect data, make network connections, or access any system resources. It is text in a chat window.

Your data stays wherever your AI provider stores chat sessions. When you close the chat, the AI forgets everything. Your local data folder is the only persistent storage, and that's just files on your machine that you control.

---

## Full Command Reference

| Command | What It Does |
|---------|-------------|
| `dump` | Brain dump — you talk, it saves notecards |
| `pitch` | Test elevator pitch, get scored |
| `notes` | Paste clean notes, extract notecards |
| `parse` | Paste messy dump, auto-sort into notecards |
| `interview` | AI asks you questions, one at a time |
| `notecards` | List all saved notecards |
| `show notecards` | Read all notecard contents |
| `outline` | Compile notecards into talk structure |
| `review` | Paste draft, line-by-line feedback |
| `comfort` | Save stage comfort techniques |
| `cue` | Set up emoji cue card bindings |
| `cues` | Show all cue card bindings |
| `sheet` | Print cue card cheat sheet |
| `status` | Session stats |
| `sos` | Drop format, normal AI help mode |
| `reset` | Re-anchor structured mode |
| `help` | Show command list |

---

**Z.O.E. Foundation** — 2026
Aeonic Worlds Studios • Emanation Interactive LLC

*"You know things. Structure them. Ship it."*
