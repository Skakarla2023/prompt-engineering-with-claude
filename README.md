# Prompt Engineering with Claude
Personal notes and experiments from Anthropic's applied AI course series and the **Prompt Engineering** course on Udemy.
Built as a reference I'd actually go back to — not just a course archive.

**Courses covered:** Prompt Engineering (Udemy) · AI Fluency Frameworks & Foundations · Building with the Claude API · Introduction to Model Context Protocol
**Status:** 🟡 In Progress

---

## Why This Matters for a Backend Engineer

As an AI Backend Engineer, you won't just call APIs — you'll write system prompts, design prompt pipelines, wire up tool calls, and debug when LLM output breaks your application logic.

This repo tracks that progression end to end: how to prompt well → how to think about AI collaboration → how to build against the Claude API → how to expose tools and context to models via MCP.

---

## Structure

```
prompt-engineering-with-claude/
├── 01-prompt-engineering-udemy/
│ ├── 01-foundations/
│ │ ├── Prompting Essentials.md
│ │ └── Best Practices and Templates.md
│ ├── 02-prompting-techniques/
│ │ ├── Chain-of-thought Prompting.md
│ │ ├── Role Prompting.md
│ │ ├── Step-back Prompting.md
│ │ └── chain-of-density-prompt.txt
│ ├── 03-reasoning-frameworks/
│ │ ├── Program-of-thought.md
│ │ ├── Skeleton-of-thought.md
│ │ └── Tree-of-Thought.md
│ ├── 04-hyperparameters/
│ │ ├── Prompt Hyperparameters.md
│ │ └── Hyperparameter Tuning.md
│ ├── 05-prompt-tuning/
│ │ └── Prompt Tuning.md
│ └── 06-evaluation-and-testing/
│ ├── Prompt AB Testing.md
│ └── Prompt Evaluation.md
│
├── 02-ai-fluency-frameworks-and-foundations/
│ ├── 001-...md
│ ├── 002-...md
│ └── 003-What is Generative AI?.md
│
├── 03-building-with-the-claude-api/
│ └── part1.md
│
├── 04-introduction-to-model-context-protocol/
│ └── part1.md
│
└── README.md
```


---

## Key Techniques at a Glance (Prompt Engineering)

| Technique | What it does | When to use |
|-----------|-------------|-------------|
| Zero-shot | Ask directly, no examples | Simple or general tasks |
| Few-shot | Provide examples in the prompt | Complex or format-specific outputs |
| Chain-of-thought | Ask model to reason step-by-step | Math, logic, multi-step problems |
| Role prompting | Assign a persona or system role | Production system prompts |
| Step-back prompting | Derive principles before answering | Abstract or domain-heavy questions |
| Tree-of-thought | Explore branching reasoning paths | Decision-making, planning |
| Program-of-thought | Use code as an intermediate reasoning step | Numerical reasoning, structured logic |

---

## What Each Section Covers

**01 — Prompt Engineering (Udemy)**
Core prompting techniques, reasoning frameworks, hyperparameters, and evaluation — the foundation for writing prompts that hold up in production.

**02 — AI Fluency: Frameworks & Foundations**
Conceptual grounding on generative AI and effective human-AI collaboration — what these models actually are and how to work with them, not just prompt them.

**03 — Building with the Claude API**
Hands-on: authentication, message structure, system prompts, tool use, and structured output when calling Claude programmatically.

**04 — Introduction to Model Context Protocol (MCP)**
How MCP standardizes connecting models to tools and external context — servers, resources, and tool descriptions.


---

## Resources

- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [Anthropic API Docs](https://docs.anthropic.com)
- [Model Context Protocol Docs](https://modelcontextprotocol.io)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Learn Prompting (free)](https://learnprompting.org)

---

*Part of my AI Backend Engineer learning journey — Summer 2026*
*Connect: [LinkedIn](https://linkedin.com/in/satwika-kakarla) · [GitHub](https://github.com/Skakarla2023)*
