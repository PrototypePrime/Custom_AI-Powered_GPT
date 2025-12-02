# Contributing to Gemini Gems Arsenal

🎉 **Thank you for wanting to contribute!** This project thrives on community-created AI specialists.

---

## 📜 Contribution Guidelines

### What We Accept

✅ **New Gem Prompts**
- Well-tested, production-ready prompts
- Clear use case and value proposition
- Complete documentation using our template

✅ **Improvements to Existing Gems**
- Bug fixes in prompt logic
- Enhanced capabilities
- Better examples or documentation

✅ **Documentation Updates**
- Fixing typos or broken links
- Adding clarity to setup instructions
- New use case examples

❌ **What We Don't Accept**
- Untested or theoretical prompts
- Gems for illegal/unethical purposes
- Low-effort submissions without examples
- Duplicate Gems without significant differentiation

---

## 🚀 How to Contribute

### Step 1: Fork & Clone
```bash
git clone https://github.com/YourUsername/Custom_AI-Powered_GPT.git
cd Custom_AI-Powered_GPT
```

### Step 2: Create Your Gem

1. **Copy the template:**
   ```bash
   cp GEM_PROMPTS/_TEMPLATE.md GEM_PROMPTS/[category]/[your-gem-name].md
   ```

2. **Choose the right category:**
   - `security/` - Cybersecurity, pentesting, compliance
   - `devops/` - Infrastructure, CI/CD, deployment
   - `creative/` - Writing, design, content creation
   - `data/` - Analytics, databases, data science
   - `business/` - Strategy, sales, marketing
   - Other? Create a new category!

3. **Fill out ALL template sections:**
   - Overview with clear description
   - Complete prompt (fully formatted)
   - At least 2 usage examples with real inputs/outputs
   - Setup instructions
   - Pro tips and best practices

### Step 3: Test Thoroughly

Before submitting, **you MUST test your Gem:**

- [ ] Create the Gem in Gemini
- [ ] Run at least **10 different test queries**
- [ ] Verify responses match expectations
- [ ] Test edge cases and failure scenarios
- [ ] Document any limitations or prerequisites

### Step 4: Document Evidence

**Required for approval:**
1. **Screenshot** of your Gem in action (blur any sensitive data)
2. **Example conversation** showing 3-5 exchanges
3. **Version info:** Note if it requires Free vs. Advanced tier

### Step 5: Submit Pull Request

```bash
git checkout -b gem/your-gem-name
git add GEM_PROMPTS/[category]/[your-gem-name].md
git commit -m "Add [Gem Name] for [use case]"
git push origin gem/your-gem-name
```

**In your PR description, include:**
```markdown
## Gem Submission: [Name]

**Category:** [Security/DevOps/etc.]
**Tier Required:** [Free / Advanced]

### What This Gem Does
[2-sentence description]

### Why It's Useful
[Real-world use case]

### Testing Evidence
- ✅ Tested with 10+ queries
- ✅ Screenshot attached: [link]
- ✅ Example conversation in documentation

### Checklist
- [ ] Used official template
- [ ] All sections completed
- [ ] At least 2 usage examples
- [ ] Thoroughly tested
- [ ] No sensitive data in examples
```

---

## 🎨 Style Guide

### Prompt Formatting

**Good Prompt Structure:**
```markdown
You are [Specific Role with Authority/Credentials].

PRIMARY ROLE:
[Clear statement of purpose]

HARD CONSTRAINTS:
1. [Unbreakable rule 1]
2. [Unbreakable rule 2]

RESPONSE FORMAT:
[Exact structure the Gem must follow]

EXPERTISE AREAS:
- [Specific skill 1]
- [Specific skill 2]

TONE:
[Personality description]
```

**Avoid:**
- Vague roles: ❌ "You are helpful"
- Missing constraints: ❌ No output format specified
- Overly broad expertise: ❌ "You know everything"

### Documentation Standards

- **Use headings** for scanability
- **Include code blocks** with syntax highlighting
- **Provide real examples**, not placeholders
- **Link to external resources** where helpful
- **Use emoji sparingly** for visual markers (see template)

---

## 🔍 Review Process

### What Reviewers Look For

1. **Completeness**
   - All template sections filled
   - Clear, actionable prompt
   - Multiple tested examples

2. **Quality**
   - Prompt is specific and constrained
   - Examples show real value
   - No obvious errors or broken instructions

3. **Uniqueness**
   - Not a duplicate of existing Gem
   - Adds clear value to the library

4. **Safety**
   - No prompts for illegal/unethical activities
   - Respects privacy and security

### Timeline

- **Initial Review:** Within 5 business days
- **Feedback:** We may request changes
- **Merge:** Once approved and tested

---

## 🏆 Recognition

Contributors get:
- 🎖️ **Name in the Gem's "Created by" section**
- 🌟 **Listed in our Contributors section** (coming soon)
- 💎 **Community karma** for helping others

Top contributors may be invited to co-maintain specific Gem categories!

---

## 💬 Questions?

- **💡 Idea for a Gem but need help?** [Start a Discussion](https://github.com/YourUsername/Custom_AI-Powered_GPT/discussions)
- **🐛 Found a bug?** [Open an Issue](https://github.com/YourUsername/Custom_AI-Powered_GPT/issues)
- **📧 Direct contact:** [Your email or contact method]

---

## 📜 Code of Conduct

By contributing, you agree to:
- Be respectful and constructive
- Create Gems for legitimate, ethical purposes
- Give credit where credit is due
- Help maintain a welcoming community

---

**Ready to contribute?** Let's build the ultimate AI specialist library together! 🚀
