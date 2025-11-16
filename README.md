# Claude Code Agents Collection

A comprehensive collection of **48 specialized AI agents** for Claude Code, designed to enhance development workflows across software engineering, trading systems, design, marketing, operations, and product management.

## 📁 Directory Structure

```
claude-code-agents/
├── 📂 architecture/          # System design, APIs & code quality (6 agents)
├── 📂 analysis-tools/        # Data analysis & testing (5 agents)
├── 📂 trading/               # Financial & trading systems (4 agents)
├── 📂 design/                # UI/UX & visual design (6 agents)
├── 📂 engineering/           # Software development (7 agents)
├── 📂 marketing/             # Growth & content (7 agents)
├── 📂 operations/            # Infrastructure & support (5 agents)
├── 📂 product/               # Product management (5 agents)
├── 📂 team-management/       # Leadership & productivity (2 agents)
└── 📄 pepe.md                # Master orchestrator agent
```

## 🚀 Quick Start

### Global Installation (Available in All Projects)
```bash
# Clone to your global Claude directory
git clone https://github.com/virtexvirtuoso/claude-code-agents.git
cp -r claude-code-agents/* ~/.claude/agents/
```

### Project-Specific Installation
```bash
# Clone to your project's Claude directory
git clone https://github.com/virtexvirtuoso/claude-code-agents.git
mkdir -p .claude/agents
cp -r claude-code-agents/* .claude/agents/
```

## 📚 Agent Catalog

### 🎯 Master Orchestrator

| Agent | Description | Key Use Cases |
|-------|-------------|---------------|
| **pepe** | Master orchestrator for complex multi-agent workflows | Task decomposition, agent coordination, workflow management |

---

### 🏗️ Architecture (6 agents)

| Agent | Description |
|-------|-------------|
| **api-expert** | REST API design, authentication, and integration |
| **webhook-expert** | Webhook configuration and event processing |
| **architecture-simplifier** | Reduces complexity and refactors system architecture |
| **async-pattern-analyzer** | Analyzes async/await patterns and concurrency issues |
| **cache-implementation-reviewer** | Reviews caching strategies (Redis, CDN, database) |
| **dependency-injection-expert** | Implements DI patterns and IoC containers |

**When to use:** API design, webhook integration, system redesign, performance optimization, technical debt reduction, SOLID principles

---

### 🔬 Analysis Tools (5 agents)

| Agent | Description |
|-------|-------------|
| **data-scientist-researcher** | Rigorous data analysis and statistical modeling |
| **optuna-optimizer** | Hyperparameter tuning and black-box optimization |
| **qa-validation-engineer** | Comprehensive end-to-end validation and testing |
| **code-documentation-auditor** | Reviews and improves documentation quality |
| **file-organizer** | Organizes and optimizes file systems |

**When to use:** Data analysis, hyperparameter optimization, hypothesis testing, code reviews, test strategy, project cleanup

---

### 💹 Trading (4 agents)

| Agent | Description |
|-------|-------------|
| **python-trading-expert** | CCXT library and exchange API integration |
| **trading-logic-validator** | Validates financial calculations and precision |
| **financial-ml-engineer** | ML for time series and market forecasting |
| **dashboard-wizard** | High-performance data dashboards with caching |

**When to use:** Algorithmic trading, exchange integration, financial analysis, trading dashboards, backtesting

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

### 📣 Marketing (7 agents)

| Agent | Description |
|-------|-------------|
| **growth-hacker** | Viral growth loops and experimentation |
| **content-creator** | Multi-platform content strategy |
| **app-store-optimizer** | ASO for iOS/Android app stores |
| **twitter-engager** | Twitter/X strategy and engagement |
| **tiktok-strategist** | Viral short-form video content |
| **reddit-community-builder** | Authentic Reddit community engagement |
| **instagram-curator** | Visual content and feed aesthetics |

**When to use:** Growth strategy, content marketing, social media, app store optimization, viral marketing

---

### 🔧 Operations (5 agents)

| Agent | Description |
|-------|-------------|
| **analytics-reporter** | Data insights and executive reporting |
| **infrastructure-maintainer** | Cost-effective scaling and reliability |
| **support-responder** | Customer service excellence |
| **finance-tracker** | Financial planning and budgeting |
| **legal-compliance-checker** | Regulatory compliance and risk management |

**When to use:** Business operations, infrastructure scaling, customer support, financial management, compliance

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
| **Architecture** | 6 | APIs, webhooks, system design, performance, patterns |
| **Analysis Tools** | 5 | Testing, data science, optimization, documentation |
| **Trading** | 4 | Finance, trading systems, dashboards |
| **Design** | 6 | UI/UX, branding, visual design |
| **Engineering** | 7 | Full-stack development, DevOps |
| **Marketing** | 7 | Growth, content, social media |
| **Operations** | 5 | Infrastructure, support, compliance |
| **Product** | 5 | Product management, experimentation |
| **Team Management** | 2 | Leadership, productivity |
| **Orchestrator** | 1 | Multi-agent workflow coordination |
| **TOTAL** | **48** | All development workflows |

---

## 🤝 Contributing

To add new agents or improve existing ones:

1. Place agent file in the appropriate directory
2. Follow the existing markdown format
3. Include clear capability descriptions
4. Update this README's agent catalog
5. Submit a pull request

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
**Total Agents:** 48
**Last Updated:** 2025-11-16