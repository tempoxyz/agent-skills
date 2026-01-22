# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io) format.

## Available Skills

### tempo

Build applications on the Tempo network with access to documentation and source code via MCP.

**Use when:**

- Working with Tempo transactions or TIP-20 tokens
- Integrating stablecoins or payments
- Building on the Tempo protocol
- Exploring Tempo source code

**Features:**

- Search and read Tempo documentation
- Browse source code for [`tempoxyz/tempo`](https://github.com/tempoxyz/tempo) (Rust node) and [`tempoxyz/tempo-ts`](https://github.com/tempoxyz/tempo-ts) (TypeScript SDK + Examples)
- Access related libraries: [Viem](https://viem.sh/tempo), [Wagmi](https://wagmi.sh/tempo), [Reth](https://github.com/paradigmxyz/reth), [Foundry](https://github.com/foundry-rs/foundry)

**Categories covered:**

- Transactions & accounts
- TIP-20 stablecoins
- Fee sponsorship
- Protocol integration

## Installation

Install with [`skills`](https://skills.sh/docs) CLI:

```bash
npx skills add tempoxyz/agent-skills
```

Or manually:

```bash
# Clone the repo
git clone https://github.com/tempoxyz/agent-skills.git

# Copy a skill to your agent's skills directory
cp -r agent-skills/skills/tempo ~/.config/agents/skills/
```

Or add to your project's `.agents/skills/` directory for project-specific access.

### amp

```bash
amp skill add tempoxyz/agent-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**

```
How do I create a TIP-20 stablecoin?
```
```
Show me how fee sponsorship works in Viem
```
```
Search the Tempo source for transaction validation
```

## Skill Structure

Each skill contains:

- `SKILL.md` - Instructions for the agent
- `mcp.json` - MCP server configuration (optional)

## License

MIT
