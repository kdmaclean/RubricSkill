# Rubric Builder

**Authors:** Tiffany Bayley and Kyle D. S. Maclean

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill for designing, drafting, and calibrating academic rubrics.

## Why This Exists

Building a good rubric is slow, technical work. Criteria need to align with learning outcomes. Descriptors need to be behavioral, not just strings of adjectives. Performance levels need to actually distinguish between student responses. And once the rubric is drafted, the only way to know whether it holds up is to apply it to real student work — which most instructors never have time to do before the assignment is due.

Rubric Builder was designed for educators — faculty, instructors, course designers — who want a structured collaborator for this process. It can help you build a rubric, calibrate an existing rubric against student responses, or move back and forth between those two activities as the rubric improves. It tracks your progress across sessions and saves versioned files so nothing is lost.

## What It Does

The skill has two main features:

1. **Build** — Create a rubric from scratch, import an existing rubric, choose or confirm a format, and revise criteria, descriptors, weighting, and performance levels.
2. **Calibrate** — Apply a rubric to real student responses to surface weaknesses such as ambiguity, missing dimensions, and scoring pile-ups.

You can use either feature on its own. For example, you can bring your own rubric and go straight to calibration, or you can build a new rubric and decide later whether to calibrate it. Calibration can also repeat: report, revise, optionally recalibrate, and stop when the remaining tradeoffs are intentional.

It supports **Analytic** and **Holistic** rubric formats and recommends the best fit based on your assignment.

## Example Uses

**Starting from scratch:**

> "I need a rubric for a 5-page argumentative essay in my intro philosophy course."

**Improving an existing rubric:**

> "Here's the rubric I've been using for lab reports — can you help me tighten up the descriptors?"

**Calibrating against student work:**

> "I have a rubric and 8 anonymized student papers. Can you apply the rubric and tell me where it breaks down?"

**Choosing a format:**

> "I'm not sure whether to use an analytic or holistic rubric for peer review in my seminar."

## In-Session Commands

Once a session is running, you can use these commands at any point:

| Command             | What it does                                                   |
| ------------------- | -------------------------------------------------------------- |
| `show rubric`       | Display the current rubric                                     |
| `show changes`      | Describe what changed since the last version                   |
| `build rubric`      | Begin or resume rubric building                                |
| `calibrate rubric`  | Begin calibration with real student work                       |
| `run calibration`   | Begin the calibration workflow                                 |
| `rerun calibration` | Repeat calibration after revisions or with a new sample        |
| `show report`       | Display the latest calibration report                          |
| `revise rubric`     | Return to revising the current rubric                          |
| `save checkpoint`   | Save the current rubric to file                                |
| `export`            | Produce a clean final version                                  |
| `start over`        | Reset (with confirmation)                                      |

## Installation

### Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and authenticated

### Install for all projects (personal scope)

Clone the repository into your Claude Code skills directory:

```bash
git clone https://github.com/kdmaclean/RubricSkill.git ~/.claude/skills/rubric-builder
```

The skill is now available in every Claude Code session. Start a session and ask it to build a rubric — it triggers automatically on phrases like "make a rubric," "rubric for my assignment," or "grading criteria."

### Install for a single project

Clone the repository into the project's `.claude/skills/` directory:

```bash
cd /path/to/your/project
git clone https://github.com/kdmaclean/RubricSkill.git .claude/skills/rubric-builder
```

The skill will be available only in sessions started from that project folder.

## File Structure

### Skill files (what you install)

```
rubric-builder/
  SKILL.md                          ← Skill definition
  rules/
    rubric-design-principles.md     ← Best practices applied during drafting
    rubric-formats.md               ← Format options and table structures
    calibration-protocol.md         ← Procedure for calibrating against student work
```

### Working files (created during a session)

```
rubric_current.md        ← Always the latest rubric
rubric_v1.md, v2.md...   ← Version history
calibration_report.md    ← Diagnostic report from calibration
session_notes.md         ← Tracks current feature, context, and decisions
```

## Design Principles

The skill enforces rubric design best practices drawn from assessment literature, including:

- Align criteria to learning outcomes
- Write behavioral descriptors, not adjectives
- Make performance levels meaningfully distinguishable
- Limit criteria to 4-7 to keep rubrics usable
- Weight criteria to reflect instructional priorities
- Make the top level achievable, not aspirational

See `rules/rubric-design-principles.md` for the full list.
