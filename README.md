# 🤖 AI Specialist Prompt Library
### *Universal Prompts That Work Across Any AI Platform*

<div align="center">


**Creating a Gem:**
- One-time setup: Paste prompt into "Instructions"
- Persistent: Gem remembers forever
- Instant access: Sidebar switcher
- Knowledge: Upload PDFs/docs for context

**Best for:** Personal productivity, development workflows, research

### ChatGPT (Custom GPTs)

**Creating a Custom GPT:**
- Use "Instructions" field for prompt
- Add "Conversation Starters" (4-5 example prompts)
- Can integrate APIs via "Actions"
- Shareable via GPT Store

**Best for:** Public sharing, API integrations, community tools

### Claude (Projects)

**Using with Projects:**
- Add prompt to Project instructions
- Upload supporting documents
- Best for long-form analysis

**Best for:** Book writing, research, document analysis (200K context!)

### Any Chat Interface

**Just paste** the prompt before your first question:

```
[Paste full prompt here]

Now, help me with: [Your question]
```

**Limitation:** You'll need to repaste each new conversation.

---

## 🛠️ Contributing

### Add Your Prompts

1. **Fork** this repository
2. **Copy** `PROMPTS/_TEMPLATE.md`
3. **Create** your prompt following the template
4. **Test** on at least 2 platforms (Gemini + one other)
5. **Submit** Pull Request

**Requirements:**
- ✅ Must work on Gemini, ChatGPT, and Claude
- ✅ No platform-specific features (keep it universal)
- ✅ Tested with 10+ real conversations
- ✅ Include usage examples

**[📋 Full Guidelines →](./CONTRIBUTING.md)**

---

## 🎓 Advanced Techniques

### Multi-Specialist Workflows

Chain specialists for complex tasks:

```mermaid
graph LR
    A[Research Specialist] -->|Data| B[Analyst]
    B -->|Insights| C[Writer]
    C -->|Draft| D[Editor]
    D -->|Final| E[SEO Optimizer]
    
    style A fill:#2563eb,color:#fff,stroke:#1e40af,stroke-width:2px
    style E fill:#16a34a,color:#fff,stroke:#15803d,stroke-width:2px
```

**Example:**
1. **Market Research Specialist** → Gathers data
2. **SWOT Analyst** → Finds opportunities
3. **Pitch Writer** → Creates presentation
4. **Financial Modeler** → Builds projections

### Knowledge Layering

Upload supporting documents for domain expertise:

```
Prompt (Instructions)
  ↓
+ Company Style Guide (PDF)
  ↓
+ API Documentation (Markdown)
  ↓
+ Code Review History (Text)
  ↓
= Specialist that mimics your team
```

**Works on:** Gemini (free), ChatGPT (Plus), Claude (Pro)

---

## 🔐 Privacy & Security

### Universal Best Practices

- ❌ **Don't** upload proprietary code to free tiers
- ✅ **Do** redact API keys, passwords, PII
- ✅ **Do** use separate specialists for public vs. confidential
- ✅ **Do** read each platform's data usage policy

### Free vs. Paid Tiers

**Free Tiers (Gemini, etc.):**
- Data may be used for model training
- Good for: Personal, educational, non-sensitive

**Paid Tiers:**
- Better privacy guarantees
- Often can opt out of training
- Good for: Business, proprietary, confidential

---

## 🤝 Community

- **💬 [Discussions](https://github.com/PrototypePrime/AI_Specialist_Prompt_Library/discussions)** - Share specialists, get help
- **🐛 [Issues](https://github.com/PrototypePrime/AI_Specialist_Prompt_Library/issues)** - Report bugs, suggest prompts
- **⭐ Star this repo** if you're building your AI workforce!

---

## 📄 License

MIT License - Use freely across any AI platform.

---

<div align="center">

### ⚡ Start Building Your AI Workforce

**[Browse Prompts](./PROMPTS/)** • **[Use Template](./PROMPTS/_TEMPLATE.md)** • **[Contribute](./CONTRIBUTING.md)**

---

*"One prompt library. Every AI platform."*

**✨ Recommended:** Start with Google Gemini (FREE!) • **🔄 Compatible:** ChatGPT, Claude, and more

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=PrototypePrime.AI_Specialist_Prompt_Library)

</div>