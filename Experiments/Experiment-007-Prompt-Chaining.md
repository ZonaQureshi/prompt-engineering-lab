# Experiment 007 – Prompt Chaining

# Experiment 007 – Prompt Chaining

---

# Experiment Information

| Field | Details |
|------|---------|
| Experiment ID | 007 |
| Technique | Prompt Chaining |
| Category | Prompt Engineering |
| AI Model | ChatGPT (GPT-5.5) |
| Date Conducted | 26 July 2026 |
| Status | Completed |
| Difficulty | Intermediate |
| Objective | Compare a single comprehensive prompt with a chained prompting workflow to evaluate response quality. |

---

# Model Configuration

| Parameter | Value |
|-----------|-------|
| Model | GPT-5.5 |
| Temperature | Default |
| Top-p | Default |
| Max Tokens | Default |
| System Prompt | Default ChatGPT system prompt |
| Conversation Type | Multi-turn conversation |
| Output Format | Markdown |
| Prompting Technique | Prompt Chaining |

---

# Objective

Evaluate whether Prompt Chaining produces higher-quality responses than using a single comprehensive prompt.

---

# Research Question

> Does Prompt Chaining improve response quality, organization, and depth compared to solving a complex task with a single prompt?

---

# Hypothesis

Breaking a complex task into multiple sequential prompts will improve clarity, logical flow, and completeness by allowing the AI to focus on one objective at a time.

## Objective

Evaluate whether Prompt Chaining produces higher-quality responses than using a single comprehensive prompt.

---

# Research Question

> Does Prompt Chaining improve response quality, organization, and depth compared to solving a complex task with a single prompt?

---

# Hypothesis

Breaking a complex task into multiple sequential prompts will improve clarity, logical flow, and completeness by allowing the AI to focus on one objective at a time.

---

# AI Model

- **Model:** ChatGPT (GPT-5.5)

---

# Prompt A (Single Prompt)

## Prompt

```text
Explain classical conditioning.

Include:
- Definition
- Key concepts
- Everyday example
- Importance in psychology
```

## Output

# Classical Conditioning

## Definition

**Classical conditioning** is a type of learning in which a neutral stimulus becomes capable of producing a response after being repeatedly paired with a stimulus that naturally produces that response. It was first discovered by the Russian physiologist **Ivan Pavlov** through his experiments with dogs.

genui{"biology_neuroscience_behavior_senses_learning_block":{"type_id":"CLASSICAL_CONDITIONING"}}

## Key Concepts

* **Unconditioned Stimulus (US):** A stimulus that naturally triggers a response (e.g., food).
* **Unconditioned Response (UR):** The automatic, natural reaction to the unconditioned stimulus (e.g., salivating when food is presented).
* **Neutral Stimulus (NS):** A stimulus that initially does not produce the desired response (e.g., a bell before conditioning).
* **Conditioned Stimulus (CS):** The previously neutral stimulus that, after repeated pairing with the unconditioned stimulus, triggers a response (e.g., the bell after conditioning).
* **Conditioned Response (CR):** The learned response to the conditioned stimulus (e.g., salivating when hearing the bell alone).

## Everyday Example

Imagine your phone always plays a particular notification sound before you receive a message from a close friend. Over time, you may start feeling excited as soon as you hear that notification sound, even before reading the message.

* **Unconditioned Stimulus (US):** Receiving a message from your friend.
* **Unconditioned Response (UR):** Feeling happy or excited.
* **Neutral Stimulus (NS):** The notification sound.
* **Conditioned Stimulus (CS):** The notification sound after repeated pairing with your friend's messages.
* **Conditioned Response (CR):** Feeling excited when you hear the notification sound.

## Importance in Psychology

Classical conditioning is important because it:

* Explains how many behaviors and emotional reactions are learned.
* Helps psychologists understand the development of fears, phobias, and anxiety.
* Forms the basis of some behavioral therapies, such as **systematic desensitization** for treating phobias.
* Has applications in education, advertising, and animal training by showing how associations influence behavior.


---

# Prompt B (Prompt Chaining)

## Prompt 1

```text
Explain classical conditioning in simple language.

Only include:
- Definition
- Key concepts
```

### Output

## Definition

**Classical conditioning** is a simple way of learning where a person or animal starts to connect one thing with another. After repeated pairing, a neutral thing (like a bell) can cause a response on its own.

genui{"biology_neuroscience_behavior_senses_learning_block":{"type_id":"CLASSICAL_CONDITIONING"}}

## Key Concepts

* **Unconditioned Stimulus (US):** Something that naturally causes a response (e.g., food).
* **Unconditioned Response (UR):** The natural reaction to the stimulus (e.g., salivating when seeing food).
* **Neutral Stimulus (NS):** Something that does not cause the response at first (e.g., a bell).
* **Conditioned Stimulus (CS):** The neutral stimulus after it has been paired with the unconditioned stimulus (e.g., the bell after training).
* **Conditioned Response (CR):** The learned response to the conditioned stimulus (e.g., salivating when hearing the bell).


---

## Prompt 2

```text
Using the explanation above,

Give one detailed real-life example of classical conditioning.

Explain each stage of the conditioning process.
```

### Output

### Real-Life Example: School Lunch Bell

