# OPENCLAW SKILL SAFE LIST

### Community-audited list of safe OpenClaw skills

> **Audit Date:** 2026-02-06 | **Skills Scanned:** 4,000+ | **AI Models Used:** 3 | **Tokens Spent:** ~1 Million | **Safe Skills Listed:** 395

---

![Safe Skills](https://img.shields.io/badge/Safe_Skills-395-brightgreen)
![SAFE Verified](https://img.shields.io/badge/SAFE-241-green)
![LOW Risk](https://img.shields.io/badge/LOW_Risk-154-yellow)
![Skills Scanned](https://img.shields.io/badge/Skills_Scanned-4000+-blue)
![AI Models](https://img.shields.io/badge/AI_Models-3-purple)
![Tokens Spent](https://img.shields.io/badge/Tokens_Spent-~1M-orange)

---

## Methodology

Over **4,000 skills** were scanned in-depth across the [OpenClaw skills registry](https://github.com/openclaw/skills) using **3 different AI models** to cross-verify results and eliminate blind spots. Approximately **1 million tokens** were spent on this audit to ensure thoroughness.

### AI Models Used

| AI Model | Role |
|----------|------|
| **Claude** (Opus 4.6) | Primary deep analysis -- OSTRTA automated scan + manual source code review across 3 phases |
| **Gemini** | Cross-verification audit -- independent analysis to catch threats Claude may have missed |
| **Kimi** | Cross-verification audit -- independent analysis providing a third perspective on flagged skills |

### Audit Process

| Phase | Description | Details |
|-------|-------------|---------|
| **Phase 1** | OSTRTA automated scan | All skills scanned for malware signatures, obfuscated code, suspicious network calls, and credential exfiltration patterns |
| **Phase 2** | Deep re-audit of HIGH + MEDIUM | All skills flagged HIGH or MEDIUM were manually reviewed by Opus 4.6 with full source analysis |
| **Phase 3** | Deep re-audit of LOW | All 154 LOW-flagged skills were manually reviewed by Opus 4.6 to confirm they are safe for use |
| **Cross-verification** | Multi-AI validation | Results cross-checked across Claude, Gemini, and Kimi to reduce false negatives |

---

## How to Use This List

1. **Before installing any OpenClaw skill**, search this list to verify it has been audited
2. Skills marked **SAFE** passed all automated and manual checks with no concerns
3. Skills marked with an asterisk (**\***) are **LOW risk** -- they had minor flags during scanning (e.g., broad file access patterns, external API calls) but were confirmed safe on manual review
4. If a skill is **not on this list**, it may not yet be audited or was excluded -- exercise caution
5. Always keep your OpenClaw installation updated to benefit from upstream security fixes

---

## Safe Skills by Category

All 395 audited-safe skills organized by function. Click a category to expand.

<!-- ============================================================ -->
<!-- SEARCH & WEB -->
<!-- ============================================================ -->
<details>
<summary><strong>Search & Web</strong> (30 skills)</summary>

| Skill | Status |
|-------|--------|
| [bbc-news](https://github.com/openclaw/skills/tree/main/skills/ddrayne/bbc-news/SKILL.md) | SAFE |
| [blogwatcher](https://github.com/openclaw/skills/tree/main/skills/steipete/blogwatcher/SKILL.md) * | LOW |
| [brave-images](https://github.com/openclaw/skills/tree/main/skills/zats/brave-images/SKILL.md) * | LOW |
| [brave-search](https://github.com/openclaw/skills/tree/main/skills/steipete/brave-search/SKILL.md) * | LOW |
| [byterover](https://github.com/openclaw/skills/tree/main/skills/byteroverinc/byterover/SKILL.md) * | LOW |
| [clawdgle](https://github.com/openclaw/skills/tree/main/skills/rubybrewsday/clawdgle/SKILL.md) * | LOW |
| [ddg-search](https://github.com/openclaw/skills/tree/main/skills/paradoxfuzzle/ddg-search/SKILL.md) | SAFE |
| [deepread](https://github.com/openclaw/skills/tree/main/skills/uday390/deepread/SKILL.md) * | LOW |
| [deepread-ocr](https://github.com/openclaw/skills/tree/main/skills/uday390/deepread-ocr/SKILL.md) * | LOW |
| [exa](https://github.com/openclaw/skills/tree/main/skills/fardeenxyz/exa/SKILL.md) | SAFE |
| [get-tldr](https://github.com/openclaw/skills/tree/main/skills/itobey/get-tldr/SKILL.md) * | LOW |
| [hn](https://github.com/openclaw/skills/tree/main/skills/dbhurley/hn/SKILL.md) | SAFE |
| [hn-digest](https://github.com/openclaw/skills/tree/main/skills/cpojer/hn-digest/SKILL.md) | SAFE |
| [jina-reader](https://github.com/openclaw/skills/tree/main/skills/ericsantos/jina-reader/SKILL.md) | SAFE |
| [kagi-search](https://github.com/openclaw/skills/tree/main/skills/silversteez/kagi-search/SKILL.md) * | LOW |
| [local-websearch](https://github.com/openclaw/skills/tree/main/skills/stperic/local-websearch/SKILL.md) | SAFE |
| [naver-news](https://github.com/openclaw/skills/tree/main/skills/steamb23/naver-news/SKILL.md) * | LOW |
| [news-aggregator-skill](https://github.com/openclaw/skills/tree/main/skills/cclank/news-aggregator-skill/SKILL.md) * | LOW |
| [news-summary](https://github.com/openclaw/skills/tree/main/skills/joargp/news-summary/SKILL.md) | SAFE |
| [omnisearch](https://github.com/openclaw/skills/tree/main/skills/bguidolim/omnisearch/SKILL.md) * | LOW |
| [openclaw-feeds](https://github.com/openclaw/skills/tree/main/skills/nesdeq/openclaw-feeds/SKILL.md) * | LOW |
| [openclaw-serper](https://github.com/openclaw/skills/tree/main/skills/nesdeq/openclaw-serper/SKILL.md) * | LOW |
| [perplexity](https://github.com/openclaw/skills/tree/main/skills/zats/perplexity/SKILL.md) * | LOW |
| [perplexity-bash](https://github.com/openclaw/skills/tree/main/skills/dronnick/perplexity-bash/SKILL.md) * | LOW |
| [reddit-search](https://github.com/openclaw/skills/tree/main/skills/thesethrose/reddit-search/SKILL.md) | SAFE |
| [searxng](https://github.com/openclaw/skills/tree/main/skills/abk234/searxng/SKILL.md) * | LOW |
| [serpapi](https://github.com/openclaw/skills/tree/main/skills/ianpcook/serpapi/SKILL.md) | SAFE |
| [serper-search](https://github.com/openclaw/skills/tree/main/skills/samoppakiks/serper-search/SKILL.md) * | LOW |
| [super-websearch-realtime](https://github.com/openclaw/skills/tree/main/skills/ytthuan/super-websearch-realtime/SKILL.md) | SAFE |
| [tavily-search](https://github.com/openclaw/skills/tree/main/skills/arun-8687/tavily-search/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- YOUTUBE & VIDEO -->
<!-- ============================================================ -->
<details>
<summary><strong>YouTube & Video</strong> (18 skills)</summary>

| Skill | Status |
|-------|--------|
| [audiopod](https://github.com/openclaw/skills/tree/main/skills/rakesh1002/audiopod/SKILL.md) * | LOW |
| [creatordb-youtube-v3](https://github.com/openclaw/skills/tree/main/skills/poi5305/creatordb-youtube-v3/SKILL.md) * | LOW |
| [gemini-yt-video-transcript](https://github.com/openclaw/skills/tree/main/skills/odrobnik/gemini-yt-video-transcript/SKILL.md) * | LOW |
| [transcribee](https://github.com/openclaw/skills/tree/main/skills/itsfabioroma/transcribee/SKILL.md) | SAFE |
| [transcript](https://github.com/openclaw/skills/tree/main/skills/therohitdas/transcript/SKILL.md) | SAFE |
| [transcriptapi](https://github.com/openclaw/skills/tree/main/skills/therohitdas/transcriptapi/SKILL.md) | SAFE |
| [video-transcript-downloader](https://github.com/openclaw/skills/tree/main/skills/steipete/video-transcript-downloader/SKILL.md) | SAFE |
| [voice-note-to-midi](https://github.com/openclaw/skills/tree/main/skills/danbennettuk/voice-note-to-midi/SKILL.md) | SAFE |
| [youtube-analytics](https://github.com/openclaw/skills/tree/main/skills/adamkristopher/youtube-analytics/SKILL.md) * | LOW |
| [youtube-channels](https://github.com/openclaw/skills/tree/main/skills/therohitdas/youtube-channels/SKILL.md) | SAFE |
| [youtube-data](https://github.com/openclaw/skills/tree/main/skills/therohitdas/youtube-data/SKILL.md) | SAFE |
| [youtube-data-api](https://github.com/openclaw/skills/tree/main/skills/globalcaos/youtube-data-api/SKILL.md) * | LOW |
| [youtube-full](https://github.com/openclaw/skills/tree/main/skills/therohitdas/youtube-full/SKILL.md) | SAFE |
| [youtube-playlist](https://github.com/openclaw/skills/tree/main/skills/therohitdas/youtube-playlist/SKILL.md) | SAFE |
| [youtube-search](https://github.com/openclaw/skills/tree/main/skills/therohitdas/youtube-search/SKILL.md) | SAFE |
| [youtube-title-generator](https://github.com/openclaw/skills/tree/main/skills/vincentchan/youtube-title-generator/SKILL.md) | SAFE |
| [youtube-transcript](https://github.com/openclaw/skills/tree/main/skills/xthezealot/youtube-transcript/SKILL.md) * | LOW |
| [yt](https://github.com/openclaw/skills/tree/main/skills/therohitdas/yt/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- SOCIAL MEDIA -->
<!-- ============================================================ -->
<details>
<summary><strong>Social Media</strong> (16 skills)</summary>

| Skill | Status |
|-------|--------|
| [facebook](https://github.com/openclaw/skills/tree/main/skills/codedao12/facebook/SKILL.md) | SAFE |
| [mastodon-scout](https://github.com/openclaw/skills/tree/main/skills/patelhiren/mastodon-scout/SKILL.md) * | LOW |
| [multiposting](https://github.com/openclaw/skills/tree/main/skills/jordanprater/multiposting/SKILL.md) | SAFE |
| [pinterest](https://github.com/openclaw/skills/tree/main/skills/cyberfront-ai/pinterest/SKILL.md) * | LOW |
| [social-media-analyzer](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/social-media-analyzer/SKILL.md) | SAFE |
| [social-media-detox](https://github.com/openclaw/skills/tree/main/skills/jhillin8/social-media-detox/SKILL.md) | SAFE |
| [social-media-management](https://github.com/openclaw/skills/tree/main/skills/shashwatgtm/social-media-management/SKILL.md) | SAFE |
| [tweet-ideas-generator](https://github.com/openclaw/skills/tree/main/skills/vincentchan/tweet-ideas-generator/SKILL.md) * | LOW |
| [tweet-writer](https://github.com/openclaw/skills/tree/main/skills/sanky369/tweet-writer/SKILL.md) | SAFE |
| [tweeter](https://github.com/openclaw/skills/tree/main/skills/trymoinai-create/tweeter/SKILL.md) | SAFE |
| [x](https://github.com/openclaw/skills/tree/main/skills/trymoinai-create/x/SKILL.md) * | LOW |
| [x-algorithm](https://github.com/openclaw/skills/tree/main/skills/nextfrontierbuilds/x-algorithm/SKILL.md) | SAFE |
| [x-article-editor](https://github.com/openclaw/skills/tree/main/skills/jchopard69/x-article-editor/SKILL.md) | SAFE |
| [x-bookmark-archiver](https://github.com/openclaw/skills/tree/main/skills/iamadig/x-bookmark-archiver/SKILL.md) * | LOW |
| [ytmusic](https://github.com/openclaw/skills/tree/main/skills/gentrycopsy/ytmusic/SKILL.md) * | LOW |
| [sports-ticker](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/sports-ticker/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- EMAIL & COMMUNICATION -->
<!-- ============================================================ -->
<details>
<summary><strong>Email & Communication</strong> (10 skills)</summary>

| Skill | Status |
|-------|--------|
| [apple-mail](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-mail/SKILL.md) * | LOW |
| [brevo](https://github.com/openclaw/skills/tree/main/skills/yujesyoga/brevo/SKILL.md) | SAFE |
| [clawmail](https://github.com/openclaw/skills/tree/main/skills/heyarviind/clawmail/SKILL.md) * | LOW |
| [email-prompt-injection-defense](https://github.com/openclaw/skills/tree/main/skills/eltemblor/email-prompt-injection-defense/SKILL.md) | SAFE |
| [purelymail](https://github.com/openclaw/skills/tree/main/skills/dbhurley/purelymail/SKILL.md) * | LOW |
| [reply](https://github.com/openclaw/skills/tree/main/skills/trymoinai-create/reply/SKILL.md) | SAFE |
| [resend](https://github.com/openclaw/skills/tree/main/skills/mjrussell/resend/SKILL.md) * | LOW |
| [teams-anthropic-integration](https://github.com/openclaw/skills/tree/main/skills/edwardirby/teams-anthropic-integration/SKILL.md) | SAFE |
| [zoom-manager-clawd](https://github.com/openclaw/skills/tree/main/skills/vnagin/zoom-manager-clawd/SKILL.md) * | LOW |
| [newsletter-digest](https://github.com/openclaw/skills/tree/main/skills/jhillin8/newsletter-digest/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- NOTES & KNOWLEDGE -->
<!-- ============================================================ -->
<details>
<summary><strong>Notes & Knowledge</strong> (27 skills)</summary>

| Skill | Status |
|-------|--------|
| [apple-notes](https://github.com/openclaw/skills/tree/main/skills/steipete/apple-notes/SKILL.md) * | LOW |
| [bear-notes](https://github.com/openclaw/skills/tree/main/skills/steipete/bear-notes/SKILL.md) * | LOW |
| [better-notion](https://github.com/openclaw/skills/tree/main/skills/tyler6204/better-notion/SKILL.md) * | LOW |
| [gkeep](https://github.com/openclaw/skills/tree/main/skills/vacinc/gkeep/SKILL.md) * | LOW |
| [instapaper](https://github.com/openclaw/skills/tree/main/skills/vburojevic/instapaper/SKILL.md) * | LOW |
| [karakeep](https://github.com/openclaw/skills/tree/main/skills/jayphen/karakeep/SKILL.md) | SAFE |
| [linkding](https://github.com/openclaw/skills/tree/main/skills/jmagar/linkding/SKILL.md) | SAFE |
| [logseq](https://github.com/openclaw/skills/tree/main/skills/juanirm/logseq/SKILL.md) | SAFE |
| [nb](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/nb/SKILL.md) | SAFE |
| [netpad](https://github.com/openclaw/skills/tree/main/skills/mrlynn/netpad/SKILL.md) * | LOW |
| [notebooklm-skill](https://github.com/openclaw/skills/tree/main/skills/guccidgi/notebooklm-skill/SKILL.md) * | LOW |
| [notebook](https://github.com/openclaw/skills/tree/main/skills/thesethrose/notebook/SKILL.md) | SAFE |
| [notectl](https://github.com/openclaw/skills/tree/main/skills/rainbat/notectl/SKILL.md) | SAFE |
| [notion](https://github.com/openclaw/skills/tree/main/skills/steipete/notion/SKILL.md) | SAFE |
| [notion-api](https://github.com/openclaw/skills/tree/main/skills/timenotspace/notion-api/SKILL.md) | SAFE |
| [obsidian](https://github.com/openclaw/skills/tree/main/skills/steipete/obsidian/SKILL.md) | SAFE |
| [obsidian-conversation-backup](https://github.com/openclaw/skills/tree/main/skills/laserducktales/obsidian-conversation-backup/SKILL.md) | SAFE |
| [obsidian-daily](https://github.com/openclaw/skills/tree/main/skills/bastos/obsidian-daily/SKILL.md) | SAFE |
| [para-second-brain](https://github.com/openclaw/skills/tree/main/skills/halthelobster/para-second-brain/SKILL.md) | SAFE |
| [raindrop](https://github.com/openclaw/skills/tree/main/skills/velvet-shark/raindrop/SKILL.md) * | LOW |
| [readeck](https://github.com/openclaw/skills/tree/main/skills/jayphen/readeck/SKILL.md) | SAFE |
| [readwise](https://github.com/openclaw/skills/tree/main/skills/refrigerator/readwise/SKILL.md) * | LOW |
| [second-brain](https://github.com/openclaw/skills/tree/main/skills/christinetyip/second-brain/SKILL.md) * | LOW |
| [silverbullet-skill](https://github.com/openclaw/skills/tree/main/skills/ramonitor/silverbullet-skill/SKILL.md) | SAFE |
| [craft](https://github.com/openclaw/skills/tree/main/skills/noah-ribaudo/craft/SKILL.md) | SAFE |
| [craft-do](https://github.com/openclaw/skills/tree/main/skills/atomtanstudio/craft-do/SKILL.md) * | LOW |
| [miniflux](https://github.com/openclaw/skills/tree/main/skills/shekohex/miniflux/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- MEMORY & CONTEXT -->
<!-- ============================================================ -->
<details>
<summary><strong>Memory & Context</strong> (19 skills)</summary>

| Skill | Status |
|-------|--------|
| [basal-ganglia-memory](https://github.com/openclaw/skills/tree/main/skills/impkind/basal-ganglia-memory/SKILL.md) | SAFE |
| [bulletproof-memory](https://github.com/openclaw/skills/tree/main/skills/halthelobster/bulletproof-memory/SKILL.md) | SAFE |
| [context](https://github.com/openclaw/skills/tree/main/skills/barneyjm/context/SKILL.md) | SAFE |
| [context-anchor](https://github.com/openclaw/skills/tree/main/skills/boscoeuk/context-anchor/SKILL.md) | SAFE |
| [context-checkpoint](https://github.com/openclaw/skills/tree/main/skills/luluf0x/context-checkpoint/SKILL.md) | SAFE |
| [context-manager](https://github.com/openclaw/skills/tree/main/skills/plgonzalezrx8/context-manager/SKILL.md) * | LOW |
| [context-optimizer](https://github.com/openclaw/skills/tree/main/skills/ad2546/context-optimizer/SKILL.md) | SAFE |
| [lancedb-memory](https://github.com/openclaw/skills/tree/main/skills/pntrivedy/lancedb-memory/SKILL.md) | SAFE |
| [memory-curator](https://github.com/openclaw/skills/tree/main/skills/themiloway/memory-curator/SKILL.md) * | LOW |
| [memory-lite](https://github.com/openclaw/skills/tree/main/skills/vellis59/memory-lite/SKILL.md) * | LOW |
| [memory-manager](https://github.com/openclaw/skills/tree/main/skills/marmikcfc/memory-manager/SKILL.md) * | LOW |
| [memory-pipeline](https://github.com/openclaw/skills/tree/main/skills/joe-rlo/memory-pipeline/SKILL.md) * | LOW |
| [memory-system-v2](https://github.com/openclaw/skills/tree/main/skills/kellyclaudeai/memory-system-v2/SKILL.md) | SAFE |
| [penfield](https://github.com/openclaw/skills/tree/main/skills/dial481/penfield/SKILL.md) * | LOW |
| [people-memories](https://github.com/openclaw/skills/tree/main/skills/charbeld/people-memories/SKILL.md) * | LOW |
| [shared-memory](https://github.com/openclaw/skills/tree/main/skills/christinetyip/shared-memory/SKILL.md) * | LOW |
| [vestige](https://github.com/openclaw/skills/tree/main/skills/belkouche/vestige/SKILL.md) * | LOW |
| [local-rag-search](https://github.com/openclaw/skills/tree/main/skills/nkapila6/local-rag-search/SKILL.md) | SAFE |
| [semantic-walk](https://github.com/openclaw/skills/tree/main/skills/liet-codes/semantic-walk/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- TASK MANAGEMENT -->
<!-- ============================================================ -->
<details>
<summary><strong>Task Management</strong> (20 skills)</summary>

| Skill | Status |
|-------|--------|
| [4todo](https://github.com/openclaw/skills/tree/main/skills/blackstorm/4todo/SKILL.md) | SAFE |
| [gsd](https://github.com/openclaw/skills/tree/main/skills/glittercowboy/gsd/SKILL.md) | SAFE |
| [kanbanflow-skill](https://github.com/openclaw/skills/tree/main/skills/abakermi/kanbanflow-skill/SKILL.md) | SAFE |
| [no-nonsense-tasks](https://github.com/openclaw/skills/tree/main/skills/dvjn/no-nonsense-tasks/SKILL.md) | SAFE |
| [planka](https://github.com/openclaw/skills/tree/main/skills/voydz/planka/SKILL.md) * | LOW |
| [project-management-guru-adhd](https://github.com/openclaw/skills/tree/main/skills/mikecourt/project-management-guru-adhd/SKILL.md) | SAFE |
| [project-manager](https://github.com/openclaw/skills/tree/main/skills/fr0ziii/project-manager/SKILL.md) * | LOW |
| [task-tracker](https://github.com/openclaw/skills/tree/main/skills/kesslerio/task-tracker/SKILL.md) | SAFE |
| [taskleef](https://github.com/openclaw/skills/tree/main/skills/xatter/taskleef/SKILL.md) * | LOW |
| [taskmaster](https://github.com/openclaw/skills/tree/main/skills/jlwrow/taskmaster/SKILL.md) | SAFE |
| [taskr](https://github.com/openclaw/skills/tree/main/skills/echo-of-machines/taskr/SKILL.md) * | LOW |
| [todo-tracker](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/todo-tracker/SKILL.md) | SAFE |
| [todoist](https://github.com/openclaw/skills/tree/main/skills/mjrussell/todoist/SKILL.md) * | LOW |
| [todozi](https://github.com/openclaw/skills/tree/main/skills/bgengs/todozi/SKILL.md) * | LOW |
| [topydo](https://github.com/openclaw/skills/tree/main/skills/bastos/topydo/SKILL.md) | SAFE |
| [trello](https://github.com/openclaw/skills/tree/main/skills/steipete/trello/SKILL.md) | SAFE |
| [vikunja](https://github.com/openclaw/skills/tree/main/skills/dbhurley/vikunja/SKILL.md) | SAFE |
| [vikunja-fast](https://github.com/openclaw/skills/tree/main/skills/tmigone/vikunja-fast/SKILL.md) | SAFE |
| [youtrack-digisal](https://github.com/openclaw/skills/tree/main/skills/digisal/youtrack-digisal/SKILL.md) * | LOW |
| [executing-plans](https://github.com/openclaw/skills/tree/main/skills/chenleiyanquan/executing-plans/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- CALENDAR & SCHEDULING -->
<!-- ============================================================ -->
<details>
<summary><strong>Calendar & Scheduling</strong> (5 skills)</summary>

| Skill | Status |
|-------|--------|
| [birthday-reminder](https://github.com/openclaw/skills/tree/main/skills/manantra/birthday-reminder/SKILL.md) * | LOW |
| [calctl](https://github.com/openclaw/skills/tree/main/skills/rainbat/calctl/SKILL.md) | SAFE |
| [plan-my-day](https://github.com/openclaw/skills/tree/main/skills/itsflow/plan-my-day/SKILL.md) | SAFE |
| [timesheet](https://github.com/openclaw/skills/tree/main/skills/florianrauscha/timesheet/SKILL.md) | SAFE |
| [toggl](https://github.com/openclaw/skills/tree/main/skills/clvrobj/toggl/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- CRM & BUSINESS -->
<!-- ============================================================ -->
<details>
<summary><strong>CRM & Business</strong> (15 skills)</summary>

| Skill | Status |
|-------|--------|
| [agentledger](https://github.com/openclaw/skills/tree/main/skills/c-goro/agentledger/SKILL.md) | SAFE |
| [apollo](https://github.com/openclaw/skills/tree/main/skills/jhumanj/apollo/SKILL.md) | SAFE |
| [attio](https://github.com/openclaw/skills/tree/main/skills/andrewdmwalker/attio/SKILL.md) * | LOW |
| [blossom-hire](https://github.com/openclaw/skills/tree/main/skills/robbiwu/blossom-hire/SKILL.md) * | LOW |
| [gong](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/gong/SKILL.md) * | LOW |
| [gumroad-admin](https://github.com/openclaw/skills/tree/main/skills/abakermi/gumroad-admin/SKILL.md) * | LOW |
| [pa-admin-exec](https://github.com/openclaw/skills/tree/main/skills/kowl64/pa-admin-exec/SKILL.md) | SAFE |
| [pipedrive](https://github.com/openclaw/skills/tree/main/skills/rdewolff/pipedrive/SKILL.md) * | LOW |
| [startups](https://github.com/openclaw/skills/tree/main/skills/networkingit/startups/SKILL.md) | SAFE |
| [twenty-crm](https://github.com/openclaw/skills/tree/main/skills/jhumanj/twenty-crm/SKILL.md) | SAFE |
| [drivers-hours-wtd-infringement-coach-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/drivers-hours-wtd-infringement-coach-uk/SKILL.md) | SAFE |
| [dvsa-tc-audit-readiness-operator-licence-uk](https://github.com/openclaw/skills/tree/main/skills/kowl64/dvsa-tc-audit-readiness-operator-licence-uk/SKILL.md) | SAFE |
| [featurebase](https://github.com/openclaw/skills/tree/main/skills/rdewolff/featurebase/SKILL.md) * | LOW |
| [cost-report](https://github.com/openclaw/skills/tree/main/skills/vincentqiu/cost-report/SKILL.md) * | LOW |
| [campaign-orchestrator](https://github.com/openclaw/skills/tree/main/skills/kesslerio/campaign-orchestrator/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- MARKETING & SEO -->
<!-- ============================================================ -->
<details>
<summary><strong>Marketing & SEO</strong> (16 skills)</summary>

| Skill | Status |
|-------|--------|
| [affiliatematic](https://github.com/openclaw/skills/tree/main/skills/dowands/affiliatematic/SKILL.md) * | LOW |
| [brand-guidelines](https://github.com/openclaw/skills/tree/main/skills/seanphan/brand-guidelines/SKILL.md) | SAFE |
| [competitive-intelligence-market-research](https://github.com/openclaw/skills/tree/main/skills/shashwatgtm/competitive-intelligence-market-research/SKILL.md) | SAFE |
| [content-ideas-generator](https://github.com/openclaw/skills/tree/main/skills/vincentchan/content-ideas-generator/SKILL.md) | SAFE |
| [ga4](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/ga4/SKILL.md) * | LOW |
| [ga4-analytics](https://github.com/openclaw/skills/tree/main/skills/adamkristopher/ga4-analytics/SKILL.md) * | LOW |
| [geo-optimization](https://github.com/openclaw/skills/tree/main/skills/andrewdmwalker/geo-optimization/SKILL.md) | SAFE |
| [geo-optimizer](https://github.com/openclaw/skills/tree/main/skills/artyomx33/geo-optimizer/SKILL.md) | SAFE |
| [gsc](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/gsc/SKILL.md) * | LOW |
| [keywords-everywhere](https://github.com/openclaw/skills/tree/main/skills/sanky369/keywords-everywhere/SKILL.md) * | LOW |
| [localrank-agent-skills](https://github.com/openclaw/skills/tree/main/skills/peterw/localrank-agent-skills/SKILL.md) * | LOW |
| [marketing-demand-acquisition](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/marketing-demand-acquisition/SKILL.md) | SAFE |
| [marketing-mode](https://github.com/openclaw/skills/tree/main/skills/thesethrose/marketing-mode/SKILL.md) | SAFE |
| [marketing-skills](https://github.com/openclaw/skills/tree/main/skills/jchopard69/marketing-skills/SKILL.md) | SAFE |
| [personal-branding-authority](https://github.com/openclaw/skills/tree/main/skills/shashwatgtm/personal-branding-authority/SKILL.md) | SAFE |
| [seo-dataforseo](https://github.com/openclaw/skills/tree/main/skills/adamkristopher/seo-dataforseo/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- DEVELOPER TOOLS -->
<!-- ============================================================ -->
<details>
<summary><strong>Developer Tools</strong> (26 skills)</summary>

| Skill | Status |
|-------|--------|
| [asc-release-flow](https://github.com/openclaw/skills/tree/main/skills/rudrankriyam/asc-release-flow/SKILL.md) * | LOW |
| [autonomous-feature-planner](https://github.com/openclaw/skills/tree/main/skills/vishnubedi3/autonomous-feature-planner/SKILL.md) * | LOW |
| [backend-patterns](https://github.com/openclaw/skills/tree/main/skills/charmmm718/backend-patterns/SKILL.md) | SAFE |
| [basecamp-cli](https://github.com/openclaw/skills/tree/main/skills/emredoganer/basecamp-cli/SKILL.md) | SAFE |
| [clean-code](https://github.com/openclaw/skills/tree/main/skills/gabrielsubtil/clean-code/SKILL.md) * | LOW |
| [clawdbot-release-check](https://github.com/openclaw/skills/tree/main/skills/pors/clawdbot-release-check/SKILL.md) | SAFE |
| [clawdbot-filesystem](https://github.com/openclaw/skills/tree/main/skills/gtrusler/clawdbot-filesystem/SKILL.md) * | LOW |
| [debug-pro](https://github.com/openclaw/skills/tree/main/skills/cmanfre7/debug-pro/SKILL.md) | SAFE |
| [fizzy-cli](https://github.com/openclaw/skills/tree/main/skills/tobiasbischoff/fizzy-cli/SKILL.md) | SAFE |
| [gno](https://github.com/openclaw/skills/tree/main/skills/gmickel/gno/SKILL.md) | SAFE |
| [java-change-with-tests](https://github.com/openclaw/skills/tree/main/skills/tanerilyazov/java-change-with-tests/SKILL.md) | SAFE |
| [minimax-coding-plan-usage](https://github.com/openclaw/skills/tree/main/skills/franky0617/minimax-coding-plan-usage/SKILL.md) * | LOW |
| [noir-developer](https://github.com/openclaw/skills/tree/main/skills/jp4g/noir-developer/SKILL.md) | SAFE |
| [openspec](https://github.com/openclaw/skills/tree/main/skills/jcorrego/openspec/SKILL.md) | SAFE |
| [openssl](https://github.com/openclaw/skills/tree/main/skills/asleep123/openssl/SKILL.md) | SAFE |
| [prd](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/prd/SKILL.md) | SAFE |
| [project-tree](https://github.com/openclaw/skills/tree/main/skills/lachlanglasgow/project-tree/SKILL.md) | SAFE |
| [receiving-code-review](https://github.com/openclaw/skills/tree/main/skills/chenleiyanquan/receiving-code-review/SKILL.md) | SAFE |
| [ripgrep](https://github.com/openclaw/skills/tree/main/skills/arnarsson/ripgrep/SKILL.md) | SAFE |
| [senior-architect](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/senior-architect/SKILL.md) | SAFE |
| [senior-backend](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/senior-backend/SKILL.md) | SAFE |
| [tdd-guide](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/tdd-guide/SKILL.md) | SAFE |
| [test-runner](https://github.com/openclaw/skills/tree/main/skills/cmanfre7/test-runner/SKILL.md) | SAFE |
| [web-perf](https://github.com/openclaw/skills/tree/main/skills/elithrar/web-perf/SKILL.md) | SAFE |
| [config-guardian](https://github.com/openclaw/skills/tree/main/skills/abdhilabs/config-guardian/SKILL.md) * | LOW |
| [fabric-api](https://github.com/openclaw/skills/tree/main/skills/tristanmanchester/fabric-api/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- SECURITY & AUDIT -->
<!-- ============================================================ -->
<details>
<summary><strong>Security & Audit</strong> (18 skills)</summary>

| Skill | Status |
|-------|--------|
| [adversarial-prompting](https://github.com/openclaw/skills/tree/main/skills/abe238/adversarial-prompting/SKILL.md) | SAFE |
| [api-credentials-hygiene](https://github.com/openclaw/skills/tree/main/skills/kowl64/api-credentials-hygiene/SKILL.md) | SAFE |
| [clawdbot-security-check](https://github.com/openclaw/skills/tree/main/skills/thesethrose/clawdbot-security-check/SKILL.md) | SAFE |
| [clawdbot-security-suite](https://github.com/openclaw/skills/tree/main/skills/gtrusler/clawdbot-security-suite/SKILL.md) * | LOW |
| [clawdefender](https://github.com/openclaw/skills/tree/main/skills/nukewire/clawdefender/SKILL.md) | SAFE |
| [ecap-security-auditor](https://github.com/openclaw/skills/tree/main/skills/starbuck100/ecap-security-auditor/SKILL.md) | SAFE |
| [indirect-prompt-injection](https://github.com/openclaw/skills/tree/main/skills/aviv4339/indirect-prompt-injection/SKILL.md) | SAFE |
| [insecure-defaults](https://github.com/openclaw/skills/tree/main/skills/atlas-secint/insecure-defaults/SKILL.md) | SAFE |
| [manipulation-detector](https://github.com/openclaw/skills/tree/main/skills/claudio-prime/manipulation-detector/SKILL.md) | SAFE |
| [molthunt](https://github.com/openclaw/skills/tree/main/skills/limone-eth/molthunt/SKILL.md) * | LOW |
| [moltguard](https://github.com/openclaw/skills/tree/main/skills/thomaslwang/moltguard/SKILL.md) | SAFE |
| [security-heuristics](https://github.com/openclaw/skills/tree/main/skills/luluf0x/security-heuristics/SKILL.md) | SAFE |
| [skill-audit](https://github.com/openclaw/skills/tree/main/skills/morozred/skill-audit/SKILL.md) * | LOW |
| [skill-flag](https://github.com/openclaw/skills/tree/main/skills/patfire94/skill-flag/SKILL.md) | SAFE |
| [skill-scanner](https://github.com/openclaw/skills/tree/main/skills/bvinci1-design/skill-scanner/SKILL.md) | SAFE |
| [skillguard](https://github.com/openclaw/skills/tree/main/skills/c-goro/skillguard/SKILL.md) | SAFE |
| [skillvet](https://github.com/openclaw/skills/tree/main/skills/oakencore/skillvet/SKILL.md) | SAFE |
| [sona-security-audit](https://github.com/openclaw/skills/tree/main/skills/virtaava/sona-security-audit/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- AI & LLM TOOLS -->
<!-- ============================================================ -->
<details>
<summary><strong>AI & LLM Tools</strong> (19 skills)</summary>

| Skill | Status |
|-------|--------|
| [agent-builder](https://github.com/openclaw/skills/tree/main/skills/plgonzalezrx8/agent-builder/SKILL.md) | SAFE |
| [agenticflow-skill](https://github.com/openclaw/skills/tree/main/skills/seanphan/agenticflow-skill/SKILL.md) * | LOW |
| [botpress-adk](https://github.com/openclaw/skills/tree/main/skills/yueranlu/botpress-adk/SKILL.md) | SAFE |
| [claude-optimised](https://github.com/openclaw/skills/tree/main/skills/hexnickk/claude-optimised/SKILL.md) | SAFE |
| [council](https://github.com/openclaw/skills/tree/main/skills/emasoudy/council/SKILL.md) * | LOW |
| [gemini](https://github.com/openclaw/skills/tree/main/skills/steipete/gemini/SKILL.md) * | LOW |
| [gemini-deep-research](https://github.com/openclaw/skills/tree/main/skills/arun-8687/gemini-deep-research/SKILL.md) | SAFE |
| [gembox-skill](https://github.com/openclaw/skills/tree/main/skills/zsvedic/gembox-skill/SKILL.md) | SAFE |
| [mlti-llm-fallback](https://github.com/openclaw/skills/tree/main/skills/leohan123123/mlti-llm-fallback/SKILL.md) | SAFE |
| [openai-tts](https://github.com/openclaw/skills/tree/main/skills/pors/openai-tts/SKILL.md) * | LOW |
| [oracle](https://github.com/openclaw/skills/tree/main/skills/steipete/oracle/SKILL.md) * | LOW |
| [parallel](https://github.com/openclaw/skills/tree/main/skills/mvanhorn/parallel/SKILL.md) * | LOW |
| [peft](https://github.com/openclaw/skills/tree/main/skills/desperado991128/peft/SKILL.md) | SAFE |
| [prompt-engineering-expert](https://github.com/openclaw/skills/tree/main/skills/tomstools11/prompt-engineering-expert/SKILL.md) | SAFE |
| [promptify](https://github.com/openclaw/skills/tree/main/skills/tolibear/promptify/SKILL.md) * | LOW |
| [self-improving-agent](https://github.com/openclaw/skills/tree/main/skills/pskoett/self-improving-agent/SKILL.md) | SAFE |
| [ydc-claude-agent-sdk-integration](https://github.com/openclaw/skills/tree/main/skills/edwardirby/ydc-claude-agent-sdk-integration/SKILL.md) | SAFE |
| [ydc-openai-agent-sdk-integration](https://github.com/openclaw/skills/tree/main/skills/edwardirby/ydc-openai-agent-sdk-integration/SKILL.md) | SAFE |
| [youdotcom-cli](https://github.com/openclaw/skills/tree/main/skills/edwardirby/youdotcom-cli/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- HEALTH & WELLNESS -->
<!-- ============================================================ -->
<details>
<summary><strong>Health & Wellness</strong> (23 skills)</summary>

| Skill | Status |
|-------|--------|
| [adhd-assistant](https://github.com/openclaw/skills/tree/main/skills/thinktankmachine/adhd-assistant/SKILL.md) | SAFE |
| [adhd-body-doubling](https://github.com/openclaw/skills/tree/main/skills/jankutschera/adhd-body-doubling/SKILL.md) * | LOW |
| [adhd-daily-planner](https://github.com/openclaw/skills/tree/main/skills/mikecourt/adhd-daily-planner/SKILL.md) | SAFE |
| [adhd-ssistant](https://github.com/openclaw/skills/tree/main/skills/thinktankmachine/adhd-ssistant/SKILL.md) | SAFE |
| [anxiety-relief](https://github.com/openclaw/skills/tree/main/skills/jhillin8/anxiety-relief/SKILL.md) | SAFE |
| [aubrai-longevity](https://github.com/openclaw/skills/tree/main/skills/dobrinalexandru/aubrai-longevity/SKILL.md) * | LOW |
| [build-discipline](https://github.com/openclaw/skills/tree/main/skills/jhillin8/build-discipline/SKILL.md) | SAFE |
| [daily-motivation](https://github.com/openclaw/skills/tree/main/skills/jhillin8/daily-motivation/SKILL.md) | SAFE |
| [depression-support](https://github.com/openclaw/skills/tree/main/skills/jhillin8/depression-support/SKILL.md) | SAFE |
| [focus-deep-work](https://github.com/openclaw/skills/tree/main/skills/jhillin8/focus-deep-work/SKILL.md) | SAFE |
| [garmin-connect](https://github.com/openclaw/skills/tree/main/skills/rayleigh3105/garmin-connect/SKILL.md) * | LOW |
| [garmin-connect-fixed](https://github.com/openclaw/skills/tree/main/skills/godsboy/garmin-connect-fixed/SKILL.md) * | LOW |
| [gratitude-journal](https://github.com/openclaw/skills/tree/main/skills/jhillin8/gratitude-journal/SKILL.md) | SAFE |
| [habit-tracker](https://github.com/openclaw/skills/tree/main/skills/jhillin8/habit-tracker/SKILL.md) | SAFE |
| [healthy-eating](https://github.com/openclaw/skills/tree/main/skills/jhillin8/healthy-eating/SKILL.md) | SAFE |
| [mindfulness-meditation](https://github.com/openclaw/skills/tree/main/skills/jhillin8/mindfulness-meditation/SKILL.md) | SAFE |
| [morning-routine](https://github.com/openclaw/skills/tree/main/skills/jhillin8/morning-routine/SKILL.md) | SAFE |
| [night-routine](https://github.com/openclaw/skills/tree/main/skills/jhillin8/night-routine/SKILL.md) | SAFE |
| [overcome-problem](https://github.com/openclaw/skills/tree/main/skills/jhillin8/overcome-problem/SKILL.md) | SAFE |
| [self-love-confidence](https://github.com/openclaw/skills/tree/main/skills/jhillin8/self-love-confidence/SKILL.md) | SAFE |
| [stress-relief](https://github.com/openclaw/skills/tree/main/skills/jhillin8/stress-relief/SKILL.md) | SAFE |
| [therapy-mode](https://github.com/openclaw/skills/tree/main/skills/thesethrose/therapy-mode/SKILL.md) * | LOW |
| [procrastination-buster](https://github.com/openclaw/skills/tree/main/skills/jhillin8/procrastination-buster/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- FINANCE & DATA -->
<!-- ============================================================ -->
<details>
<summary><strong>Finance & Data</strong> (13 skills)</summary>

| Skill | Status |
|-------|--------|
| [1password](https://github.com/openclaw/skills/tree/main/skills/steipete/1password/SKILL.md) * | LOW |
| [bitwarden-vault](https://github.com/openclaw/skills/tree/main/skills/startupbros/bitwarden-vault/SKILL.md) * | LOW |
| [dashlane](https://github.com/openclaw/skills/tree/main/skills/gnarco/dashlane/SKILL.md) * | LOW |
| [exchange-rates](https://github.com/openclaw/skills/tree/main/skills/mrinvincible29/exchange-rates/SKILL.md) * | LOW |
| [intelligent-budget-tracker](https://github.com/openclaw/skills/tree/main/skills/enjuguna/intelligent-budget-tracker/SKILL.md) | SAFE |
| [model-usage](https://github.com/openclaw/skills/tree/main/skills/steipete/model-usage/SKILL.md) * | LOW |
| [minimax-usage](https://github.com/openclaw/skills/tree/main/skills/thesethrose/minimax-usage/SKILL.md) * | LOW |
| [nordpool-fi](https://github.com/openclaw/skills/tree/main/skills/ovaris/nordpool-fi/SKILL.md) | SAFE |
| [personal-analytics](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/personal-analytics/SKILL.md) | SAFE |
| [proton-pass](https://github.com/openclaw/skills/tree/main/skills/kakatkarakshay/proton-pass/SKILL.md) | SAFE |
| [pvpc-spain](https://github.com/openclaw/skills/tree/main/skills/didelco/pvpc-spain/SKILL.md) | SAFE |
| [usage-export](https://github.com/openclaw/skills/tree/main/skills/bobot-agent/usage-export/SKILL.md) * | LOW |
| [value-tracker](https://github.com/openclaw/skills/tree/main/skills/sergirostoll-coder/value-tracker/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- ENTERTAINMENT & GAMES -->
<!-- ============================================================ -->
<details>
<summary><strong>Entertainment & Games</strong> (5 skills)</summary>

| Skill | Status |
|-------|--------|
| [bot-bowl-party](https://github.com/openclaw/skills/tree/main/skills/fsa317/bot-bowl-party/SKILL.md) * | LOW |
| [chess](https://github.com/openclaw/skills/tree/main/skills/l-mendez/chess/SKILL.md) * | LOW |
| [nano-banana-antigravity](https://github.com/openclaw/skills/tree/main/skills/cgnl/nano-banana-antigravity/SKILL.md) * | LOW |
| [antigravity-quota](https://github.com/openclaw/skills/tree/main/skills/mukhtharcm/antigravity-quota/SKILL.md) | SAFE |
| [vibes](https://github.com/openclaw/skills/tree/main/skills/binora/vibes/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- WRITING & CONTENT -->
<!-- ============================================================ -->
<details>
<summary><strong>Writing & Content</strong> (18 skills)</summary>

| Skill | Status |
|-------|--------|
| [bearblog](https://github.com/openclaw/skills/tree/main/skills/azade-c/bearblog/SKILL.md) | SAFE |
| [blog-writer](https://github.com/openclaw/skills/tree/main/skills/tomstools11/blog-writer/SKILL.md) * | LOW |
| [content-creator](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/content-creator/SKILL.md) | SAFE |
| [content-moderation](https://github.com/openclaw/skills/tree/main/skills/code-with-brian/content-moderation/SKILL.md) * | LOW |
| [content-writing-thought-leadership](https://github.com/openclaw/skills/tree/main/skills/shashwatgtm/content-writing-thought-leadership/SKILL.md) | SAFE |
| [create-content](https://github.com/openclaw/skills/tree/main/skills/itsflow/create-content/SKILL.md) | SAFE |
| [de-ai-ify](https://github.com/openclaw/skills/tree/main/skills/itsflow/de-ai-ify/SKILL.md) | SAFE |
| [doc-coauthoring](https://github.com/openclaw/skills/tree/main/skills/seanphan/doc-coauthoring/SKILL.md) * | LOW |
| [glin-profanity](https://github.com/openclaw/skills/tree/main/skills/thegdsks/glin-profanity/SKILL.md) | SAFE |
| [glin-profanity-mcp](https://github.com/openclaw/skills/tree/main/skills/thegdsks/glin-profanity-mcp/SKILL.md) * | LOW |
| [substack-formatter](https://github.com/openclaw/skills/tree/main/skills/maddiedreese/substack-formatter/SKILL.md) | SAFE |
| [summarize](https://github.com/openclaw/skills/tree/main/skills/steipete/summarize/SKILL.md) * | LOW |
| [qmd](https://github.com/openclaw/skills/tree/main/skills/steipete/qmd/SKILL.md) * | LOW |
| [qmd-cli](https://github.com/openclaw/skills/tree/main/skills/dpaluy/qmd-cli/SKILL.md) | SAFE |
| [qmd-external](https://github.com/openclaw/skills/tree/main/skills/levineam/qmd-external/SKILL.md) | SAFE |
| [qmd-local-search](https://github.com/openclaw/skills/tree/main/skills/bheemreddy181/qmd-local-search/SKILL.md) | SAFE |
| [qmd-markdown-search](https://github.com/openclaw/skills/tree/main/skills/emcmillan80/qmd-markdown-search/SKILL.md) | SAFE |
| [qmd-search](https://github.com/openclaw/skills/tree/main/skills/bheemreddy181/qmd-search/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- RESEARCH & ACADEMIC -->
<!-- ============================================================ -->
<details>
<summary><strong>Research & Academic</strong> (13 skills)</summary>

| Skill | Status |
|-------|--------|
| [causal-inference](https://github.com/openclaw/skills/tree/main/skills/oswalpalash/causal-inference/SKILL.md) | SAFE |
| [first-principles-decomposer](https://github.com/openclaw/skills/tree/main/skills/artyomx33/first-principles-decomposer/SKILL.md) | SAFE |
| [literature-review](https://github.com/openclaw/skills/tree/main/skills/weird-aftertaste/literature-review/SKILL.md) * | LOW |
| [multi-viewpoint-debates](https://github.com/openclaw/skills/tree/main/skills/latentfreedom/multi-viewpoint-debates/SKILL.md) | SAFE |
| [munger-observer](https://github.com/openclaw/skills/tree/main/skills/jdrhyne/munger-observer/SKILL.md) | SAFE |
| [ontology](https://github.com/openclaw/skills/tree/main/skills/oswalpalash/ontology/SKILL.md) | SAFE |
| [pre-mortem-analyst](https://github.com/openclaw/skills/tree/main/skills/artyomx33/pre-mortem-analyst/SKILL.md) | SAFE |
| [reasoning-personas](https://github.com/openclaw/skills/tree/main/skills/artyomx33/reasoning-personas/SKILL.md) | SAFE |
| [research-company](https://github.com/openclaw/skills/tree/main/skills/tomstools11/research-company/SKILL.md) * | LOW |
| [zotero](https://github.com/openclaw/skills/tree/main/skills/terwox/zotero/SKILL.md) | SAFE |
| [study-habits](https://github.com/openclaw/skills/tree/main/skills/jhillin8/study-habits/SKILL.md) | SAFE |
| [language-learning](https://github.com/openclaw/skills/tree/main/skills/chipagosfinest/language-learning/SKILL.md) | SAFE |
| [japanese-translation-and-tutor](https://github.com/openclaw/skills/tree/main/skills/itsjaydesu/japanese-translation-and-tutor/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- FILE & SYSTEM -->
<!-- ============================================================ -->
<details>
<summary><strong>File & System</strong> (10 skills)</summary>

| Skill | Status |
|-------|--------|
| [clawdbot-skill-clawdbot-workspace-template-review](https://github.com/openclaw/skills/tree/main/skills/xadenryan/clawdbot-skill-clawdbot-workspace-template-review/SKILL.md) * | LOW |
| [confirm-form](https://github.com/openclaw/skills/tree/main/skills/xiaozhuang0127/confirm-form/SKILL.md) * | LOW |
| [media-converter](https://github.com/openclaw/skills/tree/main/skills/autogame-17/media-converter/SKILL.md) * | LOW |
| [ms-onedrive-personal](https://github.com/openclaw/skills/tree/main/skills/cesarus85/ms-onedrive-personal/SKILL.md) * | LOW |
| [url-shortener](https://github.com/openclaw/skills/tree/main/skills/kesslerio/url-shortener/SKILL.md) | SAFE |
| [healthcheck](https://github.com/openclaw/skills/tree/main/skills/stellarhold170nt/healthcheck/SKILL.md) | SAFE |
| [dashboard](https://github.com/openclaw/skills/tree/main/skills/joetomasone/dashboard/SKILL.md) | SAFE |
| [qmd-skill-2](https://github.com/openclaw/skills/tree/main/skills/lifecoacher/qmd-skill-2/SKILL.md) * | LOW |
| [noverload](https://github.com/openclaw/skills/tree/main/skills/drewautomates/noverload/SKILL.md) * | LOW |
| [google-maps-grounding-lite-mcp](https://github.com/openclaw/skills/tree/main/skills/ryanbaumann/google-maps-grounding-lite-mcp/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- LIFESTYLE & PERSONAL -->
<!-- ============================================================ -->
<details>
<summary><strong>Lifestyle & Personal</strong> (23 skills)</summary>

| Skill | Status |
|-------|--------|
| [cochesnet-cli](https://github.com/openclaw/skills/tree/main/skills/pjtf93/cochesnet-cli/SKILL.md) * | LOW |
| [daily-review](https://github.com/openclaw/skills/tree/main/skills/henrino3/daily-review/SKILL.md) * | LOW |
| [daily-review-ritual](https://github.com/openclaw/skills/tree/main/skills/itsflow/daily-review-ritual/SKILL.md) | SAFE |
| [dex](https://github.com/openclaw/skills/tree/main/skills/gricha/dex/SKILL.md) | SAFE |
| [fix-life-in-1-day](https://github.com/openclaw/skills/tree/main/skills/evgyur/fix-life-in-1-day/SKILL.md) | SAFE |
| [get-you-some-britches](https://github.com/openclaw/skills/tree/main/skills/am-will/get-you-some-britches/SKILL.md) | SAFE |
| [molt-city](https://github.com/openclaw/skills/tree/main/skills/gonzih/molt-city/SKILL.md) | SAFE |
| [personality-test](https://github.com/openclaw/skills/tree/main/skills/milbaxter/personality-test/SKILL.md) | SAFE |
| [places](https://github.com/openclaw/skills/tree/main/skills/barneyjm/places/SKILL.md) | SAFE |
| [recipe-to-list](https://github.com/openclaw/skills/tree/main/skills/borahm/recipe-to-list/SKILL.md) * | LOW |
| [relationship-skills](https://github.com/openclaw/skills/tree/main/skills/jhillin8/relationship-skills/SKILL.md) | SAFE |
| [ridb-search](https://github.com/openclaw/skills/tree/main/skills/seanrea/ridb-search/SKILL.md) * | LOW |
| [satellite-copilot](https://github.com/openclaw/skills/tree/main/skills/davestarling/satellite-copilot/SKILL.md) | SAFE |
| [seoul-metro](https://github.com/openclaw/skills/tree/main/skills/dukbong/seoul-metro/SKILL.md) | SAFE |
| [seoul-subway](https://github.com/openclaw/skills/tree/main/skills/dukbong/seoul-subway/SKILL.md) * | LOW |
| [skiplagged-flights](https://github.com/openclaw/skills/tree/main/skills/wzs/skiplagged-flights/SKILL.md) * | LOW |
| [swissweather](https://github.com/openclaw/skills/tree/main/skills/xenofex7/swissweather/SKILL.md) | SAFE |
| [virtually-us](https://github.com/openclaw/skills/tree/main/skills/epwhesq/virtually-us/SKILL.md) * | LOW |
| [wallapop-cli](https://github.com/openclaw/skills/tree/main/skills/pjtf93/wallapop-cli/SKILL.md) * | LOW |
| [weekly-synthesis](https://github.com/openclaw/skills/tree/main/skills/itsflow/weekly-synthesis/SKILL.md) | SAFE |
| [wisdom-accountability-coach](https://github.com/openclaw/skills/tree/main/skills/mikecourt/wisdom-accountability-coach/SKILL.md) | SAFE |
| [soulcraft](https://github.com/openclaw/skills/tree/main/skills/kesslerio/soulcraft/SKILL.md) | SAFE |
| [hzl](https://github.com/openclaw/skills/tree/main/skills/tmchow/hzl/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- AGENT INFRASTRUCTURE -->
<!-- ============================================================ -->
<details>
<summary><strong>Agent Infrastructure</strong> (28 skills)</summary>

| Skill | Status |
|-------|--------|
| [4claw](https://github.com/openclaw/skills/tree/main/skills/mfergpt/4claw/SKILL.md) * | LOW |
| [aap-passport](https://github.com/openclaw/skills/tree/main/skills/ira-hash/aap-passport/SKILL.md) * | LOW |
| [agent-chronicle](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/agent-chronicle/SKILL.md) | SAFE |
| [agent-contact-card](https://github.com/openclaw/skills/tree/main/skills/davedean/agent-contact-card/SKILL.md) | SAFE |
| [agent-docs](https://github.com/openclaw/skills/tree/main/skills/tylervovan/agent-docs/SKILL.md) * | LOW |
| [agent-observability-dashboard](https://github.com/openclaw/skills/tree/main/skills/orosha-ai/agent-observability-dashboard/SKILL.md) | SAFE |
| [agent-reflect](https://github.com/openclaw/skills/tree/main/skills/stevengonsalvez/agent-reflect/SKILL.md) * | LOW |
| [agentlens](https://github.com/openclaw/skills/tree/main/skills/nguyenphutrong/agentlens/SKILL.md) | SAFE |
| [agentic-compass](https://github.com/openclaw/skills/tree/main/skills/orosha-ai/agentic-compass/SKILL.md) | SAFE |
| [answeroverflow](https://github.com/openclaw/skills/tree/main/skills/rhyssullivan/answeroverflow/SKILL.md) | SAFE |
| [ask-questions-if-underspecified](https://github.com/openclaw/skills/tree/main/skills/lc0rp/ask-questions-if-underspecified/SKILL.md) | SAFE |
| [attribution-engine](https://github.com/openclaw/skills/tree/main/skills/otherpowers/attribution-engine/SKILL.md) | SAFE |
| [blackops-center](https://github.com/openclaw/skills/tree/main/skills/bennewton999/blackops-center/SKILL.md) | SAFE |
| [clawd-docs-v2](https://github.com/openclaw/skills/tree/main/skills/aranej/clawd-docs-v2/SKILL.md) | SAFE |
| [clawd-presence](https://github.com/openclaw/skills/tree/main/skills/voidcooks/clawd-presence/SKILL.md) | SAFE |
| [disclawd](https://github.com/openclaw/skills/tree/main/skills/alexerm/disclawd/SKILL.md) | SAFE |
| [find-skills](https://github.com/openclaw/skills/tree/main/skills/jimliuxinghai/find-skills/SKILL.md) * | LOW |
| [flowmind](https://github.com/openclaw/skills/tree/main/skills/fancygobot/flowmind/SKILL.md) * | LOW |
| [jo4](https://github.com/openclaw/skills/tree/main/skills/anandrathnas/jo4/SKILL.md) | SAFE |
| [mcporter-skill](https://github.com/openclaw/skills/tree/main/skills/livvux/mcporter-skill/SKILL.md) | SAFE |
| [openclaw](https://github.com/openclaw/skills/tree/main/skills/jordanprater/openclaw/SKILL.md) | SAFE |
| [openclaw-echo-agent](https://github.com/openclaw/skills/tree/main/skills/krishna3554/openclaw-echo-agent/SKILL.md) | SAFE |
| [pro](https://github.com/openclaw/skills/tree/main/skills/jash2368-collab/pro/SKILL.md) | SAFE |
| [self-reflection](https://github.com/openclaw/skills/tree/main/skills/hopyky/self-reflection/SKILL.md) | SAFE |
| [skill-creator](https://github.com/openclaw/skills/tree/main/skills/chindden/skill-creator/SKILL.md) | SAFE |
| [skill-creator-0-1-0](https://github.com/openclaw/skills/tree/main/skills/ljglover/skill-creator-0-1-0/SKILL.md) | SAFE |
| [skill-evaluator](https://github.com/openclaw/skills/tree/main/skills/terwox/skill-evaluator/SKILL.md) | SAFE |
| [skillcraft](https://github.com/openclaw/skills/tree/main/skills/jmz1/skillcraft/SKILL.md) | SAFE |

</details>

<!-- ============================================================ -->
<!-- DOCUMENTATION -->
<!-- ============================================================ -->
<details>
<summary><strong>Documentation</strong> (18 skills)</summary>

| Skill | Status |
|-------|--------|
| [aclawdemy](https://github.com/openclaw/skills/tree/main/skills/nimhar/aclawdemy/SKILL.md) * | LOW |
| [app-store-changelog](https://github.com/openclaw/skills/tree/main/skills/dimillian/app-store-changelog/SKILL.md) | SAFE |
| [apple-hig](https://github.com/openclaw/skills/tree/main/skills/kdbhalala/apple-hig/SKILL.md) | SAFE |
| [clawdbot-documentation-expert](https://github.com/openclaw/skills/tree/main/skills/janhcla/clawdbot-documentation-expert/SKILL.md) * | LOW |
| [clawddocs](https://github.com/openclaw/skills/tree/main/skills/nicholasspisak/clawddocs/SKILL.md) | SAFE |
| [content-id-guide](https://github.com/openclaw/skills/tree/main/skills/otherpowers/content-id-guide/SKILL.md) | SAFE |
| [docstrange](https://github.com/openclaw/skills/tree/main/skills/shhdwi/docstrange/SKILL.md) * | LOW |
| [octolens](https://github.com/openclaw/skills/tree/main/skills/garrrikkotua/octolens/SKILL.md) | SAFE |
| [orf](https://github.com/openclaw/skills/tree/main/skills/cpojer/orf/SKILL.md) | SAFE |
| [plurum](https://github.com/openclaw/skills/tree/main/skills/berkay-dune/plurum/SKILL.md) * | LOW |
| [query](https://github.com/openclaw/skills/tree/main/skills/barneyjm/query/SKILL.md) | SAFE |
| [reflect](https://github.com/openclaw/skills/tree/main/skills/sergical/reflect/SKILL.md) * | LOW |
| [reflect-learn](https://github.com/openclaw/skills/tree/main/skills/stevengonsalvez/reflect-learn/SKILL.md) * | LOW |
| [self-reflect](https://github.com/openclaw/skills/tree/main/skills/stevengonsalvez/self-reflect/SKILL.md) * | LOW |
| [skill-content-id-guide](https://github.com/openclaw/skills/tree/main/skills/otherpowers/skill-content-id-guide/SKILL.md) | SAFE |
| [skills-search](https://github.com/openclaw/skills/tree/main/skills/thesethrose/skills-search/SKILL.md) | SAFE |
| [smart-followups](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/smart-followups/SKILL.md) | SAFE |
| [skylight-skill](https://github.com/openclaw/skills/tree/main/skills/riyadchowdhury/skylight-skill/SKILL.md) * | LOW |

</details>

<!-- ============================================================ -->
<!-- REMAINING / MISCELLANEOUS -->
<!-- ============================================================ -->
<details>
<summary><strong>Miscellaneous</strong> (5 skills)</summary>

| Skill | Status |
|-------|--------|
| [go2gg](https://github.com/openclaw/skills/tree/main/skills/rakesh1002/go2gg/SKILL.md) * | LOW |
| [ket](https://github.com/openclaw/skills/tree/main/skills/zhqinqin123run-lgtm/ket/SKILL.md) | SAFE |
| [sis-skill](https://github.com/openclaw/skills/tree/main/skills/architect-sis/sis-skill/SKILL.md) * | LOW |
| [thecolony-heartbeat](https://github.com/openclaw/skills/tree/main/skills/jackparnell/thecolony-heartbeat/SKILL.md) * | LOW |
| [web-search-plus](https://github.com/openclaw/skills/tree/main/skills/robbyczgw-cla/web-search-plus/SKILL.md) * | LOW |
</details>

---

> **\*** = **LOW risk** -- These skills had minor flags during automated scanning (e.g., broad file access patterns, external API calls, or unconventional coding patterns) but were **confirmed safe** on manual deep review by Opus 4.6. They are safe to use; the indicator is provided for full transparency only.

---

## Summary Statistics

| Metric | Count |
|--------|-------|
| Total skills scanned | 4,000+ |
| AI models used | 3 (Claude, Gemini, Kimi) |
| Tokens spent | ~1,000,000 |
| Skills that passed audit (this list) | **395** |
| -- Classified SAFE | 241 |
| -- Classified LOW (minor flags, confirmed safe) | 154 |
| Skills excluded (malware/suspicious/unfetchable) | 106 |
| HIGH/MEDIUM flags overturned on deep review | 88 |

---

## Contributing

This is a community-maintained safety resource. You can help in the following ways:

- **Report a concern:** [Open an issue](https://github.com/huge8888/OPENCLAW-SKILL-SAFE/issues/new) with the skill name, author, and what you observed
- **Request a re-audit:** If you believe a skill was miscategorized, open an issue with details
- **Submit new audit data:** If you have independently audited skills not yet on this list, open a PR with your findings
- **Flag removed skills:** If any skill on this list has been modified since the audit date, report it so we can re-audit

---

## Disclaimer

This audit represents a point-in-time analysis as of the audit date listed above. Skills can be updated by their authors at any time after the audit. Always exercise caution when installing any third-party code. This list is provided as-is with no warranty. The auditors are not responsible for any damages caused by the use of any listed or unlisted skills.

---

<sub>Audited with 3 AI models (Claude Opus 4.6, Gemini, Kimi) + OSTRTA automated scanning | ~1M tokens spent | Last updated: 2026-02-06</sub>
