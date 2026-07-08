# Lab 01: Improve a Weak Prompt

## Goal

In this lab, you will practice turning a vague prompt into a clearer and more useful AI instruction.

This is the first practical exercise in the Prompt Engineering Handbook.

---

## Why this lab matters

Prompt Engineering is not only about knowing definitions.

It is a practical skill.

The fastest way to improve is to take weak prompts, identify what is missing, improve them, and compare the results.

---

## Starting prompt

Here is the weak prompt:

```text
Write a business plan.
```

At first glance, this looks normal.

But it is too vague to produce a reliable result.

---

## Step 1: Diagnose the problem

Ask yourself what is missing.

The prompt does not explain:

- what business the plan is for;
- who the target audience is;
- what the business goal is;
- what market or location matters;
- how detailed the plan should be;
- what format the answer should follow;
- what constraints should be respected.

---

## Step 2: Define the real goal

Before improving the prompt, define the goal.

Example goal:

```text
I want a simple business plan for an online English tutoring service for beginner adults.
```

This is much clearer than just saying "business plan".

---

## Step 3: Add context

Now add information that helps the AI understand the situation.

Useful context may include:

- business type;
- target audience;
- budget;
- timeline;
- location;
- available skills;
- preferred channels;
- main challenge.

Example:

```text
The business is an online English tutoring service.
The target audience is beginner adults who want practical conversational English.
The founder is a school English teacher with limited marketing experience.
The starting budget is $100.
The goal is to get the first 5 paying students within 30 days.
```

---

## Step 4: Create an improved prompt

Improved version:

```text
You are a business strategist for solo online educators.

Create a simple 30-day business plan for an online English tutoring service.

Context:
- The service helps beginner adults improve practical conversational English.
- The founder is a school English teacher with limited marketing experience.
- Starting budget: $100.
- Main goal: get the first 5 paying students within 30 days.
- Main channels: Instagram, Telegram, direct outreach, and referrals.

Return the plan with these sections:
1. Business idea summary
2. Target audience
3. Main offer
4. Pricing suggestion
5. 30-day action plan
6. Simple marketing strategy
7. Risks and how to reduce them
8. Success metrics

Keep the plan practical, beginner-friendly, and realistic for one person working 2 hours per day.
```

---

## Step 5: Explain why it is better

The improved prompt works better because it includes:

- a clear AI role;
- specific business context;
- a measurable goal;
- realistic constraints;
- required output sections;
- success criteria;
- audience and channel information.

The model no longer has to guess what kind of business plan you need.

---

## Step 6: Your practice task

Now improve this weak prompt:

```text
Make content for my business.
```

Your improved prompt should include:

- role;
- business context;
- target audience;
- content goal;
- platform;
- output format;
- constraints;
- quality criteria.

---

## Suggested answer structure

Use this structure:

```text
You are [role].

Create [specific output] for [business type].

Context:
- [business context]
- [target audience]
- [main goal]
- [platform]
- [constraints]

Return the result as:
1. [section]
2. [section]
3. [section]

Quality criteria:
- [criterion]
- [criterion]
- [criterion]
```

---

## Self-check

Before finishing, check your improved prompt:

- [ ] Is the goal clear?
- [ ] Is the audience defined?
- [ ] Is there enough context?
- [ ] Is the output format specific?
- [ ] Are constraints included?
- [ ] Can the result be evaluated?

---

## Key takeaway

A weak prompt makes the AI guess.

A strong prompt gives the AI enough information to produce a useful result.

Prompt improvement starts by asking:

> What does the AI need to know to complete this task well?
