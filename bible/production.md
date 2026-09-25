# Production charter

1. **Mobile first.** Design for effortless vertical phone reading; desktop/PDF are secondary outputs.
2. **One generation = one case.** Never regenerate already-approved neighboring material merely to create the next beat.
3. **The case is not necessarily a rectangle.** Borders are optional; shapes, crops, fades and speech bubbles may extend into white space.
4. **White space is narrative timing.** Use it deliberately between beats, especially for two-step jokes and reveals.
5. **Continuity beats isolated beauty.** Character presence, pose logic, wardrobe, object state and location must make physical sense from one case to the next.
6. **Exact dialogue matters.** Verify French text before approval.
7. **QA before presentation.** Reject obvious visual/narrative failures before asking the user to review.
8. **Approved means immutable.** Revise an approved case only through an explicit replacement/version decision.
9. **Assembly is deterministic.** Final chapter strips/PDFs concatenate approved assets; the image generator does not redraw them.
10. **Keep the system light.** Git is the canon/version ledger, not a bureaucracy. No unnecessary CI, ticketing or schema machinery.

## Pre-presentation QA

A candidate case should pass:
- **Continuity:** correct characters, clothes, props and location.
- **Spatial logic:** positions, facing and action are physically understandable.
- **State transition:** incoming and outgoing object/story state are correct.
- **Text:** exact wording, speaker and readable lettering.
- **Mobile read:** the beat is understandable at phone width without zooming.
- **Style:** consistent with current canonical reference images.

If an important check fails, iterate before presenting when practical.
