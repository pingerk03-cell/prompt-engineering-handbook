# Prompt Anatomy

## Why this matters

A weak prompt often fails because it is missing important information.

A strong prompt works better because it has structure.

Prompt Anatomy is the practice of breaking a prompt into its core components so you can understand, improve, and test it systematically.

If you understand prompt anatomy, you can stop guessing and start designing.

---

## Learning objectives

After this chapter, you should be able to:

- identify the main parts of a professional prompt;
- explain why each part matters;
- improve a vague prompt using a structured template;
- evaluate whether a prompt has enough information to produce a useful result.

---

## Concept

A professional prompt usually includes seven key components:

1. Goal
2. Role
3. Context
4. Task
5. Output Format
6. Constraints
7. Quality Criteria

Not every prompt needs all seven components.

But when a task is important, complex, or client-facing, these components help make the output more reliable.

---

## 1. Goal

The goal defines what you want to achieve.

Weak goal:

```text
Help me with marketing.
```

Stronger goal:

```text
Create a 30-day marketing plan to help an online English tutor get the first 5 paying students.
```

A clear goal helps the AI understand the real outcome, not just the topic.

---

## 2. Role

The role tells the AI what perspective to use.

Example:

```text
You are a marketing strategist for solo online educators.
```

A role is useful when you want the AI to use a specific type of expertise.

Good roles are specific.

Weak role:

```text
You are an expert.
```

Stronger role:

```text
You are a conversion copywriter who helps beginner freelancers improve their service pages.
```

---

## 3. Context

Context gives the AI the background information it needs.

Example:

```text
The business is an online English tutoring service for beginner adults.
The founder has teaching experience but limited marketing experience.
The budget is $100.
The goal is to find the first 5 paying students in 30 days.
```

Context reduces guessing.

Without context, the AI fills the gaps with assumptions.

---

## 4. Task

The task defines exactly what the AI should do.

Weak task:

```text
Make something useful.
```

Stronger task:

```text
Create a weekly content plan with 5 Instagram posts, 3 Telegram posts, and 10 outreach message ideas.
```

A good task is specific enough that the result can be evaluated.

---

## 5. Output Format

The output format tells the AI how to structure the answer.

Example:

```text
Return the answer as a table with these columns:
1. Day
2. Platform
3. Content idea
4. Goal
5. Call to action
```

Output format matters because a useful answer is not only correct.

It must also be easy to read, compare, copy, or use.

---

## 6. Constraints

Constraints define limits and rules.

Example:

```text
Keep the plan realistic for one person working 2 hours per day.
Do not suggest paid ads above the $100 budget.
Avoid generic advice.
```

Constraints help prevent unrealistic, vague, or irrelevant answers.

---

## 7. Quality Criteria

Quality criteria define what a good answer should satisfy.

Example:

```text
A good answer should be practical, beginner-friendly, specific, and possible to implement within 30 days.
```

Quality criteria help both the AI and the human evaluate the result.

---

## Engineering perspective

A prompt is not only text.

It is a small interface between a human intention and an AI system.

When the interface is vague, the result becomes unpredictable.

When the interface is structured, the result becomes easier to test and improve.

This is why prompt anatomy matters: it gives you a repeatable way to design better AI instructions.

---

## Full example

### Weak prompt

```text
Write content for my business.
```

### Problems

This prompt does not define:

- the business;
- the audience;
- the platform;
- the goal;
- the number of content pieces;
- the tone;
- the output format;
- the success criteria.

### Improved prompt

```text
You are a content strategist for beginner online educators.

Create a 7-day content plan for an online English tutor who helps beginner adults improve conversational English.

Context:
- The tutor is just starting online.
- The goal is to attract the first 5 potential students.
- Main platforms: Instagram and Telegram.
- The tutor can spend 1 hour per day creating content.

Return the plan as a table with:
1. Day
2. Platform
3. Content topic
4. Short post idea
5. Goal of the post
6. Call to action

Constraints:
- Keep ideas simple to create.
- Avoid generic motivational posts.
- Focus on trust, usefulness, and clear value.

Quality criteria:
- The plan should be practical for one person.
- Each idea should be specific enough to publish.
- The content should help attract beginner adult learners.
```

---

## Common mistakes

### Mistake 1: Asking for a broad result

```text
Make a strategy.
```

Better:

```text
Create a 14-day Instagram strategy for a beginner online English tutor who wants to attract adult learners.
```

### Mistake 2: Forgetting the audience

If the AI does not know who the output is for, it may produce generic content.

### Mistake 3: No output format

Without a format, the answer may be hard to use.

### Mistake 4: No constraints

Without constraints, the AI may suggest unrealistic actions.

### Mistake 5: No quality criteria

Without quality criteria, it is harder to judge whether the answer is actually good.

---

## PromptForge universal prompt template

Use this template when you need a structured prompt:

```text
You are [specific role].

Goal:
[What result should be achieved?]

Context:
[Relevant background information]

Task:
[What exactly should the AI do?]

Output format:
[How should the answer be structured?]

Constraints:
[What should the AI avoid or respect?]

Quality criteria:
[What makes the answer good?]
```

---

## Practice task

Improve this weak prompt:

```text
Help me sell my service.
```

Your improved prompt should include:

- goal;
- role;
- context;
- task;
- output format;
- constraints;
- quality criteria.

---

## Self-check

Before using a prompt, ask:

- [ ] Is the goal clear?
- [ ] Is the role specific?
- [ ] Is there enough context?
- [ ] Is the task concrete?
- [ ] Is the output format defined?
- [ ] Are constraints included?
- [ ] Are quality criteria clear?

---

## Key takeaways

- A prompt is easier to improve when you can see its parts.
- Strong prompts usually include goal, role, context, task, output format, constraints, and quality criteria.
- Structure reduces ambiguity.
- Clear output format makes AI responses easier to use.
- Prompt Engineering is an iterative design process.

---

## Next chapter

Next: [`Context`](context.md)
