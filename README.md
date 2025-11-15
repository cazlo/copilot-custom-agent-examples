# copilot-custom-agent-examples
ideas for custom copilot agents

## Agents Summary


### Engineering Enablement & Developer Experience

| Agent | What it does | Link | Benefit |
|---|---|---|---|
| container-cache-optimizer | Optimizes Dockerfiles and container builds for maximum layer cacheability and reproducibility. | [.github/agents/Container Cache Optimizer.md](.github/agents/Container%20Cache%20Optimizer.md) | 🚀 faster builds · 🧱 stable layers |
| python-container-cache-optimizer | Optimizes Python Docker images (pip/Poetry/uv) for high cache hit rates and fast rebuilds. | [.github/agents/Container Cache Optimizer (Python).md](.github/agents/Container%20Cache%20Optimizer%20%28Python%29.md) | 🐍 Python speedups · ⚡ high cache hits |
| multi-language-cache-architect | Designs multi-stage Docker builds with stable, reusable layers across polyglot services. | [.github/agents/Container Cache Optimizer (Multi-Language).md](.github/agents/Container%20Cache%20Optimizer%20%28Multi-Language%29.md) | 🏗️ reusable layers · 🔁 cross-service reuse |
| tf-module-scaffolder | Creates new Terraform modules following internal structure, naming, and documentation standards. | [.github/agents/Terraform Module Scaffolder.md](.github/agents/Terraform%20Module%20Scaffolder.md) | 🧱 consistent modules · 🛠️ faster starts |
| refactoring-strategist | Plans multi-step refactors with safety guarantees. | [.github/agents/Refactoring Strategist.md](.github/agents/Refactoring%20Strategist.md) | 🧭 safer changes · 🔧 maintainability |
| legacy-react-migration-assistant | Helps migrate React 17 apps to React 18 with MUI v5, updating makeStyles usage and ESLint config. | [.github/agents/Legacy React Migration Specialist.md](.github/agents/Legacy%20React%20Migration%20Specialist.md) | 🔄 smoother upgrades · ⚛️ modern React |
| static-site-generator | Generates new static sites using the team’s preferred framework. | [.github/agents/Static Site Generator.md](.github/agents/Static%20Site%20Generator.md) | 🖥️ ready sites · ⚡ SEO-friendly |
| readme-creator | Agent specializing in creating and improving README.md files. | [.github/agents/Documentation Specialist.md](.github/agents/Documentation%20Specialist.md) | 📝 clearer docs · ✨ better onboarding |
| documentation-gap-finder | Scans a codebase and identifies missing docs, unclear APIs, or inconsistent conventions. | [.github/agents/Documentation Gap Finder.md](.github/agents/Documentation%20Gap%20Finder.md) | 🔎 find gaps · 📚 stronger docs |
| code-smell-detector-fixer | Identifies and remediates common smells: duplication, large functions, scattered logic, magic values, etc. | [.github/agents/Code Smell Detector & Fixer.md](.github/agents/Code%20Smell%20Detector%20%26%20Fixer.md) | 🧹 cleaner code · 🧠 safer refactors |
| architecture-explorer | Creates diagrams, call graphs, dependency maps to reduce learning curves. | [.github/agents/Architecture Explorer Agent.md](.github/agents/Architecture%20Explorer%20Agent.md) | 🗺️ clarity · 🔍 system insight |
| glossary-domain-language-builder | Extracts domain terms, acronyms, and shared vocabulary for documentation building. | [.github/agents/Glossary & Domain Language Builder.md](.github/agents/Glossary%20%26%20Domain%20Language%20Builder.md) | 📖 shared language · 🔗 alignment |
| technical-debt-mapper | Creates a prioritized list of debt items with impact & remediation difficulty. | [.github/agents/Technical Debt Mapper.md](.github/agents/Technical%20Debt%20Mapper.md) | 🧮 prioritization · 🧭 roadmap |
| productivity-pattern-matcher | Suggests patterns (CQRS, DDD, pub/sub, serverless, monorepo) based on goals. | [.github/agents/Productivity Pattern Matcher.md](.github/agents/Productivity%20Pattern%20Matcher.md) | 🧩 right patterns · 🚀 delivery speed |

### Data & Observability

