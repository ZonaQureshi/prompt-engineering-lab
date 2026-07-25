# Experiment 005: Evaluating Budget Constraints

## Overview

This experiment investigates how adding a budget constraint influences AI-generated recommendations. The goal was to determine whether limiting financial resources leads to more practical, realistic, and actionable responses.

---

## Research Question

Do budget constraints improve the practicality and usefulness of AI-generated recommendations?

---

## Hypothesis

Adding a strict budget constraint will encourage the AI to optimize recommendations based on affordability while maintaining recommendation quality.

---

## Experimental Setup

| Variable | Value |
|----------|-------|
| AI Model | Gemini |
| Topic | AI Tools for Students |
| Technique Tested | Budget Constraints |
| Independent Variable | Budget constraint (£0 monthly budget) |
| Dependent Variables | Practicality, cost awareness, recommendation quality, usefulness |
| Controlled Variables | Same AI model, same language, same topic |

---

## Prompt A

```text
Recommend AI tools for students.
```

---

## Prompt B

```text
I'm a Psychology student learning Prompt Engineering and preparing for AI internships.

Recommend the best AI tools I can use with a monthly budget of £0.

Requirements:
- Only free tools
- Explain why each tool was selected
- Mention any important limitations
- Recommend the best workflow using the selected tools
```

---

## Results

### Prompt A

The response recommended several excellent AI tools for studying, research, and note-taking. However, it did not evaluate whether the tools were free or suitable for users with financial constraints.

### Prompt B

The response adapted its recommendations to the specified budget. Every tool recommendation included a justification, important limitations, and a complete workflow that could be followed without purchasing premium subscriptions.

---

## Evaluation

| Criterion | Prompt A | Prompt B | Justification |
|-----------|---------:|---------:|---------------|
| Accuracy | 9/10 | 9/10 | Both responses recommended high-quality AI tools. |
| Practicality | 7/10 | 10/10 | Prompt B provided recommendations that could be used immediately without financial barriers. |
| Cost Awareness | 5/10 | 10/10 | Prompt A largely ignored cost, while Prompt B optimized every recommendation around a £0 budget. |
| Recommendation Quality | 8/10 | 10/10 | Prompt B justified each recommendation and explained important limitations. |
| Overall Usefulness | 8/10 | 10/10 | Prompt B produced a complete learning workflow instead of a simple list of tools. |

---

## Analysis

Adding a budget constraint significantly changed the AI's decision-making process.

Instead of recommending the most capable tools regardless of price, the AI optimized its recommendations around affordability while still maximizing learning value.

The model also explained the trade-offs associated with free tools, making the recommendations more transparent and practical.

---

## Key Finding

Budget constraints encourage AI systems to optimize recommendations for real-world decision-making rather than simply suggesting the most powerful available options.

---

## Practical Applications

Budget-constrained prompting is valuable for:

- Product recommendations
- Educational resource planning
- Business software selection
- Financial planning
- Travel planning
- AI tool recommendations
- Startup resource allocation

---

## Reflection

Both prompts generated useful responses. However, Prompt B demonstrated a deeper understanding of real-world constraints by balancing quality, cost, and usability simultaneously.

---

## Limitations

This experiment evaluated only one AI model on a single recommendation task. Future experiments could compare multiple models or different budget ranges.

---

## Future Work

- Compare different budget levels.
- Evaluate multiple AI models using identical prompts.
- Combine budget constraints with role prompting.
- Measure recommendation consistency across models.

---

## Experiment Metadata

| Item | Value |
|------|-------|
| Experiment | 005 |
| Technique | Budget Constraints |
| AI Model | Gemini |
| Status | Completed |
