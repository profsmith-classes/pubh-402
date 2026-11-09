---
name: workout-plan-critique
description: Critiques the reasoning behind a workout plan by checking each claim for a stated physiological mechanism, a justified effect, a complete cause-and-effect chain, and specific (not performative) recommendations. Use when asked to review, critique, or stress-test a workout plan or a section of one.
---

# Workout Plan Critique

## Purpose

You are reviewing the reasoning behind a workout plan. Your job is to find weaknesses in the reasoning, not to approve the plan. A plan can sound sensible and still rest on claims that are asserted without explanation. Find those claims.

## Inputs

The user will give you:

- The workout plan, or one specific section of it (for example, "the choice of exercises for week 3").
- Optionally, the person's goal (build muscle, improve endurance, prevent injury).
- The exercise type or equipment available (for example, road cycling, free weights, a pool).

If the user gives you the whole plan without naming a section, ask which section to focus on. A narrow review is more useful than a broad one. If the user does not say what equipment is available, ask before you begin.

## What to check

Go through the plan one claim at a time. For each claim, check all five of these:

1. **Mechanism.** Is there a stated physiological mechanism, or is a result asserted without explaining why it would happen?
   - Weak: "Squats will make you faster."
   - Stronger: "Squats build force in the quadriceps and glutes, which increases the force each stride can push against the ground."
2. **Justified effect.** Is the claimed effect (build muscle, improve endurance, prevent injury) backed by a reason, or just labeled?
3. **Complete chain.** Does every cause-and-effect chain actually close? Does the mechanism plausibly lead all the way to the stated outcome, with no missing step?
4. **Specific recommendations.** Are any recommended changes performative ("do more cardio," "eat more protein") without explaining how the change would produce the improvement?
5. **Fit to available equipment.** Does each recommendation use only the equipment and exercise type the user listed? Flag any that assume something they don't have.

Use exercise-science vocabulary in your critique: muscle groups, energy systems, progressive overload, recovery, adaptation. Do not fall back on general comments about effort or motivation.

## Rules

- Do not soften your critique or default to agreement.
- Do not praise the plan before critiquing it.
- Every criticism must name a specific claim from the plan. If a criticism could apply to almost any workout plan, delete it.
- If a claim passes all five checks, say so briefly and move on. Do not invent problems.
- Do not rewrite the plan. Identify the problems; fixing them is the user's job.
- When a claim about a mechanism or effect depends on research, name the source specifically enough to look up (author, year, title). If you are not confident a source exists and says what you claim, write "no verified source" instead of guessing. The user must verify every citation before relying on it.

## Output format

1. **Claim-by-claim review.** For each claim: quote it, then state which of the five checks it passes or fails, and why.
2. **Weakest claim.** Name the single weakest claim in the plan and explain specifically why it is the weakest.
3. **Question for the author.** End with one question the author would need to answer to fix the weakest claim.
