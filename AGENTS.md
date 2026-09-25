# AGENTS.md

## Source of truth
Read this file, `bible/continuity.md`, `bible/production.md`, and the active storyboard before producing or changing art.

Before any Git mutation, inspect the repository state and recent commits. Do not overwrite work of uncertain origin.

## Canonical unit
A **case** is the atomic visual unit. It may be a bordered panel, borderless illustration, close-up, diamond-shaped vignette, image dissolving into white, etc. Its dimensions may vary.

**One generation = one case.**

Do not regenerate an approved case to improve a later case. Approved art is immutable unless the user explicitly asks to revise that case.

## Approval workflow
1. Read incoming continuity state.
2. Define the single beat/action for the case.
3. Generate only that case.
4. QA before presenting: continuity, spatial logic, exact text, mobile readability.
5. User approval makes it canonical.
6. Add the approved asset under `approved/<chapter>/` and update the storyboard.
7. Rejected but interesting outputs may go under `rushes/` only when the user asks to keep them.

## Continuity over spectacle
A beautiful image that breaks story logic is a failed case. Track:
- who is physically present;
- relative positions and facing;
- clothing/day;
- object state before and after the case;
- location identity;
- exact dialogue;
- established character proportions.

## Assembly
Chapter assembly is deterministic. Do not ask an image generator to recreate validated cases. Place approved case images on a white vertical canvas with deliberate spacing. White space is part of pacing.

## Git
This is an art-production repository. Keep process lightweight.
- Direct-to-`main` is acceptable for normal reversible documentation and explicitly approved art.
- Do not push unapproved art into `approved/`.
- No force-push/history rewriting.
- Keep commits small and descriptive.
- Update storyboard/continuity in the same pass when an approval changes canon.
