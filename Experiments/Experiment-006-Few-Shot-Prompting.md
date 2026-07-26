# Experiment 006 – Few-Shot Prompting

## Experiment Information

| Field | Details |
|--------|---------|
| Experiment | 006 |
| Technique | Few-Shot Prompting |
| AI Model | Qwen |
| Date | 2026-07-26 |
| Task | Text Summarization |
| Objective | Evaluate whether providing examples improves summary quality compared to zero-shot prompting. |

## Objective

To evaluate whether providing examples (few-shot prompting) improves the quality, consistency, and style of AI-generated summaries compared to a zero-shot prompt.

---

## Research Question

Does providing examples before a task help an AI generate summaries that better match the desired style and structure?

---

## Hypothesis

Providing examples will improve output consistency, style matching, and overall quality while maintaining factual accuracy.

---

## Independent Variable

Presence of examples (Few-Shot Prompting).

- Prompt A: No examples (Zero-Shot)
- Prompt B: Two examples provided before the task

---

## Dependent Variable

Quality of the generated summary measured using:

- Accuracy
- Format Consistency
- Clarity
- Style Matching
- Overall Quality

---

## Controlled Variables

- AI Model: Qwen
- Task: Text summarization
- Input paragraph: Rainforests
- Evaluation rubric
- Evaluator

---

# Prompt A (Zero-Shot)

**Prompt**

Summarize this paragraph:

Rainforests are incredibly dense forests found near the equator that receive high amounts of rainfall each year. They are home to more than half of the world's plant and animal species, making them the most diverse ecosystems on Earth. Huge trees form a high ceiling called a canopy, which blocks most sunlight from reaching the forest floor. These forests act as the planet's lungs by absorbing carbon dioxide and releasing clean oxygen into the air. Despite their immense value, millions of acres are cut down every year for farming and logging.

### Output

Rainforests are dense, highly diverse ecosystems located near the equator that receive heavy annual rainfall. Characterized by a thick tree canopy that blocks sunlight, they play a vital role in regulating the Earth's atmosphere by absorbing carbon dioxide and releasing oxygen. Despite their immense ecological value, rainforests face severe threats from ongoing deforestation driven by farming and logging.

---

# Prompt B (Few-Shot)

**Prompt**

Summarize the paragraph into three concise bullet points, following the style shown in the examples.

Example 1:

Paragraph:
Honeybees are busy insects that live in large groups. They fly from flower to flower to collect sweet nectar and yellow dust called pollen. When they bring these things back to their home, they make sweet honey to eat during the cold winter months. Bees also help plants grow by moving pollen from one flower to another flower. Without bees, many plants would not make food or seeds.

Summary:

Honeybees collect nectar and pollen from flowers to make food.

They help plants grow by moving pollen between flowers.

Bees are very important for nature and food.

Example 2:

Paragraph:

The solar system is a vast and fascinating place in space. At its very center is the sun, which is a giant star that gives heat and light to everything around it. Eight large planets travel around the sun in paths called orbits. Earth is the third planet from the sun and is the only one known to have liquid water and living things. Other planets are different, like Mars, which is red and dusty, or Jupiter, which is a giant ball of gas.

Summary:

The sun is at the center of the solar system and provides light and heat.

Eight planets travel around the sun.

Earth is unique because it supports life, while other planets have different features.

Now summarize this paragraph

Paragraph:

Rainforests are incredibly dense forests found near the equator that receive high amounts of rainfall each year. They are home to more than half of the world's plant and animal species, making them the most diverse ecosystems on Earth. Huge trees form a high ceiling called a canopy, which blocks most sunlight from reaching the forest floor. These forests act as the planet's lungs by absorbing carbon dioxide and releasing clean oxygen into the air. Despite their immense value, millions of acres are cut down every year for farming and logging.

### Output

Rainforests are dense forests near the equator with high rainfall that are home to more than half of Earth's plant and animal species.

Their canopy blocks sunlight, and they act as the planet's lungs by absorbing carbon dioxide and releasing oxygen.

Despite their immense value, millions of acres are cut down each year for farming and logging.

---

# Evaluation

| Criterion | Prompt A | Prompt B |
|-----------|---------:|---------:|
| Accuracy | 9/10 | 10/10 |
| Format Consistency | 5/10 | 10/10 |
| Clarity | 8/10 | 10/10 |
| Style Matching | 4/10 | 10/10 |
| Overall Quality | 7/10 | 10/10 |

---

# Findings

- Both prompts produced factually accurate summaries.
- Prompt A generated a well-written paragraph but selected its own structure.
- Prompt B closely followed the style demonstrated in the examples.
- Few-shot prompting significantly improved consistency and style imitation.
- The model naturally adopted the formatting pattern shown in the examples without requiring additional formatting instructions.

---

# Reflection

This experiment demonstrated that Few-Shot Prompting is an effective technique for guiding AI outputs through examples rather than explicit instructions alone. While both prompts produced accurate summaries, the few-shot approach generated responses that better matched the desired writing style and structure. This suggests that providing representative examples helps the model infer formatting patterns and stylistic expectations more effectively than relying solely on a general instruction.

---

# Practical Applications

Few-Shot Prompting can be useful for:

- Educational content creation
- Report summarization
- Customer support responses
- Documentation writing
- Content generation with consistent formatting

---

# Conclusion

Providing examples before a task improved the consistency, clarity, and style of the generated summaries while maintaining factual accuracy. Few-Shot Prompting proved more effective than a simple Zero-Shot prompt when a specific output style was desired.

## Experiment Information

- **Technique:** Few-Shot Prompting
- **Model:** Qwen
- **Date:** 26 July 2026
- **Task:** Text Summarization
