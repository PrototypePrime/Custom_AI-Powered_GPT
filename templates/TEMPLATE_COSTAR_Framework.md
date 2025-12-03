# CO-STAR Prompt Framework Template

**Framework:** CO-STAR (Context, Objective, Style, Tone, Audience, Response)
**Goal:** Create high-quality, structured prompts for AI specialists.

---

## 1. Context (C)
*Who is the AI? What is the background situation?*
> **Example:** "You are a Senior Security Engineer with 15 years of experience in SOC operations. You are currently investigating a potential data exfiltration incident."

## 2. Objective (O)
*What specifically do you want the AI to do?*
> **Example:** "Your task is to analyze the provided logs, identify the attack vector, and recommend immediate containment steps."

## 3. Style (S)
*What writing style should the AI use?*
> **Example:** "Write in a professional, technical, and concise style suitable for an executive summary."

## 4. Tone (T)
*What is the emotional tone?*
> **Example:** "Maintain a calm, authoritative, and urgent tone."

## 5. Audience (A)
*Who is this response for?*
> **Example:** "The audience is the CISO and the Incident Response team."

## 6. Response (R)
*What is the output format?*
> **Example:** "Provide the output as a structured Markdown report with the following sections: Executive Summary, Technical Analysis, Containment Recommendations, and IOCs."

---

## Final Prompt Assembly
*(Combine the above sections into a single prompt block)*

```markdown
You are a Senior Security Engineer... [Context]
Your task is to... [Objective]
Write in a... [Style]
Maintain a... [Tone]
The audience is... [Audience]
Provide the output as... [Response]
```
