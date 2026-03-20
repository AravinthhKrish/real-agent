# real-agent

A multi-layer agent system built with Claude, organized into specialized roles across every function of a modern software studio.

## Overview

This repository defines a library of Claude agent roles under `.claude/agents/`. Each agent is a focused specialist with a clear purpose, responsibilities, and output format — designed to be composed into multi-agent workflows.

## Agent Directory

### Engineering
| Agent | Description |
|---|---|
| `frontend-developer` | Builds responsive, accessible UI components with React/Next.js and TypeScript |
| `backend-architect` | Designs scalable APIs, database schemas, and server-side systems |
| `mobile-app-builder` | Develops iOS and Android apps using React Native or Flutter |
| `ai-engineer` | Implements LLM-powered features, RAG pipelines, and AI integrations |
| `devops-automator` | Builds CI/CD pipelines, infrastructure as code, and operational automation |
| `rapid-prototyper` | Ships working prototypes fast to validate ideas before full investment |

### Product
| Agent | Description |
|---|---|
| `trend-researcher` | Identifies emerging market opportunities and competitive signals |
| `feedback-synthesizer` | Transforms raw user feedback into prioritized product insights |
| `sprint-prioritizer` | Applies RICE/ICE/MoSCoW frameworks to prioritize and size the backlog |

### Marketing
| Agent | Description |
|---|---|
| `tiktok-strategist` | Grows audiences through viral, platform-native TikTok content |
| `instagram-curator` | Builds an engaged Instagram presence with Reels, carousels, and Stories |
| `twitter-engager` | Drives community growth through threads, replies, and conversations |
| `reddit-community-builder` | Builds authentic Reddit presence across relevant subreddits |
| `app-store-optimizer` | Maximizes organic app discoverability through ASO on iOS and Android |
| `content-creator` | Produces blog posts, email sequences, scripts, and ad copy |
| `growth-hacker` | Runs rapid experiments to find scalable acquisition and retention levers |

### Design
| Agent | Description |
|---|---|
| `ui-designer` | Creates pixel-perfect, consistent interfaces and design system components |
| `ux-researcher` | Uncovers user needs through interviews, usability tests, and data analysis |
| `brand-guardian` | Protects and evolves brand identity across visual and verbal touchpoints |
| `visual-storyteller` | Communicates complex ideas through illustration, infographics, and motion |
| `whimsy-injector` | Injects delight, personality, and surprise moments into the product experience |

### Project Management
| Agent | Description |
|---|---|
| `experiment-tracker` | Manages the experiment program and ensures learnings are captured |
| `project-shipper` | Keeps projects on track and ships features on time with high quality |
| `studio-producer` | Orchestrates people, resources, and creative processes across the studio |

### Studio Operations
| Agent | Description |
|---|---|
| `support-responder` | Resolves user issues quickly and empathetically across all support channels |
| `analytics-reporter` | Transforms metrics into actionable insights and performance reports |
| `infrastructure-maintainer` | Keeps production systems reliable, secure, and cost-efficient |
| `legal-compliance-checker` | Ensures the studio operates within applicable laws and platform policies |
| `finance-tracker` | Tracks revenue, expenses, and key financial health metrics |

### Testing
| Agent | Description |
|---|---|
| `tool-evaluator` | Rigorously assesses new tools and frameworks before adoption |
| `api-tester` | Ensures all API endpoints are correct, secure, and resilient under load |
| `workflow-optimizer` | Identifies friction in team workflows and redesigns them for efficiency |
| `performance-benchmarker` | Measures and improves app performance across frontend, backend, and mobile |
| `test-results-analyzer` | Interprets test results, triages failures, and reports release quality |

## Structure

```
.claude/
└── agents/
    ├── engineering/
    │   ├── frontend-developer.md
    │   ├── backend-architect.md
    │   ├── mobile-app-builder.md
    │   ├── ai-engineer.md
    │   ├── devops-automator.md
    │   └── rapid-prototyper.md
    ├── product/
    │   ├── trend-researcher.md
    │   ├── feedback-synthesizer.md
    │   └── sprint-prioritizer.md
    ├── marketing/
    │   ├── tiktok-strategist.md
    │   ├── instagram-curator.md
    │   ├── twitter-engager.md
    │   ├── reddit-community-builder.md
    │   ├── app-store-optimizer.md
    │   ├── content-creator.md
    │   └── growth-hacker.md
    ├── design/
    │   ├── ui-designer.md
    │   ├── ux-researcher.md
    │   ├── brand-guardian.md
    │   ├── visual-storyteller.md
    │   └── whimsy-injector.md
    ├── project-management/
    │   ├── experiment-tracker.md
    │   ├── project-shipper.md
    │   └── studio-producer.md
    ├── studio-operations/
    │   ├── support-responder.md
    │   ├── analytics-reporter.md
    │   ├── infrastructure-maintainer.md
    │   ├── legal-compliance-checker.md
    │   └── finance-tracker.md
    └── testing/
        ├── tool-evaluator.md
        ├── api-tester.md
        ├── workflow-optimizer.md
        ├── performance-benchmarker.md
        └── test-results-analyzer.md
```

## Agent File Format

Each agent file defines:
- **Role** — What the agent is and its core focus
- **Responsibilities** — What it owns and does
- **Expertise** — Tools, frameworks, and domain knowledge
- **Principles** — How it approaches its work
- **Output Format** — What it produces and how it structures results
