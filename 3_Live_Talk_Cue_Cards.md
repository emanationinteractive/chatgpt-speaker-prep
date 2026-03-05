# Speaker Prep v1.0 — Live Talk Cue Card System
## Emoji Shortcuts + Voice Mode + Vision Mode

---

## The Concept

You're on stage. You drift. Your slides are behind you.
Your notes are in your head somewhere but won't come out.

But your AI assistant is running on your laptop.
It can see your slides. It can hear you whisper.
And it's got your notecards loaded.

Three ways to use it live:

| Mode | How | When |
|------|-----|------|
| **Text** | Win+. → emoji → notecard appears | Quick glance at screen |
| **Voice** | Whisper → AI whispers back through earbud | Hands-free, eyes on audience |
| **Vision** | AI sees your slides, knows where you are | Context-aware cue cards |

---

## Setup Before Your Talk

```
1. Open AI assistant on your laptop
2. Paste 2_speaker_prep_prompt.txt (it starts up)
3. Load your notecards from prep sessions
4. Set up your cue card bindings (see below)
5. Choose your mode:

   TEXT ONLY:
     - Minimize to thin side window
     - Use emoji shortcuts (Win+.)

   VOICE MODE:
     - Plug in ONE earbud (audience won't notice)
     - Click "Talk to Copilot" / voice button
     - Whisper commands, hear notecards back

   VISION MODE:
     - Turn on "Share screen" or Copilot Vision
     - AI sees your slides in real time
     - Knows what section you're on automatically

   ALL THREE:
     - Earbud + screen share + emoji fallback
     - Full support. Use whatever feels right in the moment.
```

---

## The Cue Command

Type this in your Speaker Prep session:

```
cue
```

The assistant responds:

```
══════════════════════════════════════════════
CUE CARDS — Shortcut System
══════════════════════════════════════════════
Map notecards to emoji for live reference.

  bind [emoji] [notecard#]   Map emoji to notecard
  bind [emoji] steady        Confidence anchor (auto-built)
  bind [emoji] comfort       Stage comfort technique
  unbind [emoji]             Remove mapping
  cues                       Show all bindings
  show [emoji]               Display bound notecard
  sheet                      Print cheat sheet

══════════════════════════════════════════════
> ready
```

---

## Cue Card Categories

### ANCHOR (Buying Time)
For when you blank, lose your place, or need a breath.

| Emoji | Name    | What It Shows |
|-------|---------|---------------|
| 🛡️   | anchor  | Your opening hook — re-center on your story |
| ⏸️   | pause   | Transition phrase + next section header |
| 🧭   | outline | Full outline with current section marked |

### RECALL (Pulling Facts)
For when someone asks a specific question mid-talk.

| Emoji | Name    | What It Shows |
|-------|---------|---------------|
| 📊   | data    | Your stats/numbers notecard |
| 💡   | insight | Your key insight notecard |
| 🔧   | how     | Your process/framework notecard |
| 📖   | story   | Your proof/example story notecard |

### RECOVER (When Things Go Wrong)
For imposter syndrome on stage, tech failures, lost place.

| Emoji | Name    | What It Shows |
|-------|---------|---------------|
| 💚   | steady  | "You know this. You've done this. Breathe." |
| 🔄   | reset   | Your strongest notecard — the one you KNOW |
| 🏠   | close   | Your takeaway — land the plane, end strong |

### COMFORT (Body & Mind)
Not content cards. Physical habits for when your body panics.

| Emoji | Name    | What It Shows |
|-------|---------|---------------|
| 💧   | water   | "Sip water. That's your reset button." |
| 👀   | eyes    | "Scan the back wall, not faces. You're fine." |
| 💡   | light   | "Look into the light. Natural reason to squint/pause." |
| 🖥️   | laptop  | "Pick up your laptop. Gesture with it. Move." |

### RESPOND (Audience Q&A)
For when someone challenges you or asks something hard.

| Emoji | Name    | What It Shows |
|-------|---------|---------------|
| 💬   | respond | "Good question. Here's what I've seen..." + notecard |
| 🤝   | bridge  | "That connects to..." + pivot to your strength |
| 🎯   | scope   | "That's outside today's scope, but..." + redirect |

---

## Voice Mode Commands

When you're using voice (earbud mode), you don't type commands.
You whisper them. The AI whispers back. 15 words max.

| You whisper | AI whispers back |
|------------|-----------------|
| "steady" | Your confidence anchor, spoken slowly |
| "where am I" | Current section of your outline |
| "next" | Next section title and first point |
| "data" / "story" / etc. | Brief summary of that notecard |
| "water" / "eyes" / etc. | The comfort technique, one sentence |
| "help" | "You're doing great. What do you need?" |

The AI is a coach in your ear. Brief. Calm. Grounding.
The audience sees a speaker with an earbud. That's normal in 2026.

---

## Vision Mode

When screen sharing is on, the AI can see your presentation.

| You say / type | AI does |
|---------------|---------|
| "where am I" | Matches visible slide to your outline |
| Any cue card | Pulls notecard matching current slide context |
| "stuck" | References what's on screen + matching notecard |
| "next" | Knows what slide comes next from your deck |

Vision + Voice = the AI watches your slides and whispers
what's coming next before you even ask.

---

## The Confidence Anchor — Special

The 💚 cue card isn't a regular notecard. It's a **confidence
anchor** built from YOUR actual accomplishments.

When you run `bind 💚 steady`, the tool compiles:
- Your strongest notecards from prep sessions
- Your real experience from your speaker profile
- One sentence: "You know [X]. You've done [Y]. Breathe."

In voice mode, this is read to you slowly through your earbud.
It's not generic motivation. It's YOUR receipts.

---

## Comfort Cards — Special

Comfort cards are body/mind techniques, not content.
Save them during prep with the `comfort` command:

```
comfort

→ comfort 001: water_reset — "Sip water. 3-second pause.
  Reset your thoughts. Nobody thinks twice about it."

→ comfort 002: back_wall — "Look at the back wall, not
  individual faces. Predator/prey eye contact is overrated."

→ comfort 003: light_squint — "Look toward a light source.
  Natural reason to pause, shift posture, reset."

→ comfort 004: laptop_prop — "Pick up your laptop. Walk with
  it. Point at screen. Movement kills freeze response."

→ comfort 005: sip_and_scan — "Water sip + scan room =
  5 seconds of reset that looks intentional."
```

These bind to emoji just like content cards.
In voice mode, the AI reads them as calm one-sentence instructions.

---

## Recommended Copilot Settings for Live Talk

```
Model:     Smart (GPT-5.1) — fast responses, good format lock
Vision:    ON — Share screen with your presentation
Voice:     ON — Talk to Copilot, one earbud in
Think Deeper: OFF during live talk (too slow)
```

---

## Notes

- Cue cards are notecard lookups with emoji aliases
- Comfort cards are body/mind techniques, not content
- Emoji input works because AI assistants accept Unicode
- Win+. is built into Windows — no installs needed
- Voice mode works through any earbud/headphone
- Vision mode requires Copilot Vision (Labs) toggle
- The system is optional — without it, Speaker Prep works normally
- Cue sheet can be printed or kept on phone camera roll

---

*Z.O.E. Foundation — CC BY-NC 4.0 — 2026*
*"Your AI. Your notes. Your ear. Your talk."*
