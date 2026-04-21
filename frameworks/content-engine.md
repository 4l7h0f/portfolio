# Framework: AI-Optimized Content Engine

## Purpose
This framework provides a repeatable system for producing content that ranks in traditional search AND gets cited by AI systems.

## Core Principle
> Content must be **retrievable by machines** and **valuable to humans**.

---

## Phase 1: Topic Selection & Validation

### Step 1.1: Identify Opportunity
- Extract queries from GSC with:
  - Impressions > 100
  - CTR < 3%
  - Position 3–15
- Validate with Ahrefs/SEMrush for competitor gaps

### Step 1.2: Intent Classification
| Intent Type | Content Format | Example |
|-------------|----------------|---------|
| Informational | Guide, How-to, List | "What is entity SEO" |
| Commercial | Comparison, Review | "Best AI SEO tools" |
| Transactional | Pricing, Demo | "SEO software pricing" |
| Navigational | Brand page | "Clearscope login" |

### Step 1.3: AI Landscape Check
Query the topic in:
- ChatGPT
- Perplexity AI
- Google AI Overview

**Document:**
- Who is cited?
- What structure is used?
- What questions are answered?

---

## Phase 2: Content Brief Creation

### Brief Template

```markdown
## Topic: [Primary Topic]
## Target Entity: [Brand/Product/Concept]
## Primary Intent: [Informational/Commercial/Transactional]

## Target Queries
1. [Primary query]
2. [Secondary query]
3. [Related question]

## AI Answer Analysis
- Current AI answer includes: [Summary]
- Missing from AI answer: [Gap]
- Our angle: [Differentiation]

## Content Structure
H1: [Title with primary entity]
H2: [Section 1 - Direct answer to primary query]
H2: [Section 2 - Supporting context]
H2: [Section 3 - Practical application]
H2: [Section 4 - FAQs]

## Entities to Include
- [Entity 1] - Definition needed
- [Entity 2] - Relationship to topic
- [Entity 3] - Example or case

## Internal Links
- Link to: [Related pillar page]
- Link from: [Supporting articles]

## Distribution Plan
- Primary: [Blog]
- Secondary: [LinkedIn, Reddit, Newsletter]
```

## Phase 3: AI-Assisted Drafting

### Step 3.1: Generate Outline

**Prompt template:**
```markdown
Create a detailed outline for an article about [TOPIC].
Target audience: [AUDIENCE]
Key entities to cover: [ENTITIES]
Structure should include: H1, 4-6 H2s, key points under each.
```

### Step 3.2: Expand Sections

**Prompt template:**
```markdown
Expand this section: [SECTION TITLE]
Context: [BRIEF CONTEXT]
Include:
- Direct answer to "[QUERY]"
- 1 concrete example
- 1 actionable takeaway
Tone: Professional but accessible.
```

### Step 3.3: Add AI Retrieval Optimizations


| Element | Requirement |
|---------| ----------- |
| H1 | Contains primary entity |
|| First paragraph | Direct answer to main query (40-60 words) |
| H2s |	Clear, descriptive, scannable |
| Lists | Bulleted for definitions and steps |
| Tables | For comparisons and data |
| FAQ section |	3-5 questions with concise answers |

## Phase 4: Human Editing Layer

### Editing Checklist

**Accuracy Check**
- All claims verified with source
- Statistics have citations
- No AI hallucinations present

**Expertise Layer**
- Added original insight not found in AI draft
- Included real example from experience
- Stated opinion or position on debated topic

**Readability Check**
- Sentences under 25 words
- Paragraphs under 4 sentences
- Jargon defined or removed

**AI Retrieval Check**
- Can AI summarize this accurately?
- Are key points extractable in 3 bullets?
- Would this get cited in an AI answer?

## Phase 5: Publishing Checklist

### Pre-Publish
- Title tag: 50-60 chars, includes primary entity
- Meta description: 150-160 chars, includes value proposition
- URL: Short, contains primary keyword
- Schema markup: Article + FAQ (if applicable)
- Internal links: 3-5 contextual links added
- Images: Alt text includes entity name

### Post-Publish
- Submit to Google Search Console
- Share on LinkedIn (within 24 hours)
- Post to relevant subreddit (if authentic value)
- Add to internal link audit list

## Phase 6: Performance Tracking

### Week 1 Metrics

| Metric | Tool | Target |
|--------|------|--------|
| Indexed |	GSC | Within 3 days |
| Impressions | GSC | > 50 first week |
| Avg Position | GSC | Track baseline |

### Week 4 Metrics

| Metric | Tool | Action if Below Target |
|--------|------|------------------------|
| CTR | GSC | Optimize title/meta |
| Avg Position | GSC | Improve internal links |
| Time on Page | GA4 | Add more depth/examples |

### AI Visibility Check (Monthly)
- Query topic in ChatGPT/Perplexity
- Document: Mentioned? (Y/N)
- Document: Which competitors appear?
- Adjust content based on gaps

### Content Decay Detection

**Triggers for Refresh**
| Signal | Threshold | Action |
|--------|-----------|--------|
| CTR decline | >20% drop in 30 days | Update title tag |
| Position decline | Dropped >3 positions | Refresh content, add new data |
| Impressions decline | >30% drop in 60 days | Check cannibalization |
| No AI mention | After 60 days	Improve | structure and clarity |

### Refresh Protocol
1. Review AI answers for topic (what changed?)
2. Update outdated statistics/examples
3. Add new section addressing emerging questions
4. Update publish date
5. Resubmit to GSC
6. Re-distribute on social

### Content Engine Metrics Dashboard

**Weekly Pulse Check**
```markdown
Week of: [DATE]

Content Published: [COUNT]
Pages Refreshed: [COUNT]
CTR Fixes Applied: [COUNT]

Top Performer: [URL] - [+X% CTR]
Needs Attention: [URL] - [ISSUE]

AI Mentions Checked: [COUNT]
AI Mentions Gained: [COUNT]
```

### Integration with Other Frameworks
| Framework | Integration Point |
|-----------|-------------------|
| topical-authority.md | Content clustering and internal linking |
| entity-seo.md | Entity definitions and consistency |
| distribution-engine.md | Post-publish amplification |

### Sources
This framework synthesizes insights from:
- Bernard Huang (Clearscope) — AI retrieval optimization (source: Bernard Huang, https://www.clearscope.io/blog from 15.01.2026)
- Gael Breton — Continuous optimization and CTR focus (source: Gael Breton, https://www.linkedin.com/posts/gael-breton_i-dont-think-people-realize-you-can-replace-activity-7425464338192371713-ZwE1 from 05.11.2025)
- Koray Tuğberk GÜBÜR — Topical clustering and semantic structure (source: Koray Tuğberk GÜBÜR, https://topicalauthority.digital from 15.06.2025)
- Lily Ray — E-E-A-T and human editing layer (source: Lily Ray, https://www.linkedin.com/posts/lily-ray-44755615_so-much-of-what-i-see-as-the-right-way-to-activity-7397358107875524608-4MhO from 18.11.2025)