A student hears the **school lunch bell** every day just before going to lunch. At first, the bell has no special meaning. After many days of hearing the bell before eating, the student starts feeling hungry as soon as the bell rings, even before seeing any food.

genui{"biology_neuroscience_behavior_senses_learning_block":{"type_id":"CLASSICAL_CONDITIONING"}}

### Stages of the Conditioning Process

1. **Before Conditioning**

   * **Unconditioned Stimulus (US):** Food.
   * **Unconditioned Response (UR):** Feeling hungry or salivating when food is presented.
   * **Neutral Stimulus (NS):** The school lunch bell, which does not make the student hungry by itself.

2. **During Conditioning**

   * The **lunch bell** is rung every day just before food is served.
   * The student repeatedly hears the bell and then receives food.
   * The student begins to associate the sound of the bell with eating.

3. **After Conditioning**

   * The **bell becomes the Conditioned Stimulus (CS)** because it has been linked with food.
   * The **Conditioned Response (CR)** is feeling hungry or beginning to salivate when hearing the bell, even if no food is visible yet.

This example shows how a neutral stimulus (the lunch bell) becomes associated with a natural stimulus (food), leading to a learned response (feeling hungry).


---

## Prompt 3

```text
Using the previous explanation and example,

Explain why classical conditioning is important in psychology.

Keep the explanation concise and suitable for university students.
```

### Output

## Importance of Classical Conditioning in Psychology

Classical conditioning is important because it explains how people and animals learn through **association**. It helps psychologists understand how emotions, habits, fears, and preferences develop over time.

genui{"biology_neuroscience_behavior_senses_learning_block":{"type_id":"CLASSICAL_CONDITIONING"}}

It is widely used to:

* Understand the development of **phobias, anxiety, and emotional responses**.
* Develop **behavioral therapies**, such as treating phobias through gradual exposure.
* Explain how **everyday experiences** shape behavior through repeated associations.
* Study learning processes in both humans and animals, providing a foundation for behavioral psychology.


---

# Evaluation Rubric

| Criterion | Prompt A | Prompt B |
|-----------|:--------:|:--------:|
| Accuracy | 8/10 | 10/10 |
| Organization | 8/10 | 10/10 |
| Depth | 7/10 | 10/10 |
| Logical Flow | 8/10 | 10/10 |
| Overall Quality | 8/10 | 10/10 |

---

# Analysis

## Prompt A

### Strengths

- Correct explanation of classical conditioning.
- Covered all requested topics.
- Easy to read.
- Suitable as a quick overview.

### Weaknesses

- Limited depth due to addressing multiple tasks simultaneously.
- Everyday example was relatively brief.
- Less structured progression between concepts.

---

## Prompt B

### Strengths

- Broke the learning process into manageable stages.
- Produced more detailed explanations.
- Included a richer real-life example.
- Improved logical progression from concept to application.
- Better suited for educational purposes.

### Weaknesses

- Required three separate prompts.
- Took longer to complete.
- Consumed more tokens than a single prompt.

---

# Findings

Prompt Chaining produced noticeably better results than using a single comprehensive prompt.

Instead of asking the AI to complete several objectives at once, the task was divided into three sequential prompts:

1. Explain the concept.
2. Demonstrate the concept with a real-life example.
3. Explain its significance.

This approach allowed the AI to focus on one objective at a time, resulting in more organized, detailed, and coherent responses.

---

# Key Observations

- Prompt Chaining improved response depth.
- Sequential prompts reduced cognitive load on the model.
- Each response provided useful context for the following prompt.
- The final explanation felt more like a structured lesson than a single generated answer.

---

# Practical Applications

Prompt Chaining is particularly useful for:

- Educational tutoring
- AI learning assistants
- Research assistance
- Technical documentation
- Report generation
- Workflow automation
- Multi-step reasoning tasks
- Content creation pipelines

---

# Limitations

Although Prompt Chaining improves output quality, it has several trade-offs:

- Requires multiple interactions.
- Takes longer than a single prompt.
- Consumes additional tokens/API calls.
- Errors introduced early in the chain may propagate to later responses.

---

# Conclusion

The results support the hypothesis that Prompt Chaining improves response quality by decomposing complex tasks into smaller, sequential steps.

Compared with a single prompt, Prompt Chaining produced responses that were more organized, detailed, and easier to understand.

While this technique requires additional prompts and computational resources, the improvement in response quality makes it valuable for educational content, professional workflows, and AI-assisted reasoning systems.

---

# Key Takeaways

- Prompt Chaining improves organization and logical flow.
- Breaking tasks into smaller steps increases response depth.
- Sequential prompting produces more coherent explanations.
- Prompt Chaining is well suited for complex, multi-stage AI workflows.
- It is commonly used in production AI systems where one prompt builds upon the output of another.

---

# Skills Demonstrated

- Prompt Chaining
- Sequential Prompt Design
- Prompt Engineering
- AI Evaluation
- Comparative Analysis
- Experimental Design
- Technical Documentation
- Critical Thinking

---

# Future Improvements

Future experiments could investigate:

- Combining Prompt Chaining with Few-Shot Prompting.
- Comparing Prompt Chaining across multiple LLMs.
- Measuring token usage and response time.
- Evaluating Prompt Chaining for coding, research, and creative writing tasks.
- Building automated prompt chains using APIs.
