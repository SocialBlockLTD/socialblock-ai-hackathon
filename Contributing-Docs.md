```markdown
# 📝 CONTRIBUTING_DOCS.md

Welcome to the **Documentation Contribution Guide** for the [SocialBlock AI Hackathon](https://github.com/SocialBlockLTD/socialblock-ai-hackathon)!

If you're looking to improve, fix, or add to the documentation — you’re in the right place. Whether it’s a typo fix, new tutorial, clarification, or best practices guide, every contribution helps make the hackathon better for all participants.

---

## 📚 What You Can Contribute

You can contribute to the documentation by:

- Fixing typos, broken links, or grammar
- Improving clarity and formatting
- Adding missing sections to guides
- Creating tutorials for starter kits or toolchains
- Writing architectural or design explanations
- Translating key documents (optional)
- Providing SocialFi + AI integration examples

---

## 🗂️ Docs Structure

The documentation lives primarily under:

```

/docs
├── index.md                  # Entry point
├── getting-started.md        # Initial setup and onboarding
├── tutorials/
│    ├── build-with-langchain.md
│    └── deploy-to-solana.md
├── guides/
│    ├── socialfi-integration.md
│    └── zk-reputation-layer.md
├── glossary.md               # Terms and concepts
└── faq.md

```

Starter kits also include internal docs in their respective folders:
```

/starter-kits/<kit-name>/README.md

````

---

## 🧑‍💻 How to Contribute Docs

1. **Fork the repository** to your GitHub account.

2. **Clone your fork**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/socialblock-ai-hackathon.git
   cd socialblock-ai-hackathon
````

3. **Create a new branch**:

   ```bash
   git checkout -b docs/add-tutorial-langchain-scoring
   ```

4. **Add or edit documentation** in the appropriate folder (`/docs` or `/starter-kits/...`).

5. **Write clear, markdown-based documentation**, and follow these conventions:

   * Use `#` and `##` for heading structure
   * Include code blocks with syntax highlighting
   * Prefer active voice
   * Link to other docs with relative paths when possible
   * Use visuals, diagrams, or screenshots when helpful

6. **Commit your changes**:

   ```bash
   git add .
   git commit -m "docs: add LangChain scoring tutorial"
   ```

7. **Push and create a pull request** to the `main` branch of the official repo.

---

## 🧾 Markdown Style Guide

* Use `camelCase` or `snake_case` for code variables
* Use backticks \` for inline code
* Prefer numbered steps (`1.`, `2.`, `3.`) over unordered lists for sequences
* Add anchors for sections if linking internally
* Include `## Prerequisites` and `## Outcomes` in tutorials
* Limit lines to \~100 characters for readability

---

## 💡 Template: Tutorial Structure

Here’s a recommended format for new tutorials:

```markdown
# Build a LangChain-Powered Reputation Score AI

## 🧩 Overview

In this tutorial, you'll build an AI agent using LangChain that dynamically updates on-chain reputation scores.

## ✅ Prerequisites

- Node.js 18+
- LangChain installed
- SocialBlock starter kit cloned

## 🚀 Steps

1. Set up your project folder...
2. Configure the agent memory...

## 🧠 Outcome

You’ll learn how to integrate LangChain with zk-Reputation scoring and see results on the Validator Dashboard.
```

---

## 👮 Code of Conduct

All documentation contributors must follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 🧵 Join the Docs Community

We welcome async collaboration and active writers. Join us on:

* [Telegram](https://t.me/socialblockverify)
* [X Community](https://x.com/i/communities/1883598415004573838)

---

## 💙 Thank You

SocialBlock is built by and for the community. Your contributions to the docs ensure everyone has the knowledge and clarity to build something impactful.

Let’s keep the frontier open and documented ✍️

— The SocialBlock Team

```
