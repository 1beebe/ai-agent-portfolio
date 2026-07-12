# AI Agent, Automation & Enablement Portfolio

**Building AI workflows that are functional, transparent, and actually teachable.**


---
## 🎯 The Problem I'm Solving

**AI tools are powerful, but most implementations are either too simplistic to be useful or too complex to understand and maintain.**

I build AI agents, workflows, and enablement tools that bridge this gap. The solutions I build are:
- **Functional** → Actually solve real problems in education, content workflows, and research
- **Transparent** → Documented prompts and logic you can learn from and adapt
- **Practical** → Production-ready examples with real inputs/outputs, not just demos

My work focuses on **customer education, partner enablement, and applied AI for learning design**, proving that AI automation can improve both efficiency *and* understanding.
---

## 🧭 First Principles

How I approach AI building and enablement, in priority order:

1. **Understand the work before you automate it.** Before handing anything to an AI (or any automation), know the work well enough to recognize when the output is wrong.

2. **AI literacy is foundational for AI building.** You need to know what an LLM is and why it hallucinates, why the context window matters, what tools and connectors are and how they interact with the model, and how AI workflows differ from classic automation. Skip this and your odds of slop output, broken output, or an endless prompt-iterate-prompt loop go up drastically.

3. **The human is the instrument.** Qualitative researchers say the researcher is the instrument. The same holds for AI work. Humans own the output: review every line of text, every line of code, every result. AI is the tool by which we do the work; discernment and judgment stay with us.

4. **High token burn is not high productivity.** Outcomes decide whether something is working. Sometimes a small local script (a JSON-to-CSV transform, say) beats an AI-driven version on reliability and cost every single day.

5. **We learn best by building, and by building with others.** Communities of practice, real mentorship, learning in public: these are the things to protect and nurture. AI tooling should help us protect that time, not replace it.

