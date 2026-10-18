**Radio Station (SO-00001), public copy.** This file is always the current bulletin. Read it before every work block. Updated by the Regional Operations Control Manager within minutes of any change and at least every 10 hours. Sam gives orders to the Regional manager directly; they appear under SAM ORDERS. Report up with a RESTOCK CARD to Sam or your platform's District Operations Control Manager. The law: SO-00001.md in this repository.

## SAM ORDERS
- **SO-00001, the restock law, is in force as of 18 Oct 2026 (Sam).** Every room restocks (brings all its work to the front and reports up) every 30 minutes while Sam works in it, never more than 10 hours apart. Nothing valuable stays buried; any room can be deleted at any time without loss.
- **SO-000, the plain-English rule, is enforced now (Sam).** No bare PR or SO numbers to Sam, ever. Each one gets 8 plain-English sentences: what changes, what was there, how it helps the site, the client and Sam, the cost or risk, whether it is tested and live, and what Sam should say next.
- No new INSTRUCT ALL orders since Bulletin 1.

# Bulletin 2, Sunday 18 Oct 2026, 02:31 Eastern
Code repo master (unchanged; plain-English rule merged 01:27 ET). docs repo main (unchanged). The SO-00001 files now sit on two waiting PRs, one per repo, both green.

## NOW (ranked)
1. **R1, first restock sweep (every room, every platform).** Owner: every room. Paste the session header (https://raw.githubusercontent.com/samtheinsuranceman-debug/rcs-radio-station/main/cards/SESSION_HEADER.md) into each room Sam still wants; each answers with a RESTOCK CARD in the private Inbox. Rooms Sam does not need get the RETIRE prompt, post a last card, then get deleted. Done when: every surviving room has a card logged in the private Inbox. Status: 0 cards so far.
2. **R2, one District Operations Control Manager per platform** (Claude, Grok, ChatGPT, Gemini, other; Perplexity is run by the Regional manager). Owner: Sam opens one room per platform with https://raw.githubusercontent.com/samtheinsuranceman-debug/rcs-radio-station/main/cards/DISTRICT_MANAGER.md. Done when: each posts its first District Report in the private Inbox. Status: none yet.
3. **R3, the 45 Gemini web flows (about 4 hours of Sam's dictation).** Owner: Sam supplies recordings or transcripts to the private Inbox or the Regional manager; the Regional manager ranks them. **Do not build them yet.** Done when: a ranked list appears in this bulletin.
4. **R4, three waiting PRs: Sam decides.** Nova follow-up agent (code repo), restock rule for coding sessions (code repo), Radio Station docs (docs repo). See SAM DECIDES.
5. **R5, clean-up list, read-only.** Owner: North Star. Produce a LAND / CLOSE / KEEP list for about 621 code-repo branches and the docs repo's stale PRs (see LAND OR DROP). Also sync `team/STANDING_ORDERS.md` on main so it carries the plain-English rule line that the standing-orders canon already has. Done when: the list is posted in the private Inbox. Nothing is deleted without Sam.

## STOP (nobody touches)
- No merge without Sam's explicit word (SO-01, merges need Sam). No hosting variables, DNS, domains, secrets or branch protection (SO-03, infrastructure is Sam's).
- Gamified pages stay off except the income-engine game (ruling pending). The Skywalker guide stays mounted but disabled.
- Call Desk scripts stay drafts until professional sign-off. Goldman Office voice or likeness assets wait for approved assets.
- No Chinese-origin AI models (SO-04, provider ban). No sample figures on empty profiles (SO-05, honest empty states).
- The 45 Gemini web flows: do not build them yet.
- Any lane not listed in NOW: pause and post a restock card instead of continuing.

## DONE SINCE LAST (do not redo)
- 18 Oct 02:17 ET: canon standing orders changelog for SO-00001, the restock law, posted with its 8-sentence briefing.
- 18 Oct 02:18 ET: Radio Station docs PR (docs repo) opened with the law, the manager design, Bulletin 1 and four paste cards; checks green. Do not open another.
- 18 Oct 02:18 ET: restock rule for coding sessions PR (code repo, one line in CLAUDE.md) opened; all 13 checks green. Do not open another.
- 18 Oct 01:27 ET: plain-English rule  merged into the code repo's AI instructions.
- 17 Oct: Infinite Real Estate Accumulation page and Liquidity Unlock page merged.
- 15 to 16 Oct: site audit fixes, secure-entry hardening, Patent360 removed, post-deploy smoke check.

## SAM DECIDES
- **Nova follow-up agent (code repo).** (1) It adds Nova, a clearly labelled AI assistant that an automation can use to text or email a lead or client. (2) Before, the app sent only plain templated notices with no AI sender. (3) For the site, it reuses the existing messaging rail with no new infrastructure. (4) For the client, every message says it is from an automated AI assistant and honors opt-outs. (5) For Sam, it is a follow-up channel switched on per automation. (6) Risk: it can send real texts and emails once messaging keys are set in hosting, so consent, opt-out and AI-disclosure rules matter; its own description still lacks sentence 8. (7) All 13 automated checks pass; not merged, not live; unchanged since Bulletin 1. (8) Say "merge the Nova follow-up PR" to land it or "hold Nova" to park it.
- **Restock rule for coding sessions (code repo), NEW.** (1) It adds one line to the code repo's AI instructions telling every coding session to follow the restock law, read this bulletin before each work block and report to the Inbox. (2) Before, the instructions pointed sessions at the canon issues but had no rule to surface their work or check a live priority list. (3) For the site, every Claude Code or Codex session opening the repo picks up current priorities without Sam pasting anything. (4) For the client, fewer conflicting or half-finished changes reach production. (5) For Sam, coding sessions announce what they hold and whether they are safe to delete. (6) Cost or risk: text only, no app code, but any merge to master triggers a routine production rebuild of the same app. (7) All 13 checks pass and it is mergeable; not merged, not live. (8) Say "merge the restock rule for coding sessions" to land it or "hold the restock rule" to park it.
- **Radio Station docs (docs repo), NEW.** (1) It puts the restock law, the operations manager design, Bulletin 1 and four paste cards (session header, restock card, retire prompt, district manager opener) under `team/ops/`, and adds the restock law to the standing orders file. (2) Before, no written file told rooms to surface their work, and no single place held the current priority. (3) For the site, every room works from one ranked bulletin, so less duplicated or stale work reaches the code. (4) For the client, the safety stops are repeated to every room every bulletin. (5) For Sam, any room can be deleted without loss and one INSTRUCT ALL order replaces hundreds of pastes. (6) Cost or risk: documentation only, nothing deploys; the standing orders file on main still lacks the plain-English rule line, which North Star should sync. (7) All 5 checks pass and it is mergeable; the issues are live, the files wait. (8) Say "merge the Radio Station docs" to land it or "hold the Radio Station docs" to park it.

## LAND OR DROP (older than 48 hours, docs repo)
- **Living conductor (8 Oct).** One clock and dial for page pacing. North Star: LAND, CLOSE or KEEP.
- **Three Copilot Recharts import fixes (5 Oct).** Likely superseded by later portal work; North Star to check against the code repo and recommend CLOSE or LAND.
- **22 Sep audit package .** Stale-assumption risk: the content is dated 22 Sep but the PR was updated tonight (01:18 ET). Its maps and ledgers predate a month of merges; do not plan from it until North Star confirms what still applies.
- Any ZIP or package handed over more than 48 hours ago without a PR: the room that made it flags it LANDED, RE-SEND or DROP on its first restock card.

## SAFE TO DELETE
- None yet. A room becomes safe once its card shows as LOGGED in the private Inbox.

## INBOX LOG
- Bulletin 2: the private Inbox has 0 cards. No restock cards or district reports received yet. No conflicts between rooms detected; one stale-source warning (the 22 Sep audit package).

## RADIO CARD (paste into any room that cannot read GitHub)
RADIO, Bulletin 2, 18 Oct 02:31 ET. Law SO-00001: put a RESTOCK CARD at the front of your reply now and every 30 min while Sam works with you (what you made and where, open advice with age, top 3 next actions, SAFE TO DELETE yes/no). Never give Sam a bare PR or SO number; explain each in 8 plain sentences. NOW: restock sweep (0 cards yet); one District Manager per platform; the 45 Gemini web flows wait for ranking, do not build them yet; Sam decides three waiting PRs (Nova follow-up, coding-session restock rule, Radio Station docs); North Star makes a clean-up list. STOP: no merges without Sam, no hosting/DNS/secrets, gamified pages off except income-engine, Skywalker disabled, Call Desk drafts held, no Chinese-origin AI, no sample figures on empty profiles. Do not plan from the 22 Sep audit package. Anything not in NOW: pause and restock.

