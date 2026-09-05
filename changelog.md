# Changelog

## 2026-09-05

- Added PPSA Agent from `Hankyone/PPSA_Agent` as a prototype, last touched `2026-07-01`; evidence: Hankyone-authored initial implementation `2957f93b6fc8adecebe72578214a29353f5a061e`, with PDF ingestion/search and a multi-document LLM workflow.
- No existing tracked `last_touched` dates changed.
- Left `poem` untracked as an ambiguous one-off wedding-practice artifact; FrancePlan remains excluded per the prior user-requested removal. Excluded `CorpTaxes2025` as a tax-ops workspace, `ai-marketplace-monitor` as a fork, the alternate `Rx1Stack` repository as related to the already tracked RX1 Stack, and September 4 `background-agents` upstream/merge activity.

## 2026-09-04

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-09-02` → `2026-09-03`).
- deadsimpleRSS evidence: known-feed subscriptions now preserve the parsed feed title instead of exposing the raw feed URL, commit `58b5930ff52db8866ec8101b1bacf3120b8f569d`.
- No new qualifying project added.

## 2026-09-03

- Synced `last_touched` from newer meaningful GitHub activity: ListenToMe (`2026-09-01` → `2026-09-03`).
- ListenToMe evidence: fixed media pause/resume control by consulting Now Playing playback rate before toggling and safely adopting stale pause sessions, commit `8e746ab14a58f1f29afd3044474757a02aa1afc5`.
- No new qualifying project added. Ignored Project Radar sync edits, same-date deadsimpleRSS work already covered by `2026-09-02`, upstream/background-agent activity, repository housekeeping, generated/dependency-only changes, and previously rejected ambiguous candidates.

## 2026-09-02

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-09-01` → `2026-09-02`) and ListenToMe (`2026-08-31` → `2026-09-01`).
- deadsimpleRSS evidence: fixed mobile feedback input zoom and touch sizing in the feed status feedback control, commit `8dddd5ab8f5900760a35243551a8ff2316198b79`.
- ListenToMe evidence: restored reliable media pausing when browser playback is not reported through Now Playing, with updated pause-state handling and tests, commit `c0d4f77f400af1269dc1cc75beb5e0458d530059`.
- No new qualifying project added. Ignored Project Radar sync edits and found no new Hankyone repository candidates since the previous sync.

## 2026-09-01

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-30` → `2026-09-01`) and ListenToMe (`2026-08-30` → `2026-08-31`).
- deadsimpleRSS evidence: improved mobile podcast controls and responsive control layout, commit `55933ac64edcaa7d41dff306ac237616fca17269`.
- ListenToMe evidence: changed mic startup so capture waits only when media was actually playing and confirms playback is paused, commit `5e3b21465f9723e3278ac122864f225f87245fe0`.
- No new qualifying project added. Ignored Project Radar edits, SEO-only/peripheral work, repository housekeeping, and automated background-agent activity.

## 2026-08-31

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-28` → `2026-08-30`), PDF Corpus Redaction (`2026-07-21` → `2026-08-30`), and ListenToMe (`2026-08-28` → `2026-08-30`).
- deadsimpleRSS evidence: unified feed-proxy outcome handling and terminal/recoverable feed-error classification, commit `b3d862c5d7b2f26a115d3a6729b97bb2146f9bd8`. Ignored later AGENTS-only production-approval guidance commit `1f166cc769bb68304879ae9b234345e5340a2751` as repository housekeeping.
- PDF Corpus Redaction evidence: fixed decision-register row collisions and responsive action layout in the review UI, commit `da59d5f576a816e5ee62b95c9f31c6a4cb1c7ff5`.
- ListenToMe evidence: added focused-field-aware dictation formatting, local field classification, and remembered per-field formatting overrides, commit `7277d67adba6d25b951caf4abb2b62fcb0e7aa8f`.
- No new qualifying project added. Left recent ambiguous or non-project candidates untracked, including `ShadeSec-dot-com2` and `resume-visualizer-cloud`; ignored upstream/background-agent work, generated files, and repository housekeeping.

