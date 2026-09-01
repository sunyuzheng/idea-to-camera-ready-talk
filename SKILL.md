---
name: idea-to-camera-ready-talk
description: >
  Turn a developed idea, argument, article, research bundle, or rough outline into a camera-ready
  spoken script and recording cue cards. Use for solo explainers, long-form talking-head videos,
  speeches, lectures, or podcast monologues when the speaker needs an opening that can be delivered
  exactly and a body they can understand, pause on, and express naturally instead of reading a
  teleprompter. Do not use for interview preparation, audience-facing presentation decks, or
  post-production editing.
---

# Idea to Camera-Ready Talk

Move an idea through three distinct contracts without confusing them:

- The **idea** decides what is worth saying and what evidence supports it.
- The **spoken script** proves that a listener can understand the argument once, in time order, without rereading.
- The **recording cards** help the speaker re-enter that argument on camera without memorizing or reading the whole script.

The finished package should preserve the idea's substance while making both listening and delivery easier.

## Inputs

Use the strongest available source: an idea card, article, transcript, research notes, examples, or a prior draft. Also resolve, from the brief or by reasonable inference:

- who is listening and what tension, desire, or question already matters to them;
- the intended duration and recording style;
- which facts, first-person experiences, quotations, and claims are authoritative;
- how freely the speaker wants to improvise;
- whether a rendered browser deck or PDF is actually needed.

Ask only when a missing choice would materially change the argument, evidence boundary, or delivery format. Do not invent an author's memories, motives, evidence, or certainty to make the talk smoother.

## Deliverables

Unless the user asks for a different package, produce:

1. `spoken-script.md`: the complete, camera-ready spoken version.
2. `recording-cue-cards.md`: the compressed recording map, with every card marked `VERBATIM` or `NAVIGATION`.
3. When requested, a rendered cue-card deck and PDF that preserve the Markdown card logic.

The full script is the canonical argument. Cue cards may compress it, but must not introduce new claims or silently change meaning.

A partial package is valid when the user asks for only an opening, one section, or a card sample. Do not manufacture the missing artifacts merely to satisfy the default package; the last delivered card may hand off to a section that will be developed later.

## Shape the listener's path

Before polishing sentences, establish the talk's organizing force. For an explanatory or argumentative talk, this is often a short sequence of audience questions whose answers naturally create the next question. For a story, demonstration, or reflective monologue, the organizing force may instead be time, discovery, contrast, a decision, or a changing interpretation.

A useful path lets the audience feel frequent progress: they understand one relationship, receive its implication, and know why the next part matters. Do not disguise an author's table of contents as a listener roadmap. “Definition, mechanism, solution” names sections; “What is this, why does it keep happening, and what changes now?” names questions a listener can care about.

Read `references/spoken-script-design.md` when the source is concept-dense, the opening is not landing, or a written article must become something people can understand by hearing once.

## Write for one-pass understanding

The spoken script should begin substance early. Its opening normally makes four things clear without conceptual pile-up: the recognizable tension, why it matters now, the promise of the talk, and the first question or claim.

Move through new ideas serially. A sentence may be short or long, but it should normally advance one main relationship at a time. Anchor the listener in something already understood, add one change, show the consequence or example, then earn the next question. Use curiosity to pull forward; do not use missing definitions or delayed clarity as suspense.

Examples should reveal a mechanism, cost, choice, or consequence—not merely decorate a claim. Memorable lines should arrive after the reasoning has made them feel true. Transitions should complete one unit of thought and create the need for the next, rather than announce “the next section.”

Treat a source marked canonical or verified by the current project as sufficient unless the user asks for a fresh audit. Otherwise, trace exact quotations, precise numbers, and consequential factual claims to the strongest linked evidence available before repeating them. Preserve uncertainty when the evidence does not support exactness.

The script is a thinking and rehearsal artifact. It does not imply that every line must be read during recording.

## Choose exact-language and free-delivery zones

Do not treat verbatim delivery and improvisation as an all-or-nothing choice.

Use `VERBATIM` where exact wording materially improves entry, clarity, trust, or timing. The opening is the strongest default candidate because the speaker is not yet in flow and the first lines carry disproportionate attention and framing work. A definition, delicate claim, crucial transition, closing line, or CTA may also deserve exact wording when the current talk benefits from it.

Use `NAVIGATION` for passages the speaker understands well and can explain more naturally in their own words—typically the body of the argument, examples, and elaboration.

