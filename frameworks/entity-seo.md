# Framework: Entity SEO & Brand Authority Building

## Purpose
This framework provides a system for establishing your brand as a recognized entity that AI systems and search engines trust, understand, and recommend.

## Core Principle
> **"Identity is the new ranking." AI systems favor recognizable, well-defined entities over anonymous content.**

---

## Phase 1: Entity Definition

### Step 1.1: Core Entity Statement

Define your brand entity in a single, clear statement:

**Template:**
```markdown
[Brand Name] is a [Category] that helps [Target Audience] achieve [Primary Outcome] through [Unique Mechanism].
```

**Example:**
```markdown
Clearscope is an AI-powered content optimization platform that helps SEO professionals and content marketers achieve higher search rankings through semantic analysis and actionable content grading.
```

### Step 1.2: Entity Attributes

Document consistent attributes that define your entity:

| Attribute Type | Example | Must Be Consistent Across All Platforms |
|----------------|---------|----------------------------------------|
| Brand Name | Clearscope | ✅ Exact spelling and capitalization |
| Category | Content optimization platform | ✅ Same phrasing everywhere |
| Founded | 2016 | ✅ Same year everywhere |
| Founder | Bernard Huang | ✅ Same name spelling |
| Headquarters | Austin, TX | ✅ Same location |
| Primary Offering | AI content optimization | ✅ Same description |
| Target Audience | SEOs, content marketers | ✅ Same audience definition |

### Step 1.3: Entity Relationships

Map how your entity relates to other entities:

| Relationship Type | Related Entity | How to Establish |
|-------------------|----------------|------------------|
| Competitor | Surfer SEO | Mention in comparison content |
| Complementary | Google Search Console | Integration documentation |
| Industry | SEO software | Category association |
| Founder of | Bernard Huang → Clearscope | Consistent attribution |
| Used by | B2B SaaS companies | Case studies, logos |

---

## Phase 2: Entity Home Creation

### Step 2.1: Entity Home Page Requirements

Your "Entity Home" is the canonical source of truth for AI systems.

**Required Elements:**

```markdown
# [Brand Name]

## What Is [Brand Name]
[Clear, concise definition using core entity statement]

## What [Brand Name] Does
- [Primary function 1]
- [Primary function 2]
- [Primary function 3]

## Who [Brand Name] Helps
- [Target audience 1]
- [Target audience 2]

## How [Brand Name] Works
[Brief explanation of unique mechanism]

## Why [Brand Name] Exists
[Mission or founding story]

## [Brand Name] Facts
| Attribute | Value |
|-----------|-------|
| Founded | [Year] |
| Founder | [Name] |
| Headquarters | [Location] |
| Customers | [Number/Range] |

## Recognition
- [Awards]
- [Certifications]
- [Notable mentions]
```

### Step 2.2: Schema Markup for Entity Home
```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "[Brand Name]",
  "url": "https://[domain].com",
  "logo": "https://[domain].com/logo.png",
  "description": "[Core entity statement]",
  "foundingDate": "[YYYY]",
  "founder": {
    "@type": "Person",
    "name": "[Founder Name]"
  },
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "[City]",
    "addressRegion": "[State]",
    "addressCountry": "[Country]"
  },
  "sameAs": [
    "https://linkedin.com/company/[brand]",
    "https://twitter.com/[brand]",
    "https://crunchbase.com/organization/[brand]"
  ]
}
```

### Step 2.3: Entity Home URL
| Best Practice | Example | Avoid |
|---------------|---------|-------|
| Dedicated page | /about or /company | Burying on homepage only |
| Linked from footer | Site-wide link | Hidden in navigation |
| Indexable | Allow crawling | Noindex tag |

## Phase 3: Entity Consistency Across Platforms

