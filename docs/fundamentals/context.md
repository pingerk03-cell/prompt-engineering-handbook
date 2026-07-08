# Context

## Why this matters

AI models do not automatically know your situation.

They can generate useful answers, but they need enough background information to understand the task correctly.

Context is the information that helps the AI understand what matters.

Without context, the model guesses.

With good context, the model can produce a more relevant, specific, and useful answer.

---

## Learning objectives

After this chapter, you should be able to:

- explain what context means in Prompt Engineering;
- identify missing context in weak prompts;
- add useful context without overloading the prompt;
- use context to make AI outputs more specific and practical.

---

## Concept

Context is the background information that shapes the AI response.

It can include:

- who the user is;
- who the audience is;
- what the goal is;
- what has already happened;
- what constraints exist;
- what examples should be followed;
- what tone or style is needed;
- what information must be avoided.

Context turns a generic task into a specific task.

---

## Weak prompt

```text
Write an email to a client.
```

This is too vague.

The AI does not know:

- who the client is;
- what the email is about;
- whether the tone should be formal or friendly;
- what outcome is expected;
- what information must be included.

---

## Stronger prompt with context

```text
You are a professional freelance communication assistant.

Write a polite follow-up email to a client who asked about my AI prompt engineering service on Kwork but has not replied for 3 days.

Context:
- The client is interested in prompts for business content creation.
- I want to sound helpful, not pushy.
- The goal is to invite the client to clarify their task.
- Keep the message short and friendly.

Return only the email text.
```

This version gives the model enough information to write a useful answer.

---

## Engineering perspective

Context is not extra decoration.

It is part of the system design.

When context is missing, the model must infer details. Sometimes those assumptions are wrong.

When context is clear, the output becomes easier to control, evaluate, and improve.

Good context improves:

- relevance;
- tone;
- specificity;
- accuracy;
- usefulness;
- alignment with the real goal.

---

## How much context is enough?

More context is not always better.

Useful context should be relevant to the task.

Ask yourself:

> Does this information help the AI produce a better answer?

If yes, include it.

If no, remove it.

---

## Types of context

### 1. User context

Information about the person using the AI.

Example:

```text
I am a beginner freelancer creating my first Kwork service.
```

### 2. Audience context

Information about who will read or use the output.

Example:

```text
The target audience is small business owners who do not understand AI tools well.
```

### 3. Business context

Information about the product, service, market, or goal.

Example:

```text
The service helps entrepreneurs create better prompts for marketing and sales.
```

### 4. Task context

Information about what needs to happen.

Example:

```text
The goal is to create a clear service description that builds trust and explains the value.
```

### 5. Constraint context

Information about limits.

Example:

```text
The text must be under 1200 characters and should not sound aggressive.
```

### 6. Style context

Information about tone and communication style.

Example:

```text
Use a professional but friendly tone. Avoid hype and exaggerated promises.
```

---

## Common mistakes

### Mistake 1: No context

```text
Write a post.
```

Better:

```text
Write a Telegram post for beginner freelancers who want to learn how AI can help them find clients.
```

### Mistake 2: Too much irrelevant context

Do not include long background stories that do not affect the answer.

### Mistake 3: Hidden assumptions

If something is important, write it clearly.

Do not expect the AI to infer your exact intention.

### Mistake 4: Conflicting context

Avoid giving mixed signals.

Example:

```text
Make it very short, but include a detailed explanation of every point.
```

These instructions conflict with each other.

---

## Context template

Use this structure when adding context:

```text
Context:
- My situation: [describe briefly]
- Audience: [who the output is for]
- Goal: [what should happen]
- Constraints: [limits or rules]
- Tone: [style of communication]
- Important details: [must-include information]
```

---

## Practice task

Improve this weak prompt by adding useful context:

```text
Create a social media post.
```

Your improved prompt should include:

- who the post is for;
- what platform it is for;
- what the goal is;
- what tone should be used;
- what should be included;
- what should be avoided.

---

## Self-check

Before sending a prompt, ask:

- [ ] Did I define the audience?
- [ ] Did I explain the real goal?
- [ ] Did I include relevant background?
- [ ] Did I remove irrelevant details?
- [ ] Did I include constraints?
- [ ] Did I define tone or style if needed?

---

## Key takeaways

- Context helps the AI understand the real situation.
- Missing context creates guessing.
- Good context makes outputs more specific and practical.
- More context is not always better; relevant context is better.
- Context is one of the most important parts of reliable Prompt Engineering.

---

## Next chapter

Next: Instructions — coming soon.
