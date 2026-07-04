---
name: ai-writing-humanizer
description: Detect AI writing patterns and rewrite to sound human. Removes "delve into," "it's worth noting," and robotic transitions.
tags: [writing, editing, ai-detection, quality]
---

# AI Writing Humanizer

AI writes like AI. This skill makes it write like you.

## Trigger

Load when the user says "make this sound less like AI," "remove AI-isms," or wants to humanize AI content before publishing.

## Workflow

### 1. Scan for AI Patterns

**Sentence-level:**
- "It's worth noting that..."
- "Delve into..."
- "In the ever-evolving landscape of..."
- "Furthermore / Moreover / Additionally" (chains)
- "Not only... but also..."
- "In conclusion / To summarize"

**Structure-level:**
- Every paragraph same length
- Perfect paragraph→transition→paragraph rhythm
- Conclusion restating intro verbatim
- No personal anecdotes
- Hedging: "may be," "could potentially"

**Voice-level:**
- Neutral academic tone throughout
- No humor, sarcasm, personality
- Generic examples ("a company," "a user")
- No strong opinions

### 2. Fix Strategy

| Pattern | Fix |
|---------|-----|
| "It's worth noting" | Delete. Just say it. |
| "Delve into" | "Look at" / "Dig into" |
| "Furthermore" chain | Cut. No transition needed. |
| "Ever-evolving landscape" | Specific: "since GPT-4" / "last 6 months" |
| Hedging | Take a stand. "This works" not "this may work" |
| Perfect structure | Break one paragraph short. Vary rhythm. |
| No personality | Add: "I tried this..." / "Honestly..." |
| Generic examples | Specific: "Notion" not "a company" |

### 3. Voice Calibration (Optional)

- **Casual**: Contractions, fragments, exclamation marks
- **Professional**: Precise, data citations, confident
- **Technical**: Domain jargon OK, code blocks welcome
- **Warm**: Personal stories, "you" not "users"
- **Blunt**: Short sentences, strong opinions

### 4. Iterate

After first pass: does any sentence still sound like a textbook? Would I say this to a friend? Is there one risky/personal sentence? If no to any → another pass.

## Example

**AI:** "In the ever-evolving landscape of content creation, it's worth noting that AI tools have revolutionized the way creators approach their workflow."

**Human (casual):** "AI changed content creation. Not 'someday' — right now, one person with good AI tools can do what took a team of five. I've seen it. I've done it."

## Pitfalls

- Over-correction: too casual on B2B = unprofessional
- Removing ALL transitions: kill formulaic, keep organic
- Forgetting audience: dev blog should sound like a dev
- False confidence: wrong certainty worse than hedging