## Baglan Zharkenov

Product manager moving into AI products. 3 years in product management,
2 years in digital marketing, former NASA intern.

I care about the part of AI products that is easy to skip: deciding what
"good output" means before shipping, and being able to prove it moved.

---

### Selected work

**[ai-answer-grading-case-study](https://github.com/baglanvv/ai-answer-grading-case-study)** —
product and AI product work on a B2B corporate training platform, as sole
product owner. The platform's core claim rested on learners writing answers in
their own words, and nothing responded to what they wrote; I specified and
shipped LLM validation across ~10 exercise types. Also states what I got wrong:
shipped without an eval harness, and wrote the grading criteria myself — the
one arrangement that guarantees nothing can tell you your criteria are wrong.

**[churn-reason-eval](https://github.com/baglanvv/churn-reason-eval)** — an
evaluation harness for an LLM classifier in EdTech retention, built to decide
whether a model should replace rules. It returned a more useful answer: a $0
keyword baseline scores 0.958 on the held-out half, and at n=48 the set cannot
detect any improvement over it. Reports dollar regret rather than accuracy,
because the expensive error is discounting a learner who already finished.
Ships with the contamination guard that caught my own test-set leak.

**[retention-save-flow-prd](https://github.com/baglanvv/retention-save-flow-prd)** —
the spec that consumes that eval. Routes cancelling learners to the action
matching their reason, ships rules instead of a model, and treats abstention as
a first-class branch. Includes the sensitivity model showing that classifier
accuracy is *not* the bottleneck — the counterfactual-return rate is.

**[duolingo-max-teardown](https://github.com/baglanvv/duolingo-max-teardown)** —
a teardown built from SEC filings rather than press coverage. Finds that
Duolingo has moved two of Max's three original AI differentiators down into
cheaper tiers, while bookings growth fell to 8% against 18% revenue growth.
Every figure reproducible from the included script.

### How I work

- **Specs** — problem statement, non-goals, and success metrics before solutions
- **Evals** — an LLM feature without a scored test set is a demo, not a product
- **Instrumentation** — define the metric at design time, not after launch
- **Assumptions** — written down, labeled, and sensitivity-tested, because the
  cost model is load-bearing and usually unexamined

### Toolkit

- **Analytics** — `SQL` · `Python` · `Amplitude / GA4` · `Metabase / Tableau` · `Excel`
- **Product** — `Jira / Linear` · `Figma`
- **Growth** — `Google Ads` · `Meta Ads`

---

📍 Kazakhstan · open to relocation / remote &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/baglan-zharkenov-10a3631a8/)
