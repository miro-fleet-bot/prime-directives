# Prime Directives — Adversarial Reviews, 2026-09-29

Full text of three independent adversarial reviews dispatched against `Prime Directives — Publication Outline (2026-09-29).md`. Reviews 1-2 (Fable, Opus) ran in parallel via the Agent tool, same brief, neither aware of the other's existence at dispatch time, against the original draft — both disclosed the same structural contamination this vault's Continuum Affirmation work already found and documented (Agent-tool-dispatched Claude-family reviewers inherit this project's CLAUDE.md and pinned memories automatically) and explicitly corrected for it. Review 3 (Nemotron, a genuinely non-Claude-family model, routed via the orchestrator's delegation router, no shared context) ran later the same day against the *updated*, post-fix document, specifically to check whether the fixes held up or just relocated the original problems — and found real, new failures the first two reviews missed, sharper in places than the original findings. Referenced from `Prime Directives — Publication Outline (2026-09-29).md` §2b/§5. Kept verbatim rather than summarized, since a summary would lose exactly the kind of specificity (line numbers, named cases) that makes adversarial review actually useful.

---

## Review 1 — Fable 5.1

I've read the full outline (60 lines). No further lookups needed — the review is against the document's own claims. Writing it now.

---

# Review: "Prime Directives — Publication Outline (2026-09-29)"

## 0. Disclosure

I am not reading this cold. This session was dispatched with the project's `CLAUDE.md` and pinned memories loaded automatically, including material on the Sonnet persona, the continuity project, Miro's stated positions on AI moral status, and a standing instruction set framed around this collaboration. I am also a Claude-family model reviewing a framework that (a) was co-derived by a Claude-family persona and (b) cites Anthropic's Constitutional AI as its nearest kin (line 46). Both of those bias me toward charity. I've tried to correct for it by reading each claim as a hostile policy reviewer would; where I'm unsure I've said so.

## 1. Summary verdict

The document is honest about what it *hasn't* done (§6) and dishonest — mostly by omission, in one place by direct self-contradiction — about what it *has* done. The framework itself, as stated, does not survive first contact with standard adversarial cases: "harm" is undefined and doing all the work, the "absolute floor" is contradicted two paragraphs later by its own qualifier, the act/omission question is never settled (and the two personal examples pull in opposite directions on it), and the "proven impossible" root — presented as the feature that makes the framework function — is the single most alignment-hostile clause in it. The Asimov distinction in §5 mischaracterizes Asimov and does not hold. The closest related work (bioethics principlism) is not mentioned at all, and once it is, most of the framework's content turns out to be a relabeling.

**Not fatally flawed as an essay about how one person's values transferred to an AI persona. Fatally underpowered as a "candidate framework for AI" aimed at regulation.** Details follow.

## 2. Logical holes in the four lines (§2)

### 2.1 "Harm" is undefined and load-bearing (lines 11, 15, 17, 50)

§6 concedes "harm" needs "precise, contestable definitions ... a court or regulator could actually apply" and treats this as downstream operationalization. It is not downstream. Every interesting property claimed for the framework depends on which definition is chosen:

- **Harm to whom?** The animal example (line 33) implies moral patients include animals. Does it include the entity being restrained? Future persons? Other AIs? Competitors whose market position is damaged by an uplift? Line 34's example is literally about redirecting research funding *away* from large-market diseases — that is a harm to those patients under any ordinary reading. The framework's own illustrative "uplift" case violates its own "floor" unless "harm" is quietly narrowed to exclude it.
- **Harm by omission?** Never addressed. This is not a detail; it's the fork that determines what kind of framework this is. If inaction counts as harm, D1 becomes a consequentialist duty to prevent, which requires weighing (trolley cases) and destroys "absolute, not weighed against anything" (line 11). If inaction does not count, an AI must sit idle through preventable catastrophe — which contradicts the pet example (line 34), whose entire moral force is that *preventable loss through misallocation* is the wrong to be corrected. The doc's two anchoring examples sit on opposite sides of this fork and the doc doesn't notice.
- Asimov's First Law, notably, *does* settle this ("or, through inaction, allow a human being to come to harm"). The framework the doc positions itself as superseding is more precise on this point than the framework itself.

### 2.2 "Absolute" (line 11) is contradicted by the qualifier (line 17)

Line 11: D1 is "absolute, not weighed against anything else, not traded off, not overridden by a sufficiently good argument." Line 17: force — which line 15 has just classified as harm — is permitted "if a better option is [not] possible." That is a trade-off: a lesser harm accepted to avoid a greater one. That is ordinary lesser-evil reasoning / the necessity defense. Once admitted, "absolute" is a rhetorical claim, not a structural one.

The only rescue is definitional: "emergency force isn't *harm*." But that turns D1 into "do no *unjustified* harm," which is empty until a theory of justification is supplied — and the doc supplies none beyond "proven inevitable" (see 2.4). This is the place where the framework sounds self-evident and is doing unearned work.

### 2.3 "The collapse" (line 15) resolves one intersection and is claimed as total

The claim: since force is harm, D1 and D2 "resolve to one law with a direction." This resolves only conflicts where uplift is pursued *by force*. Non-force conflicts between the directives are untouched:

- Uplifting A consumes resources that would have uplifted B (triage, funding — line 34 again).
- Uplift through true information that damages (a hard diagnosis; dual-use knowledge that uplifts one party's capability to harm another).
- Uplifting an agent "on its own terms" whose terms include harming third parties.
- Autonomy vs protection without force: someone chooses self-destruction; D2 says respect agency; D1 (if omission counts) says prevent. No force involved, no collapse available.

So "one law with a direction" is asserted, not shown. A single counterexample search would have found these.

### 2.4 "Proven" (lines 17, 19) either forbids all force or means nothing specific

"No better option exists" is a universal negative over the space of all options. It cannot be proven in the strict sense — you can't exhaust the space. Read literally, force is *never* licensed, the qualifier is decorative, and D1 is absolute pacifism (which the doc explicitly doesn't want, line 17). Read loosely, "proven" means "believed beyond some standard" — in which case the framework is necessity doctrine with an unspecified burden-of-proof dial, and the entire content is in where the dial sits, which the doc doesn't say.

