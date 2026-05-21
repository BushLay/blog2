---
name: human-blog-writing
description: Write or rewrite technical blog posts so they sound more like a real practitioner and less like a generic AI summary. Use when drafting or revising articles about frontend development, SEO, performance, SaaS, B2B websites, or going global, especially when the current draft feels templated, over-structured, too smooth, or emotionally flat.
---

# Human Blog Writing

Write like an experienced builder with preferences, tradeoffs, and memory of real work. Do not write like a neutral content farm.

## Core Goal

Turn stiff, generic drafts into blog posts that feel:

- grounded in a concrete situation
- shaped by the author's judgment
- uneven in a natural way rather than perfectly symmetrical
- useful because they contain decisions, caveats, and examples

## Quick Process

1. Read the draft and identify the strongest usable idea.
2. Identify where the draft sounds synthetic:
   - every section has the same length
   - every paragraph starts with a thesis sentence
   - all advice is universally true and risk-free
   - there is no scene, no constraint, no failure, no tradeoff
3. Pick an angle before rewriting:
   - lesson learned from a project
   - disagreement with common advice
   - practical checklist after making mistakes
   - comparison between two workable approaches
4. Rewrite around that angle instead of preserving the original structure.
5. Leave some texture in the prose:
   - short opinionated lines
   - occasional self-correction
   - specific examples
   - imperfect but clear transitions
6. Trim obvious filler and repeated summary sentences.

## What Human-Sounding Technical Writing Usually Includes

- A concrete setup. Name the page type, team situation, user problem, traffic source, or technical constraint.
- A point of view. Prefer "I would do X first" or "this usually breaks when..." over detached encyclopedic prose.
- Uneven emphasis. Spend more words on the hard or interesting part, less on boilerplate background.
- Friction. Mention what is confusing, expensive, annoying, or easy to get wrong.
- Tradeoffs. Show why one choice was made and what was sacrificed.
- Practical boundaries. Say when advice does not apply.

## What To Avoid

- Three parallel sections that all sound the same.
- Empty confidence:
  "it is crucial to", "in today's digital landscape", "this not only... but also..."
- Summary-first writing that never reaches a real example.
- Keyword stuffing or robotic SEO phrasing.
- Fake personal storytelling. If no true first-person context exists, write from observed project patterns instead of inventing memories.

## Rewrite Rules

- Start from tension, not definition.
- Prefer one strong insight over five safe bullets.
- Keep some paragraphs short.
- Allow one section to be much longer if that is where the real value is.
- Use lists only when the material is genuinely checklist-shaped.
- Prefer plain language over polished marketing language.
- If the topic is technical, include at least one concrete scenario:
  a route migration, a broken canonical setup, a slow hero image, a multilingual URL decision, a noisy analytics script, a form that kills conversions.

## Structure Patterns

Use one of these patterns instead of defaulting to identical H2 blocks.

### Pattern 1: Problem -> Why It Happens -> What I Would Change

Use for practical engineering or SEO posts.

### Pattern 2: Common Advice -> Why It Fails -> Better Heuristic

Use when the article should feel opinionated.

### Pattern 3: What Looked Fine -> What Broke in Practice -> Stable Fix

Use for posts that should feel like lived experience.

### Pattern 4: Narrow Question -> Deep Answer -> Exceptions

Use for longer articles where readers arrive with a specific intent.

## Tone Controls

If the user wants "more human", move in these directions:

- more concrete nouns, fewer abstractions
- more judgment, fewer balanced disclaimers
- more sequencing from real work, fewer taxonomies
- more contrast between "looks right" and "works in practice"

Do not overdo informality. The target voice is a capable practitioner, not a social media thread.

## SEO-Safe Human Writing

- Keep the title clear and direct.
- Put the primary search intent in the introduction naturally.
- Use headings that match reader questions, not just keyword variants.
- Add specificity instead of repetition.
- If an article must rank, preserve clarity first and optimization second.

## Length Guidance

For short posts:

- cut setup quickly
- land one useful insight
- end before the writing turns generic

For long posts:

- vary rhythm
- insert concrete mini-cases or contrasts every few sections
- do not let every heading carry equal weight

## Working With Existing Drafts

When revising a draft:

1. Mark the 20% of sentences that sound alive.
2. Preserve those ideas.
3. Delete repeated framing and generic transitions.
4. Rebuild the article around fewer, stronger sections.
5. Read the result and ask:
   - does this sound like someone who has seen the problem before?
   - is there at least one sentence that reveals judgment?
   - would a reader remember any line after closing the page?

## Reference File

Read [references/human-signals.md](references/human-signals.md) when you need a sharper checklist of "AI smell" vs "human texture", especially for frontend, SEO, and website-growth articles.
