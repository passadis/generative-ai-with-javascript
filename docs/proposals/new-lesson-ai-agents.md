# Proposal: Assessing a potential Lesson 09 (AI agents)

## 1) Gap analysis
The current 8-lesson arc is coherent and progressive for beginners: Lesson 01 establishes GenAI/LLM fundamentals, 02 gets learners shipping a first app, 03 improves prompt quality, 04 introduces structured outputs, 05 adds grounded responses with RAG, 06 adds capability extension through tool calling, and 07-08 teach MCP basics and advanced MCP client patterns. Together, this already covers the core path from "hello world" prompting to practical interoperability patterns in JavaScript.

The single most valuable missing topic is **AI agents/orchestration**, because it is the natural next conceptual step after tool-calling (06) and MCP integration (07-08): learners can combine model reasoning, tool selection, and iterative execution into a controlled loop. Compared with evaluations/testing, safety/guardrails, multimodal apps, deployment, or observability/cost, agents are the strongest fit *for this specific course narrative and sequence* since they directly compose concepts already taught here (prompts + tools + MCP) into end-to-end behavior learners can immediately recognize and build on.

## 2) Go / No-go recommendation
> ## **NO-GO (for now)**

Although AI agents are the most logical next topic, I recommend **not** adding Lesson 09 in this PR. For this beginner track, the current 8-lesson scope is already complete and appropriately bounded, and introducing agents now risks increasing conceptual load right after MCP. The repository already points learners to a dedicated **AI Agents for Beginners** course, which is a better venue for deeper agent orchestration patterns without overextending this course’s beginner promise. Revisit a Lesson 09 proposal later only if maintainers explicitly want this course to expand beyond its current foundational scope.