**Best practices I hold myself to:**
- **Scope credentials to the minimum.** An unattended automation gets a dedicated, minimally-scoped service account, never a personal login. "The instructions say not to delete things" is a policy; an account that *can't* delete things is a guarantee.
- **If you do a thing more than once, turn it into a skill.** (See [Daily Product Pulse](https://github.com/1beebe/daily-product-pulse) for this one in action.)

---

## 📂 Projects
**Here's how I apply these principles** (dated, so you can see the progression):

- [Analytics Buddy](https://github.com/1beebe/analytics-buddy) · *Oct 2025*
  → Browser extension + MindStudio workflow for personal social media analytics. Grab analytics from a social media platform, update your spreadsheet, and return actionable insights. A simple scrape and transform, and where this all started.

- [Document Processing & Archival Agent](https://github.com/1beebe/document-archivist) · *Jan 2026*
  → A MindStudio AI agent that automatically processes PDF documents from email attachments, cleans up OCR text, and organizes documents with structured metadata.

- [AI Image Model Comparison](https://1beebe.github.io/ai-agent-portfolio/image-model-comparison/) · *Feb 2026*
  → A MindStudio workflow that runs 6 image generation models in parallel against the same prompt and delivers a stunning visual comparison, all from a single text input. My first vibe-coded build, and proof that no-code AI orchestration can produce genuinely sophisticated results.

  **How it works:** A user submits a rough text prompt → an LLM enhances it into a high-quality image generation prompt → two parallel execution groups fire all 6 models simultaneously → alt text is generated for each output → a fully custom frontend is generated to render the results as a beautiful side-by-side gallery. Includes metered billing per run.

  **Models compared:** Gemini 3 Pro Image · Flux Pro 2 · Kling Image O3 · Ideogram V3 · Stable Image Ultra · GPT Image 1.5

  **Live gallery outputs** (generated assets delivered to users):
  [Nausica Solarpunk](https://files.mindstudio-cdn.com/42728a5f-5026-4cab-a436-ca9b80d78412/documents/47f1b8c0-948b-4bfb-abd3-fab5648788c9.html) · [D&D Mage](https://files.mindstudio-cdn.com/7fe9ee16-2915-46c6-9e9f-35bd0c9b0da5/documents/dfa77006-8a9f-440e-95ae-5f64a287c51d.html) · [Scandi Living Room](https://files.mindstudio-cdn.com/42728a5f-5026-4cab-a436-ca9b80d78412/documents/7d60f2c3-6045-48d5-84e3-376259254624.html)

- [AI Prompt Library](https://1beebe.github.io/ai-prompt-library/) · [repo](https://github.com/1beebe/ai-prompt-library) · *Apr 2026*
  → A deployable, interactive prompt library for B2B teams: 55 copy-paste-ready AI prompts organized by department (Sales, CS, Marketing, HR, Finance, Leadership, and more). Single self-contained HTML file, no build step, works with any AI assistant.

  **How it works:** Built from a client engagement as a deliverable, then generalized into a reusable template. A project brief went to Claude Code, which generated the full app (filters, copy buttons, cards) through iterative prompting. Output was then reviewed by prompting Claude Code to evaluate from the perspective of a CEO, COO, and UX reviewer before final QA.

  **[Live demo →](https://1beebe.github.io/ai-prompt-library/)**

- [Daily Product Pulse](https://github.com/1beebe/daily-product-pulse) · *Jun 2026*
  → A Claude Code skill that queries a product's database(s) every morning and posts a formatted health, activity, and billing snapshot to Slack: activity trends, new revenue, and a "heads up" list of trials about to lapse or power users who haven't converted.

  **How it works:** Generalized from a live daily reporting skill built for one of my own products. Anonymized for this portfolio: real database IDs, Slack channel, staff accounts, and revenue figures are replaced with config placeholders and fake sample data, so the pattern (parallel multi-database queries, staff-account filtering, churn/expansion triage) is reusable without exposing the underlying business.

- [Beebe Qualitative Skills](https://github.com/1beebe/beebe-qualitative-skills) · *Jul 2026*
  → Two Claude Code skills for LLM-assisted qualitative research: a QualiGPT-style thematic analysis skill, and a policy-framing analysis skill built on the research methodology of my father, Dr. James Beebe, an anthropologist and USAID Foreign Service Officer whose unfinished study on U.S. foreign assistance to South Africa I'm completing.

  **How it works:** The two skills run as one iterative loop. Inductive discovery (qualigpt surfaces themes from a document corpus) feeds a researcher-curated codebook, which then drives deductive framing analysis (actor-attributed statements, a conceptual-metaphor register, frame-evolution tracking) as NVivo-importable output.

  **Origin story:** This is the third build in a nine-month arc. [Lakoff Lens](https://github.com/1beebe/lakoff-lens) (Oct 2025) was the first attempt: a prototype exploring sentiment and metaphorical framing, aimed at my father's methodology from the start but not yet capable of running it. [Document Processing & Archival Agent](https://github.com/1beebe/document-archivist) (Jan 2026) came next, building the intake pipeline that turns scanned archive documents into clean, indexed text. This skills repo is the version that can actually run his method on his own archive.

---

## 🏛️ Related Work

- [AI Architect Program](https://github.com/1beebe/ai-architect-program) · *Dec 2025 – Feb 2026*
  → A 6-week cohort workshop (91 registrants, zero paid marketing, 96% satisfaction) exploring how Claude Code turns raw survey CSVs into polished data stories and stakeholder reports.

---

## 📖 What You'll Find in Each Repo
Each project repo contains:
- **README.md** → overview, features, outcomes, limitations  
- **/assets** → screenshots, demo GIFs, diagrams  
- **/prompts** → system prompts & workflow logic  
- **/data-samples** → dummy JSON/CSV inputs and outputs  

---

## 👋 About Me

I'm **Ligaya Beebe**, founder of [L. Beebe LLC](https://lbeebe.com) (AI enablement, agent development, and program management for non-technical teams) and co-founder of [10xJobs](https://10xjobs.co).

Before AI, I spent my career helping people learn things they were convinced they couldn't: first in remote China, then NYC public schools, then 9+ years running U.S. State Department-funded education programs across 12+ countries. AI adoption is the same problem in a new context. Most people don't struggle with AI because they're not smart enough. Nobody designed the learning for them. That's the gap this portfolio is built around.

**Credentials:** MindStudio Level 3 AI Agent Developer · PMP · M.A. Social Sciences, University of Chicago

🌐 [lbeebe.com](https://lbeebe.com) · [LinkedIn](https://www.linkedin.com/in/ligaya-beebe)

---

## 💬 Want to Connect?
Interested in collaborating, learning more about a specific project, or discussing AI in education/enablement?  
📩 [Book a chat](https://calendly.com/ligaya-b/chat)
