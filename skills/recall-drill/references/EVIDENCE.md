# Evidence behind recall-drill

Two core papers, read in full from local copies: Roediger & Karpicke 2006 and
Rowland 2014. A third section covers the research behind grading by concept.
Each source there is tagged by how it was checked.

## Roediger & Karpicke 2006, Test-Enhanced Learning

Psychological Science 17(3), 249-255. Prose passages, free recall, **no feedback**.
Mean proportion of idea units recalled on the final test:

| Condition | 5 min | 2 days | 1 week |
| --- | --- | --- | --- |
| Study, study (Exp 1) | 81% | 54% | 42% |
| Study, test (Exp 1) | 75% | 68% | 56% |
| SSSS, four study periods (Exp 2) | 83% | | 40% |
| SSST, three study, one test | 78% | | 56% |
| STTT, one study, three tests | 71% | | 61% |

What each row is doing to this skill:

- **The crossover.** Restudy wins at 5 minutes, loses at 2 days and 1 week. The
  drill will feel less effective than rereading in the moment. Say so once.
- **Reads vs recall.** STTT read the passage 3.4 times on average, SSSS read it
  14.2 times. Fewer exposures, more retention. Proportional forgetting over the
  week: 14% for STTT, 28% for SSST, 52% for SSSS.
- **Confidence is inverted.** Asked to predict week-later recall on a 7-point
  scale, SSSS rated highest (4.8) and scored lowest (40%). This is why the skill
  never asks the user how well they think they know it.
- **Scoring.** Subjects wrote "without concern for exact wording or correct
  order", scored 1 point per idea unit out of 30 (p. 250). Interrater r = .95.
  The skill copies the meaning-over-wording standard. It does not use the flat
  count as feedback: that count was a measurement instrument, and the authors
  limit their claims to "fact-based courses" (p. 254). See the concept section
  below.
- **Section size.** 30 idea units per passage, 256 and 275 words. A useful
  ceiling for one pass, and the reason the skill splits anything much bigger.

## Rowland 2014, meta-analysis

Psychological Bulletin 140(6). 159 effect sizes, testing versus restudy.
Overall g = 0.50, CI [0.42, 0.58]. High-exposure subset g = 0.66.

Moderators that shaped the design:

| Moderator | g |
| --- | --- |
| No feedback | 0.39 |
| Feedback | 0.73 |
| No feedback, initial recall under 50% | 0.03 |
| No feedback, 51 to 75% | 0.29 |
| No feedback, over 75% | 0.56 |
| Retention interval under 1 day | 0.41 |
| Retention interval over 1 day | 0.69 |
| Recognition, multiple choice | 0.36 |
| Cued recall | 0.72 |
| Free recall | 0.81 |

Last three rows are from the high-exposure subset, which Rowland identifies as
the appropriate analysis for initial test type.

What each one is doing to this skill:

- **Feedback is the biggest lever available.** 0.39 to 0.73. And the g = 0.03
  row is the failure mode: a hard section, recalled poorly, with no answer given,
  is wasted effort. This is why the skill always reveals in the end, and why it
  grades against the supplied text rather than from memory.
- **Free recall over cued recall over recognition.** Blank page first, cues only
  on the gaps, no multiple choice ever.
- **Effort helps when it succeeds.** Restricted to studies that gave feedback,
  low initial performance under 50% gave g = 0.99, versus 0.40 for over 75%.
  Hard retrieval plus feedback is the best cell in the table. Hard retrieval
  without feedback is the worst.
- **One test is enough.** No reliable relationship between number of initial
  tests and effect size. One good pass per section, not three.
- **Format match does not matter.** Initial-to-final test match was not a
  reliable moderator, so the drill does not need to imitate any later exam.
- **The benefit grows with delay.** Log retention interval was the only
  significant continuous moderator. The payoff is not visible today.

## Why the drill grades by concept, not by unit count

Version 1.0 graded with a flat idea-unit count and cued misses in list order.
On a 27-unit section that produced "11 of 27", put a minor date next to the
section's core ideas, and spent the first cues on a job title. The user's
verdict: it cared about each point, not about what the section was saying.

Tags:

