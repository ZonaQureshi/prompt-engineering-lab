# Experiment 002: Evaluating Role Prompting

## Overview

This experiment investigates whether assigning a professional role to an AI model changes the quality, depth, and style of its response.

Unlike Experiment 001, which focused on structured prompting, this experiment isolates **role prompting** by comparing a neutral prompt with one that assigns the AI the role of an environmental researcher.

---

## Research Question

Does assigning the AI a professional role improve the quality of its response?

---

## Hypothesis

Assigning the AI the role of an environmental researcher will produce a more analytical and evidence-oriented response without changing the underlying factual accuracy.

---

## Experimental Setup

| Variable | Value |
|----------|-------|
| AI Model | Claude |
| Topic | Climate Change |
| Technique Tested | Role Prompting |
| Independent Variable | Assigned role |
| Dependent Variable | Response quality and reasoning style |
| Controlled Variables | Same AI model, same topic, same language, same session |

---

## Prompt A

```text
Can rapid shifts to renewable energy still prevent the worst outcomes?
```

---

## Prompt B

```text
Act as an environmental researcher.

Explain whether rapid shifts to renewable energy can still prevent the worst outcomes of climate change.

Use clear language suitable for a university student.
```

---

## Results

### Prompt A

The response accurately explained the current state of renewable energy adoption and acknowledged that global emissions remain high. It provided a balanced answer but mainly presented facts without deeply explaining the mechanisms behind them.

### Prompt B

The response demonstrated a more research-oriented style. Instead of simply presenting facts, it synthesized evidence, explained causal relationships, and discussed uncertainty. The response also reframed the question by emphasizing that the duration and magnitude of temperature overshoot are more important than crossing the 1.5°C threshold alone.

---

## Key Observations

- The AI naturally adopted a more analytical tone.
- Evidence was synthesized rather than simply listed.
- The response explained *why* emissions remain high instead of only reporting that they remain high.
- Scientific trade-offs and uncertainty were communicated more clearly.

---

## Evaluation

| Criterion | Prompt A | Prompt B |
|-----------|---------:|---------:|
| Accuracy | 10/10 | 10/10 |
| Clarity | 8/10 | 10/10 |
| Depth of Explanation | 7/10 | 10/10 |
| Evidence Integration | 7/10 | 10/10 |
| Educational Value | 8/10 | 10/10 |

---

## Analysis

The role prompt did not appear to change the factual accuracy of Claude's response. Instead, it changed **how** the information was communicated.

The AI adopted the reasoning style of an environmental researcher by integrating evidence, explaining causal mechanisms, acknowledging uncertainty, and presenting a balanced interpretation rather than a simple summary.

This suggests that role prompting primarily influences communication style and analytical framing rather than factual knowledge.

---

## Reflection

One particularly interesting observation was that Claude did not explicitly state that it was acting as an environmental researcher. Instead, it naturally adopted the reasoning style expected from someone in that role. This indicates that role prompting can influence how an AI organizes and presents knowledge without changing the underlying facts.

---

## Limitations

This experiment focused on a single topic using one AI model (Claude). Results may differ for other domains or models.

Future experiments should compare role prompting across multiple AI systems and subject areas.

---

## Future Work

- Compare role prompting across Claude, ChatGPT, and Gemini.
- Test different professional roles on the same topic.
- Evaluate whether role prompting improves reasoning quality across different domains.

---

## Experiment Metadata

| Item | Value |
|------|-------|
| Experiment | 002 |
| Technique | Role Prompting |
| Model | Claude |
| Status | Completed |

## Practical Applications

The findings from this experiment suggest that role prompting can improve AI performance in tasks that require analytical reasoning and clear communication.

Potential applications include:

- **Educational tutoring:** Creating AI tutors that explain concepts in a structured, student-friendly manner.
- **Research assistance:** Helping researchers summarize literature, interpret evidence, and communicate findings.
- **Technical report writing:** Producing reports with a professional tone and logical organization.
- **Science communication:** Making complex scientific topics easier for non-experts to understand while preserving important nuances.
