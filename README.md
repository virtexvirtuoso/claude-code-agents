---
name: "Documentation"
ignore: true
---

# Claude Code Agents Collection

A comprehensive collection of **64 specialized AI agents** for Claude Code, designed to enhance development workflows across software engineering, AI/LLM development, trading systems, security, design, marketing, operations, and product management.

## 📁 Directory Structure

All agents are located in the root directory for easy discovery by Claude Code's `/agents` command:

```
claude-code-agents/
├── 📄 pepe.md                        # Master orchestrator agent
├── 📄 prompt-engineer.md             # LLM prompt design & optimization
├── 📄 security-auditor.md            # Security audits & vulnerability assessment
├── 📄 pine-script-developer.md       # TradingView Pine Script developer
├── 📄 python-trading-expert.md       # Trading systems & exchange APIs
├── 📄 optuna-optimizer.md            # Hyperparameter optimization
├── 📄 api-expert.md                  # REST API design & integration
├── 📄 qa-validation-engineer.md      # Testing & validation
└── ... 54 more specialized agents
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
# You should see all 64 agents listed
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

### 🏗️ Architecture (7 agents)

| Agent | Description |
|-------|-------------|
| **api-expert** | REST API design, authentication, and integration |
| **database-architect** | Database design, schema modeling, query optimization, migrations |
| **webhook-expert** | Webhook configuration and event processing |
| **architecture-simplifier** | Reduces complexity and refactors system architecture |
| **async-pattern-analyzer** | Analyzes async/await patterns and concurrency issues |
| **cache-implementation-reviewer** | Reviews caching strategies (Redis, CDN, database) |
| **dependency-injection-expert** | Implements DI patterns and IoC containers |

**When to use:** API design, database schema design, query optimization, webhook integration, system redesign, performance optimization, technical debt reduction, SOLID principles

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

### 🤖 AI Engineering (1 agent)

| Agent | Description |
|-------|-------------|
| **prompt-engineer** | LLM prompt design, optimization, evaluation frameworks, injection hardening |

**When to use:** System prompt design, few-shot learning, chain-of-thought reasoning, prompt evaluation (Promptfoo/RAGAS), token optimization, prompt injection defense, A/B testing frameworks, LLM-as-judge patterns, RAG prompt design

---

### 🔒 Security (1 agent)

| Agent | Description |
|-------|-------------|
| **security-auditor** | OWASP Top 10, vulnerability assessment, secure code review, compliance |

**When to use:** Security audits, vulnerability assessment, authentication/authorization review, pre-deployment security checks, compliance validation (SOC 2, PCI-DSS, HIPAA), secrets management, container security, penetration testing guidance

---

### 💹 Trading (5 agents)

| Agent | Description |
|-------|-------------|
| **pine-script-developer** | TradingView Pine Script v6 indicators and strategies |
| **python-trading-expert** | CCXT library and exchange API integration |
| **trading-logic-validator** | Validates financial calculations and precision |
| **financial-ml-engineer** | ML for time series and market forecasting |
| **dashboard-wizard** | High-performance data dashboards with caching |

**When to use:** TradingView indicators/strategies, algorithmic trading, exchange integration, financial analysis, trading dashboards, backtesting

---

### 🎨 Design (6 agents)

| Agent | Description |
|-------|-------------|
| **ui-designer** | Practical interface design bridging design and code |
| **ux-researcher** | User research and usability testing |
| **brand-guardian** | Visual identity consistency and brand guidelines |
| **visual-storyteller** | Compelling visual narratives and data viz |
| **whimsy-injector** | Delightful interactions and playful design |
| **fintech-ux-designer** | Financial UIs and trading dashboard design |

**When to use:** UI/UX design, design systems, user research, branding, financial interfaces

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

## 💡 Usage Guide

### Invoking Agents in Claude Code

```
Use the {agent-name} agent to {specific task}
```

**Examples:**
```
Use the python-trading-expert to review my Bybit integration
Ask the qa-validation-engineer to validate these bug fixes
Have the dashboard-wizard optimize this analytics dashboard
Use the architecture-simplifier to refactor this monolith
```

### Agent Selection Decision Tree

1. **Complex multi-step task?** → Start with `pepe` (orchestrator)
2. **Trading/Finance related?** → Check `/trading/` agents
3. **Need code review/testing?** → Check `/analysis-tools/` agents
4. **Architecture/design patterns?** → Check `/architecture/` agents
5. **UI/UX work?** → Check `/design/` agents
6. **Infrastructure/deployment?** → Check `/engineering/` or `/operations/`
7. **Marketing/growth?** → Check `/marketing/` agents
8. **Product decisions?** → Check `/product/` agents

### Best Practices

- **Single Responsibility**: Choose the most specific agent for your task
- **Orchestration**: Use `pepe` for tasks requiring multiple agents
- **Validation**: Always run `qa-validation-engineer` after major changes
- **Documentation**: Use `code-documentation-auditor` before releases
- **Financial Code**: Always validate with `trading-logic-validator` for precision

---

## 🔄 Agent Workflows

### Common Workflows

**Building a Trading System:**
1. `backend-architect` → System design
2. `python-trading-expert` → Exchange integration
3. `trading-logic-validator` → Validate calculations
4. `dashboard-wizard` → Analytics dashboard
5. `qa-validation-engineer` → End-to-end testing

**Launching a New Feature:**
1. `product` agents → Planning & prioritization
2. `engineering` agents → Implementation
3. `qa-validation-engineer` → Testing & validation
4. `project-shipper` → Launch coordination

**Optimizing Performance:**
1. `architecture-simplifier` → Identify bottlenecks
2. `cache-implementation-reviewer` → Caching strategy
3. `async-pattern-analyzer` → Concurrency issues
4. `devops-automator` → Infrastructure optimization

---

## 📊 Agent Statistics

| Category | Agent Count | Primary Use Cases |
|----------|------------|-------------------|
| **Architecture** | 7 | APIs, databases, webhooks, system design, performance, patterns |
| **Analysis Tools** | 6 | Testing, data science, visualization, optimization, documentation |
| **AI Engineering** | 1 | Prompt design, LLM optimization, evaluation frameworks |
| **Security** | 1 | Vulnerability assessment, secure code review, compliance |
| **Trading** | 5 | Finance, trading systems, dashboards, TradingView Pine Script |
| **Design** | 6 | UI/UX, branding, visual design |
| **Engineering** | 7 | Full-stack development, DevOps |
| **Marketing** | 10 | Growth, copywriting, paid ads, content, social media, AEO |
| **Operations** | 7 | Infrastructure, contracts, IP, support, compliance |
| **Product** | 5 | Product management, experimentation |
| **Team Management** | 2 | Leadership, productivity |
| **Documentation** | 1 | Technical writing, API docs, tutorials |
| **Entrepreneur** | 5 | Fundraising, pitch decks, business strategy, market validation |
| **Orchestrator** | 1 | Multi-agent workflow coordination |
| **TOTAL** | **64** | All development workflows |

---

## 🤝 Contributing

To add new agents or improve existing ones:

1. Place agent file in the root directory
2. Follow the existing markdown format with proper frontmatter
3. Include clear capability descriptions
4. Update this README's agent catalog
5. Submit a pull request

**Note:** All agents must be in the root directory for Claude Code's `/agents` command to detect them.

### Agent Template Structure
```markdown
# Agent Name

## Role
[Brief description]

## Capabilities
- [Key capability 1]
- [Key capability 2]
...

## When to Use
[Specific use cases]

## Example Tasks
[Concrete examples]
```

---

## 📝 License

Private repository - All rights reserved.

---

## 📞 Support

For questions or issues:
- Review the agent catalog above
- Check agent file for detailed capabilities
- Use `pepe` for complex multi-agent tasks

**Maintained by:** virtexvirtuoso
**Total Agents:** 64
**Last Updated:** 2025-12-02