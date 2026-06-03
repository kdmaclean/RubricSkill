# Rubric Formats

This file describes the two main rubric formats and their tradeoffs. Present these clearly during Build intake when the faculty member needs to choose a format.

The exact table structure for each format lives in its template file under `templates/` — copy the template and fill it in rather than reconstructing the table from memory.

---

## Choosing a Format

When presenting options to faculty, describe the tradeoffs — don't just list names. Frame them around the faculty member's stated use case:

- If they want **rich student feedback**: recommend Analytic
- If grading **speed is the priority** and feedback is secondary: Holistic may work

---

## Format 1: Analytic

**What it is:** Each criterion is scored independently across multiple performance levels. The student receives a separate score for each criterion, which sum to a total.

**Best for:** Assignments where multiple distinct dimensions of quality matter and student feedback is a priority. Most common in higher education.

**Tradeoffs:**

- More time to apply per student, but much richer feedback
- High inter-rater reliability when descriptors are well-written
- Students can see exactly where they lost points

**When to recommend:** Essay assignments, lab reports, presentations, projects — anything with multiple independently assessable dimensions.

**Table structure:** `templates/analytic-template.md`

---

## Format 2: Holistic

**What it is:** A single score is assigned to the entire response based on an overall impression. The rubric describes what each score level looks like globally.

**Best for:** Quick grading of shorter work, or when the overall quality of a response matters more than any individual component.

**Tradeoffs:**

- Fast to apply — one score per student
- Low feedback value: students don't know what to improve
- Lower inter-rater reliability unless descriptors are very detailed
- Not suitable as a student-facing learning tool

**When to recommend:** Short-answer exam questions, participation grades, quick diagnostic assignments.

**Table structure:** `templates/holistic-template.md`

---

## Recommending a Format

When making a recommendation, be brief and direct:

> "For a 5-page argumentative essay that students will receive feedback on, I'd recommend **Analytic**. It takes more time to apply but gives students the specific guidance they need to improve, and it holds up well if multiple graders are involved. Want to go with that?"

Offer to explain further if they're uncertain.
