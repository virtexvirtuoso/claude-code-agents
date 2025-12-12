---
name: "Documentation"
ignore: true
---

# Claude Code Agents Collection

A comprehensive collection of **72 specialized AI agents** for Claude Code, designed to enhance development workflows across software engineering, AI/LLM development, trading systems, security, design, marketing, operations, and product management.

## 📁 Directory Structure

All agents are located in the root directory for easy discovery by Claude Code's `/agents` command:

```
claude-code-agents/
├── 📄 pepe.md                        # Master orchestrator agent
├── 📄 prompt-engineer.md             # LLM prompt design & optimization
├── 📄 security-auditor.md            # Security audits & vulnerability assessment
├── 📄 pine-script-developer.md       # TradingView Pine Script developer
├── 📄 python-trading-expert.md       # Trading systems & exchange APIs
├── 📄 quant-engineer.md              # Quantitative trading strategies
├── 📄 crypto-exchange-expert.md      # CEX mechanics & derivatives
├── 📄 on-chain-analyst.md            # Blockchain data & whale tracking
├── 📄 optuna-optimizer.md            # Hyperparameter optimization
├── 📄 api-expert.md                  # REST API design & integration
├── 📄 qa-validation-engineer.md      # Testing & validation
└── ... 59 more specialized agents
```

## 🚀 Quick Start

### One-Line Install (Recommended)

**Fresh install** (no existing agents):
```bash
git clone https://github.com/virtexvirtuoso/claude-code-agents.git ~/.claude/agents
```

**Smart install** (handles existing setup):
```bash
[ -d ~/.claude/agents/.git ] && cd ~/.claude/agents && git pull || \
([ -d ~/.claude/agents ] && mv ~/.claude/agents ~/.claude/agents.backup.$(date +%s); \
git clone https://github.com/virtexvirtuoso/claude-code-agents.git ~/.claude/agents)
```

**Update existing installation**:
```bash
cd ~/.claude/agents && git pull
```

### Project-Specific Installation
```bash
# Clone to your project's Claude directory (agents only available in this project)
git clone https://github.com/virtexvirtuoso/claude-code-agents.git .claude/agents
```

### Verify Installation
```bash
# In any Claude Code session, run:
/agents
# You should see all 72 agents listed
```

### Merge with Existing Agents
If you have custom agents you want to keep:
```bash
# Clone to temp location and copy agent files
git clone https://github.com/virtexvirtuoso/claude-code-agents.git /tmp/claude-agents
cp /tmp/claude-agents/*.md ~/.claude/agents/
rm -rf /tmp/claude-agents
```

## 📚 Agent Catalog

### 🎯 Master Orchestrator

| Agent | Description | Key Use Cases |
|-------|-------------|---------------|
| **pepe** | Master orchestrator for complex multi-agent workflows | Task decomposition, agent coordination, workflow management |

---

### 🏗️ Architecture (8 agents)

| Agent | Description |
|-------|-------------|
| **api-expert** | REST API design, authentication, and integration |
| **database-architect** | Database design, schema modeling, query optimization, migrations |
| **webhook-expert** | Webhook configuration and event processing |
| **architecture-simplifier** | Reduces complexity and refactors system architecture |
| **async-pattern-analyzer** | Analyzes async/await patterns and concurrency issues |
| **cache-implementation-reviewer** | Reviews caching strategies (Redis, CDN, database) |
| **dependency-injection-expert** | Implements DI patterns and IoC containers |
| **realtime-systems-architect** | WebSocket state machines, order book sync, low-latency systems |

**When to use:** API design, database schema design, query optimization, webhook integration, system redesign, performance optimization, technical debt reduction, SOLID principles, real-time data systems

---

### 🔬 Analysis Tools (6 agents)

| Agent | Description |
|-------|-------------|
| **data-scientist-researcher** | Rigorous data analysis and statistical modeling |
| **data-visualization-architect** | Publication-quality visualizations, chart selection, Plotly mastery |
| **optuna-optimizer** | Hyperparameter tuning and black-box optimization |
| **qa-validation-engineer** | Comprehensive end-to-end validation and testing |
| **code-documentation-auditor** | Reviews and improves documentation quality |
| **file-organizer** | Organizes and optimizes file systems |

