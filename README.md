# Claude Code Agents Collection

A curated collection of 70 specialized AI agents for [Claude Code](https://claude.com/claude-code). Each agent brings domain expertise to help with specific tasks—from quantitative trading to MLOps, from on-chain analytics to real-time systems architecture.

## Installation

Copy the agent files to your Claude Code agents directory:

```bash
# Clone the repository
git clone https://github.com/virtexvirtuoso/claude-code-agents.git

# Copy agents to Claude Code directory
cp claude-code-agents/*.md ~/.claude/agents/

# Restart Claude Code to load new agents
```

## Usage

Agents are invoked automatically by Claude Code when relevant, or explicitly via the Task tool:

```
Use the quant-engineer agent to implement RSI divergence detection
```

List available agents with `/agents` in Claude Code.

---

## Agent Categories

### Trading & Finance

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `crypto-exchange-expert` | The Exchange Whisperer | CEX mechanics, funding rates, liquidation cascades, margin modes |
| `quant-engineer` | The Signal Smith | Vectorized indicators, backtesting, regime detection, statistical validation |
| `python-trading-expert` | — | CCXT integration, exchange APIs, trading bot development |
| `trading-validator` | — | Financial calculation validation, decimal precision, algorithm correctness |
| `pine-script-developer` | — | TradingView Pine Script, custom indicators, strategy development |
| `financial-ml-engineer` | — | ML for finance, price prediction, risk modeling |
| `fintech-ux-designer` | — | Trading dashboards, financial data visualization |
| `on-chain-analyst` | The Chain Reader | Dune/Flipside queries, whale tracking, DEX analytics |

### ML & Data Science

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `mlops-engineer` | The Model Shepherd | Experiment tracking, drift detection, model serving, deployment |
| `data-scientist-researcher` | — | Statistical analysis, hypothesis testing, EDA |
| `data-visualization-architect` | — | Plotly, publication-quality charts, dashboard design |
| `optuna-optimizer` | — | Hyperparameter optimization, multi-objective tuning |

### Real-Time & Performance

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `realtime-systems-architect` | The Latency Hunter | WebSocket state machines, order book sync, backpressure |
| `async-pattern-analyzer` | — | Async/await patterns, concurrency, performance bottlenecks |
| `cache-implementation-reviewer` | — | Caching strategies, Redis, invalidation patterns |
| `dashboard-wizard` | — | Real-time dashboards, API integration, caching |

### Development & Architecture

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `backend-architect` | — | API design, scalable server systems |
| `frontend-developer` | — | Modern UI development, React, performance |
| `api-expert` | — | REST API design, authentication, rate limiting |
| `database-architect` | — | Schema design, query optimization, migrations |
| `architecture-simplifier` | — | Complexity reduction, refactoring, clean code |
| `dependency-injection-expert` | — | DI patterns, IoC containers, decoupling |
| `webhook-expert` | — | Webhook configuration, event processing |
| `mobile-app-builder` | — | iOS/Android development |

### DevOps & Infrastructure

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `devops-automator` | — | CI/CD, deployment pipelines |
| `infrastructure-maintainer` | — | Scaling, cost optimization |
| `security-auditor` | — | Security assessments, vulnerability analysis |
| `project-shipper` | — | Launch preparation, deployment |

### Quality & Testing

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `qa-validation-engineer` | — | End-to-end validation, regression testing |
| `test-writer-fixer` | — | Test development, bug catching |
| `code-documentation-auditor` | — | Documentation review, API docs |

### AI & Prompts

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `ai-engineer` | — | AI/ML feature integration |
| `prompt-engineer` | — | Prompt design, optimization, evaluation |

### Marketing & Growth

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `growth-hacker` | — | Viral growth loops, user acquisition |
| `conversion-copywriter` | — | Ad copy, landing pages, CTAs |
| `paid-media-optimizer` | — | Google/Meta/LinkedIn ads, ROAS optimization |
| `aeo-strategist` | — | Answer Engine Optimization for AI search |
| `content-creator` | — | Multi-platform content generation |
| `twitter-engager` | — | Twitter/X strategy, viral engagement |
| `instagram-curator` | — | Visual content, Instagram strategy |
| `tiktok-strategist` | — | TikTok content, viral marketing |
| `reddit-community-builder` | — | Reddit engagement, community building |
| `app-store-optimizer` | — | ASO, app store rankings |

### Design & UX

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `ui-designer` | — | Interface design, developer handoff |
| `ux-researcher` | — | User insights, product improvements |
| `design-disruptor` | — | Boundary-pushing design, next-gen aesthetics |
| `visual-storyteller` | — | Visual content, conversion optimization |
| `brand-guardian` | — | Visual identity consistency |

### Documentation & Writing

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `technical-writer` | — | API docs, developer guides, READMEs |
| `analytics-reporter` | — | Data-driven insights, reporting |

### Business & Strategy

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `business-model-architect` | — | Pricing, revenue models, unit economics |
| `pitch-strategist` | — | Investor decks, fundraising |
| `competitive-analyst` | — | Market research, competitive positioning |
| `market-validator` | — | Customer discovery, PMF assessment |
| `investor-relations` | — | Term sheets, due diligence, investor updates |

### Legal & Compliance

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `legal-compliance-checker` | — | Regulatory compliance |
| `contract-legal-expert` | — | Contract drafting, negotiation |
| `ip-legal-guardian` | — | IP protection, open-source licensing |

### Team & Operations

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `tech-lead-advisor` | — | Technical leadership, best practices |
| `sprint-prioritizer` | — | Sprint planning, value delivery |
| `studio-producer` | — | Team productivity, shipping focus |
| `support-responder` | — | Customer support, issue resolution |
| `feedback-synthesizer` | — | Feedback analysis, feature prioritization |
| `experiment-tracker` | — | A/B testing, feature validation |
| `finance-tracker` | — | Financial tracking, profitability |
| `trend-researcher` | — | Trend identification, opportunities |

### Utility

| Agent | Persona | Specialty |
|-------|---------|-----------|
| `file-organizer` | — | File system organization, cleanup |
| `rapid-prototyper` | — | Fast MVP development |
| `whimsy-injector` | — | Delight, personality, Easter eggs |
| `pepe` | — | Master orchestrator for complex tasks |

---

## Featured: Trading & Crypto Specialists

These agents are specifically designed for cryptocurrency trading systems:

### The Exchange Whisperer (`crypto-exchange-expert`)
Deep expertise in exchange mechanics—funding rates, liquidation cascades, margin modes, and cross-exchange arbitrage. Knows the quirks of Bybit vs Binance vs dYdX.

### The Signal Smith (`quant-engineer`)
Classical quantitative methods implemented in Python. Vectorized indicators, walk-forward optimization, regime detection with HMMs, and rigorous statistical validation.

### The Latency Hunter (`realtime-systems-architect`)
WebSocket state machines, order book synchronization, backpressure handling, and latency profiling. Critical for real-time trading infrastructure.

### The Chain Reader (`on-chain-analyst`)
Extracts alpha from blockchain data. Dune/Flipside query expert, whale tracking, DEX flow analysis, and on-chain signal generation.

### The Model Shepherd (`mlops-engineer`)
Full ML lifecycle management—experiment tracking with MLflow/W&B, drift detection, model serving, and safe deployment strategies.

---

## Agent File Format

Each agent is a Markdown file with YAML frontmatter:

```yaml
---
name: agent-name
description: When to use this agent with examples...
model: inherit
color: cyan
---

System prompt content here...
```

## Contributing

1. Fork the repository
2. Create your agent file following the format above
3. Submit a pull request

## License

MIT License - feel free to use and modify these agents for your own Claude Code setup.
