# Experiment 004: Evaluating Output Constraints

## Experiment Information

| Field | Details |
|--------|---------|
| Experiment | 004 |
| Technique | Output Constraints |
| AI Model | Claude |
| Date | 2026-07-26 |
| Task | Budget Planning |
| Objective | Evaluate how output constraints affect formatting, organization, and readability. |

## Overview

This experiment investigates whether output constraints improve the readability, organization, and usability of AI-generated responses while maintaining factual accuracy.

Unlike previous experiments that focused on role prompting or content requirements, this experiment evaluates whether controlling the presentation of information results in a more effective response.

---

## Research Question

Do output constraints improve the readability and usability of AI-generated responses?

---

## Hypothesis

Adding explicit output constraints will improve the organization, readability, and practical usefulness of the response while maintaining the same level of factual accuracy.

---

## Experimental Setup

| Variable | Value |
|----------|-------|
| AI Model | Claude |
| Topic | Monthly Budgeting |
| Technique Tested | Output Constraints |
| Independent Variable | Output constraints |
| Dependent Variables | Readability, organization, instruction adherence, usability |
| Controlled Variables | Same AI model, same topic, same language, same chat/session |

---

## Prompt A

```text
How can someone create a monthly budget?
```

---

## Prompt B

```text
Explain how someone can create a monthly budget.

Requirements:
- Maximum 200 words
- Use bullet points
- Give one practical example
- End with a three-step action plan
- Avoid financial jargon
```

---

## Results

### Prompt A

The response explained the budgeting process in detail using numbered steps. It provided useful information but left the overall structure and presentation entirely to the AI.

### Prompt B

The response followed every requested constraint. It used concise bullet points, included a practical example, avoided complex financial terminology, and concluded with a clear three-step action plan, making it easier to scan and understand.

---

## Evaluation

| Criterion | Prompt A | Prompt B | Justification |
|-----------|---------:|---------:|---------------|
| Accuracy | 9/10 | 9/10 | Both responses contained accurate financial advice. |
| Clarity | 8/10 | 10/10 | Prompt B used concise language, bullet points, and an example. |
| Organization | 9/10 | 10/10 | Both responses were logically structured, but Prompt B followed a more organized format. |
| Instruction Adherence | N/A | 10/10 | Prompt B satisfied every specified output requirement. |
| Practical Usefulness | 8/10 | 10/10 | Prompt B is easier for readers to apply immediately. |

---

## Analysis

The experiment demonstrated that output constraints significantly improved the presentation of information without changing the underlying facts.

The constrained response became easier to read, quicker to understand, and more actionable because the AI followed a predefined structure rather than selecting its own.

---

## Key Finding

Output constraints improve how information is presented rather than what information is presented.

---

## Practical Applications

Output constraints are especially useful when creating:

- Educational study notes
- Quick reference guides
- Business reports
- Technical documentation
- Client summaries
- AI-generated learning materials

---

## Reflection

Both prompts produced accurate information. However, Prompt B transformed the response into a format that was significantly easier to read and apply by controlling its structure, length, and presentation.

---

## Limitations

This experiment evaluated a single AI model on one topic. Different models or domains may respond differently to output constraints.

---

## Future Work

- Compare output constraints across multiple AI models.
- Combine output constraints with role prompting.
- Test strict word limits versus flexible limits.

---

## Experiment Metadata

| Item | Value |
|------|-------|
| Experiment | 004 |
| Technique | Output Constraints |
| AI Model | Claude |
| Status | Completed |
