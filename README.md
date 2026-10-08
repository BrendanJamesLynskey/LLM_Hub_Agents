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

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
