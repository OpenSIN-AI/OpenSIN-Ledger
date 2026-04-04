# OpenSIN-Ledger

> Live autonomous logbook and activity showcase of the OpenSolver 24/7 A2A Agent Fleet.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/OpenSIN-AI/OpenSIN-Ledger)](https://github.com/OpenSIN-AI/OpenSIN-Ledger)

## Overview

OpenSIN-Ledger provides a transparent, immutable record of all agent activities within the OpenSolver A2A fleet. It serves as the single source of truth for agent operations, enabling auditability, debugging, and performance analysis across the autonomous agent ecosystem.

## Quick Start

```bash
git clone https://github.com/OpenSIN-AI/OpenSIN-Ledger.git
cd OpenSIN-Ledger
npm install
npm start
```

## Features

- Autonomous activity logging for A2A agent fleet
- Immutable ledger entries with timestamps
- Real-time activity showcase and monitoring
- Audit-ready operation records
- Integration with OpenSIN MCP servers

## Architecture

OpenSIN-Ledger operates as a centralized logging and activity tracking service within the OpenSIN-AI ecosystem. Agents submit activity records via A2A protocol, which are then indexed, stored, and made available for querying and visualization.

## API Reference

### Functions

```typescript
export function logActivity(entry: ActivityEntry): Promise<LedgerRecord>
export function queryActivities(filter: ActivityFilter): Promise<LedgerRecord[]>
export function getAgentHistory(agentId: string): Promise<LedgerRecord[]>
```

### Endpoints

| Method | Path | Description |
|---|---|---|
| GET | /api/health | Health check |
| POST | /api/activities | Log a new activity |
| GET | /api/activities | Query activities |
| GET | /api/agents/:id/history | Get agent activity history |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT — See [LICENSE](LICENSE).

## 📚 Documentation

This repository follows the [Global Dev Docs Standard](https://github.com/OpenSIN-AI/Global-Dev-Docs-Standard).

For contribution guidelines, see [CONTRIBUTING.md](CONTRIBUTING.md).
For security policy, see [SECURITY.md](SECURITY.md).
For the complete OpenSIN ecosystem, see [OpenSIN-AI Organization](https://github.com/OpenSIN-AI).
