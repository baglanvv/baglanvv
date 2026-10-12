## Baglan Zharkenov

Product manager moving into AI products. Three years in product management, two
in digital marketing, former NASA intern.

The part of AI products I care about is the part that's easy to skip: deciding
what "good output" means before you ship, and being able to show it moved.

---

### Selected work

**[ai-answer-grading-case-study](https://github.com/baglanvv/ai-answer-grading-case-study)**

Product and AI work on a B2B corporate training platform, as the only product
person on it. The platform's teaching claim rested on learners writing answers
in their own words, and nothing in the product responded to what they wrote. I
specced and shipped LLM validation across about ten exercise types. The write-up
also covers what I got wrong: no eval harness, and I wrote the grading criteria
myself, which is the one setup guaranteed to never tell you your criteria are
off.

**[churn-reason-eval](https://github.com/baglanvv/churn-reason-eval)**

An eval harness for LLM classification of cancellation reasons in EdTech. Built
to answer whether a model should replace rules, it ended up answering something
more useful: a keyword baseline with no model at all scores 0.958 on the
held-out half, and at 48 rows the test set can't detect any improvement over
that. Reports regret in dollars instead of accuracy, because the expensive
mistake is handing a discount to someone who already finished the course. Comes
with the contamination guard that caught my own test-set leak.

**[retention-save-flow-prd](https://github.com/baglanvv/retention-save-flow-prd)**

The spec that uses that eval. Routes cancelling learners to whichever retention
action matches their actual reason, ships rules rather than a model, and treats
"don't know" as a real branch instead of an error. Includes the sensitivity
model, which showed that classifier accuracy isn't the bottleneck. The
counterfactual return rate is.

**[duolingo-max-teardown](https://github.com/baglanvv/duolingo-max-teardown)**

A teardown built from SEC filings rather than press coverage. Duolingo has
quietly moved two of Max's three original AI features down into cheaper tiers,
while bookings growth fell to 8% against 18% revenue growth. Every number
reproduces from the included script.

### How I work

- Specs: problem, non-goals and success metrics before solutions
- Evals: an LLM feature without a scored test set is a demo, not a product
- Instrumentation: define the metric while designing, not after launch
- Assumptions: written down, labeled, and sensitivity-tested, because the cost
  model holds up everything else and usually nobody checks it

### Toolkit

- Analytics: `SQL` · `Python` · `Amplitude / GA4` · `Metabase / Tableau` · `Excel`
- Product: `Jira / Linear` · `Figma`
- Growth: `Google Ads` · `Meta Ads`

---

Kazakhstan, open to relocation or remote · [LinkedIn](https://www.linkedin.com/in/baglan-zharkenov-10a3631a8/)