### Step 3.1: Platform Audit Checklist
| Platform | Entity Name | Description Match? | Attributes Match? | URL Claimed? |
|----------|-------------|--------------------|-------------------|-------------|
| Website | [Check] | [Y/N] | [Y/N] | ✅ |
| LinkedIn | [Check] | [Y/N] | [Y/N] | ✅ |
| Twitter/X | [Check] | [Y/N] | [Y/N] | ✅ |
| Crunchbase | [Check] | [Y/N] | [Y/N] | ✅ |
| Google Business | [Check] | [Y/N] | [Y/N] | ✅ |
| Trustpilot/G2 | [Check] | [Y/N] | [Y/N] | ✅ |
| Wikipedia	| [Check] | [Y/N] | [Y/N] | ⚠️ |

### Step 3.2: Consistency Fix Protocol
For each inconsistency found:
- Document current state (screenshot)
- Update to canonical version
- Log change date
- Re-audit quarterly

### Step 3.3: Canonical Entity Reference Sheet
Create a single reference document for all team members:
```markdown
# [Brand Name] Entity Reference

## Always Use Exactly:
- Brand Name: [Exact spelling and capitalization]
- Tagline: [Exact phrasing]
- Description: [Core entity statement]
- Founded: [Year]
- Founder: [Full name]

## Never Use:
- [Variant spelling 1]
- [Old tagline]
- [Outdated description]
```

## Phase 4: Entity Reinforcement Strategy

### Step 4.1: Content-Level Reinforcement
| Content Type | Reinforcement Method |
|--------------|----------------------|
| Blog posts | Consistent author attribution; brand mention in context |
| Case studies | Entity-to-entity relationship building |
| Press releases | Structured entity announcements |
| Guest posts | Consistent bio with entity statement |
| Podcast appearances | Standardized introduction |

### Step 4.2: External Validation Signals
AI systems look for entity validation from trusted third parties:

| Signal Type | Examples | Priority |
|-------------|----------|----------|
| Knowledge Graph presence | Google Knowledge Panel | High |
| Wikipedia mention | Entity page or list inclusion | High |
| Crunchbase profile | Complete and verified | Medium |
| Industry awards | Listed on award sites | Medium |
| Media mentions | Major publications | High |
| Review platforms | G2, Capterra, Trustpilot | Medium |

### Step 4.3: Entity Relationship Building
Build connections to established entities:

| Method | Example |
|--------|---------|
| Integration partnerships | "Clearscope integrates with WordPress" |
| Co-marketing | Joint webinar with complementary brand |
| Expert quotes | "According to [Brand]'s research..." |
| Industry associations | Membership in recognized bodies |

## Phase 5: Knowledge Graph Optimization

### Step 5.1: Knowledge Panel Triggers
Factors that influence Knowledge Graph inclusion:

| Factor | Action |
|--------|--------|
| Entity Home with schema | ✅ Phase 2 complete |
| Wikipedia presence | Seek legitimate inclusion |
| Consistent NAP (Name, Address, Phone) | Verify across all platforms |
| Branded search volume | Build through marketing |
| External references | Earn media mentions |

### Step 5.2: Knowledge Panel Management
Once a Knowledge Panel appears:

| Action | How To |
|--------|--------|
| Claim panel | Google Search → "Claim this knowledge panel" |
| Suggest edits | Correct inaccurate information |
| Monitor changes | Quarterly review |

## Phase 6: AI-Specific Entity Optimization

### Step 6.1: AI Retrieval Triggers
AI systems retrieve entities based on:

| Trigger | Optimization |
|---------|--------------|
| Clear definition | Entity Home with concise description |
| Consistent naming | Standardized across all platforms |
| Relationship clarity | Explicit connections to other entities |
| Trust signals | Third-party validation |

### Step 6.2: Prompt Engineering for Entity Visibility
Test how AI systems describe your entity:

Test Prompts:
```text
"What is [Brand Name]?"
"Who founded [Brand Name]?"
"What does [Brand Name] do?"
"Who are [Brand Name]'s competitors?"
"How does [Brand Name] compare to [Competitor]?"
```

