# Source: https://join-staging.com/en/glossary/ai-bias-in-hiring

[Back to glossary](https://join-staging.com/en/glossary)

## Where the bias comes from

Three sources, in approximate order of frequency:

- **Training data**: the model learns from historical hiring decisions. If historical decisions favored one demographic, the model treats that as the right answer and reproduces it.
- **Feature selection**: which signals the model is given access to. Excluding “name” doesn’t help if “graduation year” is a proxy for age, or “neighborhood” a proxy for socioeconomic status.
- **Feedback loops**: a model trained on past hires, where past hires were filtered by past biased decisions, learns the bias compound — every retraining widens the gap.

The Amazon hiring-AI case (2018) is the textbook example: a model trained on a decade of mostly-male hires learned to penalize “women’s” — as in “women’s chess club captain” — and the model was killed.

## What audits actually catch

Bias audits are required for high-risk AI systems under the [EU AI Act](https://join-staging.com/en/glossary/eu-ai-act-in-hr). They typically check:

- **Disparate impact**: do candidates from protected groups advance at the same rate?
- **Equalized odds**: is the false-rejection rate the same across demographics?
- **Counterfactual fairness**: would the same candidate get a different score with a different name or photo?

No audit catches everything. The honest read: audits reduce known biases; emergent biases require ongoing monitoring.

## Mitigation that works

- **Human review of every advance and every rejection**, especially around the threshold.
- **Diverse training data**, where the dataset reflects the candidate pool you want, not just the one you have.
- **Regular re-audits**: every quarter, not once at launch.
- **Vendor transparency**: ask what data trained the model, what fairness metrics were tested, when the last audit happened.

## Where Join fits

Join’s AI features are audited per [EU AI Act](https://join-staging.com/en/glossary/eu-ai-act-in-hr) requirements; bias-audit results are publicly summarized at [trust.join.com](https://trust.join.com). See the [features page](https://join-staging.com/en/features).

Start today

## Start your 14-day free trial and make hiring your advantage.

[Sign up](https://join-staging.com/auth/signup/company) [![](https://join-staging.com/_astro/cta-01.qBWewP_G_Z2arhKX.webp)![](https://join-staging.com/_astro/cta-02.D5MVGSn1_Z2a0V4Q.webp)Request a demo](https://join-staging.com/en/book-a-demo)