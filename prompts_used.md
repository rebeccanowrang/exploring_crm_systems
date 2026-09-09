# Prompts Used and AI Reflection

## AI Tool

**ChatGPT (GPT-5.6 Sol)** was the primary generative AI research
assistant.

## Best Prompts

### 1. CRM Fundamentals

> Act as a CRM consultant teaching a software engineering student.
> Explain CRM's definition, purpose, history, evolution, major modules,
> and organizational uses. Separate stable concepts from claims
> requiring current verification.

**Result:** Established vocabulary and a clear research structure.

### 2. Commercial Comparison

> Compare Salesforce Sales Cloud, HubSpot CRM, Zoho CRM, and Microsoft
> Dynamics 365 Sales. Include target customer, strengths, weaknesses,
> and pricing model. Flag pricing and other time-sensitive facts for
> official verification.

**Result:** Produced consistent comparison criteria and highlighted
information likely to change.

### 3. Open-Source Comparison

> Compare SuiteCRM, EspoCRM, and Odoo Community as open-source CRM
> options. Include features, technology stack, community/ecosystem,
> installation difficulty, and best-fit organization.

**Result:** Helped compare technical and business considerations rather
than only features.

### 4. Architecture

> Act as a software architect. Design an MVP CRM using HTML, CSS,
> JavaScript, jQuery, Bootstrap, PHP, and MySQL. Identify modules,
> database tables, useful libraries, security controls, and a layered
> architecture.

**Result:** Connected CRM research to software engineering and the
required stack.

### 5. Security Review

> Review a PHP/MySQL CRM for authentication, authorization, password
> storage, SQL injection, XSS, CSRF, sessions, HTTPS, privacy, backups,
> and audit logging. Explain practical MVP mitigations.

**Result:** Added security requirements that a feature-only design could
miss.

### 6. Validation Prompt

> Act as a skeptical technical reviewer. Identify claims in my CRM
> research that may be outdated, vendor marketing, version-specific, or
> otherwise require validation. Recommend authoritative source types.

**Result:** Encouraged critical evaluation rather than automatic
acceptance.

## AI Effectiveness Analysis

### What AI Did Well

AI explained unfamiliar terminology quickly, organized a large
assignment, created useful comparison criteria, suggested database
entities, explained common security controls, and turned broad
requirements into an MVP.

### What AI Struggled With

AI can state changing information as if it were permanent. Pricing,
software versions, licensing, product packaging, popularity, and
installation requirements can change. It can also oversimplify product
comparisons by treating subjective recommendations as facts.

### Information That Required Validation

I validated current commercial pricing using official vendor pages.
SuiteCRM installation requirements were checked against its official
documentation and compatibility matrix. EspoCRM database/install claims
were checked against official documentation. Odoo's
Community-edition/open-source statement was checked on Odoo's site.
Library descriptions were checked against their official projects.

### Incorrect or Incomplete AI Responses

The main weakness was not a single dramatic error but **staleness
risk**. Initial AI summaries could have used older product pricing or
version requirements. I corrected this by using current official sources
and by describing pricing as a snapshot rather than a permanent fact. I
also avoided unsupported exact market-share claims.

### What Surprised Me

I expected CRM mainly to mean sales contacts. The research showed that
modern CRM can connect sales, marketing, service, activities, reporting,
automation, and integrations. I was also surprised by how much
infrastructure responsibility comes with self-hosted open-source
software.

### What I Would Do Differently

I would start with a validation plan: first ask AI for a research
outline, then identify time-sensitive claims, then collect official
sources before writing the final comparison. I would also keep a source
beside each important claim while researching.

### Would I Trust AI for Software Research?

I would trust AI as a **research assistant**, not as the only source. It
is valuable for discovery, explanation, comparison, brainstorming, and
synthesis. Important decisions should still be checked against
authoritative documentation, especially when money, security, licensing,
compatibility, or current product behavior is involved.
