# Awesome-Relationship-Intelligence

## Relationship Intelligence Platforms / Agents for Dealmakers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Relationship Intelligence for Private Capital, Venture Capital & Investment Banking*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **relationship intelligence platforms/agents** designed for dealmakers in private equity, venture capital, and investment banking. These tools help find, manage, and close deals efficiently by mapping networks, surfacing warm introductions, automating data capture from email/calendar, enriching contacts, managing pipelines, and leveraging AI for relationship strength scoring and deal sourcing.

**Examples** include Affinity (the category leader), along with 4Degrees, Rings AI, DealCloud, and others. Tools listed here emphasize **agentic capabilities** (multi-step reasoning, network graph analysis, automated enrichment, warm intro recommendations, pipeline intelligence) tailored for high-value relationship-driven dealmaking.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local LLMs (Ollama), custom agents, personal relationship management, and full data control — ideal for privacy-conscious investors and teams building custom deal flow systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (Relationship Intelligence for Dealmakers)

- **[Affinity](https://www.affinity.co/)**  
  Leading relationship intelligence CRM purpose-built for private capital, VC, and investment banking. Automatically captures data from email, calendar, and meetings, maps firm-wide relationships, scores connection strength, and surfaces warm introductions to accelerate deal sourcing and closing.

- **[4Degrees](https://www.4degrees.ai/)**  
  Strong Affinity alternative focused on private equity, VC, and deal-driven teams. Automates data capture, provides true network-based relationship intelligence, flexible pipelines, and warm intro mapping with fast implementation.

- **[Rings AI](https://www.rings.ai/)**  
  Next-generation AI-powered relationship intelligence platform (XRM). Goes beyond existing networks with AI-driven prospecting, dynamic relationship mapping, predictive scoring, and real-time intelligence for VC and PE firms.

- **[DealCloud (Intapp)](https://www.intapp.com/dealcloud/)**  
  Enterprise-grade CRM with deep relationship intelligence, pipeline management, and third-party data integration tailored for private equity, investment banking, and M&A advisory.

- **[Meridian](https://www.meridian-ai.com/)**  
  AI-native CRM built specifically for private equity teams (by ex-Blackstone/Thoma Bravo professionals). Turns relationships and deal data into intelligence-driven sourcing and execution.

### Advanced & Specialized Platforms

- **[Navatar](https://www.navatargroup.com/)**  
  CRM designed for dealmakers in private equity, investment banking, corporate development, and VC with strong relationship mapping and automation.

- **[Attio](https://attio.com/)**  
  Modern, flexible CRM popular among VC and growth teams with customizable pipelines and relationship intelligence features.

**Other notable mentions**: Dynamo (asset management + IR), Salesforce with custom configurations, and Folk CRM.

## Open-Source GitHub Projects

### Dedicated Relationship Intelligence & Dealmaking Agent Projects

- **[Relaticle](https://github.com/relaticle/relaticle)**  
  Open-source CRM with native AI agent support. Includes a production-grade MCP server with 30+ tools for full CRM operations. Self-hosted, built with Laravel & Filament — ideal for connecting external AI agents (Claude, GPT, or local models) to manage relationships and deals.

- **[Twenty](https://github.com/twentyhq/twenty)**  
  The #1 modern open-source CRM and open alternative to Salesforce, explicitly designed for AI. Gives technical teams full building blocks for custom, extensible relationship management and deal pipelines with high customizability and AI integration.

- **[Monica](https://github.com/monicahq/monica)**  
  Popular personal relationship management (PRM) tool. Helps organize contacts, track interactions, reminders, and relationship history with strong emphasis on privacy and self-hosting. Great foundation for individual dealmakers or small teams building personal networks.

- **[Octagon VC Agents](https://github.com/OctagonAI/octagon-vc-agents)**  
  MCP server running AI-driven venture capitalist agents. Enriches thinking with private data and simulates expert VC decision-making for deal sourcing and evaluation.

- **[Synaptra Agents](https://github.com/Synaptravc/agents)**  
  Multi-agent system for venture investment. Includes specialized agents for opportunity identification, financial analysis, risk evaluation, and execution — highly relevant for AI-powered deal flow.

- **[WhiteRock](https://github.com/kyegomez/WhiteRock)**  
  Fully autonomous AI VC fund. Automates the entire investment process including deal sourcing, evaluation, and decision-making using advanced agents.

- **[Free-CRM](https://github.com/go2ismail/Free-CRM)**  
  Open-source CRM for managing leads, campaigns, deals, budgets, and sales pipelines. Self-hosted and fully customizable for dealmaking workflows.

- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**  
  Mature, enterprise-ready open-source CRM with sales automation, workflows, reporting, and modules for opportunities/deals. Extensible with AI for relationship intelligence.

- **[EspoCRM](https://github.com/espocrm/espocrm)**  
  User-friendly open-source CRM with workflow automation, customizable modules, and strong support for sales pipelines and contact/relationship management.

- **[Frappe CRM](https://github.com/frappe/crm)**  
  Simple, modern, fully featured open-source CRM designed for sales teams with unlimited users and clean architecture.

- **[Django CRM](https://github.com/DjangoCRM/django-crm)**  
  Python/Django-based open-source CRM with lead/deal management, tasks, projects, and email marketing capabilities.

### Additional Strong Open-Source Options

- **[BottleCRM](https://github.com/MicroPyramid/opensource-startup-crm)** — Modern multi-tenant CRM for startups and SMBs with pipeline and opportunity management.  
- **[Krayin Laravel CRM](https://github.com/krayin/laravel-crm)** — Laravel-based CRM with AI-powered features in some forks.  
- **[Dolibarr ERP/CRM](https://github.com/Dolibarr/dolibarr)** — All-in-one ERP/CRM suitable for deal tracking and financials.  
- **awesome-open-source-crm** (https://github.com/sneg55/awesome-open-source-crm) — Curated list of personal and business relationship management tools.

**Frameworks for building custom agents**: Combine **LangGraph**, **CrewAI**, or **AutoGen** with the above CRMs + vector databases for RAG on deal notes/contracts. Use MCP servers (like in Relaticle) to connect agents to your relationship graph. Integrate with LinkedIn/Gmail scrapers (ethically) or public data sources for deal sourcing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Always verify data privacy (GDPR, CCPA), security, and compliance when handling sensitive deal and relationship data, especially with self-hosted open-source tools.
- AI relationship intelligence agents are powerful tools but **not substitutes** for human judgment, ethical networking practices, or professional legal/financial advice.

---

**Made for venture capitalists, private equity professionals, investment bankers, and dealmakers.**  
Let's make relationship-driven dealmaking smarter, faster, and fully controllable.

## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Relationship-Intelligence&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Relationship-Intelligence&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Relationship-Intelligence&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Relationship-Intelligence&type=date&legend=bottom-right" />
 </picture>
</a>
