# Treatment plan document template

Build the .docx with the sections below, in this order. Use US Letter paper, 1" margins, and Calibri or Arial 11 pt. Put the draft notice in the header, and put the page number plus "Draft — for BCBA review" in the footer.

## Branding
- **Title block:** "LEAP Therapy" (Lead · Empower · Advocate · Play), with the document title *Individualized ABA Treatment Plan — Draft*.
- **Colors (use sparingly):** teal #1A9E92 for headings, navy #1D2B3A for body text, and a light sand #E8DDD3 fill for table header rows.
- **Logo:** if `svgleap.svg` or `LEAP-Black-Text@10x.png` is in the repo root, you may place the PNG in the header, about 1.2" wide.

## Sections

1. **Identifying information (de-identified)**
   - Learner alias, age, diagnosis and support level, communication modality, home languages, service settings, and recommended hours per week.
   - Leave blank lines for the BCBA name and credential, the plan date, and the funder, for the BCBA to fill in.

2. **Reason for referral and family priorities**
   - Summarize the caregiver's priorities in 2–4 sentences.
   - Quote the caregiver's own words with transcript timestamps.

3. **Assessment summary**
   - List the assessments used and their dates, e.g. Vineland (edition, form, respondent), ESDM Curriculum Checklist, caregiver interview and transcripts, and direct observation.
   - **Vineland table:** ABC and domains (standard score, percentile, adaptive level), then subdomains (v-scale, age equivalent, adaptive level). Add the Maladaptive index if one was given.
   - **ESDM table:** level for each domain, with the P/F and F items that drove the goals.
   - **Transcript findings:** 4–8 bullets of key themes, each with a timestamped quote.
   - **Strengths and interests.**
   - **Medical-necessity summary:** use `clinical_summary`.

4. **Skill acquisition goals**
   - Number the goals and group them by domain.
   - For each goal:
     - Title and priority
     - Goal statement
     - Baseline
     - Mastery criteria
     - Short-term objectives (numbered)
     - Evidence (italic quotes)
     - Target date

5. **Behavior reduction plan**
   - For each behavior:
     - Operational definition
     - Measurement
     - Baseline
     - Hypothesized function and its evidence
     - Reduction goal and short-term objectives
     - Replacement behavior goal(s)
     - Summary of antecedent, teaching and consequence strategies
     - Crisis note if safety-significant

6. **Caregiver training goals**
   - Each goal with its fidelity criterion and the routine it targets.
   - The BST plan and a proposed schedule, based on the stated availability.

7. **Coordination of care and referrals**
   - Everything from `clinician_flags` that concerns other providers.

8. **Items for BCBA verification**
   - The remaining `clinician_flags`: missing baselines, conflicting sources, and verifying garbled transcript lines.

9. **Signatures**
   - Blank lines for the BCBA, the caregiver (acknowledging review), and the date.

10. **Appendix — transcript evidence**
    - The evidence table, organized by theme.

Keep tables readable: header row shaded, no merged cells in the goal tables, and goal statements as normal paragraphs rather than inside table cells, so they can be copied into funder portals.
