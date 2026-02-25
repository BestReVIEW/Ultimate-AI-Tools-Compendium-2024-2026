# 🌏 Long-Context Specialists
*For when you need to process entire libraries*

---

## Context Window Comparison

| Model | Context | Input Cost (1M tokens) | Best For |
|-------|---------|------------------------|----------|
| **Gemini 1.5 Pro** | 2M tokens | $3.50 | Video analysis, massive documents |
| **Kimi K2.5** | 256K tokens | $0.45-$2.00 | Coding, value-conscious processing |
| **Claude 3.5 Sonnet** | 200K tokens | $3.00 | Reasoning quality, safety |
| **Grok-2** | 128K tokens | $2.00 | Real-time data, social media |

---

## Kimi K2.5 (Moonshot AI)

| Attribute | Details |
|-----------|---------|
| **Best For** | Processing entire codebases, long-document analysis, Chinese/English bilingual |
| **Context Window** | **256K tokens** (up to 200K Chinese characters) |
| **Pricing** | Free tier; Moderato: ~$19/mo; API: $0.45-$2.00/$2.20-$5.00 per 1M tokens |
| **Unique Edge** | Largest context-to-price ratio, "Kimi Slides" (generates editable PPTx), video-to-code, agent swarm |
| **Benchmarks** | 96.2% MATH 500, 77.5% AIME, 94th percentile Codeforces (matches OpenAI o1) |
| **vs. Gemini 1.5 Pro** | 4x smaller context but 9x cheaper API and better coding benchmarks |
| **Limitations** | Chinese company (data sovereignty), newer to Western markets |

**Value Verdict:** ⭐⭐⭐⭐⭐ *Unbeatable value for long-context processing*

### Key Features

- **Visual Programming**: Drop Figma mockup → get React/Vue code
- **Video-to-Code**: Watch demo video, reproduce interactive components  
- **Kimi Code CLI**: Native VSCode/Cursor/Zed integration
- **Researcher Mode**: Autonomous web research with citations
- **Agent Swarm**: 100 parallel agents for complex tasks

### Pricing Tiers

| Plan | Price | Features |
|------|-------|----------|
| **Free** | $0 | Limited access to 256K context |
| **Moderato** | ~$19/mo | Higher rate limits, priority access |
| **Allegro** | Custom | Enterprise features, API access |

---

## Gemini 1.5 Pro (Google)

*See [Essential Tier](./essential-tier.md) for full details*

**Best for:** Video analysis (up to 2M tokens = hours of video), massive document repositories

**Strengths:**
- True 2M token context (largest available)
- Native video understanding
- Google Workspace integration

**Weaknesses:**
- Inconsistent reasoning at extreme contexts
- More expensive than Kimi for API usage

---

## When to Use Which?

| Scenario | Recommendation | Why |
|----------|---------------|-----|
| **Analyze 500-page PDF** | Kimi K2.5 | 9x cheaper than Claude, sufficient context |
| **Analyze 10-hour video** | Gemini 1.5 Pro | Only option with 2M context |
| **Codebase-wide refactoring** | Kimi K2.5 | Best coding benchmarks, IDE integration |
| **Sensitive enterprise docs** | Claude 3.5 | Best safety practices, SOC 2 compliance |
| **Real-time social analysis** | Grok-2 | Live X/Twitter data integration |

---

## Migration: Claude → Kimi?

**Do it if:**
- You hit Claude's 200K limit regularly
- API costs are a concern (9x savings)
- You need video-to-code features
- You work with Chinese content

**Keep Claude if:**
- Maximum reasoning quality is critical
- Enterprise compliance requirements
- You rely on Claude's "Artifacts" feature
- Safety/censorship preferences
