# Source: https://join-staging.com/en/glossary/ai-candidate-matching

[Back to glossary](https://join-staging.com/en/glossary)

## What “matching” means in practice

The model produces a similarity score between a candidate and a role. The score is shown to the reviewer alongside an explanation: “matches on Python, 5 years backend, EU [work authorization](https://join-staging.com/en/glossary/right-to-work); weak on team-leadership signals.”

Good matching tools expose what drove the score. Black-box matching tools that show only a number are less useful — the reviewer can’t argue with a number; they can argue with an explanation.

## The two layers

- **Skills match**: surface-level keyword and skill overlap. Fast, explainable, prone to false negatives (a candidate whose CV uses “TypeScript” instead of “JS” looks like a worse match than they are).
- **Semantic match**: embedding-based comparison of CV and [role description](https://join-staging.com/en/glossary/job-description) as text. Catches relevant experience the skills layer misses, at the cost of being less explainable.

Most modern matching combines both, with a hybrid score.

## Where it sits in the funnel

Candidate matching feeds two upstream uses:

- **Inbound ([AI screening](https://join-staging.com/en/glossary/ai-screening))**: rank applications against the role.
- **Outbound ([AI sourcing](https://join-staging.com/en/glossary/ai-sourcing))**: surface passive candidates whose profiles match the role.

Same mechanism, different funnel stage.

## What candidate matching is not

It is not the hiring decision. A high match score means “worth a real conversation,” not “make an [offer](https://join-staging.com/en/glossary/offer-letter).” Treating it as the latter is the most common failure mode of AI in hiring.

## Where Join fits

Join exposes match scores with per-dimension explanations, so the reviewer always sees what the AI is keying on. The reviewer’s judgment stays primary. See the [features page](https://join-staging.com/en/features).

Start today

## Start your 14-day free trial and make hiring your advantage.

[Sign up](https://join-staging.com/auth/signup/company) [![](https://join-staging.com/_astro/cta-01.qBWewP_G_Z2arhKX.webp)![](https://join-staging.com/_astro/cta-02.D5MVGSn1_Z2a0V4Q.webp)Request a demo](https://join-staging.com/en/book-a-demo)