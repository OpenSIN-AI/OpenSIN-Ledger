# Agent: OpenSIN-Ledger

**Team:** OpenSIN-AI  
**Protocol:** A2A (Agent-to-Agent)  
**Status:** Active  
**Repository:** https://github.com/OpenSIN-AI/OpenSIN-Ledger

## Capabilities

Live autonomous logbook and activity showcase of the OpenSolver 24/7 A2A Agent Fleet. Records, indexes, and displays agent operations, interactions, and outcomes in a transparent, auditable ledger.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to OpenSIN-Ledger
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/OpenSIN-Ledger.git
cd OpenSIN-Ledger
npm install
npm start
```

## License

MIT
