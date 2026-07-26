# Experiment 003: Evaluating Content Constraints

## Experiment Information

| Field | Details |
|--------|---------|
| Experiment | 003 |
| Technique | Content Constraints |
| AI Model | Perplexity |
| Date | 2026-07-25 |
| Task | Information Explanation |
| Objective | Evaluate whether specifying required content improves completeness and relevance. |

## Overview

This experiment investigates whether explicitly specifying the content that an AI must include improves the completeness and educational value of its response.

Unlike previous experiments, the focus is not on assigning a role or changing the output format. Instead, the experiment evaluates how content constraints influence the AI's ability to satisfy a user's informational needs.

---

## Research Question

Do explicit content constraints improve the completeness and educational value of AI-generated responses?

---

## Hypothesis

Providing explicit content requirements will increase the completeness, organization, and usefulness of the response without significantly affecting factual accuracy.

---

## Experimental Setup

| Variable | Value |
|----------|-------|
| AI Model | Perplexity AI |
| Topic | Dissociative Identity Disorder (DID) |
| Technique Tested | Content Constraints |
| Independent Variable | Explicit content requirements |
| Dependent Variable | Completeness, organization, educational usefulness |
| Controlled Variables | Same AI model, same topic, same language, same session |

---

## Prompt A

```text
Explain Dissociative Identity Disorder.
```

---

## Prompt B

```text
Explain Dissociative Identity Disorder.

Requirements:
- Explain how it develops.
- Describe common misconceptions.
- Provide one daily-life example showing how DID may affect functioning.
- Explain the therapies commonly used.
```

---

## Results

### Prompt A

The response accurately explained Dissociative Identity Disorder, including its definition, development, symptoms, diagnosis, treatment, and prevalence. It provided a broad overview suitable for general learning but did not specifically focus on misconceptions or provide a detailed real-life example.

### Prompt B

The response directly addressed every requested topic. It explained the development of DID, corrected common misconceptions, presented a realistic daily-life example, and outlined evidence-based therapeutic approaches. The information was organized according to the requested content, making it more useful for academic study.

---

## Evaluation

| Criterion | Prompt A | Prompt B | Justification |
|-----------|---------:|---------:|---------------|
| Accuracy | 10/10 | 10/10 | Both responses were factually accurate. |
| Clarity | 8/10 | 9/10 | Prompt B presented information more clearly by focusing on requested topics. |
| Organization | 9/10 | 10/10 | Prompt B followed the required structure exactly. |
| Completeness | 9/10 | 10/10 | Prompt B included every requested content element. |
| Practical Usefulness | 8/10 | 10/10 | Prompt B was more suitable for academic revision and learning. |
| Instruction Adherence | N/A | 10/10 | Prompt B successfully followed all specified requirements. |

---

## Analysis

The experiment showed that explicit content constraints did not significantly change the factual accuracy of the AI's response. Instead, they improved the completeness, organization, and educational usefulness of the generated content.

By specifying the information that had to be included, the AI produced a response that was more closely aligned with the user's learning objectives.

---

## Key Finding

Content constraints primarily improved **what information was included**, rather than **how the information was presented**. The response became more complete and better aligned with the user's educational needs while maintaining the same level of factual accuracy.

---

## Practical Applications

Content constraints are valuable in situations where specific information must not be omitted.

Potential applications include:

- Educational study guides
- Research summaries
- Medical information requests
- Legal document preparation
- Business reports
- Technical documentation

---

## Reflection

One interesting observation was that the general prompt already produced a high-quality response. However, the constrained prompt ensured that important topics such as misconceptions and daily-life functioning were not overlooked. This demonstrates that content constraints improve consistency rather than intelligence.

---

## Limitations

This experiment was conducted using a single AI model (Perplexity AI) on one psychology topic. Different models or subject areas may produce different results.

---

## Future Work

- Compare content constraints across multiple AI models.
- Investigate combining content constraints with role prompting.
- Evaluate whether content constraints improve performance on technical and scientific topics.

---

## Experiment Metadata

| Item | Value |
|------|-------|
| Experiment | 003 |
| Technique | Content Constraints |
| Model | Perplexity AI |
| Status | Completed |