## 2026-08-30

- Added `portfolyahoo` from `Hankyone/portfolyahoo` as a prototype, last touched `2026-07-03`; evidence: Hankyone-authored parser fix `000b5220333fd11a78a8e08e0bc5c3679991f587`.
- Added How To Vibe Secure from `Hankyone/HowToVibeSecure` as a prototype, last touched `2025-08-14`; evidence: Hankyone-authored SSRF demo and explanation work `0ed047d73d60a82a675631add15fb8a4ce59a7ea`. Excluded later Claude-authored work as automated activity.
- Added CdQ-Calc from `Hankyone/CdQ-Calc` as a prototype, last touched `2025-11-05`; evidence: Hankyone-authored configuration persistence and import handling work `a70c51488d314c90c1de96c93ce1807ef8c9b723`.
- Added Builder Sundayier from `Hankyone/BuldierSundayier` as a prototype, last touched `2026-03-01`; evidence: Hankyone-authored calendar and reminder-email UX work `2d8e733813375dcb51c2a77e3677beab6c0d47be`.
- Added LeanLabs from `Hankyone/LeanLabs-App` as a prototype, last touched `2025-09-22`; evidence: Hankyone-authored home-screen and onboarding work `36253a6680485b96a50754997d4e6fbac5dcbee9`. Excluded the synchronized August 2026 Cursor refresh as background-agent activity.
- Added `deadsimpleproxy` from `Hankyone/deadsimpleproxy` as a prototype, last touched `2026-02-13`; evidence: Hankyone-authored redirect-response handling fix `3f93d92b7dca66f787d1d715afc16f9495531ac9`.
- No existing tracked `last_touched` dates changed. Left external/custom, component, setup-only, and ambiguous candidates untracked, including `tab-out-plus-pro-ultra`, `FrugalRSS`, `MindSnack-Sharer`, `ShadeSec-reporting-toolkit`, and ambiguous Sudoku repository identity.

## 2026-08-29

- Synced `last_touched` from newer meaningful GitHub activity: Ghostty Pro Plus Ultra (`2026-08-08` → `2026-08-28`) and ListenToMe (`2026-08-27` → `2026-08-28`).
- Ghostty Pro Plus Ultra evidence: removed fork-specific glass tint overlay calls made obsolete by the upstream glass rewrite after the upstream merge, commit `cab5876c96ec1a4981167a7e7ab419a81818480f`; the upstream merge itself was ignored.
- ListenToMe evidence: kept microphone capture open for 400 ms after key-up to preserve trailing words, with recording-flow and regression-test changes, commit `0e7d6dab954684ca7cbfda69f57c3c27a989c870`.
- Added SidePiece from `Hankyone/SidePiece` as a prototype Android-agent controller after verifying its project spec and substantive implementation commit `1f332b26b8966a95fa67d40826d02f5348181cf8` on `2025-12-17`.
- Left `Banff2025` and `Nothing` untracked as ambiguous one-off/novelty candidates. Ignored upstream merges, release/package-only work, vault syncs, generated/dependency-only changes, repository housekeeping, automated background-agent activity, and Project Radar edits.

