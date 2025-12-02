# Contributing to AI Specialist Prompt Library

🎉 **Thank you for contributing!** This library provides universal prompts that work across all AI platforms.

---

## 📜 Contribution Guidelines

### What We Accept

✅ **Universal Prompts**
- Work on Gemini, ChatGPT, Claude (minimum 3 platforms)
- No platform-specific features or integrations
- Well-tested and production-ready
- Complete documentation using our template

✅ **Improvements**
- Bug fixes in existing prompts
- Better examples or documentation
- Performance enhancements

❌ **What We Don't Accept**
- Platform-specific prompts (must be universal)
- Untested or theoretical prompts
- Low-effort submissions
- Prompts for illegal/unethical purposes

---

## 🚀 How to Contribute

### Step 1: Fork & Clone
```bash
git clone https://github.com/PrototypePrime/AI_Specialist_Prompt_Library.git
cd AI_Specialist_Prompt_Library
```

### Step 2: Create Your Prompt

1. **Copy the template:**
   ```bash
   cp PROMPTS/_TEMPLATE.md PROMPTS/[your-prompt-name].md
   ```

2. **Naming Convention:**
   - Use descriptive names: `Git_Commit_Message_Writer.md`
   - Use underscores for spaces
   - No category subfolders needed (keep it flat!)

3. **Fill out ALL template sections:**
   - Overview with clear description
   - Complete universal prompt
   - At least 2 platform-specific usage examples
   - Testing notes for multiple platforms

### Step 3: Test Across Platforms

**REQUIRED:** Test on at least 3 platforms before submitting:

- [ ] ✅ **Google Gemini** (Free Tier - create a Gem)
- [ ] ✅ **ChatGPT** (Plus - create Custom GPT)
- [ ] ✅ **Claude** (Free Tier or Pro Project)
- [ ] ✅ **Standard chat** (paste prompt in any AI)

**Minimum requirements:**
- 10+ test conversations per platform
- Document any platform-specific quirks
- Verify output quality is consistent

### Step 4: Document Evidence

Include in your prompt file:

1. **Platform compatibility table**
   ```markdown
   | Platform | Tested | Works | Notes |
   |----------|--------|-------|-------|
   | Gemini | ✅ | ✅ | Perfect on Free Tier |
   | ChatGPT | ✅ | ✅ | Requires Plus for Custom GPT |
   | Claude | ✅ | ✅ | Works on Free (paste) or Pro (Project) |
   ```

2. **Example conversations** (at least 2)
3. **Screenshots** (blur sensitive data)

### Step 5: Submit Pull Request

```bash
git checkout -b prompt/your-prompt-name
git add PROMPTS/[your-prompt-name].md
git commit -m "Add [Prompt Name] for [use case]"
git push origin prompt/your-prompt-name
```

**In your PR description:**
```markdown
## Prompt Submission: [Name]

**Category:** [Security/DevOps/etc.]
**Universal Compatibility:** ✅ Yes

### What This Prompt Does
[2-sentence description]

### Why It's Useful
[Real-world use case]

### Platform Testing
- ✅ Gemini: Tested, works perfectly
- ✅ ChatGPT: Tested as Custom GPT
- ✅ Claude: Tested in Projects
- ✅ Standard chat: Works with copy-paste

### Checklist
- [ ] Used official template
- [ ] No platform-specific features
- [ ] Tested on 3+ platforms
- [ ] At least 2 usage examples
- [ ] All sections completed
```

---

## 🎨 Universal Prompt Standards

### Must Be Platform-Agnostic

**✅ GOOD - Universal:**
```markdown
You are a senior Python developer who reviews code for security issues.

RULES:
- Scan for SQL injection, XSS, CSRF
- Provide specific line numbers
- Suggest secure alternatives
- Format: Issue → Risk → Fix
```

**❌ BAD - Platform-Specific:**
```markdown
You are a Gemini Gem that analyzes Google Drive files...
[Uses Actions to call external API...]
[References GPT Store integrations...]
```

### Required Sections (from Template)

1. **Overview** - Category, difficulty, use case
2. **The Prompt** - Complete, copy-paste ready
3. **Usage Examples** - 2+ with inputs/outputs
4. **Platform Notes** - How to use on each platform
5. **Pro Tips** - Optimization advice
6. **Testing Notes** - What you verified

---

## 🔍 Review Process

### What Reviewers Check

1. **Universality**
   - Works on Gemini (Free Tier)
   - Works on ChatGPT (Plus Tier)
   - Works on Claude (Free/Pro Tier)
   - Works in standard chat (copy-paste)

2. **Quality**
   - Clear, specific instructions
   - Proper constraints and format
   - Well-defined expertise domain
   - Real usage examples

3. **Documentation**
   - All template sections filled
   - Platform testing documented
   - Examples with real inputs/outputs

4. **Safety**
   - No illegal/unethical guidance
   - Privacy-respecting
   - No hardcoded secrets/keys

### Timeline

- **Initial Review:** 5 business days
- **Feedback:** We may request changes
- **Merge:** Once approved and universality verified

---

## 🏆 Recognition

Contributors get:
- 🎖️ **Name in prompt's "Created by" section**
- 🌟 **Listed in Contributors section**
- 💎 **Community recognition**

---

## 💬 Questions?

- **💡 Need help?** [Start a Discussion](https://github.com/PrototypePrime/AI_Specialist_Prompt_Library/discussions)
- **🐛 Found a bug?** [Open an Issue](https://github.com/PrototypePrime/AI_Specialist_Prompt_Library/issues)

---

## 📜 Code of Conduct

By contributing, you agree to:
- Create prompts for legitimate, ethical purposes
- Test thoroughly across platforms
- Be respectful and constructive
- Help maintain quality standards

---

**Ready to contribute?** Grab the [template](./PROMPTS/_TEMPLATE.md) and build something amazing! 🚀
