# Changelog

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

## 2026-07-23

- Synced `last_touched` from newer meaningful GitHub activity: deadsimpleRSS.
- Added OpenOutposts after confirming the active coding-agent control plane and outpost execution architecture.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, repository housekeeping, upstream-only activity, and Project Radar edits.

## 2026-07-21

- Synced `last_touched` from newer meaningful GitHub activity: RapidRecap and PDF Corpus Redaction.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated assets, repository housekeeping, upstream-only Ghostty activity, and Project Radar edits.

## 2026-07-20

- Synced `last_touched` from newer meaningful GitHub activity: Control+s, deadsimpleRSS, RapidRecap, and PDF Corpus Redaction.
- Added FrancePlan after confirming the wedding planning app and its initial implementation.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored generated files, repository housekeeping, Project Radar edits, and RX1-Robot activity already covered by RX1 Stack's current date.

## 2026-07-18

- Synced `last_touched` from newer meaningful GitHub activity: Control+s, RapidRecap, PDF Corpus Redaction, and Anouar.ca.
- Found no new clearly intentional Hankyone projects missing from `projects.json`.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored upstream-only Ghostty merges and Project Radar repository edits as evidence for project activity.

## 2026-07-17

- Synced `last_touched` from newer meaningful GitHub activity: Control+s.
- Found no newly created Hankyone repositories since the previous sync.
- Left existing project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-16

- Added PDF Corpus Redaction after confirming `Hankyone/PDF-Corpus-Redaction`.
- Set status to building and `last_touched` to `2026-07-16` from current repo activity.

## 2026-07-14

- Synced `last_touched` from newer meaningful GitHub activity: Control+s.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-13

- Synced `last_touched` from newer meaningful GitHub activity: Control+s, RapidRecap, Ghostty Pro Plus Ultra, and Anouar.ca.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-12

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-11

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s and Ghostty Pro Plus Ultra.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-10

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s, deadsimpleRSS, and Ghostty Pro Plus Ultra.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-09

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-08

- Follow-up sync from newer meaningful GitHub activity: Control+s, Ghostty Pro Plus Ultra, and Maccy Pro Plus Ultra.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-08

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s, Ghostty Pro Plus Ultra, and Hearabouts.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-07

- Synced `last_touched` dates from newer meaningful GitHub activity: deadsimpleRSS, Ghostty Pro Plus Ultra, and Hearabouts.
- Left project summaries, statuses, tags, and links unchanged.
- Ignored Project Radar repository edits as evidence for other project activity.

## 2026-07-05

- Synced `last_touched` dates from newer meaningful GitHub activity: Project Radar, Canary Grid, RX1 Stack, Hearabouts, and Fusion Compliance Engine.
- Left project summaries, statuses, tags, and links unchanged.

## 2026-07-04

- Synced `last_touched` dates from newer meaningful GitHub activity: Control+s and deadsimpleRSS.
- Left project summaries, statuses, tags, and links unchanged.

## 2026-07-03

- Synced `last_touched` dates from newer meaningful GitHub activity: Project Radar, Control+s, RX1 Stack, RapidRecap, Too Many Projects Chrome Extension, Ghostty Pro Plus Ultra, ExTweets, Fusion Compliance Engine, Mech-Interp-Lab, and Maccy Pro Plus Ultra.
- Left project summaries, statuses, tags, and links unchanged.
- Corrected Project Radar domain references to `projects.anouar.ca`.
- Renamed NearTalk to Hearabouts and updated its `last_touched` date to reflect recent development.
- Rolled back OptimalEats `last_touched` to `2026-06-01`; the July GitHub activity was not meaningful project work.

## 2026-07-02

- Synced `last_touched` dates from GitHub activity: Project Radar, Control+s, Canary Grid, deadsimpleRSS, and OptimalEats.
- Left project summaries, statuses, tags, and links unchanged.

## 2026-07-01

- Added FloorPlanMagic (renovation scope platform, deployed at floorplan.anouar.ca).
- Added Scoping Estimation Tool (renovation scope compiler spec).
- Added ShadeSec CIP (cyber intelligence platform for security industry market signals).
- Removed URL from Luma RSS description.

## 2026-06-29

- Created public `project-radar` repository.
- Expanded README with update model and public-safety rules.
- Reset `projects.json` to a minimal approved state before repository-based seeding.
- Started GitHub activity discovery for candidate project entries.
- Added `CNAME` for `projects.anouar.ca`.
- Added `.nojekyll` and a minimal static dashboard page.
- Simplified schema to lifecycle status, last touched date, one-line summary, tags, and optional public links.
- Seeded the first approved public project list from user classification.
- Added 16 missing projects discovered by scanning home directory, Documents, and Codex folders: Fusion Compliance Engine, VisionDJ, Mech-Interp-Lab, ShadeSec SkillCheck, OptimalEats, Blurred Pro Plus Ultra, EMG-MyoWare Experiments, WhatsInTheBackground, Polymarket Leaderboard Archiver, CISSP Practice App, Quorum, GhostOperator, ScraperReverser, Fourier2Chirp, WindowAgent, TapAndCert.
- Merged `quorum-backtester` into the new `quorum` entry (backtester is a component of the broader Quorum platform).
- Updated 20 project descriptions against source code: NearTalk, Capital Flow Tool, NewGame, Maccy PPU, Ghostty PPU, MacDown PPU, BLEUnlock PPU, RapidScope, Wi-Fi Boost, WindowVision, slop2prod, Waitless/NoHoldBot, ShadowAI Monitor, PRHub, OpenMicForm, DroneTO-311, SimpleDocket, Realtime Voice Agent.
- Removed "public" framing from the page, README, and projects.json; the tracker is for personal use.
- On mobile, filters now scroll horizontally on one line instead of wrapping, and the expand-all button sits in the same filter row.
- On mobile, the footer now stacks vertically instead of merging text.
