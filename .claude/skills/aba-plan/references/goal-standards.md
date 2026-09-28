# Goal-writing standards

These match the guidance the BCBA Goal Assistant page sends to Claude, with more detail. Apply every rule to every goal.

## Anatomy of a goal

Each goal has these parts, and nothing can be left as a `[placeholder]`:

- **Condition / antecedent**: the situation, instruction, or materials, e.g. "When a preferred item is visible but out of reach during snack…".
- **Learner behavior**: observable and countable. Use verbs like *requests, points, imitates, completes, waits*. Avoid *understands, knows, appreciates*.
- **Criterion**: accuracy or rate plus duration of mastery, e.g. "80% of opportunities across 3 consecutive sessions" or "10+ independent requests per hour".
- **Generalization**: at least 2 adults, at least 2 settings, and varied materials, including caregivers.
- **Baseline**: current performance with its source, e.g. "Vineland Expressive v=7 (Low)", "ESDM P/F", "0 of 5 opportunities in the intake observation", or "caregiver reports daily at [00:04:44]". If no baseline exists, say exactly what to probe and when.
- **Short-term objectives**: 2–4 steps, for example prompted → reduced prompts → independent with one adult → generalized and maintained.
- **Evidence**: 1–3 transcript quotes with timestamps, observer notes, or scores.

Use the goal defaults in `interpreted_scores.goal_defaults` (mastery %, sessions, timeline, reduction target, fidelity %) unless the data justifies otherwise. If you deviate, say why in the rationale.

## Individualize

- **Match the communication modality in every expressive goal.** Write for AAC, PECS, or sign when that's the modality, and name the system.
- **Pick targets at the emerging edge.** Use ESDM P/F items first, then the earliest F items. Base Vineland targets on age equivalents, not only chronological age.
- **Use the learner's own reinforcers and interests.** For example, "during 'Baby Shark' song routines" rather than "during play".
- **Respect home languages.** If the family is bilingual, accept target responses in either language and involve every caregiver who is present.
- **Anchor goals in the family's routines.** Use the routines the caregivers named, such as leaving the house, stopping the tablet, or the grocery store.

## Priority

1. **Safety**: elopement, severe aggression or self-injury, pica, water or road safety.
2. **Caregiver-stated priorities**, especially the ones stated in their own words in the transcripts.
3. **Pivotal skills**: functional communication and requesting, imitation, joint attention, play, and tolerating "wait" or "no".
4. **Other significant deficits** from the Vineland or ESDM results.

## Behavior goals

- **Operational definition**: restate it so that two observers would agree.
- **Reduction goal**: baseline → target, for example an 80% reduction held for 4 consecutive weeks across settings. Include an interim objective at 3 months.
- **Replacement behavior**: every reduction goal gets a replacement that matches its function:
  - attention → appropriate bids for attention
  - escape → requesting a break or help, plus task tolerance
  - tangible → requesting, plus tolerating delay or denial
  - automatic → a matched sensory alternative or enriched environment
- **Unknown function**: don't guess. Add "FBA needed" to `clinician_flags` and write the replacement goal as pending.
- **Safety-significant behavior**: note that the BIP needs a crisis or safety protocol.
- **Use the least restrictive procedures.** Never write goals that rely on punishment or restraint.

## Compassionate, assent-based practice

- **Don't suppress harmless autistic behaviors.** Stimming, avoiding eye contact and preferring solitary play are not goals unless they cause harm or block learning, and the data shows that they do.
- **No compliance for its own sake.** Goals should increase the learner's autonomy, communication, independence, participation and quality of life.
- **Respect assent.** Where it applies, include teaching the learner to refuse or protest appropriately, for example saying or signing "no" or "all done".

## Caregiver training goals

- **Use Behavioral Skills Training.** Instruction → modeling → rehearsal → feedback, with a fidelity criterion (default at least 90% across 3 consecutive observations).
- **Build goals around the family's real routines** and the availability they stated.
- **Include what's relevant:** delivering reinforcement, creating communication opportunities, antecedent supports for difficult routines, BIP implementation, data collection (agreement with RBT data, i.e. IOA, at least 90%), and ESDM joint activity routines when ESDM data exists.

## Scope and referrals (clinician_flags)

Flag, rather than write goals for, anything outside ABA scope or needing another provider:

- **Feeding and oral-motor concerns**: SLP, OT or feeding specialist.
- **Sleep with possible medical causes**: pediatrician.
- **Motor delays**: OT or PT.
- **Suspected hearing or vision issues.**
- **Mental health concerns.**

Also flag missing baselines and conflicts between sources.

## Style

- **Plain language** a caregiver can read. Define any jargon the first time it appears.
- **Refer to the learner by the alias only.** Use they/them if a pronoun is needed.
- **One goal per skill.** Don't bundle unrelated skills into one goal.