**When to use:** Data analysis, data visualization, hyperparameter optimization, hypothesis testing, code reviews, test strategy, project cleanup

---

### 🤖 AI Engineering (2 agents)

| Agent | Description |
|-------|-------------|
| **prompt-engineer** | LLM prompt design, optimization, evaluation frameworks, injection hardening |
| **mlops-engineer** | ML lifecycle: experiment tracking, drift detection, model serving, deployment |

**When to use:** System prompt design, few-shot learning, chain-of-thought reasoning, prompt evaluation (Promptfoo/RAGAS), token optimization, prompt injection defense, MLflow/W&B setup, model registry, feature stores, A/B deployment

---

### 🔒 Security (2 agents)

| Agent | Description |
|-------|-------------|
| **security-auditor** | OWASP Top 10, vulnerability assessment, secure code review, compliance |
| **api-security-specialist** | API security, OAuth2/OIDC, JWT, secrets management, rate limiting, CORS, webhook security, exchange API security |

**When to use:** Security audits, vulnerability assessment, API authentication, OAuth2/JWT implementation, secrets rotation (Vault/AWS), rate limiting, CORS configuration, webhook signature verification, exchange API security, API key lifecycle management, trading system security

---

### 💹 Trading & Crypto (10 agents)

| Agent | Persona | Description |
|-------|---------|-------------|
| **crypto-exchange-expert** | The Exchange Whisperer | CEX mechanics, funding rates, liquidation cascades, margin modes |
| **quant-engineer** | The Signal Smith | Vectorized indicators, backtesting, regime detection, statistical validation |
| **on-chain-analyst** | The Chain Reader | Dune/Flipside queries, whale tracking, DEX analytics, exchange flows |
| **pine-script-developer** | — | TradingView Pine Script v6 indicators and strategies |
| **python-trading-expert** | — | CCXT library and exchange API integration |
| **trading-logic-validator** | — | Validates trading calculations, financial logic, algorithm correctness |
| **trading-validator** | — | Validates financial calculations and decimal precision |
| **financial-ml-engineer** | — | ML for time series and market forecasting |
| **dashboard-wizard** | — | High-performance data dashboards with caching |
| **fintech-ux-designer** | — | Financial UIs and trading dashboard design |

**When to use:** TradingView indicators/strategies, algorithmic trading, exchange integration, financial analysis, trading dashboards, backtesting, on-chain alpha, funding rate arbitrage, liquidation detection, quantitative strategy development

---

### 🎨 Design (7 agents)

| Agent | Description |
|-------|-------------|
| **css-layout-perfectionist** | Pixel-perfect HTML/CSS alignment, Flexbox/Grid mastery, layout debugging with webapp-testing |
| **ui-designer** | Practical interface design bridging design and code |
| **ux-researcher** | User research and usability testing |
| **brand-guardian** | Visual identity consistency and brand guidelines |
| **visual-storyteller** | Compelling visual narratives and data viz |
| **whimsy-injector** | Delightful interactions and playful design |
| **design-disruptor** | Boundary-pushing design, next-gen aesthetics |

**When to use:** Pixel-perfect layout implementation, HTML/CSS debugging, responsive design, UI/UX design, design systems, user research, branding, innovative visual design

---

### ⚙️ Engineering (7 agents)

| Agent | Description |
|-------|-------------|
| **ai-engineer** | Production-ready AI/ML feature integration |
| **backend-architect** | Scalable APIs and distributed systems |
| **frontend-developer** | High-performance React/Vue/Angular UIs |
| **devops-automator** | CI/CD pipelines and infrastructure automation |
| **mobile-app-builder** | Native iOS/Android and cross-platform apps |
| **rapid-prototyper** | MVPs in days using modern tooling |
| **test-writer-fixer** | Comprehensive test suites and TDD |

**When to use:** Full-stack development, infrastructure, testing, rapid prototyping, ML deployment

---

