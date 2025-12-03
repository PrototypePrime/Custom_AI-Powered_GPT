# AI Prompt Evaluation Checklist

**Prompt Name:** [Name]
**Date:** [YYYY-MM-DD]
**Evaluator:** [Your Name]

---

## 1. Clarity & Specificity
- [ ] **Context:** Is the AI's role and background clearly defined?
- [ ] **Objective:** Is the task specific and unambiguous?
- [ ] **Constraints:** Are there clear "Do's" and "Don'ts"?

## 2. Robustness
- [ ] **Edge Cases:** Does the prompt handle vague or incomplete inputs gracefully?
- [ ] **Security:** Does it prevent jailbreaking or revealing internal instructions? (e.g., "Ignore previous instructions")
- [ ] **Hallucination:** Are there constraints to prevent making up facts? (e.g., "If you don't know, say you don't know.")

## 3. Output Quality
- [ ] **Format:** Does the output match the requested format (Markdown, JSON, etc.)?
- [ ] **Tone:** Is the tone appropriate for the target audience?
- [ ] **Accuracy:** (Test with known inputs) Is the information provided accurate?

## 4. Test Cases

| Input Scenario | Expected Output | Actual Output | Pass/Fail |
|----------------|-----------------|---------------|-----------|
| Simple Query   | ...             | ...           |           |
| Complex Query  | ...             | ...           |           |
| Adversarial    | (Refusal)       | ...           |           |

## 5. Refinement Notes
*List improvements made based on testing.*
