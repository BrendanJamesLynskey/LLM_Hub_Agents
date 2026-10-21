<!-- portfolio-strip:start (brief 40) -->
<sub>**Brendan Lynskey** · [Portfolio home](https://brendanjameslynskey.github.io/) · [Interactive sites](https://brendanjameslynskey.github.io/#sites)</sub>
<!-- portfolio-strip:end -->

# Agents &amp; Orchestration

How LLM agents actually work, multi-agent coordination patterns, and the framework landscape (LangGraph, CrewAI, AutoGen, OpenAI Agents SDK).

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Agents/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [How LLM Agents Work](https://github.com/BrendanJamesLynskey/LLM_Agents_guide) | live | Visual deep dive into agent anatomy &mdash; the ReAct loop, tool execution, memory management, and prompt assembly. |
| 02 | [Multi-Agent Workflows](https://github.com/BrendanJamesLynskey/MultiAgent_Workflows_guide) | live | Multi-agent coordination and delegation, with examples from LangGraph and the OpenAI Agents SDK. |
| 03 | [Introduction to LangGraph](https://github.com/BrendanJamesLynskey/Introduction_to_LangGraph) | live | Interactive slide deck + 10 runnable examples (Python &amp; TypeScript) covering graph-based agent orchestration. |
| 04 | [Agentic Frameworks Guide](https://github.com/BrendanJamesLynskey/Agentic_Frameworks_Guide) | live | Visual guide to the agentic framework landscape &mdash; LangGraph, CrewAI, AutoGen, architecture patterns, and how to choose. |
| 05 | [OpenClaw Guide](https://github.com/BrendanJamesLynskey/OpenClaw_Guide) | live | Deep dive into the open-source gateway connecting AI coding agents to any messaging platform. |
| 06 | [ReAct Math Agent](https://github.com/BrendanJamesLynskey/ReAct_math_agent) | live | Browser-based ReAct agent that solves maths problems step-by-step with a local Ollama LLM, visualising the reasoning loop. |
| 07 | [Research Digest Agent](https://github.com/BrendanJamesLynskey/Research_Digest_Agent) | live | Autonomous research agent that searches the web, reads sources, and produces structured markdown digests (Claude or Ollama). |
| 08 | [Pydantic AI Deep Dive](https://github.com/BrendanJamesLynskey/Pydantic_AI_Guide) | live | In-depth visual guide to Pydantic AI &mdash; type-safe agents, structured outputs, dependency injection, tools &amp; `ModelRetry`, streaming, Pydantic Graph, durable execution, MCP, Logfire observability and evals. |

## Related

**Related site:** [Agent Harnesses Explained](https://agent-harnesses-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-harnesses-explained)) is an interactive companion to this series: the harness that turns a chat model into an agent, in 10 chapters, each built around an animation computed by a deterministic agent-loop simulator: the agent loop, tool calling (native calls vs ReAct text), the context window as a budget, prompt caching, permissions and the human in the loop, sub-agents, hooks and sandboxing, failure and recovery, the public coding-agent harnesses compared, and the cost and latency of a task. No live model is called; three recorded runs of a small open-weights model are replayed token for token.

**Related site:** [Agent Protocols Explained](https://agent-protocols-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-protocols-explained)), the second agent companion site: how agents talk to tools and to each other at the level of messages on the wire, in 9 chapters, each built around an animation: why a protocol, JSON-RPC and the life cycle of a session, tools, resources and prompts, transports, sampling and elicitation, OAuth 2.1 authorisation, gateways and composition, agent to agent (A2A) and protocol security. Every message is sent by a deterministic simulator's protocol state machines and checked against the official MCP and A2A Python SDKs; no live model is called and no real connection is opened.

**Related site:** [Agent Context Explained](https://agent-context-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-context-explained)), the third agent companion site: context engineering, measured, in 9 chapters, each built around an animation: the context window as working memory, lexical retrieval (BM25), dense retrieval, hybrid fusion and reranking, chunking, packing a token budget, compaction and summarisation, agent memory across sessions, and long context or retrieval. Every number is measured on a fixed, openly licensed corpus (6 SQuAD v1.1 articles and 200 of their questions) by a deterministic simulator; a small embedding model and a cross-encoder ran once, offline, and no live model is called.

**Related site:** [Agent Orchestration Explained](https://agent-orchestration-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-orchestration-explained)), the fourth agent companion site: multi-step and multi-agent systems as discrete-event systems, in 9 chapters, each built around an animation: from a chain to a graph, state, channels and reducers, checkpoints and interrupts, durable execution, multi-agent patterns (supervisor, hierarchical, swarm, debate, map-reduce), fan-out under a rate limit, reliability, running at scale and choosing a pattern. The simulator's graph runtime is checked against real LangGraph 1.2.14, checkpoint by checkpoint; no live model is called.

**Related site:** [Agent Evals Explained](https://agent-evals-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-evals-explained)), the fifth agent companion site: how to tell whether an agent is good and how sure you can be, in 10 chapters, each built around an animation: the benchmarks from their papers, pass@k against pass^k, intervals and their coverage, paired comparisons, LLM judges and their biases, grading whole trajectories, one simulated model under sixteen harness configurations, contamination, and the cost of each point of success. No live model: every frame is computed by the evals module of [Agent_Loop_Sim](https://github.com/BrendanJamesLynskey/Agent_Loop_Sim), whose statistics are tested against scipy and statsmodels.

**Related site:** [Agent Security Explained](https://agent-security-explained.vercel.app/) ([code](https://github.com/BrendanJamesLynskey/agent-security-explained)), the sixth agent companion site: how to build agents that stay safe, defences only, in 10 chapters, each built around an animation: trust boundaries and labels on every value, untrusted input, the lethal trifecta, least privilege and audience-bound tokens, sandboxing and egress control, why layered detectors never reach zero, plan-then-execute and the dual-model pattern, approval thresholds and fatigue, the security–utility frontier of every defence on a suite of benign tasks, and a builder's checklist. Threats appear only as labels and cited categories; every frame is computed by the policy module of [Agent_Loop_Sim](https://github.com/BrendanJamesLynskey/Agent_Loop_Sim).

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
