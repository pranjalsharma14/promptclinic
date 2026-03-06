# Prompt Diagnosis Framework

PromptClinic introduces a structured system to analyze and improve AI prompts.

Instead of relying on trial-and-error prompting, this framework evaluates prompts using defined quality indicators.

---

# Framework Stages

## 1. Prompt Input

The initial prompt provided by a user.

Example:

Write a blog about marketing.

This prompt is analyzed before being sent to the AI model.

---

## 2. Prompt Diagnosis

The prompt is evaluated for structural weaknesses.

Key diagnostic questions:

• Does the prompt define a clear objective?  
• Is the target audience specified?  
• Are output constraints included?  
• Is tone or style defined?  
• Is the task scope clear?

---

## 3. Weakness Detection

Common prompt weaknesses include:

| Weakness | Impact |
|--------|--------|
| Lack of context | Generic responses |
| Missing audience | Irrelevant tone |
| No constraints | Unpredictable output length |
| No structure | Poor readability |
| Vague objective | Low-value output |

---

## 4. Prompt Repair

The framework reconstructs the prompt by adding:

• clear task objective  
• audience specification  
• tone guidelines  
• structure requirements  
• output constraints  

Example repair:

Weak Prompt  
Write a blog about marketing.

Repaired Prompt  
Write a 500-word beginner-friendly blog explaining digital marketing basics for small business owners. Include 5 key strategies and practical examples.

---

## 5. Output Comparison

Both prompts are executed to compare results.

Evaluation focuses on:

• clarity  
• structure  
• relevance  
• usefulness

---

## 6. Prompt Health Score

Each prompt is scored using a structured evaluation system.

Example:

| Criteria | Score |
|--------|-------|
| Clarity | 2/5 |
| Context | 1/5 |
| Structure | 1/5 |
| Constraints | 1/5 |
| Audience Definition | 1/5 |

Total Score: **6 / 25**

Higher scores indicate stronger prompts.

---

# Why This Framework Matters

Most AI users assume poor output means weak AI.

In reality, poor prompts are the main cause.

PromptClinic demonstrates how structured prompt engineering dramatically improves AI output quality.
