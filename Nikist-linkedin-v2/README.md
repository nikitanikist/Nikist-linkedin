# Nikist LinkedIn — Claude Code Plugin Marketplace

A Claude Code plugin marketplace by **Amit (Nikist)** that installs the **LinkedIn Growth Engine** — an AI-powered LinkedIn growth system trained on 23+ hours of insider strategies from a premium LinkedIn mastery course.

## Installation

In Claude Code, run:

```
/plugin marketplace add nikitanikist/Nikist-linkedin
/plugin install linkedin-growth-engine@nikist-linkedin
```

That's it — the plugin's six skills are now available to Claude.

## What's Inside

**linkedin-growth-engine** — a single plugin containing six composable skills:

| Skill | What It Does | Trigger Phrases |
|-------|-------------|-----------------|
| **ICP Builder** | Creates ideal customer profiles through guided discovery | "build my ICP", "who should I target", "define my audience" |
| **Profile Optimizer** | Audits and optimizes LinkedIn profiles for lead generation | "optimize my profile", "LinkedIn profile audit", "fix my headline" |
| **Content Engine** | Creates posts, lead magnets, and content calendars | "write a LinkedIn post", "content calendar", "create a lead magnet" |
| **Outreach Machine** | Executes DMs, connection requests, and follow-up sequences | "send LinkedIn messages", "outreach campaign", "DM strategy" |
| **Engagement Bot** | Runs the 10-Creator engagement system and commenting strategy | "engage on LinkedIn", "commenting strategy", "daily engagement" |
| **Strategy Planner** | Creates 30/60/90-day growth plans with metrics tracking | "LinkedIn growth plan", "what should I do this week", "LinkedIn GTM" |

## How It Works

1. **Start with ICP Builder** → Define who you're targeting
2. **Run Profile Optimizer** → Make your profile convert visitors to leads
3. **Launch Content Engine** → Create content that attracts your ICP
4. **Activate Engagement Bot** → Build visibility in your niche
5. **Deploy Outreach Machine** → Send personalized messages at scale
6. **Use Strategy Planner** → Track metrics and scale systematically

## Chrome Automation

The plugin uses Claude in Chrome to execute LinkedIn actions directly — navigating profiles, sending connection requests, posting content, and logging activity.

## Updating

To pull the latest version:

```
/plugin marketplace update nikist-linkedin
```

## Repo Structure

```
Nikist-linkedin/
├── .claude-plugin/
│   └── marketplace.json        ← marketplace definition
└── linkedin-growth-engine/     ← the plugin
    ├── .claude-plugin/
    │   └── plugin.json
    ├── README.md
    └── skills/
        ├── content-engine/
        ├── engagement-bot/
        ├── icp-builder/
        ├── outreach-machine/
        ├── profile-optimizer/
        └── strategy-planner/
```

## License

Built by Amit (Nikist). Contact: nikistofficial@gmail.com
