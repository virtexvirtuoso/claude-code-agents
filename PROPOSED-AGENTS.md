---
name: "Proposed Agents"
ignore: true
---

# Proposed New Agents

Analysis of gaps in the current agent collection and recommended additions.

## Current Coverage Analysis

| Category | Current Count | Gap Assessment |
|----------|---------------|----------------|
| Architecture | 7 | Well covered |
| Analysis Tools | 5 | Good coverage |
| AI Engineering | 1 | **Major gap** - Only prompt-engineer |
| Security | 1 | Could expand |
| Trading | 5 | Well covered |
| Design | 6 | Missing accessibility |
| Engineering | 7 | Good coverage |
| Marketing | 9 | Excellent coverage |
| Operations | 7 | Missing observability |
| Product | 5 | Good coverage |
| Team Management | 2 | Minimal |
| **Total** | **56** | |

---

## Recommended New Agents

### Priority 1: High Impact (Immediate Value)

#### 1. technical-writer ✅ ADDED
- **Category**: Documentation
- **Gap filled**: Comprehensive documentation creation
- **Covers**: API docs, READMEs, tutorials, runbooks, architecture docs, changelogs
- **Why critical**: code-documentation-auditor reviews docs but doesn't create them

#### 2. rag-architect
- **Category**: AI Engineering
- **Gap filled**: RAG is THE dominant LLM application pattern
- **Covers**:
  - Chunking strategies (semantic, recursive, agentic)
  - Retrieval optimization (hybrid search, reranking)
  - Vector database selection and tuning
  - Evaluation frameworks (RAGAS, context relevance)
  - Production RAG pipelines
- **Why critical**: Everyone building LLM apps needs RAG expertise

#### 3. observability-architect
- **Category**: Operations
- **Gap filled**: Zero coverage for monitoring/logging/tracing
- **Covers**:
  - Logging strategies (structured logging, log aggregation)
  - Metrics collection (Prometheus, StatsD, custom metrics)
  - Distributed tracing (OpenTelemetry, Jaeger)
  - APM tools (Datadog, New Relic, Grafana stack)
  - Alerting and on-call optimization
  - Dashboard design
- **Why critical**: Every production system needs observability

#### 4. accessibility-expert
- **Category**: Design
- **Gap filled**: None of 6 design agents cover WCAG/a11y
- **Covers**:
  - WCAG 2.1/2.2 compliance (A, AA, AAA levels)
  - Screen reader optimization
  - Keyboard navigation
  - Color contrast and visual accessibility
  - Cognitive accessibility
  - Accessibility testing and auditing
  - Legal compliance (ADA, EAA, Section 508)
- **Why critical**: Legal requirements and inclusive design

#### 5. kubernetes-expert
- **Category**: Engineering/DevOps
- **Gap filled**: K8s complexity beyond devops-automator's scope
- **Covers**:
  - Deployment strategies (rolling, blue-green, canary)
  - Helm charts and Kustomize
  - Custom operators and CRDs
  - Service mesh (Istio, Linkerd)
  - Network policies and security contexts
  - Resource optimization and autoscaling
  - GitOps (ArgoCD, Flux)
  - Multi-cluster management
- **Why critical**: K8s is ubiquitous and complex

#### 6. llm-ops-engineer
- **Category**: AI Engineering
- **Gap filled**: Production LLM deployment distinct from prompting
- **Covers**:
  - Model serving (vLLM, TGI, Triton)
  - Cost optimization and token management
  - Caching strategies (semantic caching)
  - Rate limiting and quota management
  - A/B testing for models
  - Monitoring LLM-specific metrics
  - Fallback and reliability patterns
  - Multi-model routing
- **Why critical**: LLM deployment has unique challenges

---

### Priority 2: Medium Impact (Valuable Additions)

#### 7. sre-specialist
- **Category**: Operations
- **Partial overlap**: infrastructure-maintainer covers some
- **Unique value**:
  - SLO/SLI/SLA definition and tracking
  - Error budgets and reliability targets
  - Incident management and postmortems
  - Chaos engineering
  - Capacity planning
  - Toil reduction

#### 8. graphql-architect
- **Category**: Architecture
- **Partial overlap**: api-expert covers REST
- **Unique value**:
  - Schema design and best practices
  - Federation and distributed schemas
  - N+1 query prevention
  - Subscriptions and real-time data
  - Performance optimization
  - Security (depth limiting, query complexity)