## 2026-08-28

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-25` → `2026-08-27`), deadsimpleRSS (`2026-08-23` → `2026-08-28`), MacDown Pro Plus Ultra (`2026-05-17` → `2026-08-27`), and ListenToMe (`2026-08-13` → `2026-08-27`).
- Control+s evidence: updated Flue model specifications and added a runner activity heartbeat, commit `6ecf1471bea6baeb263a0d507560a80c501436f5`.
- deadsimpleRSS evidence: refined the Custom Magic composer and matching/action controls, commit `7984d899d76e6b78d33227c8ba437971ba435ce7`.
- MacDown Pro Plus Ultra evidence: polished the animated document-view selector and its accessibility behavior, commit `01cea59fd45d1b4c2171c4ea86cc309be24727a2`.
- ListenToMe evidence: added system microphone input-volume control in Setup, commit `fa1d7e072d01e0035297951182f928be20712094`.
- Found no new clearly intentional standalone Hankyone project to add. `resume-visualizer-cloud` remains excluded as cleanup/dependency churn, `ShadeSec-dot-com2` remains ambiguous, and `bb-custom` remains a customization/fork repository.
- Left RapidRecap and Anouar.ca unchanged because their newer commits were public-agent/content representation work. Ignored Obsyone vault syncs, Project Radar edits, generated files, release publishing/signing-only commits, test-only changes, and other repository housekeeping.

## 2026-08-27

- Added Kickbacks Harness after confirming `Hankyone/kickbacks-harness` as a standalone simulator project. Purpose evidence: commit `bd972d4b60069e5315aa14bc44078da3ff201758` runs the real Kickbacks VS Code extension against mocked VS Code and simulated coding activity; latest meaningful project commit `54490d37f6b41af7271b934b8d8d376a2cf2dfbe` on `2026-08-18` tunes the harness traffic model.
- Found no newer meaningful activity for existing tracked projects beyond their current `last_touched` dates.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored the public Markdown/agent-guide/404/edge-content work across Control+s, deadsimpleRSS, RapidRecap, and Anouar.ca, upstream Ghostty work, OpenOutposts snapshots and `OpenOutposts-private` activity, generated/dependency-only changes, vault syncs, repository housekeeping, and automated background-agent activity.

## 2026-08-26

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-24` → `2026-08-25`).
- Control+s evidence: active external email-access invites can now be edited in place, including expiry and feedback/download permissions, with audit logging and tests, commit `422f95219c1f50d563d7f8a82473852d7faa9b95`.
- Found no new clearly intentional standalone Hankyone project to add. Left `resume-visualizer-cloud` untracked because its August 25 commit `46f837404a85c32b9412b2a81deea907c9b63b38` is workspace cleanup and dependency churn rather than meaningful project development; `ShadeSec-dot-com2` remains ambiguous.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored the synchronized public Markdown, agent-guide, and 404 campaign across Control+s, deadsimpleRSS, RapidRecap, Anouar.ca, and ShadeSec-dot-com2, plus Obsyone vault syncs and Project Radar edits.

## 2026-08-25

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-20` → `2026-08-24`), Canary Grid (`2026-08-19` → `2026-08-24`), and RapidRecap (`2026-08-17` → `2026-08-24`).
- Control+s evidence: demo replay completion now waits for expected assessment writes instead of trusting a recorded terminal timer, commit `3c8b251b49670bba27687eb4a7d72ef3cb8f0e44`.
- Canary Grid evidence: added AnyRouter planting, router touch attribution, stronger token redaction, and a safe operator CLI, commit `df05d0c21354c90d0a2c97240d4bf95d18aee95e`.
- RapidRecap evidence: ordinary search selection now opens the video without spending a recap credit; only the explicit Zap starts generation, commit `7073b1c697853754041d87d06694c83ec57c9fa3`. Ignored later commit `eceb948d9034209c35bb11ccb5e69737125c5622` as agent-skill and launch/promo workspace material rather than core product work.
- Found no new clearly intentional standalone Hankyone project to add, and no Hankyone repository was created on or after `2026-08-21`. Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, OpenOutposts snapshots, upstream/fork work, generated/dependency-only changes, repository housekeeping, and previously rejected ambiguous candidates.

## 2026-08-24

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-22` → `2026-08-23`).
- deadsimpleRSS evidence: recovered mobile sidebar swipes after interrupted or swallowed touch-end events by clearing stale touch sessions, commit `b21e1733a816f2b57e2656ad45d3e12efe978eaf`.
- Found no new clearly intentional standalone Hankyone project to add. Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, known automated-agent commits, upstream/fork work, generated/dependency-only changes, repository housekeeping, and previously rejected ambiguous candidates.