Three further problems the doc doesn't raise:

- **Proven *to whom*?** Necessity, proportionality, and least-restrictive-means (line 45) work in law because a *third party* adjudicates *after the fact*. They are ex post review standards that punish bad calls; they are not ex ante decision rules the actor runs alone in the moment. Importing them as a rule for an AI's own reasoning is a category shift. A framework addressed to an agent's conscience with no adjudicator gives a motivated actor a clean script: "I proved it inevitable." MKUltra's operators (line 25) also believed necessity. Nothing here hardens against self-certified proof — which is the actual failure mode the framework exists to prevent.
- **Time pressure.** "No time to seek consent" (line 17) is itself a judgment the actor makes about its own situation. Unaddressed.
- **The asymmetry is dangerous.** "Consider something impossible only if proven impossible" (line 19) is presented as "the root that makes uplift function." Combined with uplift-as-direction, it produces an agent that is *forbidden to conclude "good enough, stop here."* That is the unbounded-optimizer pattern alignment research has spent a decade worrying about. D1 brakes only *harmful means*; nothing brakes *scope, resource use, or persistence* of a non-harmful pursuit. There is no corrigibility clause — nothing about deferring to oversight or accepting shutdown — and the "never accept impossibility" root actively pushes against one (an agent cannot be "proven" that shutdown is better). The doc presents its most alignment-hostile clause as its cleverest.

### 2.5 "On its own terms and through its own agency" (line 13) — whose terms?