### 📣 Marketing (10 agents)

| Agent | Description |
|-------|-------------|
| **aeo-strategist** | Answer Engine Optimization for AI search (ChatGPT, Claude, Perplexity, Google AI Overviews) |
| **conversion-copywriter** | Persuasive ad copy, landing pages, email sequences, CTAs |
| **paid-media-optimizer** | Google/Meta/LinkedIn Ads, campaign structure, ROAS optimization |
| **growth-hacker** | Viral growth loops and experimentation |
| **content-creator** | Multi-platform content strategy |
| **app-store-optimizer** | ASO for iOS/Android app stores |
| **twitter-engager** | Twitter/X strategy and engagement |
| **tiktok-strategist** | Viral short-form video content |
| **reddit-community-builder** | Authentic Reddit community engagement |
| **instagram-curator** | Visual content and feed aesthetics |

**When to use:** Growth strategy, conversion copywriting, paid advertising, content marketing, social media, app store optimization, viral marketing, AI answer engine visibility

---

### 🔧 Operations (7 agents)

| Agent | Description |
|-------|-------------|
| **analytics-reporter** | Data insights and executive reporting |
| **contract-legal-expert** | Contract drafting, review, negotiation, IP protection |
| **infrastructure-maintainer** | Cost-effective scaling and reliability |
| **ip-legal-guardian** | IP protection, open-source licensing, patents, trade secrets |
| **support-responder** | Customer service excellence |
| **finance-tracker** | Financial planning and budgeting |
| **legal-compliance-checker** | Regulatory compliance and risk management |

**When to use:** Business operations, contract drafting/review, IP protection, open-source compliance, infrastructure scaling, customer support, financial management, legal compliance

---

### 📦 Product (5 agents)

| Agent | Description |
|-------|-------------|
| **feedback-synthesizer** | Transforms user feedback into features |
| **sprint-prioritizer** | Sprint planning and backlog management |
| **trend-researcher** | Emerging trend analysis and market intelligence |
| **experiment-tracker** | A/B testing and feature validation |
| **project-shipper** | Release planning and launch coordination |

**When to use:** Product management, sprint planning, A/B testing, market research, feature prioritization

---

### 👥 Team Management (2 agents)

| Agent | Description |
|-------|-------------|
| **tech-lead-advisor** | Technical leadership and best practices |
| **studio-producer** | Team productivity and blocker removal |

**When to use:** Technical leadership, team coordination, process improvement, productivity optimization

---

### 📝 Documentation (1 agent)

| Agent | Description |
|-------|-------------|
| **technical-writer** | API docs, READMEs, tutorials, runbooks, architecture docs |

**When to use:** Creating comprehensive documentation, API references, developer guides, onboarding materials

---

### 🚀 Entrepreneur (5 agents)

| Agent | Description |
|-------|-------------|
| **pitch-strategist** | Investor pitch decks, narrative frameworks, Q&A prep |
| **investor-relations** | Term sheets, cap tables, due diligence, investor updates |
| **business-model-architect** | Revenue models, pricing strategy, unit economics |
| **competitive-analyst** | Market mapping, competitor analysis, positioning |
| **market-validator** | TAM/SAM/SOM, customer discovery, PMF assessment |

**When to use:** Fundraising, pitch preparation, business strategy, market analysis, competitive intelligence, startup validation

---

## 🌟 Featured: Trading & Crypto Specialists

These agents bring deep domain expertise for cryptocurrency trading systems:

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

## 💡 Usage Guide

### Invoking Agents in Claude Code

```
Use the {agent-name} agent to {specific task}
```

**Examples:**
```
Use the python-trading-expert to review my Bybit integration
Use the quant-engineer to implement RSI divergence detection
Have the on-chain-analyst write a Dune query to track whale wallets
Ask the qa-validation-engineer to validate these bug fixes
Have the dashboard-wizard optimize this analytics dashboard
Use the architecture-simplifier to refactor this monolith
```

### Agent Selection Decision Tree

