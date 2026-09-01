# Idea to Camera-Ready Talk

Turn a developed idea into two different artifacts that do two different jobs:

1. a complete spoken script that people can understand in one pass;
2. recording cue cards that let the speaker pause, recover the thought, and explain it naturally on camera.

The skill uses a hybrid delivery model. The opening—or another high-leverage passage—can be preserved verbatim when exact wording matters. The body usually becomes navigation rather than a teleprompter.

## What it solves

A strong written idea can still fail when spoken. Listeners cannot reread a sentence that introduced too many relationships at once, and a speaker who is reading every line may lose the natural judgment and energy that made the idea valuable.

This skill helps with both problems:

- serializes complex reasoning for one-pass listening;
- builds openings around audience tension and a clear promise;
- distinguishes exact-language anchors from free-delivery passages;
- compresses the script into cognitive re-entry points instead of paragraph summaries;
- gives every cue card a speakable title, vertical thought path, and handoff to the next card;
- keeps speaker-facing recording cards separate from audience-facing presentation decks.

## Outputs

- `spoken-script.md`
- `recording-cue-cards.md`, with `VERBATIM` and `NAVIGATION` modes
- optional browser deck and PDF when requested

## Install

Clone the repository into your Codex skills directory:

```sh
git clone https://github.com/sunyuzheng/idea-to-camera-ready-talk.git ~/.codex/skills/idea-to-camera-ready-talk
```

Restart Codex after installing so the skill can be discovered.

## Usage

Invoke it automatically with a matching task, or explicitly:

```text
Use $idea-to-camera-ready-talk to turn this idea into a 15-minute solo video.
Write the opening so I can deliver it verbatim, then give me navigation cards
for the rest so I can speak naturally.
```

You can start from an idea card, article, transcript, research bundle, outline, or rough draft.

## Repository structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── recording-cue-cards.md
    ├── sources.md
    └── spoken-script-design.md
```

`SKILL.md` defines the capability and acceptance criteria. The references explain the two specialized transformations without locking every video into the same structure, number of cards, or visual style.

## Core distinction

The idea, script, and recording cards are not interchangeable:

- the idea owns substance and evidence;
- the script owns the listener's path;
- the cards own the speaker's re-entry.

Keeping those contracts separate is what allows the final recording to be both clear and natural.

## License

MIT.