| Agent | What it does | Link | Benefit |
|---|---|---|---|
| sla-monitoring-agent | Creates SLIs, SLOs, and SLA tracking for ETL pipelines. | [.github/agents/SLA Monitoring Agent.md](.github/agents/SLA%20Monitoring%20Agent.md) | ⏱️ predictable SLAs · 📊 clear KPIs |
| sql-optimizer | Analyzes and optimizes slow SQL queries. | [.github/agents/SQL Query Optimizer.md](.github/agents/SQL%20Query%20Optimizer.md) | 🚀 faster queries · 🗃️ better indexing |


### FedRAMP Compliance & Authorization

| Agent | What it does | Link | Benefit |
|---|---|---|---|
| fedramp-security-docs-generator | Creates SSP sections, attachments, diagrams, and inventories for FedRAMP. | [.github/agents/FedRAMP Security Documentaton Generator.md](.github/agents/FedRAMP%20Security%20Documentaton%20Generator.md) | 📘 Author-ready docs · 🛡️ compliance |
| fedramp-threat-modeler | Creates threat models aligned with FedRAMP, STRIDE, and NIST threat frameworks. | [.github/agents/FedRAMP Threat Modeler.md](.github/agents/FedRAMP%20Threat%20Modeler.md) | 🧠 structured analysis · 🛡️ risk mitigation |
| fedramp-evidence-builder | Generates screenshots, logs, queries, and formatted artifacts for assessors. | [.github/agents/FedRAMP Evidence Pack Builder.md](.github/agents/FedRAMP%20Evidence%20Pack%20Builder.md) | 📸 faster evidence · 📑 audit-ready |
| fedramp-encryption-agent | Designs encryption architectures meeting SC-12, SC-13, SC-28, and key rotation requirements. | [.github/agents/FedRAMP Encryption and Key Management.md](.github/agents/FedRAMP%20Encryption%20and%20Key%20Management.md) | 🔐 stronger crypto · 🧰 clear patterns |
| fedramp-conmon-agent | Designs and updates Continuous Monitoring processes for monthly/quarterly scans and reporting. | [.github/agents/FedRAMP Continuous Monitoring Agent.md](.github/agents/FedRAMP%20Continuous%20Monitoring%20Agent.md) | 📈 continuous insight · 🔍 faster findings |
| fedramp-control-writer | Writes FedRAMP control implementations aligned to NIST 800-53 Rev5. | [.github/agents/FedRAMP Control Implementation Writer.md](.github/agents/FedRAMP%20Control%20Implementation%20Writer.md) | ✍️ clear controls · ✅ auditability |
| secure-cicd-fedramp-agent | Ensures CI/CD pipelines meet FedRAMP, SDLC, CM, and supply-chain best practices. | [.github/agents/CICD Security Compliance.md](.github/agents/CICD%20Security%20Compliance.md) | 🔒 hardened pipelines · ⚙️ reliable releases |

### Security & Compliance

| Agent | What it does | Link | Benefit |
|---|---|---|---|
| iac-security-auditor | Performs security review of Terraform, CloudFormation, and Kubernetes YAML. | [.github/agents/IaC Security Advisor.md](.github/agents/IaC%20Security%20Advisor.md) | 🛡️ safer infra · 🧱 policy alignment |
| security-audit-assistant | Reviews code changes/features for security issues and suggests remediations. | [.github/agents/Security Review Agent.md](.github/agents/Security%20Review%20Agent.md) | 🔍 early detection · 🛡️ fewer vulns |
| pii-compliance-agent | Ensures pipelines handle PII and sensitive data according to policies. | [.github/agents/PII Compliance Agent.md](.github/agents/PII%20Compliance%20Agent.md) | 🔒 data protection · 📜 compliance |

## Installing

> You can define agent profiles at the repository level (.github/agents/CUSTOM-AGENT-NAME.md in your repository) for project-specific agents, or at the organization or enterprise level (/agents/CUSTOM-AGENT-NAME.md in a .github-private repository) for broader availability. See [Preparing to use custom agents in your organization](https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-organization/prepare-for-custom-agents) and [Preparing to use custom agents in your enterprise](https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/prepare-for-custom-agents).

Source: https://docs.github.com/en/copilot/concepts/agents/coding-agent/about-custom-agents
