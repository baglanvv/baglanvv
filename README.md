## Baglan Zharkenov

Senior product manager. Five years on B2C subscription products across the US,
Canada and new markets, plus fintech and EdTech in the CIS. CS degree, two
AI-related research publications, and a habit of settling arguments with an
experiment.

Currently Product Lead at Zimran, where I grew a subscription app into the #1
EdTech app in the US (Newsweek) and scaled it into 150+ markets.

The part of AI products I care about is the part that's easy to skip: deciding
what "good output" means before you ship, and being able to show it moved.

---

### Experience

**Growth Product Lead, Zimran** · Mar 2025 to present
B2C mobile subscription EdTech/fintech for the US and other tier-1 markets. Led
a cross-functional team of 20. Ran 130+ A/B experiments across web and mobile,
which moved upsell rate 65%, D7 retention 45%, and CSAT 2x, and cut CAC and
refund rate by 6pp. Scaled to 150+ markets with full localization of currency,
tax, compliance and language. Cut funnel production time 3x with AI automation.

**Product Manager, BCC** · Aug 2023 to Jan 2025
One of the top fintech banks in the CIS. Led three products inside a B2C
super-app (PFM tools, cashback, admin panel), moving MAU, NPS and retention up
to 10% QoQ. Ran 40+ CustDev sessions. Managed a team of 8 to 12 through the
super-app's move from monolith to microservices.

**Co-Founder & CPO, Vesso** · Dec 2020 to Oct 2024
MarkTech and EdTech startup, later pivoted. Shipped two apps that made 11M KZT
in two months, built an LLM chatbot for retail clients, and launched an LMS with
10 private schools in Kazakhstan. Raised ~$50K pre-seed. Google for Startups,
Berkeley SkyDeck, Dubai WEIF 2022. Showcased at WebSummit 2022.

### Selected work

**[experiment-velocity-case-study](https://github.com/baglanvv/experiment-velocity-case-study)**

We had more experiment ideas than we could build, so I treated production
throughput as the growth constraint instead of ideation. AI generation across
funnel assembly, creative and idea digests took a funnel from two weeks to four
days, which is what made 130+ experiments possible. Covers the video model
stack, the localization QA chain for 150+ markets, and why I won't claim faster
production caused the numbers it enabled.

**[ai-chatbot-retail-case-study](https://github.com/baglanvv/ai-chatbot-retail-case-study)**

An LLM chatbot for retail clients in 2021, when there was no eval tooling and
no shared vocabulary for a model that confidently says something false. A small
body of work, described at its real size. The useful part is what was missing:
no written definition of a good reply, and a client inbox full of labeled
training data I never used.

**[ai-answer-grading-case-study](https://github.com/baglanvv/ai-answer-grading-case-study)**

Product and AI work on a B2B corporate training platform. The platform's
teaching claim rested on learners writing answers in their own words, and
nothing in the product responded to what they wrote. I specced and shipped LLM
validation across about ten exercise types. The write-up also covers what I got
wrong: no eval harness, and I wrote the grading criteria myself, which is the
one setup guaranteed to never tell you your criteria are off.

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

- Analytics: `SQL` · `Python` · `Power BI / Tableau` · `GA` · `AppsFlyer`
- Product: `Postman` · `n8n` · `Cursor` · `UX/UI design`
- Strengths: A/B testing and funnel optimization, product-led growth,
  stakeholder management, rapid iteration under ambiguity

### Education

**B.Sc. Computer Science, Nazarbayev University** · GPA 3.6/4.0
Interned at IBM quantum school, contributed to two AI-related research
publications, served as President of the Volunteering club.
NASA Space School summer research intern in Houston, where I led a five-person
international team. Summer Science International Program in Indiana on a full
scholarship.

---

Kazakhstan, open to relocation or remote · English C1, Russian C2, French A2 · [LinkedIn](https://www.linkedin.com/in/baglan-zharkenov-10a3631a8/)