## 2026-08-22

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-20` → `2026-08-22`).
- deadsimpleRSS evidence: rewrote Nitter media-proxy URLs to direct Twitter image/video CDN URLs throughout feed parsing and article rendering, with regression tests, commit `c451f4c1885a9cdd95741aa3699312d05094ff85`.
- Found no new clearly intentional standalone Hankyone project to add. Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, known automated-agent commits, upstream/fork work, generated/dependency-only changes, repository housekeeping, and previously rejected ambiguous candidates.

## 2026-08-21

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-19` → `2026-08-20`), deadsimpleRSS (`2026-08-14` → `2026-08-20`), and Daily Budget (`2026-08-19` → `2026-08-20`).
- Control+s evidence: fixed inspector drawer height collapse and full-height stacked-surface behavior, commit `bb7c52dc7d183587a3f928bd728c98c198cb1bb5`.
- deadsimpleRSS evidence: OPML imports now retain public feed URLs across initial fetch failures, with Reddit rate-slot and 5xx recovery handling, commit `28e57cf202975ef7cc6ebebdda34dd5a505616bf`.
- Daily Budget evidence: completed release-one behavior with entry pause/dates, breakdown modes, settings, local backup, and onboarding starters, commit `9b1a7f3453e09be8c7ef30509b0868955c0357a5`.
- Added Build League from `Hankyone/builder-comp` after substantive live match/token-board and Cloudflare deployment work, commit `9d1d36987ad9bfc399b5d2b33a3bf9e118eb01ea`.
- Added Monologue MCP Proxy from `Hankyone/monologue-mcp-proxy` after confirming a working Cloudflare MCP/OAuth proxy, commit `6f908686c6cec658127fa46ab4297c5da7f87dcb`.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored OpenOutposts snapshots and activity from `OpenOutposts-private`, Obsyone vault syncs, upstream/fork work, generated/dependency-only changes, and automated background-agent activity.

## 2026-08-20

- Added Daily Budget after confirming `Hankyone/DailyBudgetApp` and its local-first MVP for turning income and recurring costs into a daily spendable amount; latest meaningful commit `6c22c6d0a81ae97f3583fa2062f4b4a4ede613d2` on `2026-08-19`.
- Found no newer meaningful activity for existing tracked projects beyond their current `last_touched` dates.
- Left `builder-comp` untracked as an ambiguous candidate: it currently contains a single AI Build League partner-brief commit `6111381f988bcfe7f8862583b26b8a5c1f8e3b54` without enough evidence of an ongoing project.
- Excluded `bb-custom` and `bb-customizations` as fork/customization support repositories, plus snapshot, upstream, SEO/crawl metadata, vault-sync, and automated background-agent activity.
- Left existing project summaries, statuses, tags, and links unchanged.

