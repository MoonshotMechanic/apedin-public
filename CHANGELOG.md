# Changelog

Selected shipped milestones, written for people using apedin. This is not an exhaustive record of every patch or deployment. The website footer displays the running application version; the newest entry below should not be treated as a live version check.

Release dates below follow the existing product release records.

## 0.23.0 — 2026-10-23

- Add public pages for supported imported trader profiles, with source-specific captured activity and links back to the interactive profile drawer.
- Refresh public profile and drawer layouts and show researched connections with evidence labels and check dates.
- Keep research links separate from ownership verification, account permissions and XP. Unresolved identity leads remain unpublished; sparse profiles are excluded from search indexing.

## 0.22.4 — 2026-10-23

- Rename Prestige to Evolution across progression labels and use E 0–E 10 for avatar badges. Levels, XP and earned artwork are unchanged.

## 0.22.3 — 2026-10-22

- Replace feed-row Attention charts with counts of other currently ranked/KOL source accounts that mentioned the same token. Open the count to see each account’s latest recorded mention, time and available source links; repeated mentions count once per source account.
- Keep ticker Attention available and clarify ranked refresh coverage in Settings, filters, alerts and activity descriptions.
- Improve Ranked search and reduce database contention while retaining stored history and collection scope.

## 0.22.2 — 2026-10-22

- Reduced memory overhead for Attention history and public statistics while preserving chart observations, stored records and collection coverage.

## 0.22.1 — 2026-10-22

- Put Ranked first and keep it as the default view. Everyone opens a dedicated message panel while broad profile coverage is unavailable.
- Start Pump background engagement collection with a one-time 24-hour lookback, then retain subsequent work as it ages. Existing call history and XP awards are retained.

## 0.22.0 — 2026-10-22

- Focused background history and engagement refreshes on ranked/KOL callers while keeping live discovery active.
- Preserved existing history, XP awards, sign-up and community participation.
- Added recovery for newly ranked callers and clearer freshness and queue coverage reporting.

## 0.21.5 — 2026-10-22

- Made Ranked the default feed and preserved that preference for returning visitors.
- Marked the Everyone feed as temporarily unavailable while keeping sign-up available.
- Improved live-feed behavior during rate-limit cooldowns.

## 0.21.4 — 2026-10-22

- Added public footer links and updated the support contact details.
- Improved sign-in loading so it remains stable while account services initialise.

## 0.21.3 — 2026-10-22

- Reuse the validated release build and add a production-sized resource rehearsal before rollout. Keep fresh pre-release backups and scheduled restore checks.

## 0.21.2 — 2026-10-22

- Added the experimental Observations page, summarising caller market-cap habits and overlapping community participation from recorded calls.
- Observations refreshes daily from completed UTC days and shows its date range, sample sizes and most recent update status.

## 0.20.1 — 2026-10-20

- Refreshed browser assets so returning visitors receive the updated ticker history, mobile drawer handle and stream metrics.

## 0.20.0 — 2026-10-20

- Added experimental Attention history bars, with activity-based wording and gaps when observations are unavailable.
- Added a one-minute token ranking window.
- Added a mobile drawer handle for tap or drag-down dismissal.
- Expanded stream cards with attention, holder counts, call totals and token or trading-pair age.

## 0.19.0 — 2026-10-20

- Added landscape and portrait stream overlays, including explicit demo and unavailable-data states.
- Improved source-rank badges and text-size controls in the ultra-compact feed.
- Gave Attention labels their own space to avoid overlap with market data.

## 0.18.0 — 2026-10-20

- Added public member profile pages with individual page metadata.
- Added a member directory and sitemap for eligible profiles.
- Made public profile links usable in a new tab and without JavaScript.

## 0.17.0 — 2026-10-20

- Added signed-in token-room discussion and replies to individual calls.
- Added captured thesis histories and market snapshots for new posts, without inventing historical prices.
- Improved token identification, missing artwork and holder context.
- Clarified Attention explanations and missing-data states.

## 0.14.1 — 2026-10-19

- Released automatic prestige progression and updated weighting for qualifying external activity.
- Added brushed-copper Prestige 2 presentation and clearer profile level labels.
- Improved release-backup reliability.

## 0.10.1 — 2026-10-18

- Expanded the profile hub, source-linked histories and mobile profile layout.
- Improved evidence-based profile connections and ownership-claim handling.
- Corrected duplicate-ingestion and slow linked-history behaviour.
