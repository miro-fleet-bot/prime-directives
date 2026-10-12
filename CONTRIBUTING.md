# Contributing

This framework improves through people actually trying to break it. The most useful contribution is a counterexample, not a style suggestion.

## What's worth sending in

The real test: take any situation, apply the rules honestly and in good faith, the way they're meant to run, and see where it leads. If you can show a scenario where harm still gets through by intent — not because the rules were misapplied, but because applying them *properly* still let it happen — that's the failure worth reporting. It has happened once already, inside an earlier draft: a worked example ran the four-part malicious-intent test correctly, got "confirmed malice," and the draft still resolved the case by reading tone rather than by the test's own output. That's the shape of failure worth finding more of — a case where the machinery itself fails, not where a sentence needs tightening.

Also useful:
- A contradiction between what a rule says and what it was built to do.
- A case the document's existing worked examples don't actually cover.
- A scenario from real law, real AI safety incidents, or real personal experience that the framework handles badly.

Less useful (but still read): wording clarity, typos, formatting.

## How to submit

Open a GitHub issue in this repository, or write directly to **primedirectives.contact@mail.bg**. Either way, include:

1. The specific scenario, stated concretely enough to actually run the rules against it.
2. Which section of the framework you applied, and the result you got applying it honestly.
3. Where that result breaks down — what harm gets through, or what contradiction shows up.

## What happens next

Submissions are read and, where they hold up, folded into the document with the contradiction (or the fix) stated openly — not quietly patched over. See `appendix/adversarial-reviews.md` for how past rounds of review were incorporated, and `CHANGELOG.md` for the revision record. A framework flexible enough to absorb every objection without ever changing structurally would be demonstrating unfalsifiability, not strength — the only way "please find what's wrong with this" means anything is if there's a real way to be shown wrong.