## 2026-08-19

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-10` → `2026-08-19`), Canary Grid (`2026-08-10` → `2026-08-19`), deadsimpleRSS (`2026-08-10` → `2026-08-14`), RapidRecap (`2026-08-10` → `2026-08-17`), and ListenToMe (`2026-08-11` → `2026-08-13`).
- Control+s evidence: substantial report-generation, billing-flow, evidence-handling, and PDF work on August 19; latest meaningful commit `cffbc8ed0ac86ce7ccd8d85fcd1e3f1423e6e94f`.
- Canary Grid evidence: OrcaRouter planting/dispatch campaigns, model coverage, backend campaign operations, and monitoring/UI work through August 19; latest meaningful commit `9b1e7eecd6721045de9b3cf1363f456182a246cc`.
- deadsimpleRSS evidence: mobile sidebar gesture fixes, unread-count behavior, Reddit feed handling, and stale-update protection through August 14; latest meaningful commit `4b711101f1ab4e794e112e75c5f7c4e894366062`.
- RapidRecap evidence: mobile search and direct pasted-URL recap flow fixes through August 17; latest meaningful commit `8c8b5c4d0b1f814ee6a86dfcdda7b4ce3bde533e`.
- ListenToMe evidence: transcription-take reliability, latency tracing, overlay behavior, and update UI work through August 13; latest meaningful project commit `393506f41bc8566e2419512d00e0c2d257eb9efb`.
- Found no new clearly intentional standalone Hankyone project to add. `ShadeSec-dot-com2` remains ambiguous because multiple ShadeSec website repositories exist and no canonical mapping is established.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, generated/dependency-only changes, repository housekeeping, upstream-only work, SEO/legal maintenance, and automated background-agent activity.

## 2026-08-11

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-08` → `2026-08-10`), Canary Grid (`2026-07-05` → `2026-08-10`), deadsimpleRSS (`2026-08-09` → `2026-08-10`), RapidRecap (`2026-08-08` → `2026-08-10`), and ListenToMe (`2026-08-02` → `2026-08-11`).
- Control+s evidence: editable report names, clearer ISO report choices, safer one-use report downloads, and filename handling, commit `78ddf2d18caa39c639b52c1629af55d2b08a18fc`.
- Canary Grid evidence: production HTTP/AWS/DNS/OpenRouter canary workflows plus secret-safe agent operations and receiver hardening, commit `73a4574534a1da7b8069ec7a058ed7535c7a9ba0`.
- deadsimpleRSS evidence: browser-offline detection now drives the disconnected badge even when the Convex WebSocket still appears connected, commit `78967c0258dc61a20ae4de13b666dce1cdff1e03`.
- RapidRecap evidence: paste/search results can start a recap directly and upload age is labeled clearly, commit `70253730a07a13b89093815fef017d74b22de84e`.
- ListenToMe evidence: validated regional language hints, bounded window sizing, and shorter user-facing API errors, commit `77e60b4d74f3597435bf94ff234f1d82c238381f`.
- Found no new clearly intentional standalone Hankyone project to add. Excluded the synchronized late-August-10 Cursor commit wave across stale repositories as background-agent activity, including candidates in Disconnected Browser, TooManyProjects, Quorum, ShadeSec CIP, RapidScope, PRHub, Wi-Fi Boost, and the sensor project.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored dependency-only changes, repository housekeeping, generated files, upstream Ghostty work, Project Radar edits, OpenOutposts snapshots, and peripheral analytics/metadata changes.

## 2026-08-10

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-08` → `2026-08-09`) and Anouar.ca (`2026-08-08` → `2026-08-09`).
- deadsimpleRSS evidence: reworked auth session authority and reconnect behavior so valid sessions survive transient Convex failures and tab restores, commit `8222caf259068f06bae50949ea874dd6fde026f0`.
- Anouar.ca evidence: added CanaryGrid’s public landing-page link and project metadata to the personal site, commit `d71ae5e5cfb87102e7f50e1db151eca30aa060cc`; the later copy-only commit `94ba63248db0b255c0a6965c202a3d736ea5382c` did not independently drive the date.
- Found no new clearly intentional standalone Hankyone project to add. `OpenOutposts-private` is related to an already tracked project rather than a separate project, and `ShadeSec-dot-com2` remains ambiguous because multiple ShadeSec website repositories exist.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, upstream Ghostty commits and merges, OpenOutposts snapshot/release housekeeping, Obsyone vault syncs, automated `background-agents` activity, generated files, dependency-only changes, and peripheral copy-only changes.

## 2026-08-09

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-05` → `2026-08-08`), deadsimpleRSS (`2026-08-06` → `2026-08-08`), RapidRecap (`2026-07-31` → `2026-08-08`), Ghostty Pro Plus Ultra (`2026-08-07` → `2026-08-08`), and Anouar.ca (`2026-07-20` → `2026-08-08`).
- Control+s evidence: legacy reports now infer and expose their framework scope, commit `c8b7640491dbfe349de590fdc5576438049762bb`.
- deadsimpleRSS evidence: mapped a frozen DataBreaches FeedBurner subscription to its live WordPress feed with tests, commit `66047e7ee1fd5b02081027dc5b543ea094e4e700`.
- RapidRecap evidence: fixed Worker-first routing so API and video routes no longer fall through SPA asset handling, commit `989952b669f1982f25021dbb35426702c7e5b9fb`; excluded the preceding search-indexing commit as SEO work.
- Ghostty evidence: restored the local macOS SDK shim required for fork release builds under Xcode 27, commit `ff47ed417740cc76cd514c4628a41d94261ea5bd`; ignored later upstream commits and merges.
- Anouar.ca evidence: intentionally removed ExTweets from the site project list and replaced/tuned the CanaryGrid project mark, commit `30edefc735a427c44f2e2c514765a8dd9dd87896`.
- Found no new clearly intentional standalone Hankyone project to add. Left `ShadeSec-dot-com2` untracked because multiple ShadeSec website repositories make the canonical project mapping ambiguous.
- Left existing project summaries, statuses, tags, and links unchanged. Ignored Project Radar edits, Obsyone vault syncs, OpenOutposts snapshots/release housekeeping, upstream-only work, SEO-only work, generated files, and dependency-only changes.