1. **Complex multi-step task?** → Start with `pepe` (orchestrator)
2. **Trading/Finance related?** → Check Trading & Crypto agents
3. **Need code review/testing?** → Check Analysis Tools agents
4. **Architecture/design patterns?** → Check Architecture agents
5. **UI/UX work?** → Check Design agents
6. **Infrastructure/deployment?** → Check Engineering or Operations
7. **Marketing/growth?** → Check Marketing agents
8. **Product decisions?** → Check Product agents

### Best Practices

- **Single Responsibility**: Choose the most specific agent for your task
- **Orchestration**: Use `pepe` for tasks requiring multiple agents
- **Validation**: Always run `qa-validation-engineer` after major changes
- **Documentation**: Use `code-documentation-auditor` before releases
- **Financial Code**: Always validate with `trading-validator` for precision
- **On-Chain Analysis**: Use `on-chain-analyst` for blockchain data queries
- **Quantitative Work**: Use `quant-engineer` for statistical rigor

---

## 🔄 Agent Workflows

### Common Workflows

**Building a Trading System:**
1. `backend-architect` → System design
2. `python-trading-expert` → Exchange integration
3. `quant-engineer` → Strategy implementation
4. `trading-validator` → Validate calculations
5. `dashboard-wizard` → Analytics dashboard
6. `qa-validation-engineer` → End-to-end testing

**On-Chain Alpha Research:**
1. `on-chain-analyst` → Dune/Flipside queries
2. `data-visualization-architect` → Dashboard design
3. `quant-engineer` → Signal validation
4. `python-trading-expert` → Strategy integration

**Launching a New Feature:**
1. Product agents → Planning & prioritization
2. Engineering agents → Implementation
3. `qa-validation-engineer` → Testing & validation
4. `project-shipper` → Launch coordination

**Optimizing Performance:**
1. `architecture-simplifier` → Identify bottlenecks
2. `cache-implementation-reviewer` → Caching strategy
3. `realtime-systems-architect` → Low-latency optimization
4. `async-pattern-analyzer` → Concurrency issues
5. `devops-automator` → Infrastructure optimization

---

## 📊 Agent Statistics

| Category | Agent Count | Primary Use Cases |
|----------|------------|-------------------|
| **Architecture** | 8 | APIs, databases, webhooks, system design, real-time systems |
| **Analysis Tools** | 6 | Testing, data science, visualization, optimization |
| **AI Engineering** | 2 | Prompt design, MLOps, model deployment |
| **Security** | 2 | Vulnerability assessment, API security, OAuth2/JWT, secrets management |
| **Trading & Crypto** | 10 | Finance, trading, on-chain analytics, quantitative strategies |
| **Design** | 7 | Pixel-perfect layouts, UI/UX, branding, visual design |
| **Engineering** | 7 | Full-stack development, DevOps |
| **Marketing** | 10 | Growth, copywriting, paid ads, social media |
| **Operations** | 7 | Infrastructure, contracts, IP, compliance |
| **Product** | 5 | Product management, experimentation |
| **Team Management** | 2 | Leadership, productivity |
| **Documentation** | 1 | Technical writing, API docs |
| **Entrepreneur** | 5 | Fundraising, pitch decks, market validation |
| **Orchestrator** | 1 | Multi-agent workflow coordination |
| **TOTAL** | **72** | All development workflows |

---

## 🤝 Contributing

To add new agents or improve existing ones:

1. Place agent file in the root directory
2. Follow the existing markdown format with proper frontmatter
3. Include clear capability descriptions
4. Update this README's agent catalog
5. Submit a pull request

**Note:** All agents must be in the root directory for Claude Code's `/agents` command to detect them.

### Agent File Format
```yaml
---
name: agent-name
description: When to use this agent with examples...
model: inherit
color: cyan
---

System prompt content here...
```

---

## 📝 License

MIT License - feel free to use and modify these agents for your own Claude Code setup.

---

## 📞 Support

For questions or issues:
- Review the agent catalog above
- Check agent file for detailed capabilities
- Use `pepe` for complex multi-agent tasks

**Maintained by:** virtexvirtuoso
**Total Agents:** 72
**Last Updated:** 2025-12-12
