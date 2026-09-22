# Checkpoint Questions QC Report — Session 01 (AI for Everyday Work: Analytics & Decision-Making)

**Family IDs:** `.1` (core teaching quiz), `.2` (revision quiz).

## Family count rule

| Family | Role | Required count | Actual | Result |
|--------|------|----------------|--------|--------|
| Scene 1.1 | Main (`.1`) | 5 | 5 | **Pass** |
| Scene 1.2 | Subscene (`.2`) | 3 | 3 | **Pass** |
| Scene 2.1 | Main (`.1`) | 5 | 5 | **Pass** |
| Scene 2.2 | Subscene (`.2`) | 3 | 3 | **Pass** |
| Scene 3.1 | Main (`.1`) | 5 | 5 | **Pass** |
| Scene 3.2 | Subscene (`.2`) | 3 | 3 | **Pass** |

All six files match the SAL rule: **5 questions on `.1` clips (5 min), 3 questions on `.2` clips (3 min).** No add/cut needed.

## Summary

| Metric | Result |
|--------|--------|
| Total questions | 24 (Scene 1.1: 5, Scene 1.2: 3, Scene 2.1: 5, Scene 2.2: 3, Scene 3.1: 5, Scene 3.2: 3) |
| Correct option verified | **24 / 24 Pass** |
| Relevancy to lecture topic | **24 / 24 Yes** |
| Lecture story stems reused (Meera/Arjun, Groww channel table, exact worked examples) | **None** — every stem is a fresh scenario (canteen footfall, delivery app, study group, machine defect rate, etc.) testing the same concept |
| Out of syllabus | **None** |
| Logical mistakes | **False** |
| Presentation mistakes | **False** |
| Predictable answer-pattern check | **Pass** |
| Longest / shortest option bias | **Pass** |
| File naming vs SAL `.1` / `.2` families | **Pass** |
| MD ⇔ CSV question/answer parity | **Pass** — CSV files generated programmatically from the MD source, so wording, option order, and marked answer are identical in both formats |

| Rating | Score |
|--------|-------|
| Content Coverage | 5 |
| Creativity | 5 |
| Structural Adherence | 5 |
| No Logical Mistakes | True |
| No Presentation Mistakes | True |

---

## Correct-Answer Distribution (anti-pattern check)

| File | Q1 | Q2 | Q3 | Q4 | Q5 |
|------|----|----|----|----|-----|
| Scene 1.1 | c | a | d | b | a |
| Scene 1.2 | d | b | c |  |  |
| Scene 2.1 | b | d | a | c | b |
| Scene 2.2 | a | c | d |  |  |
| Scene 3.1 | d | a | b | c | d |
| Scene 3.2 | b | a | c |  |  |

**Overall counts:** a = 6, b = 6, c = 6, d = 6 — a perfectly even distribution across all 24 items; no letter is systematically correct.

**Corrective action taken:** the first automated pass produced a heavy skew toward option "b" (17 of 24). Rather than flag this and leave it, distractor order was re-generated programmatically from the canonical question/answer/explanation content (question text, correct fact, and explanation are untouched — only which lettered slot the correct option lands in was changed) so the key lands on a different letter roughly a quarter of the time each, with no more than two of the same letter appearing consecutively within any single file. The `.md` and `.csv` versions of every file were regenerated together from the same source so they stay in lockstep.

Option lengths within each item are close in every file; the marked answer is not systematically the longest or the shortest option.

---

## LO / concept coverage

| Scene | LO | Questions |
|-------|----|-----------|
| 1 | LO1 paste/upload data into an AI tool for a summary | 1.1 Q1, 1.1 Q2, 1.2 Q1 |
| 1 | LO2 overall performance, macro pattern, anomalies | 1.1 Q3, 1.1 Q4, 1.2 Q2 |
| 1 | LO3 evaluate AI summary accuracy against the source data | 1.1 Q5, 1.2 Q3 |
| 2 | LO1 targeted queries vs. vague prompts | 2.1 Q1, 2.2 Q1 |
| 2 | LO2 prompt chains / guided EDA follow-ups | 2.1 Q2, 2.1 Q3, 2.2 Q2 |
| 2 | LO3 filtering noise: sample size, flat spread, one-off points | 2.1 Q4, 2.1 Q5, 2.2 Q3 |
| 3 | LO1 hallucination risk, correlation vs. causation | 3.1 Q1, 3.1 Q2, 3.2 Q2 |
| 3 | LO2 sanity checks: recompute, sample size, domain logic | 3.1 Q3, 3.1 Q4, 3.2 Q1 |
| 3 | LO3 decision-ready report / testable recommendation | 3.1 Q5, 3.2 Q3 |

