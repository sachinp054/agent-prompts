# agent-prompts

Prompts for autonomous engineering agents. One folder per agent.

| Agent | Purpose |
|---|---|
| [cost-perf-optimizer](agents/cost-perf-optimizer/PROMPT.md) | Evidence-based cost and performance right-sizing. Two passes with an approval stop; read-only discovery; changes only via PRs. |

## Usage
Point your agent at a pinned version of the prompt, e.g.:
"Follow `agents/cost-perf-optimizer/PROMPT.md` at tag `cost-perf-optimizer-v2.0`."

## Contributing
All changes go through Pull Requests. Record notable changes in each agent's `CHANGELOG.md`.
