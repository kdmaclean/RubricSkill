# Rubric Formats

This file describes the four main rubric formats, their tradeoffs, and the exact table structure to use when rendering each one. Present these clearly to faculty during Stage 0 so they can make an informed choice.

---

## Choosing a Format

When presenting options to faculty, describe the tradeoffs — don't just list names. Frame them around the faculty member's stated use case:

- If they want **rich student feedback**: recommend Analytic
- If they want **fast grading with experienced TAs**: consider Single-Point
- If grading **speed is the priority** and feedback is secondary: Holistic may work
- If assessing a **skill that develops over time** (e.g., writing across a course): Developmental

---

## Format 1: Analytic

**What it is:** Each criterion is scored independently across multiple performance levels. The student receives a separate score for each criterion, which sum to a total.

**Best for:** Assignments where multiple distinct dimensions of quality matter and student feedback is a priority. Most common in higher education.

**Tradeoffs:**
- More time to apply per student, but much richer feedback
- High inter-rater reliability when descriptors are well-written
- Students can see exactly where they lost points

**When to recommend:** Essay assignments, lab reports, presentations, projects — anything with multiple independently assessable dimensions.

### Analytic Table Structure

```markdown
| Criterion | Exceeds Expectations (4) | Meets Expectations (3) | Approaching (2) | Does Not Meet (1) |
|-----------|--------------------------|------------------------|-----------------|-------------------|
| [Criterion name] | [Descriptor] | [Descriptor] | [Descriptor] | [Descriptor] |
```

- Columns: performance levels with point values in parentheses
- Rows: one per criterion
- Each cell: 1–3 sentences describing observable behavior at that level
- Final row (optional): point totals or weighting notes

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

### Holistic Table Structure

```markdown
| Score | Description |
|-------|-------------|
| 4 — Excellent | [Global descriptor of what an excellent response looks like] |
| 3 — Proficient | [Global descriptor] |
| 2 — Developing | [Global descriptor] |
| 1 — Beginning | [Global descriptor] |
```

---

## Format 3: Single-Point

**What it is:** Describes only the proficient level for each criterion. Space is left for instructor comments about what was missing (below standard) or exceptional (above standard).

**Best for:** Experienced graders who don't need a full scale spelled out; faculty who want to encourage qualitative feedback rather than point-hunting.

**Tradeoffs:**
- Minimal to create; very clean to look at
- Encourages narrative feedback rather than checkbox grading
- Requires more grader judgment — not ideal for large multi-grader courses
- Students need written comments to understand their performance

**When to recommend:** Graduate-level work, studio critique, capstone projects, small seminars.

### Single-Point Table Structure

```markdown
| Criterion | Below Standard | Meets Standard (Proficient) | Above Standard |
|-----------|---------------|----------------------------|----------------|
| [Criterion name] | [Leave blank — space for instructor comments] | [Descriptor of proficiency] | [Leave blank — space for instructor comments] |
```

---

## Format 4: Developmental (Competency-Based)

**What it is:** Describes a progression of skill development rather than performance levels on a single task. Unlike an analytic rubric — which asks "how well did this student do on this assignment?" — a developmental rubric asks "where is this student in their development of this skill?" The same rubric is applied to the same student at multiple points in time, across different assignments or across a sequence of courses, to track movement along a growth trajectory. Think of it as a growth chart: the scale stays fixed, and the student moves along it.

**Best for:** Skills assessed repeatedly across multiple assignments or courses — writing, research, clinical judgment, oral communication, and similar competencies. Common in competency-based education and program-level assessment. Most powerful when paired with a portfolio or advising structure that allows students to see their own trajectory over time.

**Tradeoffs:**
- Excellent for longitudinal assessment — shows growth in a way a single-assignment rubric cannot
- Requires surrounding infrastructure to be useful: a course sequence, portfolio, or repeated assessment points where the rubric can be applied more than once
- Most complex to design well — requires faculty to think carefully about what genuine progression looks like, not just what good vs. poor work looks like on one task
- Not suitable for a single high-stakes assignment graded once

**A note on level labels:** The language of developmental levels matters more than in other formats. Labels like *Novice / Developing / Proficient / Advanced* signal a trajectory — a student at Novice is at an early but expected stage, not failing. If you use analytic rubric language (*Does Not Meet / Approaching / Meets / Exceeds*) on a developmental rubric, it implies the lower levels represent inadequate performance rather than normal early development. Choose labels that communicate growth, not deficit.

**When to recommend:** Writing-intensive courses with assignments across multiple terms, capstone sequences, clinical or practicum programs, or any program with formal competency tracking across courses.

**When not to recommend:** If the faculty member is assessing a single assignment with no plans to reapply the rubric over time, a developmental rubric will require substantially more design work for no added benefit. Recommend analytic instead.

### Developmental Table Structure

```markdown
| Competency | Novice | Developing | Proficient | Advanced |
|------------|--------|------------|------------|----------|
| [Competency name] | [What a beginner does] | [What growth looks like] | [What competence looks like] | [What mastery looks like] |
```

Note: these levels describe a developmental trajectory, not quality on a single task. A student at "Novice" is not failing — they are at an expected stage.

---

## Hybrid Formats

The four formats above are not mutually exclusive. The most common hybrid is an analytic rubric with a single holistic row added — typically for a quality of the whole piece that no individual criterion captures, such as overall coherence or argument arc. Hybrids like this are fine as long as they are intentional: each added row should have a clear purpose, not serve as a catch-all.

---

## Recommending a Format

When making a recommendation, be brief and direct:

> "For a 5-page argumentative essay that students will receive feedback on, I'd recommend **Analytic**. It takes more time to apply but gives students the specific guidance they need to improve, and it holds up well if multiple graders are involved. Want to go with that?"

Offer to explain further if they're uncertain.
