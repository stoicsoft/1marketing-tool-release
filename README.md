# 1MarketingTool

### Local-first marketing automation for founders who ship their own product

[![Download for macOS](https://img.shields.io/badge/Download-macOS-000000?style=for-the-badge&logo=apple)](https://github.com/stoicsoft/1marketingtool-releases/releases/latest)
[![Download for Windows](https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows)](https://github.com/stoicsoft/1marketingtool-releases/releases/latest)
[![Website](https://img.shields.io/badge/Website-1marketingtool.com-2563EB?style=for-the-badge)](https://1marketingtool.com)

---

**1MarketingTool** is a desktop marketing engine for indie hackers, solo founders, and small product teams. It brings content generation, SEO research, rank monitoring, AI visibility tracking, design assets, scheduling, and directory submission into one local app.

> **Zero cloud account required.** Your workspace, content library, API keys, and marketing data stay on your machine.

![1MarketingTool Content Machine](https://1marketingtool.com/screenshots/content_machine_overview.jpg)

---

## Why 1MarketingTool?

| Fragmented Marketing Stack | With 1MarketingTool |
|----------------------------|---------------------|
| Write launches, changelogs, and social posts by hand | Generate channel-tailored campaigns from one source |
| Copy content between AI tools, docs, and schedulers | Keep every draft, asset, and publish attempt in a local library |
| Pay for separate SEO, rank, and content tools | Research keywords, build briefs, track rankings, and audit pages in one app |
| Guess whether AI answers mention your brand | Track AI visibility, citations, competitors, and sentiment |
| Manually submit to product directories | Match directories, prepare submissions, and track outcomes |
| Store strategy and credentials in cloud SaaS | Use BYOK credentials stored in the OS keychain |

---

## Key Features

### Content Machine

Drop in a feature, keyword, URL, release note, or product update. 1MarketingTool generates campaign-ready content in your brand voice, across the channels you actually use.

![Content Library](https://1marketingtool.com/screenshots/content_library.jpg)

**Content features:**
- Generate blog posts, changelogs, social posts, threads, Reddit drafts, and video scripts
- Create multi-language campaign sets from one source
- Store every generated item in a local content library
- Edit, approve, archive, schedule, or publish from one review flow
- Use product profile, brand voice, screenshots, supporting files, and optional source-code context

---

### Design Studio

Generate on-brand visuals for launches, feature posts, OG cards, banners, stories, and social campaigns. Outputs render locally into your asset library.

![Design Studio](https://1marketingtool.com/screenshots/design_studio.jpg)

**Design features:**
- Create feature images, social cards, banners, and launch visuals
- Use bundled design systems, local fonts, and product context
- Save generated assets into reusable collections
- Bring your own image-generation provider key

---

### Content Calendar & Distribution

Plan content across channels, customize each target, and publish from the desktop app. Tokens are stored in your OS keychain.

![Content Calendar](https://1marketingtool.com/screenshots/content_calendar.jpg)

**Distribution features:**
- Schedule posts across connected channels
- Publish immediately or let local auto-publish run while the app is open
- Review per-channel overrides before anything goes live
- Audit manual posts and scheduled publish attempts in distribution history
- Connect channels such as WordPress, Ghost, X, LinkedIn, Bluesky, Mastodon, Discord, Slack, Telegram, and custom APIs

---

### Performance, Search & SEO Health

Bring together Google Search Console, GA4, PageSpeed, backlinks, rank tracking, and SEO health for each product you run.

![Performance Analytics](https://1marketingtool.com/screenshots/performance_analytics.jpg)

**Performance features:**
- Unified dashboard for traffic, search, rank, SEO health, links, and page speed
- Google Search Console and GA4 setup flows
- Technical SEO crawler for indexability, metadata, headings, and content health
- Google request indexing workflow and IndexNow submissions
- Activity logs for syncs, API calls, AI runs, and automation

![IndexNow](https://1marketingtool.com/screenshots/indexnow.jpg)

---

### Keyword Explorer & SERP-Grounded Briefs

Research keywords, cluster topics, analyze ranking pages, and turn search intent into briefs that are grounded in the current SERP.

![Keyword Cluster](https://1marketingtool.com/screenshots/keyword_cluster.jpg)

**SEO research features:**
- Keyword planner with volume, difficulty, CPC, intent, and ranked keywords
- Semantic keyword clustering with your local AI CLI
- Saved keywords and topic groups per project
- Content briefs with title, meta, outline, questions, and competitor URLs
- SERP analysis with ranking pages and authority signals

![Content Brief Preview](https://1marketingtool.com/screenshots/content_brief_preview.jpg)

![SERP Analysis](https://1marketingtool.com/screenshots/serp_analysis.jpg)

---

### AI Visibility / AEO / GEO

Track how often your brand appears, ranks, and is cited inside AI-generated answers, then compare your share of voice against competitors.

![AI Visibility Dashboard](https://1marketingtool.com/screenshots/ai_visibility_dashboard.jpg)

**AI visibility features:**
- Track brand presence, citation count, rank, and sentiment across AI answer surfaces
- Monitor prompts that matter to your product category
- Compare your brand against competitors
- Save trackers and rerun them over time
- Use Prompt Explorer to run one prompt across installed AI CLI agents side by side

![AI Visibility Keywords](https://1marketingtool.com/screenshots/ai_visibility_keywords_table.jpg)

---

### Directory Submit

Turn a product profile into directory submissions without keeping a manual spreadsheet.

![Directory Submit](https://1marketingtool.com/screenshots/directory_submit.jpg)

**Directory features:**
- Curated directory database for launch, startup, SaaS, and dev-tool listings
- AI-assisted matching against your product profile
- Submission status tracking per directory
- Human review gates before submissions go out
- Fallback export for directories that require manual completion

---

## Local-First Architecture

1MarketingTool is built as a native desktop app with Electron, React, TypeScript, SQLite, and OS keychain storage.

**Privacy model:**
- App data is stored locally in SQLite
- API keys and OAuth tokens are stored in macOS Keychain or Windows Credential Manager
- There is no required 1MarketingTool cloud account
- Outbound requests go to the APIs you explicitly configure
- Backups and exports stay under your control

**AI model:**
- Bring your own OpenAI, Claude, Gemini, or other provider keys
- Use local AI CLI agents such as Claude Code, Codex, Gemini CLI, OpenCode, Amp, Qwen, or Aider where supported
- Use bundled MCP servers for rank, browser, and content workflows

---

## Supported Platforms

| Platform | Architecture | Release Asset |
|----------|--------------|---------------|
| macOS | Apple Silicon (arm64) | `.dmg`, `.zip` |
| macOS | Intel (x64) | `.dmg`, `.zip` |
| Windows | x64 | `.exe` installer |
| Linux | Roadmap | Not packaged yet |

---

## System Requirements

- **macOS**: Apple Silicon or Intel Mac
- **Windows**: Windows 10 or Windows 11, x64
- **Network**: Required only for configured APIs and publishing targets
- **API keys**: Optional, depending on which providers and workflows you enable

Packaged desktop builds do not require Node.js or a local development environment.

---

## Getting Started

1. **Download** the latest build for macOS or Windows from [GitHub Releases](https://github.com/stoicsoft/1marketingtool-releases/releases/latest).
2. **Create a workspace** and add your product name, URL, tagline, audience, and brand voice.
3. **Choose an AI engine** with BYOK provider credentials or a supported local AI CLI.
4. **Connect data sources** such as Google Search Console, GA4, DataForSEO, PageSpeed, or Ahrefs where needed.
5. **Generate your first campaign** from a keyword, feature update, URL, or release note.
6. **Review and schedule** the generated content, visuals, and channel-specific posts.

---

## Release Assets

Electron Builder currently produces these artifact names from the desktop app source:

| Asset | Purpose |
|-------|---------|
| `1MarketingTool-<version>-mac-arm64.dmg` | macOS Apple Silicon installer |
| `1MarketingTool-<version>-mac-x64.dmg` | macOS Intel installer |
| `1MarketingTool-<version>-mac-arm64.zip` | macOS Apple Silicon auto-update artifact |
| `1MarketingTool-<version>-mac-x64.zip` | macOS Intel auto-update artifact |
| `1MarketingTool-<version>-windows-setup.exe` | Windows x64 installer |

When auto-updates are enabled in the desktop source, attach the generated update metadata files to the same GitHub Release.

---

## What's New

See [CHANGELOG.md](https://github.com/stoicsoft/1marketingtool-releases/blob/main/CHANGELOG.md) for release notes.

---

## FAQ

<details>
<summary><strong>Is my data stored in the cloud?</strong></summary>

No. 1MarketingTool stores its workspace data locally on your machine. Credentials are stored in the OS keychain. The app only talks to APIs you configure.
</details>

<details>
<summary><strong>What does BYOK mean?</strong></summary>

BYOK means Bring Your Own Key. You provide provider credentials for services such as OpenAI, Claude, Gemini, DataForSEO, Google Search Console, GA4, PageSpeed, Ahrefs, and publishing channels. You pay those providers directly, with no API markup from 1MarketingTool.
</details>

<details>
<summary><strong>Do I need to connect a GitHub repo?</strong></summary>

No. Source-code context is optional. It makes feature-driven content more specific, but you can generate campaigns from product profiles, keywords, URLs, release notes, and manual descriptions.
</details>

<details>
<summary><strong>Can 1MarketingTool publish automatically?</strong></summary>

Yes, for configured channels with working credentials. Scheduled posts publish on local sweeps while the app is open and the machine is awake. You can also publish manually after review.
</details>

<details>
<summary><strong>Does it replace Ahrefs, Semrush, Surfer, Buffer, and AI writing tools?</strong></summary>

It is designed to consolidate the solo-founder workflow those tools often cover: content generation, keyword research, SERP briefs, rank visibility, scheduling, and publishing. Some workflows still depend on external data providers you configure with your own keys.
</details>

<details>
<summary><strong>Is Linux supported?</strong></summary>

Linux is on the roadmap. The current release target is macOS and Windows.
</details>

---

## Links

- **Website**: [1marketingtool.com](https://1marketingtool.com)
- **Documentation**: [1marketingtool.com/docs](https://1marketingtool.com/docs)
- **Releases**: [GitHub Releases](https://github.com/stoicsoft/1marketingtool-releases/releases)
- **Changelog**: [CHANGELOG.md](https://github.com/stoicsoft/1marketingtool-releases/blob/main/CHANGELOG.md)
- **Support**: [GitHub Issues](https://github.com/stoicsoft/1marketingtool-releases/issues)
- **Contact**: [hello@stoicsoft.com](mailto:hello@stoicsoft.com)

---

## Keywords

marketing automation, local-first marketing app, desktop marketing software, AI content generation, indie hacker marketing, solo founder marketing, content machine, content calendar, social scheduling, AI design studio, keyword research, keyword clustering, SEO content briefs, SERP analysis, rank tracking, AI visibility tracking, answer engine optimization, generative engine optimization, AEO, GEO, Google Search Console, GA4, PageSpeed, DataForSEO, IndexNow, directory submission, product launch directories, BYOK, local AI CLI, Electron app, macOS marketing app, Windows marketing app, StoicSoft

---

<p align="center">
  <strong>Your entire marketing engine. Running on your machine.</strong><br>
  <a href="https://1marketingtool.com">1marketingtool.com</a>
</p>
