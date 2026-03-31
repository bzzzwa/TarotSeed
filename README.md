# TarotSeed 🌱

*An AI tarot reader that draws cards through verifiable Python code execution — not through hallucination or storytelling dressed as chance.*

---

## How to use it

**Requirements:** An LLM with Python code execution enabled.
- Claude (claude.ai): turn on *Analysis tool* in settings
- ChatGPT: enable *Code Interpreter*
- Gemini: enable *Code execution*

**Steps:**

1. 📋 Copy the prompt — fastest via the **[raw Gist](https://gist.githubusercontent.com/bzzzwa/66db34912ff7e749146d68153030a30b/raw/0d03faf967edd84fd9e1e695f41791faaaa334ec/tarot-reader-prompt.md)**
2. Paste it as your first message in a new LLM chat (or as a system prompt)
3. The model will guide you from there

The full prompt file is also in this repo: [`tarot-reader-prompt.md`](tarot-reader-prompt.md)

---

## What is this?

TarotSeed is a carefully designed system prompt that transforms any capable LLM into a thoughtful tarot reader. The card draw uses real Python code execution with a cryptographic seed built from your personal input — making each draw both unpredictable and personally imprinted. If code execution is unavailable, the session stops. There is no fallback to simulation.

This is an experiment in the best sense of the word: *can a language model serve as a genuine instrument of reflection — without pretending to be more than it is?*

---

## Why bother?

Tarot has survived centuries not because it predicts the future, but because it does something more useful: it brings order to chaos. When life is turbid — a relationship unravelling, a decision that won't resolve, a feeling you can't name — the structure of a reading can do what our anxious minds struggle to do on their own: slow things down, frame a question, and surface what we already, somewhere, know.

TarotSeed is deliberately built for those moments. Not for idle curiosity (though that's welcome too), but for the times when things aren't going well and you need a mirror, not an oracle.

---

## What it is — and what it isn't

**TarotSeed is:**
- A reflection tool, grounded in Rider-Waite-Smith tradition and Jungian psychological frameworks
- Honest about what it doesn't know — interpretations are offered as possibilities, not verdicts
- Transparent: the card draw uses real, auditable randomness seeded by your personal input
- Platform-agnostic: works with Claude, ChatGPT, and Gemini

**TarotSeed is not:**
- A fortune teller. It will not tell you what will happen.
- A substitute for medical, legal, or psychological professional help
- A yes/no machine

---

## Versions

The current version is always in [`tarot-reader-prompt.md`](tarot-reader-prompt.md). Previous versions are archived in [`versions/`](versions/). Changes are documented in [`CHANGELOG.md`](CHANGELOG.md).

---

## Contributing

This is an open experiment. If you've tested the prompt, found edge cases, or have ideas for improvement — issues and pull requests are welcome.

---

## License

See [`LICENSE`](LICENSE).
