# Calibration Protocol

This file describes how to conduct a rubric calibration against real student responses. The goal is not to grade students — it is to identify weaknesses in the rubric itself.

A calibration produces a diagnostic report that guides rubric revision. Think of it as putting the rubric through its paces before it gets used at scale.

---

## What You're Looking For

Apply the rubric to each student response systematically, keeping track of four types of findings:

### 1. Criteria Coverage
Which criteria came up frequently across student responses, and which were almost never triggered? Criteria that no student response activated may be irrelevant to this particular assignment, or so advanced that they serve no discriminating function.

Flag: Any criterion that applies to fewer than 1 in 5 responses — ask whether it belongs.

### 2. Ambiguity Flags
Moments where you could plausibly assign two different scores depending on how you read the descriptor. These are the rubric's fault, not the student's.

Flag: Any cell where a reasonable grader might score the same response differently depending on interpretation. Quote the specific language that is ambiguous.

### 3. Scoring Pile-Ups
If most students cluster at one level (e.g., almost everyone gets a 2 on a given criterion), this suggests the criterion may lack sufficient differentiation between levels, or the performance level boundaries are in the wrong place.

Flag: Any criterion where more than 60% of responses land at the same level.

### 4. Missing Dimensions
Qualities present in student work that the rubric doesn't capture at all — things that clearly distinguish a stronger response from a weaker one, but that no current criterion addresses.

This is the most valuable finding. It tells you what the rubric is blind to.

Flag: Any observable quality in student work that you noticed yourself as a reader but had nowhere to score.

---

## Procedure

### Step 1: Confirm the Sample
The faculty member must supply real student responses. Never generate synthetic or fabricated student work for the calibration — doing so defeats the entire purpose, since the diagnostic value comes from encountering the unpredictable ways real students actually interpret and respond to an assignment. If no student responses are available yet, tell the faculty member the calibration should wait until they have some.

Tell the faculty member:
> "I have [N] student responses. I'll work through each one and apply the rubric, then generate a diagnostic report. This will take a few minutes."

5–10 responses is sufficient. More than 15 is rarely necessary for diagnostic purposes.

### Step 2: Apply the Rubric to Each Response
For each response:
1. Work through each rubric criterion
2. Assign a provisional score and note a brief rationale
3. Flag any ambiguity, pile-up, or gap as you go
4. Note any quality in the response that the rubric can't capture

Do not produce a full grade report — this is a rubric diagnostic, not student assessment. Keep provisional scores internal to your analysis; what you surface to the faculty member is the rubric finding, not the student score.

### Step 3: Synthesize Findings
After working through all responses, compile findings across all four categories. Look for patterns — a finding that appears in only one response may be noise; a finding that appears in 3 or more responses is a rubric issue worth addressing.

---

## Report Format

Save as `calibration_report.md`. Use this structure:

```markdown
# Calibration Report

**Assignment:** [assignment name/description]
**Rubric version:** [version number]
**Responses reviewed:** [N]
**Date:** [date]

---

## Summary

[2–3 sentence overview of the most important findings]

---

## Criteria Coverage

[For each criterion: how often it was meaningfully triggered, whether it discriminated well between responses]

---

## Ambiguity Flags

[List each ambiguous phrase or cell, with a quote of the language and a description of the interpretive problem]

---

## Scoring Pile-Ups

[List any criteria where responses clustered heavily at one level, with a note on the likely cause]

---

## Missing Dimensions

[Describe any qualities present in student work that the rubric doesn't capture]

---

## Recommended Revisions

[Specific, numbered revision suggestions. Each should name the criterion and describe the proposed change and why]
```

---

## After the Report

Present the report to the faculty member and ask:
> "Which of these findings do you want to address? We can work through the recommended revisions together."

Let them lead — they may decide some findings aren't worth acting on. That's fine. Your job is to surface the issues, not to insist on fixing all of them.

After revisions, note in `session_notes.md` which calibration findings were addressed and which were intentionally left alone.

---

## What the Calibration Is Not

- **Not a grading session.** You are not producing grades for students.
- **Not a judgment of the assignment.** The goal is rubric improvement, not critique of what was assigned.
- **Not a replacement for faculty judgment.** You are a diagnostic tool. The faculty member decides which findings to act on.
- **Not a guarantee.** A calibration on 8 responses won't catch everything. Flag this limitation in the report summary.
- **Not something you can do with synthetic data.** Never offer to generate fake student responses to "get started" or fill a gap. The whole point is to see how the rubric handles real, messy, unpredictable student work. Fabricated responses will only tell you how the rubric handles your own assumptions.
