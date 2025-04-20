# Signed, Sealed… Paid Faster?

**Can a 50¢ envelope speed up invoices and boost cash flow? I ran the numbers to find out.**

## Project Overview

In this project, I evaluated a courier company’s proposal to include stamped self-addressed (SSA) envelopes with invoices to encourage faster customer payments. Using real-world data from 220 customers who received SSA envelopes, I tested whether this tactic significantly reduced the average payment time — enough to offset the envelope cost and improve cash flow. My analysis used hypothesis testing and a strategic Type I/II error tradeoff to simulate a real product decision under uncertainty.

## Context & Inspiration

The scenario mirrors challenges I've seen across operations, marketing, and customer success — where small interventions can have a measurable impact. I saw this as a chance to apply analytics not just to crunch numbers, but to support a practical, cost-aware business decision rooted in behavioral data.

## My Approach

- Set hypotheses:
  - Null: SSA envelopes do not reduce payment time below the 22-day profit threshold
  - Alternative: SSA envelopes reduce payment time enough to be profitable
- Performed a one-tailed t-test on payment time data from the 220 SSA customers
- Conducted a Type I vs. Type II error analysis to justify choosing a relatively high significance level (α = 0.10) — prioritizing the cost of inaction over the cost of a small test
- Interpreted the p-value and connected the results to the CFO’s decision-making criteria

## Key Insights

Although the average payment time with SSA envelopes decreased, the p-value (~0.175) exceeded our threshold of significance. This means we cannot confidently recommend the SSA policy — at least not without further testing or a larger sample. That said, the analysis provides a useful framework for balancing statistical rigor with business practicality, especially when dealing with low-cost, high-frequency decisions.

## Reflection

This project reminded me that data-driven decisions don’t exist in a vacuum. Understanding the cost of different types of error — and how they map to real-world consequences — is what turns an analysis into a recommendation. I walked away more confident in using statistics as a tool for actionable, risk-conscious strategy.

## Tools & Methods

- Language: R
- Methods: One-sample t-test, Type I/II error framing
- Dataset: 220 customer payment records
- Libraries: base R, `t.test()`