#### 9. fine-tuning-engineer
- **Category**: AI Engineering
- **Specialized use case**: Not everyone fine-tunes
- **Unique value**:
  - Training data curation and quality
  - PEFT methods (LoRA, QLoRA, adapters)
  - Evaluation and benchmarking
  - Model merging techniques
  - Deployment of fine-tuned models
  - Cost/quality tradeoffs

#### 10. cloud-architect
- **Category**: Infrastructure
- **Partial overlap**: backend-architect, devops-automator
- **Unique value**:
  - Multi-cloud strategies
  - Cloud migration planning
  - Cost optimization (FinOps)
  - Well-architected frameworks
  - Serverless architectures
  - Cloud security posture

---

### Priority 3: Specialized (Niche but Valuable)

#### 11. ai-safety-specialist
- **Category**: AI Engineering / Security
- **Specialized use case**: Safety-critical AI applications
- **Unique value**:
  - Red teaming and adversarial testing
  - Jailbreak prevention
  - Content moderation systems
  - Alignment techniques
  - Bias detection and mitigation
  - AI governance frameworks

#### 12. vector-db-specialist
- **Category**: AI Engineering
- **Could merge with**: rag-architect
- **Unique value**:
  - Embedding model selection
  - Vector database comparison (Pinecone, Weaviate, Qdrant, Milvus)
  - Indexing strategies (HNSW, IVF)
  - Hybrid search implementation
  - Scaling and performance optimization

#### 13. performance-engineer
- **Category**: Engineering
- **Partial overlap**: Various architecture agents
- **Unique value**:
  - Profiling and bottleneck identification
  - Load testing strategies
  - Memory optimization
  - Database query optimization
  - Frontend performance (Core Web Vitals)
  - Caching at all layers

#### 14. privacy-engineer
- **Category**: Security / Compliance
- **Extends**: security-auditor, legal-compliance-checker
- **Unique value**:
  - Privacy by design
  - Data minimization
  - GDPR/CCPA technical implementation
  - Data retention and deletion
  - Anonymization techniques
  - Privacy impact assessments

---

### Entrepreneur-Focused Agents (NEW)

#### pitch-strategist ✅ ADDED
- **Category**: Fundraising
- **Covers**: Investor pitch decks, narrative frameworks, slide-by-slide guidance, Q&A prep, stage-specific advice
- **Why critical**: Every startup needs to pitch - investors, customers, hires

#### investor-relations ✅ ADDED
- **Category**: Fundraising
- **Covers**: Term sheet analysis, cap table management, due diligence prep, investor updates, board management
- **Why critical**: Navigating VC relationships and deal terms

#### business-model-architect ✅ ADDED
- **Category**: Business Strategy
- **Covers**: Revenue models, pricing strategy, unit economics, business model canvas, financial modeling
- **Why critical**: Foundation of every sustainable business

#### competitive-analyst ✅ ADDED
- **Category**: Business Strategy
- **Covers**: Market mapping, competitor analysis, positioning frameworks, battlecards, win/loss analysis
- **Why critical**: Understanding the battlefield to choose where to fight

#### market-validator ✅ ADDED
- **Category**: Business Strategy
- **Covers**: TAM/SAM/SOM sizing, customer discovery, PMF assessment, validation experiments
- **Why critical**: Validate before you build

---

## Implementation Status

| Agent | Status | Commit |
|-------|--------|--------|
| technical-writer | ✅ Added | 57a8d66 |
| pitch-strategist | ✅ Added | 722293e |
| investor-relations | ✅ Added | 722293e |
| business-model-architect | ✅ Added | 722293e |
| competitive-analyst | ✅ Added | 722293e |
| market-validator | ✅ Added | 722293e |
| rag-architect | ⏳ Pending | - |
| observability-architect | ⏳ Pending | - |
| accessibility-expert | ⏳ Pending | - |
| kubernetes-expert | ⏳ Pending | - |
| llm-ops-engineer | ⏳ Pending | - |

---

## Category Distribution After Additions

| Category | Before | After | Change |
|----------|--------|-------|--------|
| AI Engineering | 1 | 4 | +3 (rag-architect, llm-ops-engineer, fine-tuning-engineer) |
| Design | 6 | 7 | +1 (accessibility-expert) |
| Operations | 7 | 8 | +1 (observability-architect) |
| Engineering | 7 | 8 | +1 (kubernetes-expert) |
| Documentation | 0 | 1 | +1 (technical-writer) |
| Fundraising | 0 | 2 | +2 (pitch-strategist, investor-relations) |
| Business Strategy | 0 | 3 | +3 (business-model-architect, competitive-analyst, market-validator) |
| **Total** | **56** | **68** | **+12** |

---

*Last updated: 2025-11-29*
