# Lightberry

Lightberry is a San Francisco robotics software company (Y Combinator Fall 2025) that builds
conversational AI "personality" software for humanoid and quadruped robots. Its platform lets a robot
listen, speak, see its surroundings, and act on natural-language instruction without the owner writing
any code. Lightberry ships pre-installed on robots sold through its partnership with Unitree, and runs
a manufacturer-compatibility program with makers including Fourier, Booster Robotics, and High Torque.

- Website: https://lightberry.com
- Docs: https://docs.lightberry.com
- Y Combinator: https://www.ycombinator.com/companies/lightberry
- Contact: hello@lightberry.com

Backed by: y-combinator

## API surface

Lightberry publishes **no public API** as of 2026-07-19 — no developer portal, API reference, OpenAPI
or AsyncAPI definition, SDK, CLI, sandbox, changelog, or status page. Public documentation covers
device setup plus an MCP architecture note describing an MCP server that routes tool calls to
individual devices (each device exposing a REST endpoint), resolved via Tailscale. No MCP server URL,
transport, or tool list is published, so no `MCPServer` pointer is wired.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `llms/lightberry-llms.txt` | LLMsTxt | generated |
| `security/lightberry-domain-security.yml` | DomainSecurity | probed |
| `well-known/lightberry-well-known.yml` | — (negative evidence) | searched |
| `mcp/lightberry-mcp.yml` | — (status: planned) | searched |
