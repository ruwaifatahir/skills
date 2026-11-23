# Evidence behind recall-drill

Two papers.

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
  order", scored 1 point per idea unit out of 30. Interrater r = .95. That is
  the grading standard the skill copies.
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

## What is deliberately out of scope

The retention interval finding points at spacing, and spacing is a separate
phase with its own literature. This skill runs one pass close to reading and
keeps no record. Anything about when to come back is not its job.

The findings above come from prose passages read for comprehension. The drill
inherits that scope, which is why the skill turns away pure code, reference
lists, and material that is already a quiz.
