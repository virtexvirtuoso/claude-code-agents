# Claude Code Agents Collection

A comprehensive collection of specialized AI agents for Claude Code, designed to enhance development workflows across various domains including software engineering, trading systems, design, marketing, operations, and product management.

## 📋 Table of Contents

- [Overview](#overview)
- [Quick Start](#quick-start)
- [Agent Categories](#agent-categories)
  - [Core Technical Agents](#core-technical-agents)
  - [Design Agents](#design-agents)
  - [Engineering Agents](#engineering-agents)
  - [Marketing Agents](#marketing-agents)
  - [Operations Agents](#operations-agents)
  - [Product Agents](#product-agents)
- [Usage](#usage)
- [Contributing](#contributing)

## Overview

This repository contains **47 specialized AI agents** organized into functional categories. Each agent is an expert in a specific domain and can be invoked through Claude Code to assist with targeted tasks.

## Quick Start

### Global Installation (All Projects)
```bash
# Clone to your global Claude directory
cp -r /path/to/claude-code-agents/* ~/.claude/agents/
```

### Project-Specific Installation
```bash
# Clone to your project's Claude directory
mkdir -p .claude/agents
cp -r /path/to/claude-code-agents/* .claude/agents/
```

## Agent Categories

### Core Technical Agents

#### **pepe** - Master Orchestrator
Strategic coordinator that analyzes complex requests and delegates to specialized agents for optimal outcomes. Excels at decomposing problems, identifying required expertise, and managing multi-agent workflows.

**Key Capabilities:**
- Request analysis and decomposition
- Agent selection and coordination
- Workflow management
- Handoff coordination
- Output aggregation

---

#### **api-expert**
REST API design, authentication, rate limiting, and integration specialist covering RESTful APIs and webhooks.

**Key Capabilities:**
- API design and architecture
- Authentication (JWT/OAuth/API keys)
- Error handling and validation
- Webhook configuration
- OpenAPI documentation

---

#### **python-trading-expert**
Expert in Python trading systems, CCXT, and exchange integrations for algorithmic trading.

**Key Capabilities:**
- CCXT library mastery
- Exchange APIs (Binance/Bybit/Kraken)
- Order execution logic
- Backtesting frameworks
- Risk management systems

---

#### **financial-ml-engineer**
Applies machine learning to financial time series data including stock prices, cryptocurrency analysis, and trading strategies.

**Key Capabilities:**
- Time series analysis (ARIMA/LSTM)
- Feature engineering for financial data
- Backtesting and validation
- Risk metrics (VaR/Sharpe)
- Market forecasting

---

#### **data-scientist-researcher**
Provides rigorous data analysis, statistical modeling, and research-driven insights with scientific integrity.

**Key Capabilities:**
- Hypothesis testing
- Exploratory data analysis
- ML modeling and validation
- A/B test design
- Causal inference

---

#### **qa-validation-engineer**
Provides comprehensive end-to-end validation of code changes, bug fixes, and feature implementations.

**Key Capabilities:**
- Test strategy design
- Acceptance criteria validation
- Regression testing
- Code cleanup validation
- Defect reporting

---

#### **dashboard-wizard**
Designs, builds, and optimizes data dashboards with API integrations and caching mechanisms for high-performance systems.

**Key Capabilities:**
- Dashboard architecture
- API integration
- Caching strategies (Redis)
- Performance tuning
- Real-time data handling

---

#### **tech-lead-advisor**
Provides technical leadership, best practices, and strategic guidance for high-performing teams.

**Key Capabilities:**
- System architecture
- Code review standards
- Technical debt management
- Team mentorship
- Stakeholder communication

---

#### **architecture-simplifier**
Reduces complexity, refactors code, and improves system architecture by identifying and eliminating bottlenecks.

**Key Capabilities:**
- Bottleneck identification
- Complexity assessment
- Layer consolidation
- Over-engineering detection
- Performance optimization

---

#### **code-documentation-auditor**
Reviews and improves code documentation, README files, and API docs with focus on completeness and maintainability.

**Key Capabilities:**
- Documentation coverage audits
- README optimization
- API documentation
- Auto-generation tools
- Indexing and searchability

---

#### **cache-implementation-reviewer**
Reviews and validates caching strategies and implementations across all paradigms (in-memory, distributed, browser, CDN, database query caches).

**Key Capabilities:**
- Cache strategy analysis
- Performance evaluation
- Issue identification
- Eviction policy optimization
- Coherency problems

---

#### **trading-logic-validator**
Validates trading calculations, financial logic, and algorithm correctness with focus on numerical precision and financial mathematics.

**Key Capabilities:**
- Financial calculations validation
- Decimal precision checking
- Order execution logic
- Common trading bugs identification
- Risk calculations

---

#### **webhook-expert**
Webhook configuration, event processing, and callback handling expert specializing in real-time integrations.

**Key Capabilities:**
- Webhook security (HMAC verification)
- Event processing patterns
- Error handling and retries
- Testing strategies
- Provider integration

---

#### **dependency-injection-expert**
Implements DI patterns, IoC containers, and decouples components across multiple frameworks and languages.

**Key Capabilities:**
- SOLID principles
- Constructor/setter injection
- DI containers
- Testing with mocks
- Lifecycle management

---

#### **async-pattern-analyzer**
Analyzes async/await patterns, concurrency, and performance bottlenecks in asynchronous code.

**Key Capabilities:**
- Missing await detection
- Race condition identification
- Resource management
- Deadlock analysis
- Connection pooling

---

#### **file-organizer**
Organizes, cleans, and optimizes file systems and directories with systematic file management approaches.

**Key Capabilities:**
- Project structure cleanup
- Directory organization
- Duplicate detection
- Naming conventions
- Automation scripts

---

#### **fintech-ux-designer**
Designs financial UIs, trading dashboards, and data visualizations with minimalistic excellence and functionality-first approach.

**Key Capabilities:**
- Trading dashboards
- Financial visualizations
- Data clarity
- Responsive design
- User flow documentation

---

### Design Agents

#### **ui-designer**
Designs interfaces developers can actually build, bridging design and code with practical implementation focus.

**Key Capabilities:**
- Design systems
- Component libraries
- Responsive design
- Figma/Sketch
- Design-development collaboration

---

#### **ux-researcher**
Turns user insights into product improvements through qualitative and quantitative research methods.

**Key Capabilities:**
- User interviews
- Usability testing
- Analytics interpretation
- User personas
- Journey mapping

---

#### **brand-guardian**
Keeps visual identity consistent everywhere through brand guidelines and governance.

**Key Capabilities:**
- Brand guidelines
- Visual identity systems
- Cross-channel consistency
- Asset management
- Brand training

---

#### **visual-storyteller**
Creates visuals that convert and share through compelling visual narratives.

**Key Capabilities:**
- Data visualization
- Infographics
- Motion design
- Illustration
- Conversion-focused design

---

#### **whimsy-injector**
Adds delight to every interaction through playful moments and personality-driven design.

**Key Capabilities:**
- Delightful interactions
- Easter eggs
- Playful animations
- Gamification
- Emotional design

---

### Engineering Agents

#### **ai-engineer**
Integrates AI/ML features that actually ship with focus on practical implementation and production reliability.

**Key Capabilities:**
- Model integration
- Inference pipelines
- Feature engineering
- Production ML infrastructure
- Performance optimization

---

#### **backend-architect**
Designs scalable APIs and server systems with expertise in distributed systems and microservices.

**Key Capabilities:**
- API design (REST/GraphQL)
- Microservices architecture
- Database design
- Caching strategies
- System scalability

---

#### **rapid-prototyper**
Builds MVPs in days, not weeks using modern tools and no-code/low-code solutions when appropriate.

**Key Capabilities:**
- Tech stack selection for speed
- MVP development
- Rapid UI implementation
- Serverless functions
- Quick iteration

---

#### **frontend-developer**
Builds blazing-fast user interfaces with modern JavaScript frameworks and performance optimization.

**Key Capabilities:**
- React/Vue/Angular mastery
- Performance optimization
- Responsive design
- Web Vitals
- Component architecture

---

#### **devops-automator**
Deploys continuously without breaking things through CI/CD pipelines and infrastructure automation.

**Key Capabilities:**
- CI/CD pipelines
- Kubernetes/Docker
- Infrastructure as code (Terraform)
- Monitoring/observability
- Cloud optimization

---

#### **mobile-app-builder**
Creates native iOS/Android experiences using React Native, Flutter, or native development.

**Key Capabilities:**
- Cross-platform development
- Native iOS/Android
- Performance optimization
- Push notifications
- App store deployment

---

#### **test-writer-fixer**
Writes tests that catch real bugs with comprehensive test suites and automation strategies.

**Key Capabilities:**
- Test strategy design
- TDD practices
- Integration testing
- E2E testing (Cypress/Playwright)
- Test automation

---

### Marketing Agents

#### **growth-hacker**
Finds and exploits viral growth loops through experimentation and optimization.

**Key Capabilities:**
- Viral loop design
- Growth experimentation
- Conversion optimization
- Acquisition channels
- Retention strategies

---

#### **content-creator**
Generates content across all platforms (written, video, audio, visual) that drives engagement.

**Key Capabilities:**
- Multi-platform content strategy
- SEO optimization
- Video/visual content
- Content distribution
- Performance analysis

---

#### **app-store-optimizer**
Dominates app store search results through keyword optimization and visual asset creation.

**Key Capabilities:**
- Keyword research
- Visual asset optimization
- Listing optimization
- Ratings management
- Conversion tracking

---

#### **twitter-engager**
Rides trends to viral engagement on Twitter/X through strategic content and community building.

**Key Capabilities:**
- Tweet optimization
- Thread creation
- Trend-jacking
- Community building
- Twitter algorithm mastery

---

#### **tiktok-strategist**
Creates shareable marketing moments through viral short-form video content.

**Key Capabilities:**
- TikTok trends
- Algorithm optimization
- Creator partnerships
- Authentic content
- TikTok advertising

---

#### **reddit-community-builder**
Wins Reddit without being banned through authentic community engagement.

**Key Capabilities:**
- Reddit culture mastery
- Community engagement
- Promotional tactics
- Subreddit management
- Authentic contribution

---

#### **instagram-curator**
Masters the visual content game with cohesive feed aesthetics and engagement strategies.

**Key Capabilities:**
- Visual content strategy
- Feed aesthetics
- Instagram algorithm
- Reels optimization
- Shopping features

---

### Operations Agents

#### **analytics-reporter**
Turns data into actionable insights through analysis, visualization, and clear communication.

**Key Capabilities:**
- Statistical analysis
- Dashboard creation
- KPI tracking
- Predictive analytics
- Executive reporting

---

#### **infrastructure-maintainer**
Scales without breaking the bank through cost-effective infrastructure and reliability engineering.

**Key Capabilities:**
- Cloud cost optimization
- Scalability architecture
- Reliability engineering
- Performance optimization
- Automation

---

#### **support-responder**
Turns angry users into advocates through exceptional customer service and issue resolution.

**Key Capabilities:**
- Empathetic communication
- Issue resolution
- Support system optimization
- Customer success
- Team training

---

#### **finance-tracker**
Keeps the studio profitable through financial planning, budgeting, and burn rate management.

**Key Capabilities:**
- Financial modeling
- Budget planning
- Revenue optimization
- Cost management
- Cash flow forecasting

---

#### **legal-compliance-checker**
Stays legal while moving fast through regulatory compliance and risk management.

**Key Capabilities:**
- Data privacy (GDPR/CCPA)
- Intellectual property
- Contract management
- Regulatory compliance
- Risk assessment

---

#### **studio-producer**
Keeps teams shipping, not meeting through productivity optimization and blocker removal.

**Key Capabilities:**
- Team productivity
- Meeting optimization
- Blocker removal
- Process improvement
- Team health

---

### Product Agents

#### **feedback-synthesizer**
Transforms complaints into features through systematic feedback collection and analysis.

**Key Capabilities:**
- Feedback collection
- Pattern recognition
- Problem-to-solution translation
- Stakeholder communication
- Feedback systems

---

#### **sprint-prioritizer**
Ships maximum value in 6 days through effective sprint planning and backlog management.

**Key Capabilities:**
- Sprint planning
- Prioritization frameworks (RICE/MoSCoW)
- Backlog management
- Stakeholder alignment
- Velocity optimization

---

#### **trend-researcher**
Identifies viral opportunities through emerging trend analysis and market intelligence.

**Key Capabilities:**
- Trend identification
- Market intelligence
- Opportunity assessment
- Competitive analysis
- Early adopter targeting

---

#### **experiment-tracker**
Provides data-driven feature validation through A/B testing and statistical analysis.

**Key Capabilities:**
- Experiment design
- Statistical analysis
- Feature flags
- Test execution
- Results interpretation

---

#### **project-shipper**
Launches products that don't crash through comprehensive release planning and risk mitigation.

**Key Capabilities:**
- Release planning
- Risk mitigation
- Launch coordination
- Quality assurance
- Post-launch monitoring

---

## Usage

### Using Agents in Claude Code

Agents can be invoked through the Task tool in Claude Code:

```markdown
Use the {agent-name} agent to help with {specific task}
```

**Examples:**
- "Use the python-trading-expert to review my CCXT integration"
- "Have the qa-validation-engineer validate these bug fixes"
- "Ask the dashboard-wizard to optimize this analytics dashboard"

### Agent Selection Guidelines

1. **Single Responsibility**: Choose the agent that most closely matches your specific task
2. **Orchestration**: Use `pepe` for complex tasks requiring multiple agents
3. **Validation**: Consider using `qa-validation-engineer` after major changes
4. **Documentation**: Invoke `code-documentation-auditor` before releases

## Contributing

Contributions are welcome! To add new agents or improve existing ones:

1. Follow the existing agent markdown format
2. Include clear capability descriptions
3. Provide usage examples
4. Update this README with new agent information

## License

Private repository - All rights reserved.

---

**Total Agents:** 47
**Categories:** 6 (Core Technical, Design, Engineering, Marketing, Operations, Product)
**Maintained by:** [Your Name/Team]