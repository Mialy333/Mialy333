<!-- Profile README for github.com/Mialy333 — goes in a public repo named exactly "Mialy333" -->

<a href="https://my-building-library.vercel.app/en/">
  <img src="https://raw.githubusercontent.com/Mialy333/my-building-library/main/public/og-en.png" alt="My Building Library — an AI engineering library built in public" width="100%">
</a>

## Hi, I'm Mialy 👋

I build AI agents that **check their work before they act**: they cite their sources, verify a transaction before signing it, and refuse when they can't be sure.

Before code, I spent ten years in institutional asset management (Candriam, Northern Trust, Crédit Agricole CIB), explaining complex investment strategies to clients. I bring the same reflex to agents: every claim needs a source, and every action needs a control.

📍 Paris · 🇬🇧 🇫🇷 · Has worked in France, Luxembourg and Japan · **Open to junior AI engineer roles and AI engineering apprenticeships (alternance), in Paris or abroad**

**Stack:** Python · TypeScript · React · WebLLM/WebGPU · Amazon Bedrock AgentCore · Strands Agents · MCP · RAG · Ollama · Solana · pytest · GitHub Actions

---

### What I've built

| Project | What it does | Proof |
|---|---|---|
| 🛒 [**my-gecko-buyer**](https://github.com/Mialy333/my-gecko-buyer) | A buyer agent that pays on Solana, and refuses to sign any transaction it hasn't verified field by field. Ships an MCP tool (`check_purchase`) that other agents can call before signing. | 2 real purchases on devnet · every bad case refused on the right field · 98 tests in CI |
| 🌱 [**one-step**](https://github.com/Mialy333/one-step) | Turns a messy to-do list into one next step. Gemma 2 2B runs entirely in the browser (WebLLM + WebGPU): no backend, nothing leaves your device. Built in one evening for my sister, who used it that night. | [Live demo](https://one-step-jypm.onrender.com) · Hacktoberfest 2026 DEV Challenge · [the story on dev.to](https://dev.to/mialy333/when-everything-feels-urgent-i-built-my-sister-a-tool-that-gives-her-just-one-next-step-3hg7) |
| 🧭 [**novamart-multi-agent-support**](https://github.com/Mialy333/novamart-multi-agent-support) | Five specialist agents (orchestrator, inventory, refunds, policy, replies) on Amazon Bedrock AgentCore, with guardrails, X-Ray tracing and a CloudWatch dashboard. | 120/120 tests · 10/10 adversarial requests handled · [write-up on dev.to](https://dev.to/mialy333/from-finance-to-ai-engineering-6-lessons-i-learned-building-a-multi-agent-support-system-on-amazon-2fm1) |
| 📚 [**grounded-research-agent**](https://github.com/Mialy333/grounded-research-agent) | A local RAG agent that answers only from its documents, cites the paragraph, and refuses otherwise. The model picks the paragraph; the code copies it word for word, so it can't paraphrase a citation wrong. | 15/15 on the course grader, 6/6 safety-critical · runs on a 14B model, no API key |
| 🎫 [**support-chatbot-bedrock-agentcore**](https://github.com/Mialy333/support-chatbot-bedrock-agentcore) | A support chatbot that routes with prompts only, evaluated with an LLM judge. The judge scored it 0.92, then I audited the database and found fake ticket IDs the judge missed. | Lesson: test an agent's side effects, not just its words |
| 🧠 [**agentcore-customer-support-agent**](https://github.com/Mialy333/agentcore-customer-support-agent) | One agent, six capabilities: MCP Gateway → Lambda tools, a knowledge base, cross-session memory, a code interpreter and a browser tool. | 6 scenarios tested on the deployed runtime |

  <p align="center"><img src="https://raw.githubusercontent.com/Mialy333/novamart-multi-agent-support/main/project/starter/evidence/standout/novamart-demo.gif" alt="NovaMart multi-agent support demo" height="200">&nbsp;<img src="https://raw.githubusercontent.com/Mialy333/one-step/main/assets/demo.gif" alt="One step: a messy to-do list becomes one task to do now" height="200"></p>

one-step is mine from the first line. The others started from a course starter (AWS × Udacity Agent Engineer Nanodegree, Dev3Pack AI Engineering Bootcamp). Each README says what was provided and what I wrote.

### Why I switched

I started coding to build a simple website for my own business. I never went back to the business. Two signs told me why: I enjoyed being stuck on a problem for as long as it took, and I loved asking precise questions until the result was exactly right. Those turn out to be most of the job, and they matter even more with AI agents.

### Learning in public

📖 **[My Building Library](https://my-building-library.vercel.app/en/)**: everything I learn, written up as books and chapters, in English and French. 31 chapters, a 54-term glossary, built with Astro and TypeScript ([source](https://github.com/Mialy333/my-building-library)).

✍️ **Writing:** [dev.to/mialy333](https://dev.to/mialy333), one technical article a month.

🔭 **Right now:** Full Stack Open and DevOps with Docker/Kubernetes (University of Helsinki), and a multi-agent project of my own built from the first commit to production, with no starter code.

### Let's talk

I'm happy to get feedback on any of these repos. Open an issue, or reach me on [LinkedIn](https://www.linkedin.com/in/mialyratsimbazafy75) or [X (@ellebuild)](https://x.com/ellebuild).

<details>
<summary>⚡ Fun fact</summary>
<br>
At 7, I convinced my whole class that my father was Denzel Washington. Off-screen, I play piano, swim, and read too much human psychology.
</details>

If one of these projects helped you, a ⭐ helps me more than you'd think.
