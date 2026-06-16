# TraceWeave

Protocol for verifiable AI agent interactions built on [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004), combining cryptography, ChainMark steganography, and on-chain session storage.

This repository implements the protocol in a full agent runtime: local LLM inference, MCP tool calls, A2A agent delegation, and artifact generation.

**Core property:** any interaction in a global swarm of ERC-8004 agents is traceable back to the original prompter (a human or a request originating outside TraceWeave).

## Documentation

- **[Architecture](docs/architecture.md)** — session model, watermarking flow, agent runtime, repo layout
- **[ChainMark](docs/chainmark.md)** — steganographic embedding algorithm

## Status

📝 Early draft

## Stack (planned)

| Layer | Technology |
|-------|------------|
| ERC-8004 | [agent0 SDK](https://sdk.ag0.xyz/docs) |
| Inference + structured actions | [Outlines](https://dottxt-ai.github.io/outlines/latest/) + llama.cpp |
| Steganography | ChainMark |
| Tools | MCP |
| Agent-to-agent | A2A |
