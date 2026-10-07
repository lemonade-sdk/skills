# Lemonade Skills

<div align="center">

[![Lemonade](https://img.shields.io/badge/Lemonade-Local_AI-FFD43B)](https://github.com/lemonade-sdk/lemonade)
[![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-7B2D8E)](https://agentskills.io)
[![Cursor](https://img.shields.io/badge/Cursor-Compatible-000000?logo=cursor&logoColor=white)](https://cursor.com)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Compatible-F07535?logo=claude&logoColor=white)](https://www.anthropic.com/claude-code)
[![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-Compatible-412991?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMi4yODIgOS44MjFhNS45ODUgNS45ODUgMCAwIDAtLjUxNi00LjkxIDYuMDQ2IDYuMDQ2IDAgMCAwLTYuNTEtMi45QTYuMDY1IDYuMDY1IDAgMCAwIDQuOTgxIDQuMThhNS45ODUgNS45ODUgMCAwIDAtMy45OTggMi45IDYuMDQ2IDYuMDQ2IDAgMCAwIC43NDMgNy4wOTcgNS45OCA1Ljk4IDAgMCAwIC41MSA0LjkxMSA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNSAyLjlBNS45ODUgNS45ODUgMCAwIDAgMTMuMjYgMjRhNi4wNTYgNi4wNTYgMCAwIDAgNS43NzItNC4yMDUgNS45OSA1Ljk5IDAgMCAwIDMuOTk3LTIuOSA2LjA1NiA2LjA1NiAwIDAgMC0uNzQ3LTcuMDc0ek0xMy4yNiAyMi40M2E0LjQ3NiA0LjQ3NiAwIDAgMS0yLjg3Ni0xLjA0bC4xNDEtLjA4MSA0Ljc3OS0yLjc1OGEuNzk1Ljc5NSAwIDAgMCAuMzkyLS42ODF2LTYuNzM3bDIuMDIgMS4xNjhhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODNhNC41MDQgNC41MDQgMCAwIDEtNC40OTQgNC40OTR6TTMuNiAxOC4zMDRhNC40NyA0LjQ3IDAgMCAxLS41MzUtMy4wMTRsLjE0Mi4wODUgNC43ODMgMi43NTlhLjc3MS43NzEgMCAwIDAgLjc4IDBsNS44NDMtMy4zNjl2Mi4zMzJhLjA4LjA4IDAgMCAxLS4wMzMuMDYyTDkuNzQgMTkuOTVhNC41IDQuNSAwIDAgMS02LjE0LTEuNjQ2ek0yLjM0IDcuODk2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY2LTEuOTczVjExLjZhLjc2Ni43NjYgMCAwIDAgLjM4OC42NzdsNS44MTUgMy4zNTUtMi4wMiAxLjE2OGEuMDc2LjA3NiAwIDAgMS0uMDcxIDBsLTQuODMtMi43ODZBNC41MDQgNC41MDQgMCAwIDEgMi4zNCA3Ljg3MnptMTYuNTk3IDMuODU1bC01LjgzMy0zLjM4N0wxNS4xMTkgNy4yYS4wNzYuMDc2IDAgMCAxIC4wNzEgMGw0LjgzIDIuNzkxYTQuNDk0IDQuNDk0IDAgMCAxLS42NzYgOC4xMDV2LTUuNjc4YS43OS43OSAwIDAgMC0uNDA3LS42Njd6bTIuMDEtMy4wMjNsLS4xNDEtLjA4NS00Ljc3NC0yLjc4MmEuNzc2Ljc3NiAwIDAgMC0uNzg1IDBMOS40MDkgOS4yM1Y2Ljg5N2EuMDY2LjA2NiAwIDAgMSAuMDI4LS4wNjFsNC44My0yLjc4N2E0LjUgNC41IDAgMCAxIDYuNjggNC42NnptLTEyLjY0IDQuMTM1bC0yLjAyLTEuMTY0YS4wOC4wOCAwIDAgMS0uMDM4LS4wNTdWNi4wNzVhNC41IDQuNSAwIDAgMSA3LjM3NS0zLjQ1M2wtLjE0Mi4wOC00Ljc3OCAyLjc1OGEuNzk1Ljc5NSAwIDAgMC0uMzkzLjY4MXptMS4wOTctMi4zNjVsMi42MDItMS41IDIuNjA3IDEuNXYyLjk5OWwtMi41OTcgMS41LTIuNjA3LTEuNXoiLz48L3N2Zz4=)](https://openai.com/codex/)
[![Gemini CLI](https://img.shields.io/badge/Gemini_CLI-Compatible-4285F4?logo=googlegemini&logoColor=white)](https://ai.google.dev/gemini-api/docs)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

</div>

Agent skills for running AI locally with [Lemonade](https://github.com/lemonade-sdk/lemonade). They work with Cursor, Claude Code, OpenAI Codex, Gemini CLI, and other agents that support the [Agent Skills](https://agentskills.io) format.

## Skills

| Skill | What it does |
| --- | --- |
| [local-ai-use](skills/local-ai-use/SKILL.md) | Sends image generation, text-to-speech, and speech-to-text to a local AI server to save cloud tokens. |
| [local-ai-app-integration](skills/local-ai-app-integration/SKILL.md) | Adds local AI to existing apps with Embeddable Lemonade for offline support, privacy, and lower API costs. |
| [lemonade-router-builder](skills/lemonade-router-builder/SKILL.md) | Turns a plain-language routing request into a validated Lemonade router policy (JSON). |

## Testing

Every skill here is tested with [Skillscope](https://github.com/amd/skillscope), following the same approach as [amd/skills](https://github.com/amd/skills). There are three kinds of tests:

* **Structural**: Checks that the skill is well formed, with the expected files, folder layout, and working references.
* **Routing**: Checks that the skill triggers when it should and stays quiet when it shouldn't, even with the other skills installed alongside it.
* **Behavioral**: Runs the agent end to end and uses an LLM judge to confirm the skill actually does the right thing.

Each skill's test cases live in `skills/<skill>/evals/evals.json`. Structural and routing tests run on every pull request that touches a skill.

## Contributing

Want to add a skill or improve one? Open an [issue](https://github.com/lemonade-sdk/skills/issues) first so we can talk it through before you write any code. Just opening an issue isn't quite enough, though. We'll only be able to merge pull requests once we've agreed on the change there.

## License

[Apache 2.0](LICENSE)
