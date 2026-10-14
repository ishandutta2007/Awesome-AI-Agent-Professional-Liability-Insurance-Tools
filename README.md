# Awesome-AI-Agent-Professional-Liability-Insurance-Tools

## Top AI Agent Professional Liability Insurance Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agent Risk Assessment, Liability Coverage & Actuarial Frameworks*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Professional Liability Insurance Tools**. These tools enable insurers, brokers, and enterprises to assess agent-driven operational risk, quantify potential losses, and structure liability coverage for autonomous systems that execute consequential actions.



**Examples** include Coalition, Cowbell Cyber, Corvus Insurance, At-Bay, Resilience, Boost Insurance, Munich Re (aiSure), Marsh Cyber, Travelers, and Chubb (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, agent risk scoring, and open actuarial frameworks—ideal for insurers, risk engineers, and developers seeking transparent, vendor-independent agent liability assessment.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Coalition](https://www.coalitioninc.com/)**  

  Largest cyber insurtech valued at $5B, combining active cyber insurance with cybersecurity tools . Offers AI endorsement for technology E&O forms . Named as a target insurer for Kova verification framework alongside At-Bay, Corvus, and Resilience .



- **[At-Bay](https://www.at-bay.com/)**  

  Full-stack E&S carrier with InsurSec model, $1.35B valuation, AM Best A- rating . Demonstrates 7x lower ransomware claims frequency through AI-powered underwriting . Named as target insurer for agent risk verification frameworks .



- **[Corvus Insurance (Travelers)](https://www.corvusinsurance.com/)**  

  Smart Cyber Insurance with data-driven underwriting, acquired by Travelers in 2023 . Offers AI endorsement on tech E&O forms . Named as target insurer for agent liability underwriting frameworks .



- **[Resilience](https://www.resilience.com/)**  

  Cyber insurance carrier named alongside Coalition, At-Bay, and Corvus as target insurers for AI agent risk verification .



- **[Munich Re (aiSure)](https://www.munichre.com/)**  

  Standalone AI performance guarantee structure. Cited for model drift peril coverage . One of few carriers offering standalone AI policies alongside Armilla, Testudo, and Relm .



- **[Armilla AI](https://www.armilla.ai/)**  

  Specialized AI liability insurance provider. Partners with Chaucer and Hiscox for hallucination coverage, and with Munich Re for model drift performance guarantees . Offers standalone AI policies and has published lessons from a year of underwriting AI liability insurance .



- **[Mount (Y Combinator)](https://www.ycombinator.com/launches/QUI-mount-the-ai-agent-insurance-carrier)**  

  AI-Agent Insurance Carrier selling liability insurance for companies deploying agents in production. Scans and red-teams agent workflows, reduces failure modes, and insures residual risk with purpose-built AI-agent liability coverage. Sam Altman endorsement: "Insurance is shockingly important... No one is doing a good job of underwriting this right now" .



- **[Apollo ibott Syndicate 1971](https://www.apollointelligence.com/)**  

  Agentic failure coverage as autonomous/agentic liability .



- **[Chaucer / Beazley](https://www.chaucer.com/)**  

  Algorithmic bias as third-party liability coverage. Chaucer partners with Armilla for hallucination coverage .



- **[Coalition Deepfake Response](https://www.coalitioninc.com/)**  

  First-party response endorsement for deepfake incidents .



## Open-Source GitHub Projects



- **[Agent SRE](https://pypi.org/project/agent_sre/)**  

  Open-source Site Reliability Engineering framework for AI agents. Defines SLOs for agent behavior including task success rate, tool call accuracy, cost per task, policy compliance, scope chain depth, and hallucination rate. Features Replay Engine for time-travel debugging, Cost Guard for runaway tool loop prevention, Circuit Breaker for cascade failure prevention, and Chaos Engine for resilience testing. Addresses the insurance-relevant failure modes: cost explosion ($10K in minutes), cascade failures (Agent A trusts Agent B who hallucinates), and tool drift (MCP schema changes silently breaking workflows) .



- **[Kova (nobulex)](https://github.com/arian-gogani/nobulex)**  

  Actuarial framework for quantifying AI agent risk (license varies). Provides risk infrastructure for insurers with three components: **Identity binding** (who is responsible), **Covenant declaration** (what the agent committed to), and **Compliance proof** (cryptographic verification of behavior). Quantifiable risk factors include covenant coverage (percentage of actions governed), hard enforcement (CapabilityGate presence), attestation coverage, breach history, and stake ratio (economic backing). Framework lets insurers price Kova verification into premiums themselves—verified agents show X% lower incident rate (simulated → validated). Publishes whitepaper for arXiv and insurer outreach to Coalition, At-Bay, Corvus, and Resilience .



- **[VerifyWise](https://oecd.ai/en/catalogue/tools/verifywise-aiverifywise)**  

  Open-source AI governance, risk, and compliance platform (360 GitHub stars, 123 forks). Creates central repository for AI systems, models, agents, applications, and suppliers with structured inventory. Features risk assessments, governance decisions, evaluations, responsibility assignment, and mitigation tracking. Maps governance activities across EU AI Act, ISO/IEC 42001, and NIST AI RMF simultaneously—record evidence once and reuse across obligations. Includes AI evaluations and ongoing monitoring for continuous assurance rather than periodic reviews .



- **[Aegis Workbench](https://pypi.org/project/aegis-workbench/)**  

  Enterprise AI governance workbench for EU AI Act and NIST AI RMF (Apache-2.0). Catalogs every AI system, classifies against frameworks, evaluates policy-as-code, auto-generates model cards and conformity documentation. Writes every change to an Ed25519-signed append-only ledger. Includes financial-services vertical pack with SR 11-7 model risk and NYDFS Part 500. CLI commands for initialization, system registration, assessment, and Annex IV technical documentation emission .



- **[Vaara](https://oecd.ai/en/catalogue/tools/vaara)**  

  Open-source governance and evidence layer for AI agents (AGPL-3.0, 14 GitHub stars). Checks each action against defined policy and produces verifiable record of what agent did and why. Features risk scoring with allow/block/escalate decisions, adaptive scoring based on past outcomes, hash-chained audit trail (tamper-evident), offline verification using public key, and EU AI Act article-mapped evidence reports. Adapters for LangChain, CrewAI, and OpenAI Agents SDK. Can act as MCP server proxy. Shadow mode for policy testing .



- **[CRML — Cyber Risk Modeling Language](https://pypi.org/project/crml-lang/)**  

  Open, declarative language for expressing cyber risk models, telemetry mappings, simulation pipelines, and output requirements (CRML 1.1, maintained by Zeron Research Labs). Designed for Bayesian cyber risk models (QBER, MCMC-based), FAIR-style Monte Carlo engines, insurance actuarial risk systems, and enterprise cyber risk quantification platforms. Features control effectiveness modeling (quantify how security controls reduce risk with defense-in-depth calculations), multi-currency support, auto-calibration from raw loss data, and strict JSON Schema validation. Example: email security control (90% effectiveness, 95% reliability) reduces risk from 15% to ~3.5% (76% reduction) .



- **[FAIR Risk Analysis Dashboard](https://github.com/paolocarner/fair-monte-carlo-risk-analysis)**  

  Interactive CRQ Monte Carlo simulation tool for quantifying cybersecurity risk using FAIR methodology. Built for EU SMBs, vCISOs, and security practitioners. Features 1,000 to 50,000 simulation runs, external vs internal factor grouping, configurable risk tolerance, 9 preset scenarios (Ransomware, Data Breach, BEC, DDoS, Insider Threat, Zero-Day, Device Theft, System Outage, Supply Chain), ROI calculators with ROSI analysis and insurance recommendation tools, and multiple export formats. Risk = Loss Event Frequency × Loss Magnitude; LEF = Threat Event Frequency × Vulnerability .



- **[Cyber Risk Platform](https://github.com/sabrinahaniff/cyber-risk-platform)**  

  AI-powered cyber insurance underwriting platform (open-source). Automates risk assessment with scoring engine (0-100) using weighted deductions across 6 security factors: firewall presence (-20), antivirus (-15), data encryption (-20), incident response plan (-15), security training (-10), and previous breach (-10 per incident). Generates AI-written underwriting memos using LLaMA 3.3 70B via Groq. Full-stack React/Spring Boot/PostgreSQL with Docker Compose deployment. REST API for company assessments and memo generation .



- **[AgentTrust](https://pypi.org/project/nishanttyagi-agenttrust/)**  

  Evidence schema and CI gate for agent action verification (alpha, simulators only). Implements "prepare → seal → authorize → commit → verify" pipeline. Rule IDs for payment amount mismatch (AT-PAY-001), wrong payee (AT-PAY-002), unauthorized email recipient (AT-MAIL-001), unauthorized delete target (AT-DEL-001), and unauthorized deploy target (AT-DEP-001). Human approval is explicit act—CLI exits 2 and writes nothing unless `--approve` is set. Evidence Schema v1 with canonical JSON, one-way maps from AgentEval traces and CodeGovernor summaries .



- **[Ephor](https://pypi.org/project/ephor/)**  

  Passive host-side monitor for AI agent activity (v0.3, open-source). Watches what agents run, install, and look up. Supply chain monitoring: every process followed up parent chain to recognized agent; package installations snapshotted every 5 minutes (Python site-packages, npm, Homebrew, dpkg, apk); new Python/npm packages checked against OSV.dev malicious-packages list and PyPI/npm for young packages (slopsquatting detection). DNS checks for feed hits, lookalike domains, punycode, random-looking labels, and DNS-over-HTTPS usage. eBPF probe for sampling-resistant events .



### Additional Strong Open-Source Options



- **[agent-sandbox-runtime](https://pypi.org/project/agent-sandbox-runtime/)** — Docker-isolated code execution with Reflexion Loop, 5 specialist agents, and 92% benchmark success rate .

- **[OpenTelemetry GenAI Semantic Conventions](https://github.com/open-telemetry/semantic-conventions-genai)** — Vendor-neutral telemetry schema for GenAI and agent spans, covering model calls, tool calls, token usage, and agent operations .

- **[MITRE ATLAS](https://atlas.mitre.org/)** — Adversarial Threat Landscape for AI Systems. v2026.07 includes 16 tactics, 101 techniques, 37 mitigations, 68 case studies, and 3 AI Agent Tool Poisoning sub-techniques .

- **[NIST AI 600-1 GenAI Profile](https://nvlpubs.nist.gov/)** — Cross-sector companion to NIST AI RMF naming 12 GenAI risk areas and 200+ suggested actions .

- **[EU AI Act Article 12 Record-Keeping](https://artificialintelligenceact.eu/)** — Legal duty for high-risk AI systems to record events throughout lifetime. Article 26(6) requires deployers retain logs for at least 6 months .

- Community **n8n** workflows for agent risk alerting and governance automation.



**Frameworks for building custom systems**: Combine **Vaara** or **Agent SRE** for runtime agent governance and evidence capture with **VerifyWise** or **Aegis Workbench** for compliance mapping against EU AI Act and NIST frameworks, **CRML** for actuarial risk model expression, **Kova** for covenant-based verification, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade agent liability assessment platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI agent liability insurance is an emerging category. Market size projected at USD 34.2B by 2034 with 24.6% CAGR, but products and coverage positions are evolving rapidly .

- **Silent AI is the default position.** Most policies neither grant nor exclude AI risk—the answer arrives through claims and case law, meaning the policyholder funds the test case. 38% of brokers say clients don't know if their policies cover AI; only 13% say yes .

- **Exclusions are emerging.** ISO published generative AI template exclusion (effective January 2026); agentic AI template in progress. W. R. Berkley filed absolute AI exclusions barring AI use, deployment, or development. AIG, Great American, Cincinnati Financial, and others filed carrier-specific exclusions in 2025-2026 .

- **Liability allocation is unclear.** An AI error can land in professional liability, employment practices liability, contractual liability, or general liability depending on what the system did and to whom. The Workday ruling established that a vendor need not be the employer to carry exposure—it only has to have been handed the decision .

- **Open-source frameworks provide risk infrastructure, not insurance.** Verification frameworks like Kova provide data structures for covenant compliance and breach attestation; insurers provide pricing and coverage .



---



**Made for insurance actuaries, risk engineers, AI governance teams, and developers building transparent agent liability assessment solutions.**  

Let's make AI Agent Professional Liability Insurance more open, data-driven, and accountable.