- **[local]**: read in full from a local copy.
- **[secondary]**: cited from secondary summaries or abstracts, not verified
  in full text. Treat the exact figures as approximate.
- **[inference]**: a design step this skill takes from a finding, not
  something the source tested.

**The flat count is a measuring tool.**

- **[local]** Roediger & Karpicke 2006 counted 1 point per idea unit (p. 250) to
  compare conditions, and scoped their claims to "fact-based courses" (p. 254).
  Nothing in the paper says feedback should follow that list.

**Not all units are equal.**

- **[secondary]** Levels effect: Meyer 1975; Kintsch & van Dijk 1978; Brown &
  Smiley 1977. Units high in a text's hierarchy are recalled better and kept
  longer. Researchers tag units by level or importance and report recall per
  tier, not one sum. Raters agree well at the extremes (clearly central,
  clearly trivial) and less in the middle.
- **[secondary]** Gist outlasts verbatim: Kintsch et al. 1990; Brainerd &
  Reyna, fuzzy-trace theory. Surface detail fades first.
- **[secondary]** Free recall mostly measures the textbase, what the text
  said, including its macrostructure of main ideas; understanding lives in the
  situation model (Kintsch 1994). **[local]** Kobayashi 2019 classes free
  recall as a "surface" measure. Concept grading does not escape this: main
  ideas recalled freely are still textbase. What it changes is which part of
  the textbase the feedback aims at, the macrostructure rather than the
  details.

**Retrieval aimed at concepts transfers further.**

| Finding | Source |
| --- | --- |
| Fact-only quizzes did not improve higher-order performance; higher-order or mixed quizzes did | **[secondary]** Agarwal 2019, J Ed Psych 111:189 |
| Retrieval practice transfers, d ≈ 0.40; more when retrieval is elaborated and initial success is high | **[secondary]** Pan & Rickard 2018, Psych Bull 144:710 |
| Retrieval practice improved inference questions, not only verbatim ones | **[secondary]** Karpicke & Blunt 2011 |
| "Conceptualize" and "explain" prompts gave the largest effects, g = .87 and .68 | **[local]** Bisra et al. 2018 |
| Elaboration prompts after free recall improved comprehension | **[secondary]** Endres et al. 2017 |

This is why gap cues describe a situation or ask why or what happens next, and
why the optional closing question asks how one idea relates to another.

**Errors first.**

- **[secondary]** Errors made on a test persist when no feedback follows
  (Roediger & Marsh 2005). Feedback corrects them (Butler & Roediger 2008).
  This is why wrong concepts are worked first and always end in a reveal.
- **[secondary]** High-confidence errors are the easiest to correct once
  feedback arrives (Butterfield & Metcalfe 2001). This finding is about
  feedback, not cues, and the skill never measures confidence. It supports
  correcting wrong claims rather than letting them pass; nothing more.
- **[secondary, extrapolated]** Refutation texts, which set a misconception
  against the correct account, beat plain expository text (Schroeder & Kucera
  2022, g = .41). That meta-analysis covers prior science misconceptions, not
  errors made on a test. **[inference]** Setting the learner's wrong claim
  beside the section's version in step 6 extends it to test errors.

**What still holds from version 1.0.**

- **[local]** A closed-book free-recall dump first: free recall g = .81, cued
  .72, recognition .36 (Rowland 2014).
- **[local]** Cue before revealing, and always reveal: without feedback, poorly
  recalled material gains almost nothing (g = .03).

**What is a design choice, not a finding.** No paper validates a specific
weighting formula, the concept count (up to 7, usually 3 to 5), or the exact
line between core and scaffolding. Those are judgment calls grounded in the
levels-effect literature. Two guardrails keep them honest: a vague gesture that
names no specific idea gets no credit, and concept grading must not be used to
inflate the grade. It changes what the feedback aims at, not how lenient it is.
The "N details missed" line keeps details reachable for technical material
where they matter.

## What is deliberately out of scope

The retention interval finding points at spacing, and spacing is a separate
phase with its own literature. This skill runs one pass close to reading and
keeps no record. Anything about when to come back is not its job.

The core findings come from prose passages read for comprehension. The drill
inherits that scope, which is why the skill turns away pure code, reference
lists, and material that is already a quiz.
