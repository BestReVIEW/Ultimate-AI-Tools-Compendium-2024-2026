# 🔄 Migration Playbook
*Guides for switching between tools*

---

## Chat/Reasoning Models

### ChatGPT Plus → Claude Pro
**Do it if:**
- You write long-form content (200K context vs 128K)
- You need deeper analysis and reasoning
- You prioritize accuracy over creativity
- You want "Artifacts" for iterative creation

**Keep GPT if:**
- You rely on plugins (browsing, code interpreter)
- You use DALL-E integration heavily
- You need voice mode
- You use custom GPTs

**Migration Tip:** Export your ChatGPT history first. Claude doesn't import history but you can reference past conversations manually.

---

### Claude → Kimi K2.5
**Do it if:**
- You hit Claude's 200K limit regularly (Kimi: 256K)
- API costs are a concern (9x savings)
- You need video-to-code features
- You work with Chinese content
- You want "Kimi Slides" for presentations

**Keep Claude if:**
- Maximum reasoning quality is critical (Claude still edges out slightly)
- Enterprise compliance requirements (SOC 2)
- You rely on Claude's "Artifacts" feature
- Safety/censorship preferences (Claude is more conservative)

**Migration Tip:** Kimi has native VSCode/Cursor integration via Kimi Code CLI. Your coding workflow stays similar.

---

### Any → Grok
**Do it if:**
- You need real-time X/Twitter data (no other AI has this)
- You want unfiltered/less "safe" responses
- You're analyzing social media trends
- You want "fun mode" personality

**Keep Current if:**
- You need file uploads (Grok doesn't support yet)
- You want mature ecosystem (plugins, integrations)
- Enterprise use cases (Grok's personality isn't professional)
- You need long context (128K only)

---

## Coding Tools

### GitHub Copilot → Cursor
**Do it if:**
- You work on large codebases (Cursor understands entire repos)
- You need refactoring assistance ("Composer" feature)
- You want AI chat in IDE (not just autocomplete)
- You want "Agent" mode for multi-file edits

**Keep Copilot if:**
- You use multiple IDEs (Copilot supports 15+, Cursor is VS Code only)
- Strict enterprise compliance required
- You prefer simpler autocomplete (less UI clutter)
- You want GitHub-native integration

**Migration Tip:** Cursor is a VS Code fork. Your extensions and settings transfer easily.

---

### Cursor → Bolt.new
**Do it if:**
- You start new projects from scratch often
- You want browser-based development (no local setup)
- You need to test multiple frameworks quickly
- You want instant deployment (Netlify/Cloudflare)

**Keep Cursor if:**
- You work with existing large codebases
- You need deep codebase understanding
- You want the best AI chat interface
- You need local development environment

**Migration Tip:** Use Bolt.new for prototyping, then import to Cursor for long-term maintenance.

---

## App Builders

### v0 → Lovable
**Do it if:**
- You need full-stack (backend + database) automation
- You want GitHub sync with meaningful commits
- You need Figma-to-code workflow
- You're building production apps (not just components)

**Keep v0 if:**
- You focus on component-level UI generation
- You already use Vercel hosting
- You prefer manual backend wiring
- You want unlimited generations (v0 Pro)

---

### Bolt.new → Lovable
**Do it if:**
- You're building production apps for clients
- You need maintainable, documented code
- You want design-to-code (Figma integration)
- You prefer predictable pricing (messages vs tokens)

**Keep Bolt.new if:**
- You prioritize speed over code organization
- You experiment with many frameworks
- You want browser-based code editing
- You prefer token-based pricing (could be cheaper for small apps)

---

## Music Tools

### Suno → Beatoven.ai
**Do it if:**
- You're a brand/agency needing copyright-safe music
- You use music commercially (ads, client work, YouTube monetization)
- You need video sync features
- You want to avoid legal risk

**Keep Suno if:**
- Personal/non-commercial projects only
- You need vocals and full songs (Beatoven is instrumental only)
- You've verified legal clearance
- You prioritize creative features over safety

**Migration Tip:** Beatoven offers video upload for automatic sync - workflow is different from Suno's text-to-music approach.

---

### Any → Udio
**Do it if:**
- You need highest audio fidelity (48kHz)
- You want professional instrumentals
- You prefer the DeepMind team's approach

**Avoid if:**
- You need to download files (Udio restricts downloads as of 2026)
- You want vocal generation (Suno is better)
- You need copyright clarity (still emerging)

---

## Long-Context Specialists

### Claude/GPT → Kimi (Long Documents)
**Do it if:**
- Processing documents &gt;200K tokens
- Cost is a factor (9x cheaper)
- You need video-to-code capabilities
- You want 100 parallel agents for research

**Keep Claude if:**
- Document &lt;200K tokens (Claude's reasoning is still superior)
- You need maximum safety for sensitive content
- Enterprise compliance requirements

---

### Any → Gemini 1.5 Pro
**Do it if:**
- You need 2M token context (videos, massive codebases)
- You use Google Workspace heavily
- You need native video understanding
- You want integrated Google Search

**Keep Current if:**
- You prioritize reasoning over context size
- You want cheaper API costs (Gemini is pricier than Kimi for smaller contexts)
- You need mature third-party integrations

---

## Multi-Tool Workflows

### Recommended Stacks

**The Solopreneur ($50/mo)**
- Claude Pro ($20) - Reasoning and writing
- Cursor Pro ($20) - Coding
- Beatoven ($9) - Safe music

**The Content Creator ($30/mo)**
- Kimi Moderato ($19) - Long content processing
- Suno Pro ($10) - Music (personal use)

**The Startup Founder ($75/mo)**
- Claude Team ($25) - Team collaboration
- Lovable Pro ($25) - Rapid app prototyping
- Perplexity Pro ($20) - Market research

**The Enterprise (Custom)**
- Claude Enterprise - Secure reasoning
- Gemini Business - Document processing
- GitHub Copilot Business - Coding compliance
- Beatoven Enterprise - Licensed music
