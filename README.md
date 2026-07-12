# AI Agent, Automation & Enablement Portfolio

**Building AI workflows that are functional, transparent, and actually teachable.**


---
## 🎯 The Problem I'm Solving

**AI tools are powerful, but most implementations are either too simplistic to be useful or too complex to understand and maintain.**

I build AI agents, workflows, and enablement tools that bridge this gap — creating solutions that are:
- **Functional** → Actually solve real problems in education, content workflows, and research
- **Transparent** → Documented prompts and logic you can learn from and adapt
- **Practical** → Production-ready examples with real inputs/outputs, not just demos

My work focuses on **customer education, partner enablement, and applied AI for learning design** — proving that AI automation can improve both efficiency *and* understanding.
---

## 📂 Projects
**Here's how I apply these principles:**

- [Document Processing & Archival Agent](https://github.com/1beebe/document-archivist)
  → A MindStudio AI agent that automatically processes PDF documents from email attachments, cleans up OCR text, and organizes documents with structured metadata.

- [Analytics Buddy](https://github.com/1beebe/analytics-buddy)
  → Browser extension + MindStudio workflow for personal social media analytics. Grab analytics from a social media platform, update your spreadsheet, and return actionable insights.

- [AI Image Model Comparison](https://1beebe.github.io/ai-agent-portfolio/image-model-comparison/)
  → A MindStudio workflow that runs 6 image generation models in parallel against the same prompt and delivers a stunning visual comparison — all from a single text input. My first vibe-coded build, and proof that no-code AI orchestration can produce genuinely sophisticated results.

  **How it works:** A user submits a rough text prompt → an LLM enhances it into a high-quality image generation prompt → two parallel execution groups fire all 6 models simultaneously → alt text is generated for each output → a fully custom frontend is generated to render the results as a beautiful side-by-side gallery. Includes metered billing per run.

  **Models compared:** Gemini 3 Pro Image · Flux Pro 2 · Kling Image O3 · Ideogram V3 · Stable Image Ultra · GPT Image 1.5

  **Live gallery outputs** (generated assets delivered to users):
  [Nausica Solarpunk](https://files.mindstudio-cdn.com/42728a5f-5026-4cab-a436-ca9b80d78412/documents/47f1b8c0-948b-4bfb-abd3-fab5648788c9.html) · [D&D Mage](https://files.mindstudio-cdn.com/7fe9ee16-2915-46c6-9e9f-35bd0c9b0da5/documents/dfa77006-8a9f-440e-95ae-5f64a287c51d.html) · [Scandi Living Room](https://files.mindstudio-cdn.com/42728a5f-5026-4cab-a436-ca9b80d78412/documents/7d60f2c3-6045-48d5-84e3-376259254624.html)

- [AI Prompt Library](https://1beebe.github.io/ai-prompt-library/) · [repo](https://github.com/1beebe/ai-prompt-library)
  → A deployable, interactive prompt library for B2B teams — 55 copy-paste-ready AI prompts organized by department (Sales, CS, Marketing, HR, Finance, Leadership, and more). Single self-contained HTML file, no build step, works with any AI assistant.

  **How it works:** Built from a client engagement as a deliverable, then generalized into a reusable template. A project brief went to Claude Code, which generated the full app — filters, copy buttons, cards — through iterative prompting. Output was then reviewed by prompting Claude Code to evaluate from the perspective of a CEO, COO, and UX reviewer before final QA.

  **[Live demo →](https://1beebe.github.io/ai-prompt-library/)**

- [Daily Product Pulse](https://github.com/1beebe/daily-product-pulse)
  → A Claude Code skill that queries a product's database(s) every morning and posts a formatted health, activity, and billing snapshot to Slack — activity trends, new revenue, and a "heads up" list of trials about to lapse or power users who haven't converted.

  **How it works:** Generalized from a live daily reporting skill built for one of my own products. Anonymized for this portfolio — real database IDs, Slack channel, staff accounts, and revenue figures replaced with config placeholders and fake sample data — so the pattern (parallel multi-database queries, staff-account filtering, churn/expansion triage) is reusable without exposing the underlying business.

- [Beebe Qualitative Skills](https://github.com/1beebe/beebe-qualitative-skills)
  → Two Claude Code skills for LLM-assisted qualitative research: a QualiGPT-style thematic analysis skill, and a policy-framing analysis skill built on the research methodology of my father, Dr. James Beebe — an anthropologist and USAID Foreign Service Officer whose unfinished study on U.S. foreign assistance to South Africa I'm completing.

  **How it works:** The two skills run as one iterative loop — inductive discovery (qualigpt surfaces themes from a document corpus) feeds a researcher-curated codebook, which then drives deductive framing analysis (actor-attributed statements, a conceptual-metaphor register, frame-evolution tracking) as NVivo-importable output.

  **Origin story:** This is the third build in a five-month arc. [Lakoff Lens](https://github.com/1beebe/lakoff-lens) (Jan 2026) was the first attempt — a prototype exploring sentiment and metaphorical framing, aimed at my father's methodology from the start but not yet capable of running it. [Document Processing & Archival Agent](https://github.com/1beebe/document-archivist) came next, building the intake pipeline that turns scanned archive documents into clean, indexed text. This skills repo is the version that can actually run his method on his own archive.

---

## 🏛️ Related Work

- [AI Architect Program](https://github.com/1beebe/ai-architect-program)
  → A 6-week cohort workshop (91 registrants, zero paid marketing, 96% satisfaction) exploring how Claude Code turns raw survey CSVs into polished data stories and stakeholder reports.

---

## 📖 What You'll Find in Each Repo
Each project repo contains:
- **README.md** → overview, features, outcomes, limitations  
- **/assets** → screenshots, demo GIFs, diagrams  
- **/prompts** → system prompts & workflow logic  
- **/data-samples** → dummy JSON/CSV inputs and outputs  

---

## 💬 Want to Connect?
Interested in collaborating, learning more about a specific project, or discussing AI in education/enablement?  
📩 [Book a chat](https://calendly.com/ligaya-b/chat)
