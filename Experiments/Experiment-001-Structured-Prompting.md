# Experiment 001: Evaluating Structured Prompting

## Experiment Information

| Field | Details |
|--------|---------|
| Experiment | 001 |
| Technique | Structured Prompting |
| AI Model | Gemini |
| Date | 2026-07-23 |
| Task | Information Explanation |
| Objective | Evaluate whether structured prompts produce clearer and more complete responses than unstructured prompts. |

## Overview

This experiment investigates whether a structured prompt produces a higher-quality educational response than a simple prompt when explaining Autism.

The goal was to evaluate how prompt structure influences clarity, organization, and usefulness while keeping the AI model and topic constant.

---

## Research Question

Does a structured prompt improve AI-generated educational responses compared to a basic prompt?

---

## Hypothesis

A structured prompt containing role, context, and explicit instructions will produce a more comprehensive, organized, and educational response than a basic prompt.

---

## Experimental Setup

| Variable | Value |
|----------|-------|
| AI Model | Gemini |
| Topic | Autism |
| Language | English |
| Session | Same conversation |
| Independent Variable | Prompt structure |
| Dependent Variable | Quality of AI response |
| Controlled Variables | Same model, same topic, same language, same session |

---

## Prompt A

```text
What is Autism?
```

---

## Prompt B

```text
I am a Psychology student in Semester IV learning about neurological disorders.

Act as a university professor and explain Autism.

Include:

- Simple English
- Explanation of terminology
- Daily life examples
- DSM diagnostic criteria
```

---

## Results

### Prompt A

The response accurately explained Autism and covered the core concept.

However, terminology was not explained in depth, examples were limited, and the educational structure was less detailed.

### Prompt B

The response provided:

- Clear explanations of terminology
- Daily life examples
- DSM diagnostic criteria
- A structured educational format
- Content appropriate for a psychology student

---

## Analysis

The structured prompt produced a more useful educational response.

Rather than simply defining Autism, the AI adapted its explanation to the intended audience and organized information in a way that supported learning.

This demonstrates how additional context and explicit task instructions can significantly improve AI-generated educational content.

---

## Limitations

This experiment changed multiple prompt elements simultaneously, including:

- Role prompting
- Audience context
- Output requirements
- Requested examples
- Requested diagnostic criteria

Because several variables changed together, it is not possible to determine which individual prompt engineering technique contributed most to the improved response.

Future experiments should isolate one technique at a time.

---

## Key Takeaways

- Prompt structure strongly influences response quality.
- Clear instructions reduce ambiguity.
- Providing audience context improves educational explanations.
- Explicit output requirements help produce more organized responses.

---

## Future Work

Future experiments will investigate:

- Role Prompting
- Few-Shot Prompting
- Output Constraints
- Prompt Length
- Prompt Evaluation

---

## Experiment Metadata

| Item | Value |
|------|-------|
| Experiment | 001 |
| Technique | Structured Prompting |
| Model | Gemini |
| Status | Completed |

## Reflection

As a psychology student, I found it interesting that prompt engineering can be approached similarly to experimental research. By controlling variables and comparing outputs, it becomes possible to evaluate how individual prompt components influence AI responses.

This experiment reinforced the importance of clear instructions, audience awareness, and systematic evaluation rather than relying on intuition alone.