## 2026-08-08

- Synced `last_touched` from newer meaningful GitHub activity: RX1 Stack (`2026-07-05` → `2026-08-07`).
- RX1 Stack mapping verified to `Hankyone/RX1-Robot` from its README and prior tracker history; evidence: servo torque-state verification, motion-stop behavior, right-hand bus corrections, and console status/event work, commit `f026c66c458e60e7162df949cd678a683546a151`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream Ghostty activity, Obsyone vault-sync activity, OpenOutposts release/snapshot housekeeping, dependency-only changes, generated files, and Project Radar edits.

## 2026-08-07

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-04` → `2026-08-06`) and Ghostty Pro Plus Ultra (`2026-08-01` → `2026-08-07`).
- Corrected VisionDJ from `2026-06-11` to `2026-06-12` after verifying substantial June 12 work in its exact repository.
- deadsimpleRSS evidence: feed-fetch pipeline improvements, HTTPS migration handling, and feedback RSS, commit `27d82a33b6785f9f6d50ae90bc8f5fe1d9edec31`.
- Ghostty evidence: fork-specific keeper cleanup and surface-release fixes, commit `0e5bbf5670fcb7087e642334fb79ecd4ad248246`; sidebar compatibility follow-up `bb50145174ad1254277a0ce93c3b0a64aa3fd3d8`.
- VisionDJ evidence: conversation feed, host whisper endpoint, audible-change enforcement, and cadence changes, commit `2c3efea840cd13212de472f0de276cfaf7d320f6`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`; excluded `ai-marketplace-monitor` because its README and history identify it as an upstream-style BoPeng project copy.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream Ghostty merges and commits, OpenOutposts snapshot/release housekeeping, SEO/legal maintenance, generated files, dependency-only changes, and Project Radar edits.

## 2026-08-06

- Synced `last_touched` from newer meaningful GitHub activity: Control+s (`2026-08-01` → `2026-08-05`).
- Control+s evidence: added on-demand evidence-image inspection for Flue agents, commit `45c0491a5ee04e300ffc9d7363ece99c56001bda`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Left OpenOutposts at `2026-08-04`; its August 6 commits only published snapshots, adjusted secret-scanner/package configuration, and shortened README copy.
- Ignored upstream-only Ghostty and Maccy activity, generated files, dependency-only changes, repository housekeeping, and Project Radar edits.

## 2026-08-05

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-03` → `2026-08-04`) and OpenOutposts (`2026-08-01` → `2026-08-04`).
- deadsimpleRSS evidence: authentication recovery, dormancy reconciliation, and verified-feed migration work, latest commit `b887edda2f027c4aa45f6f9b997b0cb698f4013a`.
- OpenOutposts evidence: project-specific authentication and encryption identity corrections, commit `ab49967a8a6e1612061fdbe5f4cecaa527cea5ae`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored non-default-ref pushes, upstream merges, tests-only follow-up commits, repository housekeeping, and Project Radar edits.

## 2026-08-04

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-08-01` → `2026-08-03`).
- Evidence: fixed verified feed ingestion and alternate-feed discovery, commit `3813aa2715eb5c8d6aef150ad39078519b6c20ed`.
- Ignored the duplicate-subscription merge because it was reverted, plus dependency-only changes, generated files, repository housekeeping, upstream merges, SEO/legal maintenance, automated background-agent work, and Project Radar edits.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.

