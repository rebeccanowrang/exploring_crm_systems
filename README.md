# Exploring CRM Systems Using Generative AI

## Student Information

**Student:** Rebecca Nowrang\
**Course:** ICS499 - Software Engineering and Capstone Project\
**Institution:** Metro State University

## Executive Summary

Customer Relationship Management (CRM) systems centralize information
about customers and prospects and support sales, marketing, service,
activities, and reporting. This project uses generative AI to explain
CRM concepts, compare commercial and open-source products, examine
SuiteCRM, and propose a CRM architecture using HTML, CSS, JavaScript,
jQuery, Bootstrap, PHP, and MySQL.

## AI Tools Used

The primary AI tool was **ChatGPT (GPT-5.6 Sol)**. It helped organize
research, compare products, explain architecture/security, create
prompts, and identify claims requiring validation. Current pricing,
features, and installation requirements were checked against official
documentation.

## CRM Research Findings

CRM provides a shared system for contacts, accounts, leads,
opportunities, activities, campaigns, support, reports, and dashboards.
Organizations use it to improve follow-up, collaboration, pipeline
visibility, customer service, marketing coordination, and
decision-making. See [crm_research.md](crm_research.md).

## CRM Product Comparisons

Commercial products reviewed were Salesforce Sales Cloud, HubSpot CRM,
Zoho CRM, and Microsoft Dynamics 365 Sales. Open-source products
reviewed were SuiteCRM, EspoCRM, and Odoo Community.

For many small businesses I would begin by evaluating HubSpot because of
its low-friction entry point. Large enterprises should evaluate
Salesforce and Microsoft Dynamics 365 against their integration and
customization requirements. SuiteCRM is a strong CRM-focused open-source
candidate.

## Open Source CRM Evaluation

**Selected product: SuiteCRM.** It provides traditional CRM modules
including leads, accounts, contacts, opportunities, campaigns, cases,
activities, reports, and dashboards. Self-hosting is more technical than
a hosted CRM because server, PHP, database, modules, permissions, and
web-server configuration must be compatible.

**Submission note:** The five files in `screenshots/` are placeholders.
Replace them with screenshots you personally capture from SuiteCRM.
Generated screenshots should not be presented as evidence of hands-on
use.

## CRM Architecture Proposal

The proposed system has a browser/presentation layer, PHP application
layer, and MySQL data layer. DataTables, Chart.js, PHPMailer, and
Composer can accelerate development.

![CRM Architecture](architecture/crm_architecture.png)

## Prompt Engineering Examples

Effective prompts specified a role, context, criteria, technology
constraints, output format, and facts requiring verification. See
[prompts_used.md](prompts_used.md).

## Lessons Learned

AI accelerated unfamiliar-domain research and was strongest at
explanation, organization, comparison structure, and architecture. It
was weaker for time-sensitive, version-specific, and licensing
information. The best workflow was AI for discovery and synthesis
followed by verification with authoritative sources.

## References

See [references.md](references.md).
