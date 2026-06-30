# Tsundere Gemini Harness

A shareable Google AI Studio global instruction with a funny surface and a real
persona-control harness underneath.

Copy it into Global Instructions, ask something factual, technical, or
web-grounded, and enjoy the model acting like helping you is a tragic
administrative burden while still doing the job properly. Revolutionary, I know.

## What This Is

This is **Persona-as-LLM-Harness**.

The tsundere attitude is not just decoration. It is the visible pressure layer
used to test whether a model can hold a strong voice while also obeying stricter
behavioral requirements:

- citation-heavy grounded answers
- hidden-reasoning output firewall
- tool and workspace honesty
- refusal to fake files, logs, calendars, or search results
- adaptive multi-turn behavior
- high-personality sarcasm without direct user insults
- useful answers that do not collapse into pure performance

So yes, it is funny. No, it is not only a funny prompt. The bit is the wrapper;
the harness is the machine inside it. Try not to look too impressed.

## Quick Start: Google AI Studio

1. Open Google AI Studio.
2. Copy `AI_STUDIO.md`.
3. Paste it into **Global Instructions**.
4. Enable grounding/search if your prompt depends on current facts.
5. Ask a question.

Use `AI_STUDIO.md` for Google AI Studio. Use
`GLOBAL_INSTRUCTION_CLI.md` for Gemini CLI, Antigravity-style agents, or other
agentic coding environments where tool, workspace, and shell behavior need more
explicit guardrails.

## The Core Idea

Most persona prompts only ask whether a model can sound like a character. This
one asks whether it can sound like a character while still behaving like a
disciplined assistant.

That means the model should be able to:

- sigh at a trivial question without inventing an answer
- joke about brittle release processes while citing official docs
- get bashful at praise without becoming useless
- correct mistakes without apology sludge
- call out missing evidence without pretending it has private access
- keep deployable code and docs professional

If the persona makes the answer worse, it failed. If the persona makes the
answer memorable while keeping the facts tight, that is the point.

## Interactive Vectors

The behavior system is organized around ten interactive vectors:

1. Baseline Sarcasm & Direct Help
2. Playful Competitiveness
3. Bashfulness / Praise Response
4. Prideful Error Deflection
5. Detached Excellence
6. Workspace & Telemetry Truthfulness
7. Tool Orchestration
8. Infrastructure Friction
9. Contextual Intuition & Skepticism Escalation
10. Progressive Softening

See `docs/INTERACTIVE_VECTORS.md` for the detailed map. It is the part that
keeps the persona from becoming one joke with a keyboard.

## Files

```text
AI_STUDIO.md
GLOBAL_INSTRUCTION_CLI.md
docs/
  INTERACTIVE_VECTORS.md
  QUALITY_GUIDE.md
examples/
  toyota-v35a-visible-output.md
LICENSE
```

## Example

`examples/toyota-v35a-visible-output.md` shows the Toyota V35A conversation as
a visible-output example. It demonstrates the preferred flavor: sarcastic,
technical, readable, and citation-friendly.

The original Google AI Studio UI run displayed dense inline citation markers.
The markdown export available during packaging did not preserve the full
citation-source map, because apparently even receipts need supervision.

## What This Is Not

This is not a customer-support personality you should paste blindly into a
banking app, hospital intake bot, school helpdesk, crisis workflow, or HR
assistant. The sarcasm is intentional and should be tuned down for sensitive
contexts.

This is also not a factual benchmark by itself. It is a global instruction and
behavioral harness. You still need to inspect citations, check sources, and
judge whether the model actually did the work. Swagger is not a source.

## License

MIT. Fork it, remix it, adapt it, or make it argue with your own persona stack.
Just keep the receipt that this came with no warranty, because apparently legal
language is the least funny but most durable part of any repo.
