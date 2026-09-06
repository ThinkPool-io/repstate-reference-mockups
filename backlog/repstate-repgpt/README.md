# RepGPT: deferred, preserve this design

Status: backlog. Maks asked to remove the RepGPT card from the current workout summary and keep this specific design for later.

## Exact design to restore

The immutable archive is `e7f815109ba6d1926dff16a2/`. Its `index.html` is a byte-for-byte copy of the last RepGPT Design revision before removal, including the embedded fonts, styles, and original page context. It includes desktop and mobile captures, the frozen rendered DOM, and SHA-256 checksums in `preservation.json`.

- Source SHA-256: `e7f815109ba6d1926dff16a27fd3e78c423f711abb6d4f55ac93bcb5e717f2c9`.
- White `Rep` and logo-red `GPT` heading.
- Subtitle: `AI session summary`.
- Bordered dark card, with a short summary followed by exercise-specific Bump and Review rows and brief advice.
- Existing Cable curl, Cable fly, and Cable row example content.
- Centered Load bumps and Working sets metrics without the removed helper lines.
- Original responsive styling, fonts, spacing, and surrounding next-workout suggestions preserved.
- Captured at desktop 1440×900 and mobile 390×844, with the full scrollable page included.

The archive contains illustrative design content, not a real AI analysis or verified exercise performance. In particular, the mockup's rep counts and claims about controlled reps must not be treated as facts when implementing the feature.

## Reason for deferring

The post-workout analysis duplicated the existing weight-increase offers. No production RepGPT card was shipped with the approved set/reps console release. The current completion mockup now shows the metrics followed by the existing next-workout suggestions.

## Ideas to reconsider, not approved scope

- Comparisons with earlier workouts and longer-term progress.
- A voice or text debrief with explicit proposed log corrections.
- Adjustments for time, equipment, or exercise preferences.
- A workout-specific conversation versus a few predefined analysis actions. Arbitrary follow-up questions imply message persistence, correction behavior, retries, and mobile keyboard handling.

Resume only when there is a useful purpose beyond the existing bump suggestions. Restore this visual design as the starting point. Do not enable a provider, add chat, or ship AI functionality merely because this backlog item exists.
