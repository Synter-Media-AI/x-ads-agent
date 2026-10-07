# X (Twitter) Ads MCP Starter Kit — Manage X Ads with AI

> **This is a recipe repo.** The Synter MCP server itself lives at [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server): create, launch, and optimize campaigns across 16 ad platforms, with one-click install in Cursor, Claude, ChatGPT, and VS Code. Issues, releases, and ⭐ go there.


[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: X Ads](https://img.shields.io/badge/Platform-X%20Ads-000000)](https://ads.x.com)

**Combine organic growth with paid promotion on X.** Open this repo in Amp, Cursor, or VS Code and manage X (Twitter) ad campaigns with AI — promote tweets, target by trending topics, and amplify your brand's voice at pay-per-usage pricing (~$0.01/post).

---

## Install

[![Add to Cursor](https://cursor.com/deeplink/mcp-install-dark.svg)](https://cursor.com/en/install-mcp?name=synter-ads&config=eyJ1cmwiOiJodHRwczovL21jcC5zeW50ZXJhaS5jb20ifQ==)
[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Synter-0098FF?logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect/mcp/install?name=synter-ads&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.synterai.com%22%7D)

- **Cursor / VS Code:** click a button above, or open this repo — it ships `.cursor/mcp.json` and `.vscode/mcp.json`.
- **Claude Code:** this repo ships `.mcp.json`; or run:
  ```bash
  claude mcp add --transport http synter-ads https://mcp.synterai.com
  ```
- **Codex:**
  ```bash
  codex mcp add synter-ads --url https://mcp.synterai.com
  codex mcp login synter-ads
  ```
- **Claude Desktop:** copy `claude_desktop_config.json` into your Claude config directory (macOS: `~/Library/Application Support/Claude/`, Windows: `%APPDATA%\Claude\`) and replace the placeholder API key.

Your client opens Synter sign-in in the browser (OAuth). New here? Create an account at https://synterai.com/sign-up. Headless/CI fallback: send `X-Synter-Key` with a key from https://synterai.com/developer.

The MCP server itself: https://github.com/Synter-Media-AI/mcp-server

---

## Why X Ads + AI?

X is where conversations shape markets. Product launches trend, CEOs build audiences, and brand crises unfold in real time. The platform's real-time nature creates advertising opportunities that don't exist anywhere else — you can promote content about a trending topic within minutes.

In 2025, X eliminated the $5,000/month Pro tier and moved to pay-per-usage pricing (~$0.01/post). This makes X Ads accessible to startups, solo founders, and SMBs for the first time. You can run meaningful campaigns for $100-500/month.

The best X Ads strategy isn't just paid — it's organic + paid together. Build your audience with valuable tweets, identify your best-performing content, then promote the winners. The AI agent can monitor trends, craft tweets, and manage the promotion pipeline.

**Best for:** Real-time marketing, B2B thought leadership, news/media, personal branding, SaaS founders, event promotion, trending topic newsjacking.

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Promote Tweets** | "Promote my best-performing tweet from this week to a tech audience" |
| **Create Ad Campaigns** | "Launch a followers campaign targeting SaaS founders" |
| **Trend Monitoring** | "What's trending in the AI/ML space right now?" |
| **Prospect Discovery** | "Find people tweeting about switching from HubSpot to a new CRM" |
| **Content Publishing** | "Post a thread about our product launch and promote it" |
| **Audience Targeting** | "Target followers of @competitors and @industry_leaders" |
| **Campaign Analytics** | "How are my promoted tweets performing this week?" |
| **Budget Management** | "Set a $10/day budget on the brand awareness campaign" |
| **Website Cards** | "Create a Website Card ad with our landing page" |
| **Engagement Reports** | "Which promoted tweets drove the most link clicks?" |

---

## Example Conversations

### 1. The Organic-to-Paid Flywheel

> **You:** I'm a SaaS founder. I tweet regularly but want to amplify my best content. How?
>
> **Agent:** The best X Ads strategy is the organic-to-paid flywheel:
>
> **Step 1: Identify winners.** Let me analyze your last 30 days of tweets...
>
> Your top 5 tweets by engagement:
> 1. "We hit $1M ARR. Here's exactly what we spent on marketing to get there:" — 847 likes, 234 retweets
> 2. Thread: "7 cold email templates that actually got replies from VPs" — 1,203 likes
> 3. "Hot take: Your landing page doesn't need a video. It needs a better headline" — 432 likes
> 4. "Just shipped: AI-powered analytics. Here's what it found in our data" — 318 likes
> 5. "We're hiring a senior engineer. No leetcode. Here's our interview process:" — 567 likes
>
> **Step 2: Promote winners.** Tweets #1 and #2 have proven organic resonance. Promoting them will reach 10-50x more people at $0.01-0.03 per engagement.
>
> **Step 3: Target the right audience.**
> - Followers of: @paborenstein, @dhaborenstein, @lennyrachitsky, @aaborenstein
> - Interests: SaaS, Startups, Marketing
> - Geo: US, UK, Canada
>
> **Budget:** $25/day for 7 days = $175 total. Expected reach: 150,000-300,000 impressions.
>
> **You:** Promote tweet #1 and #2. $25/day each.
>
> **Agent:** Done. Both tweets now promoted with follower-look-alike targeting. I've set up Website Cards for both linking to your landing page. Remember: promoted ads on X can't contain URLs in the text body — use the Website Card instead.

### 2. Real-Time Trend Newsjacking

> **You:** A major competitor just had a data breach. Should we do anything on X?
>
> **Agent:** This is a delicate opportunity. Here's my recommendation:
>
> **Do NOT:**
> - ❌ Directly attack the competitor (looks predatory)
> - ❌ Mention the breach by name (legal risk)
> - ❌ Use any hashtags related to the breach
>
> **Instead, do this:**
> - ✅ Post a helpful thread about security best practices: "We take data security seriously. Here are the 5 steps every SaaS company should take to protect customer data"
> - ✅ Promote it to followers of the competitor's account
> - ✅ Position your brand as the responsible alternative
>
> The implied comparison is more powerful than a direct attack. People who follow your competitor are seeing breach coverage and your security-focused content in the same feed.
>
> **Timing:** Post within the next 4-6 hours while it's trending, promote for 3 days.
>
> Want me to draft the thread?

### 3. Followers Campaign for Personal Brand

> **You:** I want to grow my X following from 2,000 to 10,000. Can promoted posts help?
>
> **Agent:** Yes, but followers campaigns work differently than engagement campaigns. Here's the strategy:
>
> **Campaign type:** Followers objective
> **Budget:** $15/day ($450/month)
> **Expected cost per follower:** $1.50-3.00
> **Expected growth:** 150-300 new followers/month from paid + organic boost
>
> **Targeting:**
> - Followers of accounts your ideal followers also follow
> - Interests aligned with your content topics
> - Exclude existing followers
>
> **The multiplier effect:** Promoted tweets that gain followers also boost your organic reach. Every new follower sees your future organic tweets, creating a compounding effect.
>
> **Creative tip:** Your promoted tweet should showcase your expertise, not ask for follows. "Here's how I grew our SaaS from $0 to $1M ARR in 18 months (thread)" outperforms "Follow me for SaaS growth tips."
>
> **You:** Start with $15/day. Promote my best thread from last month.
>
> **Agent:** Created. One important note: X Ads have strict content rules for promoted posts:
> - Max 1 emoji total
> - No ✅ (green checkmark emoji is banned)
> - No URLs in tweet text (use Website Card)
> - No hashtags in ad copy
>
> I've verified your thread complies. Campaign is live.

### 4. B2B Event Promotion

> **You:** We're hosting a virtual conference in 3 weeks. How do I promote it on X?
>
> **Agent:** X is the best platform for event promotion — people check X to see what events industry leaders are attending. Here's a phased approach:
>
> **Phase 1: Awareness (3 weeks out) — $200 budget**
> - Promote the announcement tweet with event details + speaker lineup
> - Target: Industry professionals, followers of speaker accounts
> - Include a Website Card linking to registration
>
> **Phase 2: Speaker Spotlights (2 weeks out) — $150 budget**
> - Individual tweets highlighting each speaker with a pull quote
> - Promote to each speaker's follower base
> - Encourage speakers to retweet (free amplification)
>
> **Phase 3: Urgency (1 week out) — $100 budget**
> - "500 spots left — register now" with countdown
> - Retarget people who clicked previous promoted tweets but didn't register
>
> **Phase 4: Live (Day of) — $50 budget**
> - Promote the live-tweet thread in real time
> - Target people who engaged with any previous phase
>
> Total budget: $500. Expected registrations from X: 200-400 (assuming $1.25-2.50 per registration).

### 5. Competitor Audience Targeting

> **You:** Can I target followers of my competitors on X?
>
> **Agent:** Yes — this is one of X's most powerful targeting features. You can target people who follow specific accounts (look-alikes of those followers, actually).
>
> For your CRM product, I'd recommend targeting followers of:
>
> **Direct competitors:**
> - @HubSpot, @Salesforce, @Pipedrive, @monday, @notion
>
> **Industry influencers:**
> - @jaborenstein (SaaS founder), @aaronlevie (Box CEO)
> - Relevant SaaS newsletter authors
>
> **Industry publications:**
> - @SaaStr, @ProductHunt, @TechCrunch
>
> **Pro tip:** Create separate ad groups for competitor followers vs influencer followers. Competitor followers are further along the buyer journey — use direct product messaging. Influencer followers are earlier — use thought leadership content.
>
> | Audience | Messaging |
> |---|---|
> | @HubSpot followers | "Outgrew HubSpot's free tier? Here's a CRM that scales with you" |
> | @SaaStr followers | "We analyzed 500 SaaS companies' sales processes. Here's what the top 10% do differently" |
>
> Want me to set this up?

---

## X Ads Tips from the Pros

1. **Organic first, paid second.** Never promote content that flopped organically. If it didn't resonate with your existing audience, paid amplification just means more people ignore it.
2. **Pay-per-usage is a game changer.** At ~$0.01 per post, you can test many content variations cheaply. Promote 10 tweets at $5 each, find the winner, then scale it.
3. **No URLs in promoted tweet text.** X Ads policy prohibits URLs in ad copy. Use Website Cards instead — they render with a rich preview image and CTA button.
4. **Max 1 emoji, no ✅.** X's quality policy limits promoted posts to 1 emoji maximum. The green checkmark (✅) is specifically banned. No hashtags either.
5. **Website Cards drive 2x more clicks.** Always use the Website Card format instead of a plain tweet + link. The large preview image and CTA button dramatically improve click rates.
6. **Thread promotion works.** Promote the first tweet in a thread — when users click, they see the entire thread. This works well for thought leadership and storytelling.
7. **Target competitor followers.** X is the only major platform where you can target followers of specific accounts. Use this for competitive conquesting.

---

## FAQ

### Is there an MCP for X (Twitter) Ads?
Yes — this repo. It pre-configures the Synter MCP server for X Ads management via OAuth 1.0a. Works with Amp, Cursor, VS Code, and Claude Desktop.

### How much does X Ads cost?
X moved to pay-per-usage pricing in 2025. Promoted posts cost ~$0.01 each. CPC typically ranges from $0.50-2.00 depending on targeting. You can run meaningful campaigns for $100-500/month.

### Can AI write tweets for promotion?
Yes. The agent can draft tweets optimized for X's format (concise, opinionated, value-driven) and ensure they comply with X's promoted content policies (no URLs, max 1 emoji, no hashtags).

### Does X still use OAuth 1.0a?
Yes. X Ads API requires OAuth 1.0a (not OAuth 2.0). The Synter MCP server handles this automatically — you don't need to manage OAuth keys.

### Can I promote threads?
Yes. Promote the first tweet in a thread, and when users click, they see the full thread. This is effective for long-form content like data analyses, how-to guides, and founder stories.

### Is X Ads worth it compared to other platforms?
For B2B thought leadership, real-time marketing, and personal branding, X is unmatched. It's not the platform for ecommerce product ads (use Meta/TikTok), but for building authority and reaching professionals, X delivers.

---

## Related Repos

- [linkedin-ads-agent](https://github.com/Synter-Media-AI/linkedin-ads-agent) — B2B professional targeting
- [reddit-ads-agent](https://github.com/Synter-Media-AI/reddit-ads-agent) — Community-based advertising
- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Search intent capture
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-channel management
- [slack-ads-agent](https://github.com/Synter-Media-AI/slack-ads-agent) — Get X performance alerts in Slack
- [ai-creative-agent](https://github.com/Synter-Media-AI/ai-creative-agent) — Generate ad images & videos

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://synterai.com) · [Get API Key](https://synterai.com/developer) · [Documentation](https://synterai.com/docs)
