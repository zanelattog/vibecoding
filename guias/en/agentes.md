[Home](../../README.en.md) · [Português](../pt/agentes.md)

# Agents, tools and teamwork


![Planning, building and review](../../imagens/agentes.png)

## What each term means

| Term | Practical meaning |
| --- | --- |
| AI model | The system that interprets information and generates responses. |
| Agent | Uses a model, instructions and tools to make progress on a task. |
| Tool | A concrete capability, such as reading files or querying a service. |
| Plugin | A package that may provide tools, instructions or integrations. |
| Skill | Reusable instructions for a category of work. |
| MCP | A protocol used by some integrations to expose tools and context to a client. |

An agent does not need its own plugin. Multiple agents can use the same model with different tasks and context. Tool access depends on the client, authentication and permissions.

## When to divide work

A useful split has independent tasks. For example, one person or agent reviews task-list copy while another checks undo behavior. The coordinator checks the combined result afterward.

Define each task's goal, relevant files, boundaries, dependencies and verification. Avoid two agents editing the same file at once. A reviewer can work read-only.

When tasks depend on each other, run them sequentially. For a small change, use one agent. More agents can increase cost, duplicated effort and conflicts.

## What to check at delivery

Each agent saying it has finished is not enough. Inspect the files, run the required checks and verify that the parts work together. If a test did not run, record why instead of claiming validation.

[Original coordination reference](https://github.com/soumatheusgomes/vibe-coding-toolkit/blob/790a895304e0c08b70a5b215c9d334f1c86b816c/docs/tools/02-subagent-orchestration.md).


[Credits and source](../../CREDITS.en.md)
