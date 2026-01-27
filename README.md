# Castari Documentation

Documentation for [Castari](https://castari.com) — deploy Claude agents in seconds.

**[View the docs](https://docs.castari.com)**

## Quick Start

**Prerequisites:** Node.js 18+ and npm installed.

```bash
# Install the CLI
npm install -g @castari/cli

# Login
cast login

# Create an agent from a template
cast init my-agent

# Deploy it
cd my-agent
cast deploy

# Run it
cast invoke my-agent "What files are in the current directory?"
```

## Documentation

### Getting Started
- [Introduction](https://docs.castari.com)
- [Quick Start](https://docs.castari.com/quickstart)
- [Installation](https://docs.castari.com/installation)
- [First Agent](https://docs.castari.com/first-agent)

### CLI Reference
- [Overview](https://docs.castari.com/cli/overview)
- [login](https://docs.castari.com/cli/login)
- [init](https://docs.castari.com/cli/init)
- [deploy](https://docs.castari.com/cli/deploy)
- [invoke](https://docs.castari.com/cli/invoke)
- [agents](https://docs.castari.com/cli/agents)
- [secrets](https://docs.castari.com/cli/secrets)
- [logs](https://docs.castari.com/cli/logs)

### SDK Reference
- [Overview](https://docs.castari.com/sdk/overview)
- [Client](https://docs.castari.com/sdk/client)
- [Agents](https://docs.castari.com/sdk/agents)
- [Secrets](https://docs.castari.com/sdk/secrets)
- [Types](https://docs.castari.com/sdk/types)

### Concepts
- [How It Works](https://docs.castari.com/concepts/how-it-works)
- [Agents](https://docs.castari.com/concepts/agents)
- [Sandboxes](https://docs.castari.com/concepts/sandboxes)
- [Secrets](https://docs.castari.com/concepts/secrets)
- [Invocations](https://docs.castari.com/concepts/invocations)

### Guides
- [Templates](https://docs.castari.com/guides/templates)
- [Custom Agents](https://docs.castari.com/guides/custom-agents)
- [MCP Integration](https://docs.castari.com/guides/mcp)
- [Debugging](https://docs.castari.com/guides/debugging)
- [Best Practices](https://docs.castari.com/guides/best-practices)

## Development

To run the docs locally:

```bash
npm i -g mint
mint dev
```

View at `http://localhost:3000`.

## Links

- [Dashboard](https://app.castari.com)
- [CLI Repository](https://github.com/castari/cli)
- [Twitter](https://x.com/castari_dev)
