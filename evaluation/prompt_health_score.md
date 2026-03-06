# Prompt Health Scoring System

## Objective

The Prompt Health Score evaluates how well a prompt is structured for AI systems.  
A higher score indicates a clearer and more optimized prompt.

This framework helps identify weaknesses in prompts and guide improvements.

---

# Prompt Health Score Model

Each prompt is evaluated across five dimensions.

| Category | Description | Score Range |
|--------|-------------|------------|
| Clarity | Is the prompt clear and understandable? | 0–2 |
| Context | Does the prompt provide sufficient background? | 0–2 |
| Constraints | Are instructions specific and structured? | 0–2 |
| Output Definition | Is the expected output clearly defined? | 0–2 |
| Intent | Is the objective of the prompt obvious? | 0–2 |

Maximum Score = **10**

---

# Scoring Guide

### 0
Missing or extremely unclear

### 1
Partially defined but incomplete

### 2
Clearly defined and optimized

---

# Example Evaluation

## Weak Prompt

"Write about digital marketing."

### Score

| Category | Score |
|--------|------|
| Clarity | 1 |
| Context | 0 |
| Constraints | 0 |
| Output Definition | 0 |
| Intent | 1 |

Total Score = **2 / 10**

---

## Optimized Prompt

"Write a 200-word beginner-friendly explanation of digital marketing for small business owners. Include 3 main strategies and a short example for each."

### Score

| Category | Score |
|--------|------|
| Clarity | 2 |
| Context | 2 |
| Constraints | 2 |
| Output Definition | 2 |
| Intent | 2 |

Total Score = **10 / 10**

---

# Why This Matters

Prompt evaluation frameworks are important for:

• AI product teams  
• Prompt engineers  
• AI researchers  
• Content automation systems  

A structured scoring system enables consistent improvement of prompts.

---

# Integration with PromptClinic

Prompt Health Score is used in the PromptClinic workflow to:

1. Diagnose prompt weaknesses
2. Repair prompt structure
3. Compare output quality
4. Track improvement across iterations

---

# Future Improvements

Future versions of the framework may include:

• Automated prompt scoring  
• LLM evaluation benchmarks  
• Prompt testing datasets  
• AI output quality metrics
