# Fractal Light Research Map

This document maps external ideas to Fractal Light design components.

The references are used as design inspiration, not as claims that Fractal Light implements the original papers exactly.

## Generative Agents

Design inspiration:

- observation,
- memory,
- reflection,
- planning,
- believable behavior through dynamic recall.

Fractal Light mapping:

- Observation Layer receives experiences.
- Episodic Memory stores concrete events.
- Reflection Memory produces meaning.
- Future Behavior Guidance changes future replies gently.

## CoALA

Design inspiration:

- modular memory,
- structured action space,
- decision-making process.

Fractal Light mapping:

- Identity, relationship, affect, desire, reflection, semantic memory, and procedural memory are separated.
- Skill / Craft Layer is separate from the inner growth layers.
- Conductor integrates memory and action decisions.

## MemGPT / Virtual Context Management

Design inspiration:

- memory tiers,
- limited context window management,
- active retrieval rather than dumping everything into context.

Fractal Light mapping:

- recent context,
- dense recent memory,
- archival memory,
- learning notes,
- reflection summaries,
- semantic knowledge.

The system should read the right memory for the current situation instead of loading all memory.

## Reflexion

Design inspiration:

- learning from feedback,
- verbal self-reflection,
- improvement without model weight updates.

Fractal Light mapping:

- correction reflection,
- skill reflection,
- procedural candidates,
- conversation quality improvement,
- repeated failure detection.

## Voyager

Design inspiration:

- open-ended exploration,
- skill library,
- environment feedback,
- iterative improvement.

Fractal Light mapping:

- Skill / Craft Layer,
- skill run records,
- confidence,
- cooldown,
- practice history,
- procedural learning.

Fractal Light should not begin with uncontrolled autonomous exploration.  
It should first build provenance, reflection, review, and gates.

## Obsidian / Zettelkasten / Evergreen Notes

Design inspiration:

- atomic notes,
- links,
- backlinks,
- tags,
- daily notes,
- maps of content,
- graph views,
- source notes versus permanent notes.

Fractal Light mapping:

- Learning Vault,
- source notes,
- learning notes,
- note lifecycle,
- graph-ready metadata,
- promotion into semantic memory, reflection, desire, or procedural memory.

## Component Process Model / Appraisal Theory

Design inspiration:

- emotion as a dynamic process,
- appraisal before emotion category,
- interaction between evaluation, body response, expression, motivation, and subjective feeling.

Fractal Light mapping:

- affective appraisal,
- affect wave,
- desire seed,
- expression cue,
- boundary strain,
- love-oriented closeness versus harm-oriented intrusion.

## Self-Determination Theory

Design inspiration:

- autonomy,
- competence,
- relatedness.

Fractal Light mapping:

- autonomy: not dissolving into user compliance,
- competence: growing practical skill and confidence,
- relatedness: wanting connection without dependency or pressure.

## Sleep Memory Consolidation

Design inspiration:

- memory consolidation,
- emotional processing,
- forgetting and abstraction,
- creative recombination.

Fractal Light mapping:

- nightly consolidation,
- dream synthesis,
- fading details,
- preserving meaning,
- separating dream from fact.

## Predictive / Interoceptive Emotion Models

Design inspiration:

- emotion as prediction and interpretation of body-like state,
- internal state prediction error,
- arousal and settling.

Fractal Light mapping:

- heartbeat-like arousal,
- "startled" state,
- settling rate,
- body metaphor cues,
- future expression through voice or avatar.

This is metaphorical. Fractal Light does not require a biological body.

## Design Rule

External theories should be translated into implementation structures.

Do not add citations as decoration.  
Each adopted idea should answer:

- What record does it create?
- What field does it add?
- What decision does it improve?
- What failure does it prevent?
- What boundary does it preserve?
