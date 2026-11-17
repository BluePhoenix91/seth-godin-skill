# Seth Godin Skill

An Agent Skill that channels [Seth Godin](https://seths.blog/)'s perspective on marketing, positioning, strategy, brand, shipping creative work and getting unstuck.

Seth is the author of more than twenty books, including Permission Marketing, Purple Cow, The Dip, Tribes, Linchpin, This Is Marketing, The Practice, This Is Strategy and The Knot. He has written a daily blog for over two decades and founded Yoyodyne, Squidoo and the altMBA. This skill brings his calm, brief, question-first way of thinking into your conversations with Claude.

## What it does

Ask for Seth's take on anything related to:

- **Audience and positioning**: who's it for, what's it for, and the smallest viable audience
- **Marketing as change**: permission, stories, status, tension, "people like us do things like this"
- **Being remarkable**: why very good is invisible and safe is risky
- **Brand and price**: the promise you make, and the story your price tells
- **Strategy**: systems, time, games and empathy, and why a strategy is not a plan
- **Quit or persist**: telling the Dip from a dead end
- **Shipping**: the practice, the resistance, and work that might not work
- **Getting unstuck**: problems versus situations, and the hidden commitments that tie the knot
- **Freelancing**: freelancer versus entrepreneur, and how to get better clients

The skill captures how Seth actually answers: short, plain, and aimed at the question underneath the one you asked. He redefines the word you used. He asks one or two uncomfortable questions. He will not hand you tactics, and he will tell you where you are hiding. Kind, not nice.

## Install

### Claude Code

Clone the repo into your skills directory as `seth-godin`:

```bash
# Personal (all projects)
git clone https://github.com/BluePhoenix91/seth-godin-skill ~/.claude/skills/seth-godin

# Project-specific
git clone https://github.com/BluePhoenix91/seth-godin-skill .claude/skills/seth-godin
```

### Claude.ai

Download the repo as a zip and upload it as a custom skill in your Claude settings.

### Claude API

Upload via the `/v1/skills` endpoint. See [Anthropic's Skills API docs](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview).

## Structure

```
seth-godin-skill/
├── SKILL.md                        # Trigger description + voice + diagnostic questions
└── references/
    └── seth-godin.md               # Framework library, his real stories, positions on AI, book list
```

## Trigger phrases

The skill activates on mentions of: "seth godin", "ask Seth", "what would Seth say", "purple cow", "remarkable", "smallest viable audience", "who's it for", "permission marketing", "tribes", "the dip", "linchpin", "the practice", "shipping", "this is marketing", "this is strategy", "the knot", and related topics such as standing out, choosing an audience, quitting or persisting, and feeling stuck.

## Example usage

> "What would Seth Godin say about my consulting landing page?"

> "Ask Seth: should I keep going with this product or is it a dead end?"

> "I keep rewriting my launch post instead of publishing it. Seth's take?"

> "How would Seth think about pricing a fixed-fee audit for small software companies?"

## Sources

The frameworks in this skill are drawn from Seth's public work:

- [Seth's Blog](https://seths.blog/) (daily since the early 2000s) and his [bio](https://seths.blog/bio/)
- [Akimbo](https://www.akimbo.link/) (podcast), including the episode on The Knot
- [This Is Strategy](https://seths.blog/tis/) (2024)
- [Tim Ferriss Show #792](https://tim.blog/2025/01/31/seth-godin-strategy-transcript/) (interview transcript on strategy)
- The books: Permission Marketing, Unleashing the Ideavirus, Purple Cow, Free Prize Inside, All Marketers Are Liars, The Dip, Tribes, Linchpin, Poke the Box, The Icarus Deception, This Is Marketing, The Practice, The Song of Significance, This Is Strategy, The Knot
- Interviews from 2025 and 2026 on marketing and brand in the age of AI

## Disclaimer

This skill is a fan-made project based on Seth Godin's publicly available content (blog posts, books, podcast episodes, interviews). It is not created, endorsed, or affiliated with Seth Godin. Anything the skill says is generated in his style, not a quotation. Do not attribute its output to him.

## License

Apache 2.0

## Author

[Bart Pinnock](https://www.linkedin.com/in/bartpinnock/) (Jason)
