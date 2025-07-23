```markdown
# 📝 Contributing to Documentation

Thank you for your interest in improving the documentation for the **SocialBlock AI Hackathon**! Clear, useful, and accessible documentation helps us grow the community and accelerate innovation in AI + SocialFi.

This guide explains how to contribute to the documentation, including style guidelines, content types, and submission steps.

---

## 📁 Documentation Structure

Documentation is located in the `/docs/` directory of this repository:

```

/docs
├── index.md                 # Main entry point
├── getting-started.md       # Onboarding and setup
├── tutorials/               # Step-by-step how-to guides
├── guides/                  # Deep dives into systems & architecture
├── glossary.md              # Definitions and protocol terms
├── faq.md                   # Frequently asked questions
└── contributing\_docs.md     # This file

```

Additional documentation may exist inside specific starter kits:
```

/starter-kits/<kit-name>/README.md

````

---

## ✍️ What You Can Contribute

You can help by contributing:

- ✅ Fixes for typos, grammar, formatting
- 📘 New tutorials (e.g. building AI validators or bots)
- 🧠 In-depth guides (e.g. zkML, agent reputation scoring)
- 📦 Starter kit usage or deployment instructions
- 🧩 Glossary terms and protocol-specific definitions
- 🌐 Translations (optional; coming soon)

---

## 🛠 How to Contribute Docs

1. **Fork the repository**

   Click the `Fork` button at the top-right of this page.

2. **Clone your fork locally**

   ```bash
   git clone https://github.com/YOUR_USERNAME/socialblock-ai-hackathon.git
   cd socialblock-ai-hackathon
````

3. **Create a new branch**

   Name your branch clearly, e.g.:

   ```bash
   git checkout -b docs/add-ai-agent-tutorial
   ```

4. **Write or edit markdown files in `/docs`**

   Follow our style and formatting guidelines (see below).

5. **Commit and push your changes**

   ```bash
   git add .
   git commit -m "docs: add tutorial for AI Agent with LangChain"
   git push origin docs/add-ai-agent-tutorial
   ```

6. **Open a Pull Request**

   Go to your fork on GitHub and click **"Compare & pull request"**.

---

## 🧑‍🎨 Writing Guidelines

### Markdown Formatting

* Use `#`, `##`, and `###` for logical headings
* Use triple backticks for code blocks with language tags:
  \`\`\`ts
  const hello = 'world';
  \`\`\`
* Use tables, checklists, and lists when helpful
* Keep paragraphs short and scannable
* Prefer relative links (e.g. `../tutorials/...`) over full URLs

### Content Style

* Use clear, concise language
* Avoid jargon unless you define it
* Use the active voice
* Use consistent terminology: "reputation agent," "SocialBlock chain," etc.

### Tutorial Template

```markdown
# Title of Tutorial

## 🧩 Overview

What you're building and why it matters.

## ✅ Prerequisites

- Node.js v18+
- SocialBlock SDK
- Solana wallet (Phantom)

## 🚀 Steps

1. Clone the starter repo
2. Set up the config file
3. Run the scoring agent

## 🧠 Outcome

The agent will write a score to the ARP layer based on Telegram messages.
```

---

## 📚 Suggestions for New Docs

If you're unsure what to contribute, here are ideas:

* 🛡️ “How to write a zkML proof for moderation output”
* 🤖 “Creating a Telegram Bot using SocialBlock reputation scores”
* 🧱 “Deploying a validator node with testnet config”
* 🪄 “Building your own AI agent to propose governance votes”

---

## 👮 Code of Conduct

All contributors must follow our [Code of Conduct](./CODE_OF_CONDUCT.md). Harassment, plagiarism, and abuse will not be tolerated.

---

## 📬 Need Help?

If you have questions or want feedback before submitting:

* Join our [Telegram group](https://t.me/socialblockverify)
* Open a [GitHub Discussion](https://github.com/SocialBlockLTD/socialblock-ai-hackathon/discussions)
* Mention a maintainer in your PR

---

## 💙 Thank You

We’re building this together. Every edit, guide, and example improves the experience for all future builders.

**Let’s document the future of AI + blockchain.**

```