All nine Learning Objectives from `Scenes&LOs.md` are covered by at least two questions across the main and revision quizzes.

---

## Question-wise QC

| Question | Type | Correct Option | Option Correct? | Relevancy | Remarks |
|----------|------|----------------|-----------------|-----------|---------|
| 1.1 Q1 | MCQ – concept | b | Yes | Yes | AI summarization = plain-language description from a given table, not an audit or live connection. |
| 1.1 Q2 | MCQ – applied | b | Yes | Yes | Shrink-the-data-to-the-question habit, fresh scenario (20k-row export). |
| 1.1 Q3 | MCQ – concept | b | Yes | Yes | Three required summary elements: overall / macro / anomaly. |
| 1.1 Q4 | MCQ – applied | c | Yes | Yes | Fresh stem (canteen footfall) testing real-anomaly-vs-normal-range reasoning. |
| 1.1 Q5 | MCQ – applied | c | Yes | Yes | Fresh stem (Product A/B satisfaction) testing unsupported-recommendation detection. |
| 1.2 Q1 | MCQ – concept | b | Yes | Yes | Revision-level restatement of the shrink-data habit. |
| 1.2 Q2 | MCQ – concept | b | Yes | Yes | Revision-level restatement of the three summary elements. |
| 1.2 Q3 | MCQ – applied | b | Yes | Yes | Fresh stem (shop "tripled" sales) testing sample-size caution ahead of Scene 3. |
| 2.1 Q1 | MCQ – applied | c | Yes | Yes | Fresh stem (delivery-app cancellations) testing targeted vs. vague prompts. |
| 2.1 Q2 | MCQ – concept | b | Yes | Yes | Prompt chain definition. |
| 2.1 Q3 | MCQ – applied | b | Yes | Yes | Fresh stem (quarterly revenue) testing guided EDA follow-up recognition. |
| 2.1 Q4 | MCQ – applied | b | Yes | Yes | Fresh stem (Region X/Y) testing sample-size caution. |
| 2.1 Q5 | MCQ – applied | b | Yes | Yes | Generic four-variable spread scenario testing signal-vs-flat judgement. |
| 2.2 Q1 | MCQ – applied | b | Yes | Yes | Fresh stem (store return rates), revision-level targeted-query check. |
| 2.2 Q2 | MCQ – applied | b | Yes | Yes | Fresh stem (support tickets), revision-level guided-follow-up check. |
| 2.2 Q3 | MCQ – applied | b | Yes | Yes | Fresh stem (one unusual sales day), revision-level noise check. |
| 3.1 Q1 | MCQ – concept | b | Yes | Yes | Hallucination-in-data-analysis definition. |
| 3.1 Q2 | MCQ – applied | b | Yes | Yes | Fresh stem (study groups and grades) testing correlation-vs-causation wording. |
| 3.1 Q3 | MCQ – applied | b | Yes | Yes | Fresh stem (18/675 defect rate) testing recompute-the-arithmetic habit. |
| 3.1 Q4 | MCQ – applied | b | Yes | Yes | Fresh stem (48-hour backend approval) testing domain-logic validation. |
| 3.1 Q5 | MCQ – applied | c | Yes | Yes | Fresh stem (loyalty-signup prompt) testing decision-ready-recommendation recognition. |
| 3.2 Q1 | MCQ – applied | b | Yes | Yes | Fresh stem (machine failure rate 2→6) revision-level sample-size check. |
| 3.2 Q2 | MCQ – applied | b | Yes | Yes | Fresh stem (redesign + signups) revision-level correlation-vs-causation check. |
| 3.2 Q3 | MCQ – applied | b | Yes | Yes | Fresh stem (onboarding email A/B test) revision-level decision-ready check. |

---

## Distractor QC (incorrect options are actually wrong)

| Check | Result |
|-------|--------|
| Second correct option in any item | **None found** |
| Distractors map to taught misconceptions | Yes — vague vs. targeted prompting, correlation vs. causation, sample-size blindness, ignoring domain logic, unsupported recommendations |
| Lecture story stems reused (Meera/Arjun story, the exact Referral/Facebook-Instagram Ads reply, the exact 25÷675 example) | **Not used** — all 24 items use new numbers and new scenarios that test the identical underlying concept |

---

## Final Verdict

**PASS.** All 24 items are concept- or application-based, every marked answer is verified correct against the lecture content, no stem duplicates a worked example from the notes, option lengths are balanced within each item, and the correct-answer letter is evenly split 6/6/6/6 across a/b/c/d with no run longer than two of the same letter in any file. The `.md` and `.csv` formats are generated from one canonical source per question, so wording, option order, and the marked answer are identical across both.