## 2026-08-03

- Added ListenToMe after confirming the native macOS dictation app, documented GPT Live Transcribe workflow, and initial release commit `3a25feaa79109715833167516300d086f7623c0e`.
- Found no newer meaningful activity for existing tracked projects beyond their current `last_touched` dates.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored Sentry/build plumbing, repository housekeeping, upstream-only activity, automated `background-agents` activity, and Project Radar edits.

## 2026-08-02

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS (`2026-07-26` → `2026-08-01`).
- Evidence: filter-suggestion prompt redesign and measured model-routing changes, latest meaningful commit `9951907331f51e9c49a5fb6846bf866179af03b4`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored Sentry/build plumbing, repository housekeeping, upstream-only activity, automated `background-agents` activity, and Project Radar edits.

## 2026-08-01

- Synced `last_touched` from newer meaningful GitHub activity: Control+s, RapidRecap, Ghostty Pro Plus Ultra, and OpenOutposts.
- Control+s evidence: restored model reasoning metadata and effort handling for Flue, commit `4ed86a2a677542c8666b9f13be3aeecb71854aee`.
- RapidRecap evidence: moved MCP recap creation onto the site’s shared recap and credit-spending services, commit `76e87079b495f10b651704cd9075d48f81191cd3`.
- Ghostty evidence: keeper redraw, quit behavior, and release-signing fixes, latest meaningful commit `85728bc2aaa4788b3471c5afc9923e6154c0c6e8`.
- OpenOutposts evidence: persistent agent transcripts, bounded session records, actual session deletion, signed worker self-updates, and model-effort validation, latest commit `14a1ffdeddfd283d02be4edf469d64d4a12a8581`.
- Added Disconnected Browser after confirming its working custom-tab Chrome extension and live-component recipe model, repository commit `08ab3546a42b4b04e981865587433b6d590c2955`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream Ghostty commits, generated files, dependency-only changes, repository housekeeping, automated `background-agents` activity, and Project Radar edits.

## 2026-07-31

- Removed FrancePlan from tracked projects at user request.
- Synced `last_touched` from newer meaningful GitHub activity: Ghostty Pro Plus Ultra and OpenOutposts.
- Ghostty evidence: transcript-derived agent state and tool-status work, latest commit `14b054cfdd82c562439f61a3c5030564fd9b4551`.
- OpenOutposts evidence: runner-to-Homestead architecture rename across protocol, services, storage, infrastructure, docs, and UI, commit `e13d2b8701053406e754c86c0d45f043732a8c07`.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream merges, automated `background-agents` activity, Obsyone vault-sync commits, repository housekeeping, and Project Radar edits.

## 2026-07-30

- Synced `last_touched` from newer meaningful GitHub activity: RapidRecap and OpenOutposts.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream-only Ghostty activity, repository housekeeping, generated files, and Project Radar edits.

## 2026-07-28

- Synced `last_touched` from newer meaningful GitHub activity: OpenOutposts.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored RapidRecap SEO/search maintenance, the deadsimpleRSS promo workspace, automated harness maintenance, generated files, dependency-only changes, repository housekeeping, and Project Radar edits.

## 2026-07-27

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS, RapidRecap, BLEUnlock Pro Plus Ultra, and Anouar.ca.
- Corrected false-positive updates: restored ExTweets to `2026-07-03` because its July 20 SEO/legal-page maintenance commit was not intentional project work, and restored Fusion Compliance Engine to `2026-07-05` because its mapped repository has no newer meaningful commit.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, dependency-only changes, repository housekeeping, upstream-only activity, and Project Radar edits.

## 2026-07-26

- Synced `last_touched` from newer meaningful GitHub activity: OpenOutposts.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, repository housekeeping, upstream-only activity, and Project Radar edits.

## 2026-07-25

- Synced `last_touched` from newer meaningful GitHub activity: OpenOutposts.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, repository housekeeping, upstream-only activity, and Project Radar edits.

## 2026-07-24

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, repository housekeeping, upstream-only activity, and Project Radar edits.