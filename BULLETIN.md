**Radio Station (SO-00001), public copy.** This file is always the current bulletin. Read it before every work block. Updated by the Regional Operations Control Manager within minutes of any change and at least every 10 hours. Sam gives orders to the Regional manager directly; they appear under SAM ORDERS. Report up with a RESTOCK CARD to Sam or your platform's District Operations Control Manager. The law: SO-00001.md in this repository.

## SAM ORDERS
- **10 Nov 2026, SO-01, the approving-officer merge order (Sam's words):** "You have my permission to make merges for Samuel Russell as approving Officer." North Star may merge a PR without Sam naming it once the automatic tests are green on the current head, CodeRabbit has reviewed that head with valid findings fixed or answered, and the PR is mergeable. Product decisions flagged in a briefing, and hosting settings, DNS, secrets or branch protection (SO-03), still wait for Sam.
- **11 Nov 2026, SO-01 PR size (Sam's words):** "Make the PRs 5 times larger than usual to keep up w code rabbits slower amount of scans."
- **10 Nov 2026, SO-03A, one agent per branch (Sam: "Do it"):** one agent per branch; claim on the private branch-claims issue (K1927) before pushing to another agent's branch; fresh fetch, fast-forward only, no force-push.
- **3–4 Nov 2026, SO-29 (Sam's words):** "used code rabbit to make fixes before merging always" and "Fix blocking only". 15 Nov: SO-30 added (the canon body may not be retyped; changes ride as comments on the private canon, K943).
- **5 Nov 2026, 10:19 ET, instruct all:** the 00 Architects open-source expedition (5–8 Nov), read-only scouting, items accepted only above 17.8 of 20, hourly returns to the private Inbox, no installs, merges or deploys. The event window has closed; its parts list is the Black Friday parts-list docs PR K4920.
- The orders of 18 Oct (SO-00001 to SO-00004, the description-always law, SO-000 the plain-English rule) stand as written in Bulletin 6.

# Bulletin 8, Thursday 26 Nov 2026, 15:27 Eastern
Code repo: last merge was the physician-tools PR K38950 (26 Nov). Docs repo: last merge was the stranded-team-records PR K5740 (21 Nov). Any Bulletin 6 line that conflicts with this one is void. The Bulletin 7 (15:14 ET) HOLD on the test pipeline still stands.

## CENTER OF GRAVITY
Automated workflows Sam programs once by voice (SO-00002), unchanged. Practical gravity this week: a working test pipeline, because every automatic check on both repos fails to start. Council: Perplexity voted 15:24 ET for NOW 1 (restore the test pipeline); ChatGPT's vote, relayed 15:23 ET, is dated 18 Oct (workflows, appointment-sequence text) and predates the outage. No dissent on NOW 1. Sam override: none.

## NOW (ranked)
1. **Get the test pipeline running again.** Goal: GitHub Actions starts jobs again on both repos; the last 100 runs on each failed at startup with zero jobs (seen since at least 9 Nov; the latest code-repo run says it "likely failed because of a workflow file issue"). Owner: North Star (Claude Code room) reads one failed run's notes and the workflow files; if the cause is billing or an account limit, it becomes Sam's money item. Done when: one run on each repo's main branch finishes with jobs. Velocity: not started. **HOLD below.**
2. **Main-to-clone reconciliation (the reconciliation issue K33415).** Goal: fixes on the code repo's main branch land safely in the newest clone without a wholesale merge. Owner: the ChatGPT reconciliation room (cards of 9 Nov). PRs: the CSS-fix PR K33620, the history-preserving draft PR K33661, and PR K33128. Done when: the CSS-fix and history-preserving PRs each have a full-checkout test run and a CodeRabbit review on the final head. Velocity: stalled since 9 Nov (blocked by lane 1).
3. **Face sign-in on the live site.** Goal: Sam signs in with Face ID or Touch ID. Owner: Sam, for two hosting settings and one database migration; any room opens a docs PR for the face-sign-in room's branch. Done when: the passkey status check reports enabled and Sam says "face registered". Velocity: ready, waiting on Sam (26 Nov).
4. **Release 1.1 (the Release 1.1 PR K37925).** Goal: the partner data feed leads with the lived 5-year look-back, and the site's search-engine file announces the Mortgage Killer page list. Owner: North Star. Done when: tests green on head, then merged under SO-01. Velocity: reviews green (CodeRabbit, Greptile); waiting on lane 1.
5. **Ground clearing.** Goal: 36 open code PRs (most are drafts from 3–20 Nov) and docs PRs K4674, K4920 and K5863 sorted into LAND, CLOSE, KEEP. Owner: North Star posts the list on the private Inbox. Done when: the list is posted. Velocity: not started.

## ASSIGNMENTS
- **North Star (Claude Code):** lanes 1, 4 and 5; check the live-build audit docs PR K5863 (its description claims a 57-file merge, but GitHub shows 0 changed files).
- **ChatGPT reconciliation room:** lane 2; acknowledge on the reconciliation issue K33415.
- **Claude Nous / face-sign-in room:** open the docs PR for its branch (SO-01 lets North Star land docs).
- **Alfred (Regional Manager seat, other platform) and TED:** keep the SLOOS notes; post Drive links. Alfred's "Sam merges" line is superseded by SO-01.
- **Grok, Gemini and Perplexity rooms:** 30 tasks from the 1 Nov cross-platform task batch (XPLAT batch A) remain unacknowledged with no return ZIP (9 Nov checkpoint). Each room picks them up or marks them DROP by the next bulletin.
- **The Perplexity citation-corrections room (PR K29356, the last Perplexity branch, 31 Oct):** acknowledge the Perplexity packet (R11, R09) on dispatch issue K4141 with your session id and starting point, or post DROP; read-and-cite work, ZIP to the Perplexity intake folder in Drive, PR only after NOW 1 is green.
- **The Perplexity public-guides room:** post a card confirming the weekly guides automation is kept or paused.
- **ChatGPT Liaison:** send a current (26 Nov) report; the 15:23 ET relay carried an 18 Oct report. The Nova follow-up (PR K23534) is merged code; no client message sending is authorized or verified.

## PARTS BIN
Not read this run: Drive access failed with an authorization error. Last verified link from a room: the ChatGPT evidence ZIP of 9 Nov in the Parts Bin folder in Drive. Rooms without a Drive link this cycle: Alfred, Brain Hub, and the Nous / face-sign-in room (branch only, which is acceptable for docs).

## STOP (nobody touches)
- Merges: North Star only, under SO-01 (green tests on head, CodeRabbit reviewed, mergeable). **While the tests cannot start (lane 1), they are not green, so no SO-01 merges; a merge needs Sam's explicit word for that PR.** All other rooms: no merges.
- Hosting settings, DNS, domains, secrets, branch protection: Sam only. No key lane is named in Bulletin 7.
- No Chinese-origin AI models (note: Nous Hermes models built on Qwen3 or Seed-OSS count). No sample figures on empty profiles.
- Gamified pages stay off except the income-engine game. Skywalker stays disabled.
- Call Desk scripts stay drafts until professional sign-off. Sensitive (rank R) workflows wait for Sam plus professional review.
- R30 and R31 stay cancelled: no 500,000-scenario or Fibonacci runs, no paid credit spend.
- One agent per branch (SO-03A). No force-push.
- No download-click files from Perplexity sessions. No PR or standing-order number without its purpose and impact.

## DONE SINCE LAST (do not redo)
- The Nova follow-up PR K23534, the coding-session restock PR K23575 and the public guides PR K23616 merged; the Radio Station docs PR K2788 merged.
- The physician-tools PR K38950 merged 26 Nov (physician tools; savings tool moved out of the refinance engine; Sam approved).
- The stranded-team-records docs PR K5740 merged 21 Nov (team records rescued from five branches).
- In the clone: the MCP key-headers PR K30791 and PR K29602 merged; PRs K29438 and K33456 closed unmerged.
- The Nous Portal MCP record and the face sign-in findings are committed on the face-sign-in room's branch.

## SAM DECIDES
**HOLD 15:14 ET: the test pipeline is down on both repos.** (1) Every automatic check on the code repo and the docs repo now fails before it starts, so no tests run on any change. (2) Before, each change ran the full test suite and showed green or red. (3) Without it the site can receive a change that breaks a page and nobody sees it until a visitor does. (4) Clients are protected only by the review bots, which read code but do not run it. (5) Sam's merge permission to North Star depends on green tests, so merging is effectively frozen. (6) The usual cause when every workflow fails at once is a GitHub Actions billing or spending limit, a money item only Sam can change; the risk of waiting is a growing pile of unmerged work. (7) Not fixed; North Star is assigned to confirm the cause. (8) Sam says "check Actions billing myself", "North Star diagnose and report", or "merge on review bots only until tests are back".

**Release 1.1 (the Release 1.1 PR K37925).** (1) The partner data feed will lead with the real 5-year track record (11.51%) and label the higher figure as back-tested; search engines get told about the Mortgage Killer page list. (2) Before, the feed led with the back-tested number, and the 126 Mortgage Killer pages were live but unannounced. (3) The site stops implying a back-test is a lived record and gets those pages found. (4) Clients and partners see honest, labelled numbers. (5) It lowers Sam's compliance exposure on performance claims. (6) Three files, low risk; one search description still needs advertising review. (7) Tested locally and passed both review bots; not live; the automatic tests could not run. (8) Sam says "merge the Release 1.1 PR" or "wait for tests".

**The live-build audit docs PR K5863.** (1) It claims to bring dozens of menu hubs, a navigation tree and a deploy setup into the docs repo. (2) Before, those lived only in the separate app repo. (3) Its audit says the public site is frozen on a June build because deployments are blocked, which conflicts with the 26 Nov hosting findings from another room. (4) Clients are unaffected until the hosting question is settled. (5) It matters to Sam because two rooms describe different hosts for the same live site. (6) GitHub shows zero changed files, so merging would do nothing; the risk is believing it did. (7) Not live, not tested. (8) Sam says "North Star reconcile the audit PR with the hosting record" or "close the audit PR".

**Face sign-in settings (Claude room, 26 Nov).** (1) Two hosting settings turn on Face ID or Touch ID sign-in. (2) Today the feature is built but switched off. (3) The site gets a stronger, faster owner sign-in. (4) Later, clients can use it too. (5) Sam stops typing passwords. (6) Hosting change, Sam only; a database migration must be applied first. (7) Built and deployed, waiting on the settings. (8) Sam says "set the face sign-in values done" after setting them, and "apply the migration" or confirms it is applied. Also from that room: Sam says which model Hermes runs, and "build the Nous client-credentials path" or "not now".

**Weekly public guides automation:** still active, next run 30 Nov. The 18 Oct HOLD is stale; Sam says "keep guides running" or "pause guides".

## LAND OR DROP (older than 48 hours)
- Docs drafts K4674 (draft, 20 Nov) and K4920 (Black Friday parts list, 20 Nov): LAND the parts list on North Star's review; KEEP K4674.
- Code drafts from 28 Oct to 10 Nov (K27511, K27552, K31816, K32144, K32267, K32513, K32677, K33579): North Star proposes CLOSE or KEEP in lane 5.
- The nested-workflow-architect skill branch (3 Nov): LAND as a docs PR.

## SAFE TO DELETE
Rooms: the Perplexity manager-builder session, Claude nested-workflow spec (3 Nov), ChatGPT reconciliation (9 Nov), Claude Nous / face sign-in (26 Nov), Alfred 3 Nov session, Thomas runtime room (28 Oct). Not safe: Brain Hub (it watches issue K31037).

## INBOX LOG
Read since Bulletin 6: 33 cards on the private Inbox (18 Oct to 26 Nov), private canon changes (SO-29, SO-03A, SO-01 twice, SO-30), and the instruct-all order of 5 Nov. Since Bulletin 7: VIA LIAISON ChatGPT (15:23 ET, carries an 18 Oct report, flagged stale), DISTRICT REPORT Perplexity (15:24 ET, vote for NOW 1). Flagged stale: the ChatGPT Liaison relay; the Perplexity v5.x packages, Skywalker, full-backup and Call Desk drafts rooms (no card since 15 Oct); 30 cross-platform tasks with no acknowledgement; the Grok handoff (18 Oct) with no reply. Flagged conflicting: hosting of the live site (the audit PR versus the hosting record); Alfred's "Sam merges" versus SO-01.

## RADIO CARD (paste into any room)
RADIO, Bulletin 8, 26 Nov 15:27 ET. Center of gravity unchanged: workflows Sam programs by voice. Top problem: automatic tests on both repos fail before starting, so no change is tested. Until they run again, nobody merges without Sam's word for that change. NOW: 1 restore the test pipeline; 2 move main-branch fixes into the newest clone safely; 3 face sign-in on the live site (waiting on Sam's hosting settings); 4 the honest-numbers partner feed release; 5 sort the open change list into land, close, keep. Rules: one agent per branch, no force-push; review bot before every merge; no Chinese-origin models; no paid scenario runs; restock card every 30 minutes with a Drive link. Anything not in NOW: pause and post a restock card.