Keep exact-language zones selective. Their purpose is to protect high-leverage moments, not to turn the whole recording into teleprompter reading.

## Compress into recording cue cards

Find the points where the speaker may need to pause, understand, and resume. These are cognitive re-entry points, not necessarily paragraphs or slide-sized chunks.

For a `VERBATIM` card, preserve the exact words in readable speaking units. Treat “the opening is verbatim” as a delivery decision, not a one-card constraint: a 60–90 second opening will commonly need several consecutive cards. Split at thought or breath boundaries until each card can be scanned comfortably at recording distance without scrolling.

For a `NAVIGATION` card, keep one stable grammar across the deck:

- a title the speaker can say directly as the opening sentence, memorable line, or smooth transition;
- one top-to-bottom sequence of thought;
- bold wording only where a line should land with unusual precision;
- optional side notes only for delivery reminders, evidence boundaries, or points easy to forget;
- a final handoff that creates the next thought, with the next card's title continuing it.

Sequential reasoning belongs in the main vertical flow. Do not distribute one sequence across unrelated left and right blocks. Do not make the speaker relearn the layout on every card.

Read `references/recording-cue-cards.md` when deciding card boundaries, mixed modes, or rendered layout.

## Render only when it helps recording

When the user wants an iPad or browser artifact, use the appropriate presentation or deck-production tooling after the content map is stable. Choose aspect ratio, type size, contrast, navigation, and card density for the actual recording distance and device. Keep a consistent visual grammar and verify every card at the target viewport; no overflow, clipped text, accidental scroll, or tiny type.

These are speaker-facing cards, not audience slides. Visual restraint is often useful because decoration competes with re-entry, but no theme, aspect ratio, card count, or color scheme is universal.

## Acceptance criteria

The package is ready when:

- a listener hearing the script once can follow what each section changes and why the next section follows;
- the opening is direct, inviting, and easy for the speaker to enter; if marked `VERBATIM`, its exact wording is preserved on the opening card or cards;
- the script does not ask one sentence to carry several unfamiliar relationships before the audience has a frame;
- each indispensable claim, example, transition, and qualification is supported by the source;
- when the user specifies a duration, the delivered script states how timing was estimated; use an appropriate language-specific speaking rate, or read and time the passage when precision materially matters;
- each cue-card title is directly speakable, and the deck uses one recognizable navigation grammar;
- a speaker can pause on any card, understand the local thought, look up, and continue naturally;
- the last thought on one card makes the next card easier to enter;
- the cards preserve the script's causal or narrative spine without becoming a second competing draft;
- any rendered deck is readable and operable on the target device.

## Known failures from real rework

- **Correct but unlistenable:** the draft compresses audience, comparison, definition, cause, and suspense into one sentence. The ideas are accurate, but listeners leave before they can assemble them.
- **Article broken into short lines:** sentence length changes, but the nested logic and rereading burden remain.
- **Roadmap as author labels:** the opening announces categories instead of questions the audience wants answered.
- **Bullet extraction mistaken for compression:** cards summarize paragraphs but do not preserve the order in which the speaker needs to think.
- **Independent cards:** every card has a new layout or logic, so turning the page creates a new comprehension task.
- **Two-column sequence:** sequential reasoning is split spatially, forcing the speaker to decide where to look next.
- **Cue cards turned into audience slides:** decoration and complete explanations displace the speaker's re-entry cues.
- **One giant verbatim card:** an exact opening is treated as one visual unit, so the speaker must scan a page of prose under recording pressure. Keep the wording exact while splitting it into consecutive speaking beats.
- **Everything treated as improvisation:** the speaker reaches the most attention-sensitive opening before entering flow and has to invent wording under pressure.
- **Everything treated as verbatim:** natural explanation becomes reading, and the speaker loses the freedom the cards were meant to protect.

## Boundaries and handoffs

- For non-interview writing more broadly, use `substance-writing-review`; this skill owns the additional transformation into spoken delivery and recording cards.
- For interview preparation, use `prepare-guest-interview`.
- For an audience-facing presentation, use `deck-production` or the relevant presentation skill. A recording cue deck is not a substitute for a public deck.
- After recording, route editing, subtitles, graphics, and publication to `lizheng-video-editing`, `kdb-talking-head-short-production`, or the relevant post-production skill.
- User instructions and the current project's factual and publication boundaries override these defaults.

Trace the method and calibration cases through `references/sources.md` only when provenance or further examples are needed.