Document Results:
| Date | Query | AI Response | Accuracy | Action Needed |
|------|-------|-------------|----------|---------------|
| 2026-04-21 | "What is [Brand]?" | [Response] | Partial | Update | Entity Home |

### Step 6.3: Entity Gap Remediation
If AI cannot answer accurately:

| Gap | Fix |
|-----|-----|
| Doesn't know brand | Build Entity Home; increase external mentions |
| Wrong description | Update and standardize all platform descriptions |
| Wrong founder | Correct LinkedIn, Crunchbase, Entity Home |
| Missing relationships | Create content establishing connections |

## Phase 7: Entity Authority Measurement

### Step 7.1: Entity Visibility Scorecard
| Metric | Measurement Method | Frequency |
|--------|--------------------|-----------|
| Knowledge Panel exists? | Google search branded query | Monthly |
| AI correctly describes entity? | Test 5 prompts in ChatGPT/Perplexity | Monthly |
| Branded search volume | GSC / Google Trends | Monthly |
| Entity Home indexed? | Site:domain.com/about | Weekly |
| Schema validation | Rich Results Test | Quarterly |
| Platform consistency | Manual audit (10 platforms) | Quarterly |

### Step 7.2: Entity Growth Metrics
| Metric | Baseline | Target (6 mo) | Target (12 mo) |
|--------|----------|---------------|----------------|
| Branded impressions | [Current] | +25% | +50% |
| Knowledge Panel views | [Current] | +10% | +25% |
| AI mention accuracy | [%] | 80% | 95% |
| Referring domains (brand) | [Count] | +15% | +30% |

## Phase 8: Entity Crisis Prevention

### Step 8.1: Common Entity Failures
| Failure | Cause | Prevention |
|---------|-------|------------|
| Duplicate Knowledge Panels | Inconsistent NAP | Standardize all listings |
| Wrong entity association | Similar name confusion | Differentiate clearly |
| Entity decay | No updates for 12+ months | Quarterly Entity Home | refresh |
| AI hallucination | Insufficient external signals | Build third-party validation |

### Step 8.2: Entity Audit Schedule
| Audit Type | Frequency | Owner |
|------------|-----------|-------|
| Platform consistency check | Quarterly | SEO Lead |
| Knowledge Panel review | Monthly | SEO Lead |
| AI response testing | Monthly	| Content Team |
| Schema validation	| Quarterly | Developer |
| Competitor entity comparison | Bi-annually | SEO Lead |

**Integration with Other Frameworks**
| Framework | Integration Point |
|-----------|-------------------|
| content-engine.md | Entity definitions inform content briefs |
| topical-authority.md | Entity relationships feed topical maps |
| distribution-engine.md | Entity consistency across distribution channels |

**Entity SEO Quick Reference Card**
```text
ENTITY SEO CHECKLIST
☐ Core entity statement defined
☐ Entity attributes documented
☐ Entity Home page published with schema
☐ 10+ platforms audited for consistency
☐ Knowledge Panel claimed (if exists)
☐ AI prompts tested for accuracy
☐ Quarterly audit scheduled
```

### Sources
This framework synthesizes insights from:
- Jason Barnard — Entity SEO and "Identity is the new ranking" framework (source: Jason Barnard, https://kalicube.com/ from 20.01.2026)
- Jason Barnard — Entity Home concept and Knowledge Graph optimization (source: Jason Barnard, https://searchengineland.com from 20.02.2026)
- Aleyda Solís — Multi-platform presence and distributed trust signals (source: Aleyda Solís, https://humansofmartech.com/2026/01/13/202-aleyda-solis-ai-search-crawlability/ from 13.01.2026)
- Lily Ray — Owning brand narrative and proactive question answering (source: Lily Ray, https://www.linkedin.com/posts/lily-ray-44755615_so-much-of-what-i-see-as-the-right-way-to-activity-7397358107875524608-4MhO from 18.11.2025)