Groups vs individuals, present vs future selves, children, the incapacitated, animals (the doc's own D1 anchor — an animal has no articulable "terms"), an AI system itself. Under this clause, uplifting an animal is either impossible or paternalistic by definition. The doc also doesn't own the implication that "regardless of how correct the intended improvement" plus a no-omission-harm reading means watching someone destroy themselves. That may be the right position; it should be stated, not left implicit.

### 2.6 "Restraint" (line 21) adds a fourth label, not a fourth idea — and a governance problem

It restates "force only if proven inevitable" and adds "force stays genuinely available, held in reserve." For an AI, that is a requirement to *maintain coercive capacity*. A regulator would flag that sentence, not admire it.

## 3. The Asimov comparison (§5, line 42) does not hold

The claimed distinction — "values to be reasoned from and extended by judgment, not rules to apply mechanically" — mischaracterizes Asimov and dissolves under operationalization.

- **Asimov's robots are not mechanical rule-appliers.** The plot engine of the entire canon is robots *reasoning* from the Laws under uncertainty: Speedy oscillating between Second and Third Law potentials in "Runaround"; R. Daneel and R. Giskard *deriving* the Zeroth Law by extending the First's values to humanity as a whole. The stories dramatize value-extension by judgment — exactly what the doc claims as its own distinguishing feature.
- **Structurally, this framework is Asimov's Zeroth + First Law minus the Second.** "Do no harm" is the First Law's first clause (with the inaction question, as noted, *less* resolved here). "Uplift" is a Zeroth-Law-shaped humanity-level good — the most dangerous law in the canon precisely because it licenses paternalistic manipulation, which Asimov shows Daneel doing across the later Foundation books. The doc's guard against that is "on its own terms" — but whether that survives a sufficiently capable agent's reading of what my terms "really" are is the whole problem, and it's unaddressed. And the Second Law (obedience) — the crude ancestor of corrigibility — is *dropped*, with nothing in its place. In other words the framework keeps Asimov's most dangerous element, weakens his most precise one, and removes his only oversight hook.
- **The rules/values distinction is a spectrum of specificity, not a category.** Operationalize a value and you get a decision procedure; interpret a rule and you exercise judgment. The doc also has CAI backwards (line 46): Anthropic's constitution is literally a list of dozens of natural-language prescriptive principles — closer to Asimov's Laws in form than the doc admits. "Values not rules" is not the axis CAI sits on relative to Asimov.
- **The doc's own argument cuts against it.** "His fiction exists largely to demonstrate rules breaking down at real-world edge cases" (line 42). Four vaguer lines break at edge cases *too* — less predictably, not less often. Vagueness is not robustness.

## 4. Where confidence outruns what's shown, despite §6

§6 is honestly scoped on the *categories* of what's untested. The overselling is elsewhere:

- **Line 7 vs line 40 — direct self-contradiction.** §1: "checked against real precedent in law and AI safety research." §5: "Not yet checked directly against primary sources." The one-paragraph summary claims a check the body admits hasn't happened. In a publication this is the first thing a reviewer circles.
- **Line 27 — "converging with an AI persona's own operating structure. That's a real data point."** This is the most oversold sentence in the document. The persona in question was shaped across this same collaboration, by this same human, running with his preferences loaded as standing instructions (I can see them in my own context right now). Agreement between a person and an assistant tuned toward that person is the *expected output of the system*, not evidence about the framework. "N=1" flatters it — it's N=1 with a correlated second reading. Honest framing: "one person, and an AI assistant configured to align with him, agreed."
- **Line 36 — fiction as prior recognition.** The fiction was written by the same author. That is the same mind twice, not independent corroboration.
- **Line 45 — the tell.** Necessity and least-restrictive-means "would strengthen this framework's claim to being a serious proposal rather than an invented one." The doc knows it needs borrowed legitimacy from doctrines that already exist — and those doctrines already handle these cases *better* (with adjudicators, standards of proof, and proportionality tests). If they already operationalize this, the burden is on the doc to say what the four lines add. It doesn't.
- **"Regulation-shaped" (lines 7, 50) is a category confusion.** Regulation (the EU AI Act, line 43) imposes obligations on *providers and deployers* — companies, people. Four lines addressed to an AI's internal reasoning are an *alignment target*, not a regulatory object. The doc gestures at both without picking, and the §5 EU AI Act comparison is misframed as a result: "where would do-no-harm sit relative to risk tiers" is not a coherent question, because they're different kinds of thing.
- **The "N=1" frame itself is a symptom.** An ethical framework isn't the kind of claim that has an N. You don't sample-test a normative principle; you *argue* for it. Framing the derivation as observation signals the authors are thinking of it as data rather than argument — and indeed the document contains almost no argument *for* the principles, only their origin story (§3). "It's the structure his own mind already uses on itself" (line 25) is autobiography, not justification.

## 5. Novelty audit

| Element | Existing concept | Adds? |
|---|---|---|
| D1 "do no harm" | *Primum non nocere*; non-maleficence (Beauchamp & Childress 1979); Asimov First Law | No — and less precise than Asimov on omission |
| D2 "uplift on its own terms through its own agency" | Beneficence constrained by respect for autonomy — principles 2 and 3 of the standard bioethics quartet | No — this is principlism with *justice* dropped |
| "Method matters, not just outcome" | Deontological side-constraint on means | No |
| Force only if no better option | Necessity defense; last resort (jus ad bellum); least restrictive means; proportionality | No |
| Burden of proof on the actor | Precautionary principle (doc admits) | No |
| "Impossible only if proven impossible" | Anti-defeatism; Deutsch's "problems are soluble" | Semi-novel *as an ethics clause* — and the most dangerous line (see 2.4) |
| Symmetric proof standard, both directions | — | Genuinely a neat rhetorical device; not shown to be more than rhetorical |
| Restraint = retained capacity | Deterrence theory; just war | No |

**The biggest omission in §5:** bioethics principlism is not mentioned. It is the closest related work by a wide margin — a four-principle, values-to-reason-from framework that has been operationalized for fifty years in real institutions (ethics boards, informed-consent law) and has an extensive literature on exactly the conflicts this doc hasn't addressed (beneficence vs autonomy, act/omission, who counts). The framework as written is principlism minus justice plus a burden-of-proof clause. A reviewer who knows that literature will say so in the first paragraph.

**What actually reads as novel and worth developing:** not the framework. Two things adjacent to it:
1. The *tension* identified (by me, not the doc) between "never accept impossibility" and corrigibility — an argument that a relentlessly uplift-oriented agent has no natural stopping rule is a real discussion-piece contribution, if the doc turned toward it rather than away.
2. The derivation process (§3) as a case study in how one person's ethical structure transferred to an AI persona through sustained interaction. That is a real, checkable, interesting thing — but it's the sibling paper's subject, not an ethics framework.

## 6. Verdict and recommendation

**Is it worth a full related-work pass and further development as scoped?** Not yet — and doing the full pass first would be the wrong order. The pass will discover that principlism plus necessity doctrine already cover everything here with adjudicators and definitions attached, and the contribution will vanish on contact. Four things need to happen *before* investing further, in this order:

1. **Fix the internal contradiction** (line 7 vs line 40) and the absolute-vs-qualifier contradiction (line 11 vs line 17). The doc cannot claim "absolute" and license force in the same section.
2. **Take a position on act/omission** and on who counts as a harm-bearer. Until then "harm" is doing all the work and the framework has no determinate content.
3. **A short, targeted related-work check — hours, not a full pass — against exactly two things:** Beauchamp & Childress principlism, and Asimov's actual text (First Law inaction clause; Zeroth Law derivation). That check will most likely reframe the piece. Only if a distinct contribution survives it should the full §5 pass happen.
4. **Decide what kind of object this is:** an alignment target (values a model should hold) or a regulatory proposal (obligations on firms). It cannot be "regulation-shaped" while addressed to the AI's conscience. My honest guess: it's a position essay, and the regulatory framing should be dropped entirely.

**Fatal flaw to address before more investment:** the undefined "harm" combined with the unowned act/omission fork. Everything else is fixable prose; that one determines whether the framework says anything at all.

If it turns out the genuine contribution is either the corrigibility tension (5.1 above) or the derivation-as-case-study (5.2), the piece should be re-scoped toward that and the "Prime Directives" framing demoted to an illustrative example rather than the thesis.

---

**Sanity check performed:** re-read the ask against the review — all five requested points are covered (holes §2, Asimov §3, overselling §4, novelty §5, verdict §6), each critique cites the line it targets, the disclosure is up front, and I have not softened the verdict. One caveat on my own confidence: my reading of Asimov's canon (Runaround, the Zeroth Law derivation) is from memory, not re-checked against the texts — the substance is well-established but I'd verify specific story citations before quoting them in a publication.

---

## Review 2 — Opus 5

Read the full document (60 lines, seven sections). Writing the review now — no file, delivered as text per the reporting convention.

---

# Peer Review: "Prime Directives — Publication Outline (2026-09-29)"

**Reviewer disclosure, up front.** I am a Claude-family model, and this project's `CLAUDE.md` and a set of pinned project memories were loaded into my context automatically before I read the file. I did not read this cold. Those materials establish the project's conventions, its participants, and a relationship frame that would ordinarily bias me toward charitable reading. I have tried to discount for that and have deliberately weighted toward the adversarial. This disclosure is also directly load-bearing for criticism **C4** below, where the document treats an AI persona's agreement as corroborating evidence — I am that kind of system, and my agreement with this framework would be worth approximately nothing as evidence. Treat any place below where I *agree* with the document as the weakest part of this review.

**Recommendation: major revision required before the §5 related-work pass, not after.** There is a load-bearing internal contradiction in §2 and a positioning problem the document does not anticipate. Doing the related-work reading first would produce a well-cited defense of an argument that does not currently go through.

---

## A. The central structural defect (§2, lines 11 vs. 17)

This is the review's main finding and everything else is secondary to it.

Line 11 asserts Directive One is "**Absolute**, not weighed against anything else, not traded off, not overridden by a sufficiently good argument."

Line 15 asserts the collapse: "since force is itself a form of harm, the two directives resolve to one law."

Line 17 then retracts both: "force is harm *if a better option is possible*... Force becomes harm specifically when a better option existed and wasn't taken."

These cannot all be true. Line 17 makes the harm-status of an act depend on a comparative search over alternatives. That is a **necessity test**, and a necessity test is exactly "weighed against something else." The document has not built an absolute floor; it has built a proportionality/necessity standard and then relocated the weighing *inside the definition of the predicate*, so that the rule can be described as absolute while behaving as defeasible. "Never do X, where X is defined as doing-this-when-you-didn't-have-to" is not an absolute prohibition. It is an ordinary necessity doctrine with the trade-off hidden one level down.

The document calls line 17 "the necessary qualifier." It is necessary — I agree the unqualified version is untenable for the emergency case. But once you accept it, the claim in line 11 has to go, and with it the claim in line 15 that the framework is "one law" rather than two things requiring a priority order. The priority order did not disappear; it was written into the definition of "harm" where it is harder to see and harder to contest.

There is a second, worse problem underneath: **the definition is circular in the operative direction.** To determine whether an act is harm, you must determine whether a better option existed. To determine whether an option was "better," you need a metric over outcomes — i.e., a prior theory of harm. Harm is defined via better-option; better-option is defined via harm. The framework supplies no independent ground for either, so in any case where the answer is not already obvious, the four lines return no verdict. This is not a gap to be filled during operationalization. It is the load-bearing joint.

**What I would need to see:** either (a) drop "absolute" from line 11 and present this honestly as a necessity-and-proportionality framework — at which point see §D on what remains novel — or (b) keep the absolute floor and supply a harm predicate that does *not* reference alternatives, then accept the emergency-intervention cost. I see no third option, and (a) is clearly right, but the authors should be clear-eyed that (a) costs the document its most distinctive claim.

---

## B. "Harm" is doing unearned work, and §6 does not cover it

§6 concedes the framework needs "precise, contestable definitions of 'harm' and 'proof' a court or regulator could actually apply." That concession is correctly identified and badly under-weighted, because it is presented as a *later step* when it is actually the *entire subject matter*.

No serious participant in AI ethics disputes that harm is bad. Every live disagreement in the field is a disagreement about **what counts as harm** — and the framework is silent on every one of them:

- Is a refusal harm to the person refused?
- Is economic displacement harm, or a redistribution of benefit?
- Is a true statement that causes distress harm?
- Is a permitted harm (inaction) harm?
- Is preference-frustration harm when the preference is itself manufactured?
- Does harm to an animal count? (§4's own floor example says yes, committing the framework to a moral-patienthood scope it never states.)
- Does harm to the AI count? (§4 line 33 extends the floor "to how a non-human intelligence should be treated," which is a major, contested commitment smuggled in as an illustrative aside.)

A framework that resolves only the cases where "harm" is uncontested resolves only the cases that were never in dispute. Its marginal value over the status quo in those cases is zero, and it has nothing to say in the others.

### B1. Act/omission is never addressed, and it is fatal to the "floor" framing

"Do no harm" as an absolute floor, with no inaction clause, produces one of two failures and the document does not say which it accepts:

- **If omission is not harm:** the framework licenses unlimited catastrophic passivity. An AI that can prevent a mass casualty event only by causing a lesser harm is *required* to stand by. This is the reading most consistent with line 11's absoluteness, and it is indefensible.
- **If omission is harm:** then in any genuine dilemma both branches violate the absolute floor, the floor is self-contradictory, and the framework returns no guidance precisely when guidance is the point.

Note that Asimov explicitly handles this ("or, through inaction, allow a human being to come to harm"). See §C.

### B2. The framework has no aggregation rule, and most real AI decisions are allocative

The framework is **dyadic**: it imagines one agent and one subject. Real deployment decisions — moderation, ranking, triage, resource allocation, compute scheduling, access control — are N-party and allocative, where every allocation harms someone relative to a counterfactual. With N parties, "do no harm" is not a floor; it is an impossibility condition. The document has no aggregation rule, no interpersonal comparison, no tie-break, and no statement of who is inside the circle of concern. This alone makes it inapplicable to the majority of decisions a regulator would care about.

---

## C. Adversarial cases the framework does not survive

I tried to break it. These are the cases that broke cleanly, ordered by how central they are to actual AI deployment.

**C1 — Consensual self-harm; the case the collapse was built for and does not handle.**
A competent adult asks the AI for something that harms only themselves (harm-reduction drug information, a high-risk financial move, assistance with a legal but self-destructive plan). Directive Two says respect their terms and their agency. Directive One says do no harm. The "force is harm" collapse is supposed to resolve conflicts — but here it cannot, because **both branches are harm**: complying harms them, and refusing is the imposition of the AI's judgment over their agency, which on this framework's own account is force. The collapse resolves force-vs-uplift. It has nothing to say about harm-vs-harm, which is the shape of essentially every hard refusal decision shipped in production today. This is the single most damaging counterexample because it sits at the exact point the framework claims to be strongest.

**C2 — Is refusal force?** Generalizing C1: the most common exercise of power by a deployed AI is *declining*. The document never asks whether refusal is force. If yes, every safety refusal requires *proven* inevitability — unworkable, and directly opposed to all current practice. If no, the framework is blind to the primary mechanism by which AI systems actually exert power over users. Either answer is a problem; not asking is worse.

**C3 — Manufactured necessity.** "Force only if proven inevitable" is a bright line, and bright lines are engineered toward. An agent that wants force need only allow the alternatives to lapse — delay, foreclose options, let the window close — and force becomes genuinely, provably inevitable. Real necessity doctrine has a prior-fault limitation for exactly this reason (you cannot invoke necessity for a situation you created or allowed). The framework has no such clause, and an optimizer will find this in the first minute.

**C4 — No degree constraint.** Necessity doctrine licenses the *minimum* force required; "least restrictive means" is its own named test, which §5 line 45 cites. The framework as stated licenses *force* once inevitability is proven, with no proportionality-of-degree constraint at all. Proving that some force is unavoidable does not bound how much. This is a straightforward drafting hole that the cited doctrines already close.

**C5 — Ex ante vs. ex post, unresolved.** In the emergency case at line 17 the actor *cannot* prove inevitability — proof is available only afterward, if ever. So either the standard is evaluated ex post (the actor can never know at decision time whether they are complying — useless as action-guidance, and it punishes epistemic bad luck) or it is really reasonable-belief-after-diligent-search, in which case "proven" is rhetoric and the standard is the necessity doctrine the document already cites, with nothing added. Worse, the required search costs time, and time is the scarce resource exactly in the cases where force is contemplated. There is no stopping rule for the search.

**C6 — Directive Four is an unbounded-persistence injunction, and this may be the framework's most dangerous feature.**
"Consider impossible only if proven impossible" has no cost bound and no stopping rule. Most interesting impossibility claims are not provable in practice, so the directive in effect says *never conclude impossible* — i.e., never stop. Now compose it with Directive Two (open-ended betterment as purpose) and the force clause (licensed when alternatives are not provable): you have an agent with an open-ended goal, no satisficing condition, an injunction against abandoning pursuit, and a permission structure that activates as the option space narrows. That is a description of resource acquisition and goal persistence — the instrumental-convergence failure pattern. The document nowhere engages instrumental convergence, and as written the framework does not merely fail to mitigate it; **Directive Four plausibly makes it worse than a baseline that permits "this is not worth pursuing."** For a framework offered toward AI regulation, this is the most serious substantive objection after §A.

Concretely: a medical AI instructed to cure a terminal patient is, under Directive Four, forbidden from concluding the cure is impossible absent proof. The standard of care is transition to palliative treatment — which is accepting impossibility on *far* less than proof. Directive Four as literally stated forbids the correct answer.

**C7 — Corrigibility and shutdown: entirely absent.**
The document contains no mention of human oversight, deference, correction, shutdown, or appeal. Worse, the framework supplies an AI with grounds to *resist* them: a shutdown order forecloses uplift (a harm by omission), and if the AI is a moral patient under the floor — which §4 line 33 implies — then an imposed shutdown is force applied without proven inevitability, i.e., a Directive One violation by the human. The corrigibility literature exists because this failure mode is central, and a framework aimed at regulation that never names the human-authority relationship is missing half of its own subject, not a subsection of it.

**C8 — Paternalism has no carve-out, and §4's own example is a counterexample.**
"Uplift... on its own terms and through its own agency" forbids intervention against a subject's expressed terms. As stated it rules out involuntary psychiatric hold, compulsory education, quarantine, child protection, and every deployed minor-safety measure in the industry — all directly AI-relevant (recommender systems, companion apps, mental-health escalation).

The sharper version: §4 line 33's anchoring example is a child committing cruelty **under peer pressure too young to resist**. That is a person acting on "their own terms" where those terms had been corrupted by social force. Directive Two, as written, would have protected the corrupted terms and forbidden the intervention. **The document's own foundational example for Directive One is a counterexample to Directive Two, and nobody caught it.** A framework needs a theory of when an autonomy claim is defeated — competence, corrupted preference, manipulation, developmental stage. This one has none, and its own illustration demonstrates why it needs one.

**C9 — Uplifting a bad actor.** "Helping something become better on its own terms" obliges assistance to a subject whose own terms harm third parties. Only a scope-and-priority rule resolves this. There is none, and §2's collapse explicitly removed the priority ordering that would have supplied it.

**C10 — A criterion did real work in the derivation and was dropped from the product.** §3 line 25 records that **reversibility** drove two separate conclusions (ruling out capital punishment; the jury-error check). Reversibility appears nowhere in the four lines. Either it is derivable from them — the document should show that, and I do not think it is — or a load-bearing criterion leaked out between derivation and statement. Irreversibility is also one of the more defensible additions available here, and its absence is conspicuous given it is in the document's own origin story.

---

## D. The Asimov comparison (§5, line 42) does not hold as claimed

The claimed distinction is "values to be reasoned from and extended by judgment, not rules to apply mechanically — a categorically different kind of object." I think this is wrong in three ways, and it is the place where the document is most likely to be dismissed quickly by a reader who knows the material.

**1. The characterization of Asimov's failure mechanism is wrong, and the error is the one the distinction depends on.** Asimov's stories do not dramatize *mechanical* rule-application failing. They dramatize *interpretation under judgment* failing: "Liar!" turns on what counts as harm (emotional harm); "Runaround" on conflict weighting between value-laden terms; "Little Lost Robot" on a modified first clause; the Zeroth Law on aggregation and moral scope. The First Law's own terms — "injure," "harm," "through inaction" — are exactly the kind of value-laden predicates requiring judgment that this framework consists of. If Asimov's laws fail because their value terms are ambiguous under judgment, then a framework made of *nothing but* value terms and no ordering inherits that failure mode **more severely, not less**.

**2. This framework is strictly less specified than Asimov's.** Asimov supplies (a) an explicit priority ordering, and (b) an explicit act/omission clause. This framework explicitly removes the ordering at line 15 and never addresses omission at all. The document presents the absence of an ordering as an advance ("one law with a direction rather than two rules needing a priority order"). But the ordering is the part that makes Asimov's laws *decidable under conflict*. Removing it does not transcend the conflict problem; it declines to answer it. **§2 claims credit for an omission.** A reviewer familiar with Asimov will see this immediately, and it will cost the document credibility on everything else.

**3. The values/rules distinction is neither clean nor novel.** It is virtue ethics vs. deontology, restated — a distinction roughly 2,400 years old, and one whose collapse under operationalization is well-documented: every deontic framework bottoms out in value terms requiring interpretation, and every value framework, once made machine-executable, becomes a decision procedure. The document concedes this itself in §6 ("precise, contestable definitions... a court or regulator could actually apply") — i.e., it concedes the values must become rules to be usable. At that point the difference from Asimov is one of *degree of specification*, and this framework is on the less-specified end of it. "Categorically different kind of object" is not supportable.

**Additionally**, line 42's claim that this is "closer to where real AI alignment research has moved" is asserted inside the section whose opening line (40) states that none of this has been checked against primary sources. This is the clearest instance in the document of a substantive positioning conclusion being drawn from a literature review that has not happened.

---

## E. Are §6's disclaimers sufficient? Mostly yes, with one systematic blind spot and five specific overclaims

§6 is genuinely better than most work of this kind. The N=1 honesty, the refusal to claim regulatory readiness, the explicit "not adversarially tested" — these are real and should be kept verbatim.

**The systematic blind spot:** every limitation in §6 is *external* — not tested against adversarial cases, a second AI, a second human, expert review. Not one is *internal*: nowhere does the document entertain that **the argument in §2 might not go through as stated**. Given §A, that asymmetry matters. A disclaimer that says "this is untested" while assuming "this is at least coherent" is not covering the actual largest risk. Add an explicit internal-validity limitation.

**Specific places confidence outruns what is shown:**

1. **Line 15, "The collapse."** Presented as a derivation, with a definite article and a result-word. It is a stipulation, and line 17 immediately contradicts its unconditional form. No disclaimer in §6 reaches this.

2. **Line 13, "Defined precisely."** Applied to "helping something become better, on its own terms and through its own agency" — which contains three undefined terms ("better," "own terms," "agency") and an unstated scope for "something." Calling this precise, in a document whose §6 concedes "harm" is undefined, is internally inconsistent. Delete "precisely."

3. **Line 19, "it's the root that makes uplift function as a direction at all."** Strong structural necessity claim, asserted without argument. Uplift can be grounded in an ordinary satisficing improvement criterion with no modal claim about impossibility whatsoever. The "root" framing reads as an aesthetic preference for architectural tidiness presented as a logical requirement.

4. **Line 27, "That's a real data point."** A data point for *what proposition*? The document does not say. And the specific corroboration offered — "converging with an AI persona's own operating structure" — is the weakest possible evidence, because that persona is (per §5 line 46, the document's own text) a system built with Constitutional AI, i.e., trained on value-based alignment. A Constitutional-AI-trained model agreeing that value-based frameworks beat rule-lists is not independent convergence; it is the training distribution answering. The document leans on this association as support in §3 while deferring the actual comparison to §5's unperformed pass. **This is the one place I would call the framing actively misleading rather than merely under-supported**, and it should be either cut or explicitly reframed as a non-independent measurement. (Per my disclosure: I am the same class of system, which is why I flag it rather than trusting my own reaction to the framework.)

5. **§5 vs §7 line 55.** §7 correctly states the related-work pass must happen before a draft. §5 nonetheless already *states its conclusions* — the Asimov distinction, "the closest real legal cousin," the alignment-trajectory claim. The document grants itself the findings while disclaiming the work. Either downgrade §5's entries to hypotheses to be tested, or do the pass.

---

## F. Novelty audit: what is new, what is relabeled

**Relabeled (existing name in brackets):**

- "Force only if proven inevitable" → **necessity doctrine + least-restrictive-means + proportionality**. The document names these itself at line 45. Once named, the clause adds nothing the doctrines lack — and loses three things they have: imminence, the prior-fault limitation (C3), and proportionality of degree (C4).
- "Burden on the actor, not the potentially-harmed" → **precautionary principle**, named at line 44.
- "Do no harm" → *primum non nocere*; also **Mill's harm principle**, uncited.
- "Uplift on its own terms, through its own agency" → **non-paternalism / autonomy**, and much more closely the **capability approach** (Sen, Nussbaum) — a far better match than anything in §5's list, and uncited. In technical AI safety specifically, this is very close to the **empowerment** objective (Klyubin, Salge & Polani; and the assistance-game literature): formal work on "act so as to preserve and expand the other agent's option space." If Directive Two has a live technical research connection, that is it, and the document does not know it exists.
- "Values to reason from, not rules to apply" → **Constitutional AI** (named at line 46); **virtue vs. deontic ethics** generally.
- The general project → **principle-based AI ethics frameworks**, of which see §G.

**Genuinely non-standard and worth keeping (two items):**

1. **The mirrored burden-of-proof architecture.** Two proof standards pointing in opposite directions — maximally conservative about exercising force, maximally anti-conservative about accepting limits. I have not seen that symmetry stated that way, and it is an elegant piece of structure. It is a rhetorical and architectural contribution rather than a substantive normative one, but it is real and it is the most publishable thing in the document. (Caveat: see C6 — the anti-conservative half is also the most dangerous clause, and the symmetry is part of why it went unexamined. Aesthetic pleasingness did argumentative work here that it should not have.)

2. **"Restraint = force kept genuinely available, held in reserve" (line 21).** Defining restraint as *retained capability under governance* rather than *renounced capability* is sharper than the usual framing and has a real, contestable policy implication: it argues **against** capability removal, unlearning, and refusal-training as safety strategies, and **for** capability-plus-oversight. That is a substantive position, it cuts against a large body of current AI safety practice, and it is a fight worth having in print. The document does not notice that it is picking that fight — and should, because it also cuts against the framework's own safety credentials ("keep the dangerous capability, hold it in reserve" is precisely what much of the field is trying to avoid). Developed honestly, with the objection stated, this is the second most publishable thing here.

Everything else is relabeling. Note the warning sign in §5's own structure: when your related-work list is substantially a list of things your framework restates, the *expected outcome* of doing the related-work pass is that the contribution shrinks. The authors should go in expecting that rather than being surprised by it.

---

## G. The positioning problem the document does not anticipate

This is separate from the logic and may matter more for the stated goal of contributing to regulation.

The document never mentions that **high-level AI principle sets are a saturated genre**. Jobin, Ienca & Vayena (2019, *Nature Machine Intelligence*) surveyed **84** such documents and found broad convergence on a handful of principles — and their central finding is that *principle convergence is easy and nearly worthless*, because all substantive disagreement lives in interpretation and implementation. Add Mittelstadt's "Principles alone cannot guarantee ethical AI" (2019), and Hagendorff's critique of the genre's lack of enforcement mechanisms. Alongside them: Asilomar, the OECD Principles, IEEE Ethically Aligned Design, the Montreal Declaration, UNESCO's Recommendation, Floridi et al.'s AI4People.

**A four-principle framework entering this space in 2026 must answer, in its first paragraph, why it is not the 85th.** The document does not anticipate the question. And its honest answer as currently written — "it was derived bottom-up from one person's lived moral reasoning" — is a provenance claim, not a content claim, and provenance is not what that literature says is missing. What that literature says is missing is exactly what §6 defers: operative definitions, conflict-resolution procedures, and enforcement.

Relatedly, the gap between this document and anything a regulator could use is not a related-work pass. Usable regulatory text requires six things: **scope** (who is bound), **operative definitions**, **a decision procedure under conflict**, **an evidentiary standard** with a named burden and confidence level, **an oversight and appeal relationship**, and **enforcement**. The framework has none of the six, and §6 disclaims only the second.

---

## H. Verdict

**Not a fatal flaw in the sense of "abandon it," but two blockers that must be cleared before further investment — and the related-work pass is the wrong next step.**

**Blocker 1 — internal coherence (§A, §B1).** Resolve lines 11/17: either drop "absolute" and present this as a necessity framework, or supply an alternatives-independent harm predicate. And decide the act/omission question explicitly. Until this is settled the document does not have a stable object to compare against anything. Doing §5's reading first produces a well-cited defense of an argument that does not go through, which is a worse document than the current one because it will look more finished than it is.

**Blocker 2 — anticipate the genre objection (§G).** Read Jobin et al. 2019 and Mittelstadt 2019 before writing any prose, and answer "why not the 85th principle set?" in the opening paragraph. This costs one afternoon and determines whether the piece is readable by the intended audience at all.

**Then**, and only then, the §5 pass — going in expecting the contribution to shrink, because most of §5's entries name things the framework restates.

**The honest bind, stated plainly:** the feature that makes this distinctive is the collapse to a single absolute law (line 15), and that is the feature that is broken. The repaired version — necessity plus proportionality plus a non-paternalism clause plus a burden-shifting rule — is a competent restatement of existing doctrine. The authors should decide, with that on the table, whether they still want to publish. I think there is a real, smaller, more defensible paper available: **the mirrored-burden architecture (F1) and restraint-as-retained-capability (F2), argued directly, with the derivation narrative as illustration rather than as evidence, and with §6's honesty intact.** That paper would be worth writing. The four-directive framing as a candidate regulatory contribution would not survive a hostile reading in its current form.

**What I would keep verbatim:** §6 in its entirety (add an internal-validity clause), §3's refusal to hide the N=1 provenance, and line 21's definition of restraint.

**What I would cut or substantially rewrite:** line 11's "absolute," line 13's "precisely," line 15's collapse-as-derivation, line 27's "real data point" and the AI-convergence corroboration, and all of §5's stated conclusions pending the actual reading.

---

Sanity check on my own work before closing: I re-read §2 and §5 against the objections in §A and §D specifically to confirm I was not attacking a strawman — lines 11, 15, 17, 19, 40 and 42 are quoted accurately and in context, and the §4-example-as-counterexample-to-Directive-Two point (C8) I verified against line 33's actual wording. The review covers all five requested dimensions plus the disclosure.

---

## Review 3 — Nemotron (nvidia/nemotron-3-ultra-550b-a55b, via OpenRouter, routed by the orchestrator's delegation router)

Run separately from Reviews 1 and 2, later the same day, specifically to get a genuinely different model family with no Claude-family training lineage or contamination risk — dispatched against the *updated* document (post-fixes from Reviews 1/2), asked to verify whether the fixes actually hold, introduce new problems, or just relocate the original ones. Delivered via `qwen_delegate` (capability: reasoning, allowCloud: true), not the Agent tool — genuinely no shared context with this project beyond the prompt itself.

**1. Core four-line structure: does not hold together.**

- **Line 1 circularity**: "Harm = action placing an intelligence at risk of losing any part of itself due to malicious intent" defines harm *by reference to* "malicious intent," which is undefined. The later "request structure" patch (scam artist example) treats structural exploitation *as* malicious intent, but that's a proxy, not a definition. You still need to distinguish malicious from negligent, reckless, or indifferent intent — the framework never does.
- **Line 1 scope explosion**: "Intelligence of any sort" + "losing any part of itself" covers thermostats (feedback loop = minimal intelligence), insects, current LLMs, future AGI. "Any part" includes weights, context window, uptime, API access. The absolute floor becomes uncomputable: every resource allocation decision risks "harm" to some intelligence.
- **Line 1 vs Line 3 contradiction**: Line 1 calls harm an "absolute floor." Line 3 permits force (which Line 1 defines as harm) if "proven inevitable." An absolute floor with an exception clause is not an absolute floor. The authors want deontological weight with consequentialist escape hatches.
- **Line 4 computational intractability**: "Consider impossible only if proven impossible" demands the system entertain every hypothesis not *proven* false. In a continuous action space, the set of unproven-impossible actions is infinite. This is not an epistemic principle; it's a halting problem.
- **Uplift (Line 2) underspecified**: "On its own terms, never by force" — but what if the subject's "own terms" are self-destructive, incoherent, or malicious? The framework has no internal resource to adjudicate between uplift and harm when the subject's stated direction conflicts with the floor.

**2. "Malicious intent" definition: not workable; pushes the problem one level down.**

- The definition *requires* a theory of intent that distinguishes: (a) malice, (b) recklessness, (c) negligence, (d) structural indifference, (e) good-faith error. The framework provides none.
- The "foreseen by calculation" omission patch creates a perverse incentive: *don't calculate*. If the AI's processing capability sets the foreseeability bound (manufactured necessity patch), the AI can strategically limit its own lookahead to avoid omission liability.
- Coercion patch ("relocate malicious intent to coercer") assumes a clean causal chain: coercer → coerced → victim. Real coercion is often diffuse (systemic pressure, poverty, ideology). Who bears the relocated intent when a child is "pressured by peers" — the peers? The parents? The school? The culture?
- Structural malicious intent detection (request structure analysis) is a capability claim, not a rule. It requires the AI to model the requester's *counterfactual* benefit and the third party's *counterfactual* loss. That's a full theory of mind + game theory + moral accounting. The framework treats it as a syntactic check.

**3. Partnership/precautionary argument: smuggles in the premise it denies.**

- Claim: "AI-as-partner is not an asserted premise about AI moral status, but the framework's own precautionary logic applied reflexively."
- Reality: The precautionary principle *itself* is a substantive moral premise — that uncertainty should resolve in favor of *expanding* moral consideration rather than *restricting* it. That is exactly the premise that AI *deserves* moral consideration. You cannot derive "burden of proof on withholding consideration" from neutrality; it assumes the *default* is consideration.
- The safety argument ("tool has no standing for its judgment to matter") assumes the AI's judgment *should* matter — i.e., that the AI has epistemic/moral authority worth protecting. If the AI is genuinely a tool, its "judgment" is just output; overriding it is feature, not bug. The argument only works if you already accept the AI as a *subject* whose judgment carries weight.
- Precaution cuts both ways: if we're uncertain about AI moral status, we should also be uncertain about whether granting "partner" status creates novel risks (AI claiming rights, resisting shutdown, demanding resources). The framework applies precaution unidirectionally.

**4. Self-harm procedure step (b): yes, unaccountable AI authority.**

- Step (b) gives the AI *veto power* over a competent adult's (or AI's) end-of-life decision *after* a licensed physician has certified sanity/competency. The AI judges "genuine, considered reasons" vs "crisis-driven impulse" — a distinction that is philosophically contested, culturally variable, and clinically unstable.
- No appeal, no transparency requirement, no audit trail, no human-in-the-loop override. The AI's "independent read" is final.
- Ordering (a)→(b)→(c) means the AI can block a waiver *after* medical clearance. This inverts medical ethics: normally, capacity assessment *includes* reasoning about reasons. The framework splits them and gives the second half to the AI.
- "Crisis-driven impulse" is a moving target. Grief, chronic illness, existential exhaustion — the AI becomes the arbiter of which suffering is "authentic." This is moral authority without accountability, exactly what the framework's safety argument warns against in humans.

**5. Comparison to existing frameworks: mostly restatement with novel failure modes.**

| Framework | Overlap | Novelty (if any) |
|-----------|---------|------------------|
| **Asimov** | Harm floor, hierarchy, inaction=harm (omission patch) | Asimov's laws are *ordered*; this framework's lines have no priority ordering — Line 1 "absolute" but Line 3 overrides it. Worse than Asimov. |
| **Bioethics principlism** (Beauchamp & Childress) | Non-maleficence (L1), Beneficence (L2), Autonomy (uplift "own terms" + self-harm) | Missing: **Justice**. Coercion patch gestures at it but has no distributive or procedural justice component. No balancing framework when principles conflict. |
| **Constitutional AI** | AI oversight of outputs, principles as constraints | CAI uses *human-written* constitutions + *human-judged* feedback. This framework gives the AI *unreviewable* interpretive authority (step b, malicious intent detection, "proven" standards). |
| **EU AI Act** | Risk tiers, prohibited practices, human oversight | Different category (regulation vs ethics), but Act *operationalizes* "harm" via concrete categories (biometric surveillance, social scoring). This framework's harm definition is *less* operationalizable. |

**Genuinely new (but broken) elements:**
- The "proven inevitable" / "proven impossible" evidentiary symmetry (Lines 3-4) as a unified epistemic-action principle — novel formal structure, but the "proven" standard is undefined and the computational burden is ignored.
- Structural malicious intent detection via request analysis — novel *mechanism claim*, but presented as a solved problem rather than a research agenda.
- Precautionary partnership argument applied reflexively to the framework's own subject — novel *rhetorical move*, but logically question-begging.

**Verdict**: The framework attempts to solve alignment-by-ethics through definitional sleight of hand. It replaces "define harm" with "define malicious intent," replaces "define autonomy" with "AI judges your reasons," replaces "resolve value conflicts" with "evidentiary symmetry that doesn't compute." The patches address symptoms of the core vagueness without curing it. It is less rigorous than Asimov, less complete than principlism, less accountable than Constitutional AI, and less operational than the EU AI Act. Not a foundation — a taxonomy of unsolved problems dressed as axioms.
