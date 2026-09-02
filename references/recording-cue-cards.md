# Recording Cue Cards

Recording cue cards are a speaker interface. They are neither a transcript summary nor a miniature audience deck. Their job is to let the speaker stop, look, recover the thought, and continue in their own voice.

## Two card modes

### VERBATIM

Use when exact language carries unusual leverage: commonly the opening, and sometimes a definition, sensitive claim, decisive transition, closing line, or CTA.

For a discovery-driven video, the first verbatim card or cards should preserve the package-opening contract: recognize the click question, deepen it, and hand directly into the first substantive beat. Do not use a cue-card title or side note as a substitute for words the viewer actually hears.

A verbatim card should:

- show the exact words in short, readable speaking units;
- preserve sentence order and intentional emphasis;
- avoid side content that competes with reading;
- split across cards when the text cannot be scanned comfortably at the target distance; a 60–90 second opening will commonly need several consecutive verbatim cards rather than one page of prose;
- end with a clear handoff into the next card or into free delivery.

### NAVIGATION

Use when the speaker understands the material and will sound better explaining it freely.

A navigation card normally contains:

- a directly speakable title;
- a short vertical progression of claims, examples, or consequences;
- selectively bold exact lines;
- optional side reminders that are not part of the sequence;
- a final handoff into the next card.

The words may be terse, but the relationships cannot be missing. “AI → signals → inflation” is compact but often too ambiguous; “AI makes work evidence cheap → the evidence floods the system → it stops proving value” restores the causal path the speaker needs.

## Choosing boundaries

Start a new card when the speaker must enter a new question, example, mechanism, or emotional register—not merely because a paragraph ended. Within a verbatim passage, also split at a natural speaking beat when the current card would become hard to scan. Card density should match the speaker's need to pause and the device's reading distance. One talk may need many light cards; another may need fewer, denser cards.

The last line of a card should reduce the cost of turning the page. It can pose the question the next title answers, name the unresolved tension, or begin a transition that the next title completes.

## Stable visual grammar

Use the same information hierarchy and spatial logic across the deck. Sequential content runs top-to-bottom. Side areas are reserved for optional reminders, evidence boundaries, pronunciation, or delivery notes.

Avoid layouts that require the speaker to choose between two parallel paths, decode a new component on every card, or read audience-facing captions and decoration. A visual treatment may be expressive, but it should not compete with the job of re-entry.

## Suggested Markdown schema

Adapt this only when the content benefits:

```markdown
## 01｜<directly speakable title>

**Mode:** VERBATIM

<exact opening in readable speaking units>

**Handoff:** <next thought>
```

```markdown
## 02｜<directly speakable title>

**Mode:** NAVIGATION

1. <first relation>
2. <consequence or example>
3. **<line worth landing exactly>**

**Side note:** <optional delivery or evidence reminder>

**Handoff:** <question or transition answered by the next title>
```

## Rendering and verification

If the cards become HTML, slides, or PDF, verify them on the actual device or target viewport:

- all text is readable from the recording position;
- no clipping, overflow, accidental scroll, or hidden controls;
- touch, keyboard, or simple navigation works as intended;
- verbatim and navigation modes are distinguishable without changing the whole layout grammar;
- the current card number and progression are easy to recover;
- exported PDF and browser version preserve the same order and emphasis.
