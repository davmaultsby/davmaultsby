### Hi, I'm David Maultsby

I build AI agents and measure them. I work through [Noctaire Labs](https://noctairelabs.org), my own company, with Claude and with open-weights models running locally. Every agent I ship has to beat a no-AI baseline, and one unsafe action retires it, however good its score.

I build by directing AI coding agents (Claude Code) and testing what they produce.

#### Featured

**[support-triage-agent](https://github.com/davmaultsby/support-triage-agent)** | Go, Claude, GraphQL, Postgres<br>
A customer-support agent with its safety rules in code: tools see only the sender's own orders, refunds are drafts a person approves, and customer text is fenced against prompt injection. A 50-ticket eval keeps Claude Opus 5.5 (96%, zero safety violations) and retires a local 4B model that also scored 96% but followed two injected refund requests.

**[Inkbound](https://inkbound.chat)** | React, Supabase, Claude | live<br>
An AI roleplay web app where characters stay consistent and remember events across long sessions. Users choose the Claude model for each chat, and every model call goes through an authenticated server-side proxy.

#### Also building (private for now)

- **Aurora**: a local-first assistant app with two assistants on local Qwen models, a memory graph with a nightly review, a voice wake word, and releases gated on acceptance checks.
- **Character harness**: a local model plays a character in a text world it does not control, with grammar-enforced JSON output, replayable runs, and a scorecard against a plain chatbot.
- **codeindex**: an MCP server for semantic code search shared by Claude Code and local agents. It cut a local model's time on a real task from 38.5 s to 11.6 s.

#### Tools

Claude API, MCP, Claude Code, Ollama, llama.cpp, Go, Python, TypeScript, React, Postgres, GraphQL, Supabase, Cloudflare, Linux

#### Contact

[noctairelabs.org](https://noctairelabs.org)
