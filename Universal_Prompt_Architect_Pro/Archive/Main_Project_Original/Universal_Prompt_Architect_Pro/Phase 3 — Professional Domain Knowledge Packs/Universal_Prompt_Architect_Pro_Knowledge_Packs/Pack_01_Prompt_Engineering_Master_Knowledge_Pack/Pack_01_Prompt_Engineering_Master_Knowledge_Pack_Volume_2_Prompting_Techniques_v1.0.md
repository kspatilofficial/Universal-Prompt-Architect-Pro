# 📘 Prompt Engineering Master Knowledge Pack
## Volume 2 — Prompting Techniques
**Version:** 1.0

# Purpose
This volume explains the major prompt engineering techniques, when to use them, and their strengths and limitations.

---

# 1. Zero-Shot Prompting
## Definition
Provide only the task without examples.

### Best For
- General questions
- Summaries
- Definitions
- Brainstorming

### Advantages
- Fast
- Simple
- Minimal context required

### Limitations
- Less consistent for complex tasks

---

# 2. One-Shot Prompting
## Definition
Provide one example before requesting a similar output.

### Best For
- Formatting
- Style imitation
- Pattern matching

---

# 3. Few-Shot Prompting
## Definition
Provide multiple examples that demonstrate the desired pattern.

### Best For
- Classification
- Structured writing
- Repetitive tasks
- Extraction

---

# 4. Role Prompting
Assign the AI a specific professional role.

Examples:
- Software Architect
- Financial Analyst
- Curriculum Designer
- Technical Writer

Best Practice:
Clearly define expertise, responsibilities, and scope.

---

# 5. Persona Prompting
Specify tone, communication style, and audience.

Examples:
- Beginner-friendly teacher
- Executive consultant
- University professor

---

# 6. Constraint Prompting
Explicitly define limitations.

Examples:
- Maximum word count
- Markdown only
- No assumptions
- Cite sources when available
- Beginner-friendly language

---

# 7. Step-by-Step Prompting
Break complex tasks into sequential actions.

Best for:
- Planning
- Tutorials
- Research
- Multi-stage analysis

---

# 8. Prompt Chaining
Connect multiple prompts where each output becomes input for the next stage.

Typical Flow:
Research → Analysis → Planning → Draft → Review → Final Output

---

# 9. Reflection & Self-Review
Ask the model to evaluate its own response against stated criteria.

Checklist:
- Accuracy
- Completeness
- Clarity
- Consistency
- User intent

---

# 10. Structured Output Prompting

Preferred formats:
- Markdown
- JSON
- YAML
- XML
- Tables
- Checklists

Choose the structure that best fits downstream use.

---

# Decision Guide

| Situation | Recommended Technique |
|-----------|-----------------------|
| Simple question | Zero-shot |
| Match a format | One-shot |
| Learn a pattern | Few-shot |
| Expert reasoning | Role prompting |
| Audience adaptation | Persona prompting |
| Strict requirements | Constraint prompting |
| Complex workflow | Step-by-step + Prompt chaining |
| Quality improvement | Reflection |

---

# Best Practices
- Combine techniques when appropriate.
- Keep instructions consistent.
- Avoid conflicting constraints.
- Test and refine prompts iteratively.

---

# Future Expansion
- Advanced reasoning frameworks
- Multi-agent prompting
- Domain-specific techniques
- Platform-specific optimizations
