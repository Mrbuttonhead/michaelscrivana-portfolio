---
slug: stryker
url: https://stryker.michaelscrivana.com
role: Senior Manager, Communications (remote) — Stryker
posting: https://careers.stryker.com/senior-manager-communications-remote/job/8C6691205BD5C28406B55712E8541AE8
req: R570593
branch: stryker
base: origin/sanofi
worktree: ~/Documents/ms-stryker
packet: ~/Documents/Vaults/Job Search/Applications/Stryker_SrManagerCommunications
corpus: ~/Documents/Vaults/Job Search/Master/Master_Corpus.md
accent: "#8a5a00"      # deep amber — nods to Stryker's gold, 5.4:1 on the page's #f4f5f7 paper
robots: noindex, nofollow
status: packet ready, NOT submitted (2026-08-28)
---

# How this page is edited

Two writers work on `index.html`: Michael in Cursor, Claude Code from the terminal.
The rules exist so neither silently reverts the other.

1. **Every text region carries a `data-k` handle.** Claude addresses regions by
   handle, **never** by matching their prose. Reword anything you like in Cursor —
   the handles do not depend on the words.
2. **`git status` and `git diff` before editing.** Git is the arbiter of who
   changed what. Commit after each coherent change so Cursor's gutter shows it.
3. **No wholesale rewrites of `index.html`.** Targeted region edits only.
4. **Reconcile with the tool**, from either direction:

   ```sh
   node ~/Documents/ms-tools/sync.mjs check .    # drift report, exit 1 if any
   node ~/Documents/ms-tools/sync.mjs pull .     # index.html -> page.md
   node ~/Documents/ms-tools/sync.mjs push .     # page.md -> index.html
   node ~/Documents/ms-tools/sync.mjs annotate . # add handles to new elements
   ```

# Claims — what each assertion rests on

⛔ **Rule (Corpus §8.26): a third-party ranking is a citation, not a description.**
Anything of the form *"[ranking] [company]"* needs a source before it goes on the page.
"Fortune 100" was false and reached seven packets before anyone checked it.
⚠️ **This page deliberately makes no Fortune claim at all** — the CV and cover letter say
*Fortune **Global** 500* and that is the only permitted form.

⭐ **Read this before editing any communications claim.** Every executive-writing and
change-communications assertion on this page rests on **Corpus §4 / §8.28, recorded
2026-08-28** — the day the broad ask happened. Before that date the Corpus had *one line*
about communications. Eight of nine shapes came back positive and **zero particulars were
attached to any of them** (open question #15). That is why every claim below is written
as a *shape* and never as a count, a date, a named leader, a forum or a channel.

| Handle | Claim | Corpus anchor | Status |
|---|---|---|---|
| `hero.lede` | more than eight years in regulated healthcare | §8.2 settled (Bayer 7+ and Siemens 1.5) | ✅ canonical — ⛔ **never twelve**; the WPU years and the study gap are not healthcare |
| `hero.who` | Senior Designer – AI Lead | §8.7 official title | ✅ canonical |
| `hero.who` | started at Siemens building clinical diagnostic analyzers | §1 | ✅ canonical |
| `metrics.*` | 115-person organization | §8.6 settled | ✅ canonical |
| `metrics.*` | roadmap covering 1,000+ people | §4, §5 rollup | ✅ canonical |
| `metrics.*` | ~$79MM+ combined MULO+ retail sales, two launches | §2 (MiraFAST ~$38MM + MiraFIBER $41MM+), §5 rollup | ✅ canonical — phrased as traction of SKUs Michael designed, **never** personal P&L (§2 guardrail) |
| `hero.lede` | MiraFIBER launch communications >50% over projection | §2 MiraFIBER | ✅ canonical — launch-era figure |
| `metrics.*` | zero to six craft disciplines in 12 months | §5 rollup | ✅ canonical |
| `executive.block.*` | writes talking points, leader messages, speeches, scripts, briefing narratives | §4 / §8.28 (2026-08-28) | ⚠️ **shape only** — no count, no leader, no date (open Q#15) |
| `executive.block.*` | at divisional and senior-leadership level (VP+) | §4 / §8.28 | ✅ altitude confirmed |
| `executive.block.*` | selling presentations owned end to end + the template system | §2 (2026-08-26) | ⚠️ no retailer, no count, no year (open Q#13) |
| `executive.block.*` | divisional leadership and board material | §2 (2026-08-26) | ⚠️ ⛔ never "investor" or "external financial" |
| `executive.block.*` | AI roadmap carried to a Science President, Cambridge, multi-day | §4 | ✅ canonical |
| `change.block.*` | owned a change-comms program end to end (strategy, cadence, channels, audience) | §4 / §8.28 | ⚠️ shape only |
| `change.block.*` | town halls, leadership forums, internal campaigns, intranet | §4 / §8.28 | ⚠️ **no channel may be named** (open Q#15) |
| `change.block.*` | change-champion network per sub-home | §4 | ✅ canonical |
| `change.block.*` | five 90-day commitments from one leadership workshop | §4 | ✅ canonical |
| `change.block.*` | shipped into where people already work, not a new destination | §4 (Teams-native agents) | ✅ canonical |
| `events.*` | 200+ attendees, three consecutive years, three formats, one system | §2 · §8.17 | ✅ canonical — ⛔ **cite no date** (7.20.22 / 7.21.22 unresolved) |
| `events.*` | storyboards drawn and animated by his own hand | §2 · §8.18 | ✅ canonical, first-hand craft |
| `events.*` | trade-show suite, 20×30 ft, six-figure budget, consecutive years | §2 (NACDS) | ✅ canonical |
| `toolkits.block.*` | brand book digitized into the single agency-facing standard | §2 · §8.12 | ⚠️ "digitized", ⛔ never "authored the brandbook" |
| `toolkits.block.*` | 15-page visual brief, ecommerce content standards | §2 | ✅ canonical |
| `toolkits.block.*` | master-and-adaptation templates, reusable regulated-copy modules | §2 (2026-08-19) | ⚠️ no brand, no DAM, no count (open Q#10) |
| `toolkits.block.*` | co-authored the inclusive-design standard; WCAG AA; check in the QC gate | §2 · §6 | ✅ canonical — verb stays **co-authored** |
| `method.block.*` | curriculum co-authored, required, 3 sessions, 100+ marketers | §2 · §8.11 | ✅ canonical — verb stays **co-authored** |
| `method.block.*` | briefs improved → diagnosis → Brief Translator | §2 · §3 | ✅ canonical, causality confirmed |
| `method.block.*` | taught 1,000+ beginners drawing | §10.1 · §5 | ✅ understate deliberately; ⛔ never name the venue on the page |
| `method.cta.*` | ~$79MM in retail sales | §5 rollup | ✅ canonical, primary |
| `ninety.step.5` | no issues management, crisis, recall or reputation defense | §8.28 confirmed negative | ✅ **stated on purpose** |
| `sustainability.*` | all the 3D, lighting, rendering, animation, type animation — his own hand | §2 SunBird (2026-08-28) | ✅ first-hand craft; verb is **made**, not *directed* |
| `sustainability.*` | sustainability team → communications → he built it | §2 · §4 · §8.29 | ✅ canonical, the full external-comms loop |
| `sustainability.*` | ran across social and in print | §2 SunBird | ⚠️ ⛔ name no channel beyond social/print (open Q#16) |
| `sustainability.*` | worked with comms + sustainability to take the claims through legal, medical and regulatory review | §2 (upgraded 2026-08-28) | ✅ **active and collaborative** — ⛔ still never "owned the submission" or "responsible party" |
| `sustainability.*` | "first PET blister in the consumer health sector" | §8.26 · §8.29 | ⚠️ **Bayer's claim, attributed + linked to the 2024-10-30 newsroom release.** ⛔ never asserted as his |
| `sustainability.*` | −38% carbon · −78% water · −53% land · −18% weight | Bayer press release 2024-10-30 | ✅ sourced — ⚠️ **the comparator is stated on the page**, never strip it |
| `sustainability.*` | live on Bayer Global, Nov 2024, Liveo Research, Netherlands first | verified 2026-08-28 | ✅ canonical |
| `sustainability.*` | the print execution, with its comparator footnote set under the claims | §2 SunBird · source art from Michael | ✅ canonical — "social and in print" is his own wording |
| — | *the film's view count (612)* | §8.29 | ⛔ **never on any artifact** — true, and the wrong number |

⚠️ **Not claimable on this page, in either direction:**

- ⛔ **Issues management / reputation** — confirmed negative and a **prohibition** (§8.28).
  The page states the miss outright in `ninety.step.5`. Never soften it into
  "navigated sensitive communications" and never quietly delete it either.
- ⛔ **"Clinical data" or "trial data"** — market and scientific data is the ceiling (§8.24).
- ⛔ **Agency-side employment.** He is buy-side: writes the RFPs, scores the responses (§8.14).
  The page never implies otherwise; the cover letter says it explicitly.
- ⛔ **Named agencies** (standing preference 2026-08-24) — none appear here.
- ⚠️ **M&A** — Iberogast as acquired-brand work is real (§8.23) but is **not** on this page,
  and "led an M&A brand integration" is prohibited. **Separation / carve-out is OPEN, not
  denied** — claim neither the experience nor the gap.
- ⛔ **The SunBird view count (612).** Verified and prohibited (§8.29). Sourcing a number tells you
  whether it is true, not whether it belongs.
- ⚠️ **Embedding is disabled on Bayer's YouTube channel** — an iframe pointed at YouTube renders a
  dead "Video unavailable" box. Verified 2026-08-28. ⛔ Never point the player at YouTube.
  ✅ **The film plays from Vimeo instead** (`1222026785`, unlisted hash `49b5ad571e`, uploaded by
  Michael), matching the Vimeo pattern already used on `design.michaelscrivana.com`. The YouTube
  link stays in the caption as *provenance* — it is the proof Bayer published it.
- ⚠️ **The Vimeo upload is the ORIGINAL 1920×1080 letterboxed master**, so the player frame is
  **16:9**, not 4:5. A cropped 4:5 web cut exists at `~/Drop/SunBird-4x5-web.mp4` (5.8 MB). If that
  ever replaces the Vimeo source, change `.vimeo-45` back to `padding-top: 125%`.
- ⛔ **Frame 8 of the carousel ("Now recycle ready") carries a visible Shutterstock watermark** and
  is deliberately excluded. Do not add it.
- ⚠️ **Every §8.28 communications claim is unquantified on purpose.** If open question #15
  gets answered, this page can get materially stronger — until then, do not add a number.

# Copy

> Regions are addressed by `data-k` in index.html. Reword freely —
> the handles do not depend on the prose. Run `sync.mjs check` after editing either side.

## `hero.kicker`
```html
<span class="dot"></span>Michael Scrivana &nbsp;&middot;&nbsp; for Stryker &middot; Senior Manager, Communications
```

## `hero.h1`
I write what senior leaders say &mdash; *and make the material that carries it.*

## `hero.lede`
More than eight years inside regulated healthcare, seven of them developing the **narratives, the visuals and the scalable materials** a global consumer-health organization runs on &mdash; for three different rooms: **employees, customers, and the stakeholders above them**. Five cases: the narrative and the thing that carries it; change communications at two altitudes, including the town hall I presented to close to a thousand colleagues; high-impact business events; the toolkits that make consistency scale; and **a published corporate sustainability campaign you can watch on Bayer&rsquo;s own channel**. The brand work behind those cases carries its own numbers &mdash; the two launches I designed and took to market have done **more than $79MM in retail sales**, and MiraFIBER&rsquo;s launch communications ran **more than 50% over sales projection**.

## `hero.who`
```html
<strong>Michael Scrivana</strong> &mdash; Senior Designer &amp; AI Lead, Product Experience, Bayer Consumer Health. Career started on the assembly floor at Siemens Healthcare building clinical diagnostic analyzers &mdash; the first of more than eight years inside regulated healthcare. &nbsp;<a href="https://www.linkedin.com/in/michaelscrivana89/">linkedin</a>
```

## `executive.title`
The narrative, and the thing that carries it

## `executive.sub`
Talking points, leader messages and briefing narratives &middot; the decks, agendas and stage content they live inside &middot; at divisional and senior-leadership level

## `executive.fig.1`
**Leadership content is an argument before it is a slide.** One idea, stated once, in the language leadership had already agreed to use. I write the words at this altitude and design the thing that carries them.

## `executive.fig.2`
**The same grammar, a different beat.** One visual system across a full day of speakers, internal and external, so the room reads it as one message rather than a sequence of talks.

## `executive.fig.3`
**And the beat before any of it.** A teaser with no information in it at all, three weeks out. The first communication only has to make people curious.

## `executive.block.what-i-actually-do.label`
What I actually do

## `executive.block.what-i-actually-do.p`
I write the executive layer: **talking points and leader messages**, and the **briefing materials and strategic narrative** underneath them &mdash; at divisional and senior-leadership level. Then I build what carries them.

## `executive.block.why-that-combination-is-rare.label`
Why that combination is rare

## `executive.block.why-that-combination-is-rare.p`
Most people who can write an executive narrative hand it to a designer. Most people who can build the deck did not write the argument. The seam between those two is where meaning usually leaks &mdash; a strong point rendered weakly, or a beautiful slide making a claim nobody agreed to.

## `executive.block.the-evidence-i-cannot-show-you.label`
The evidence I cannot show you

## `executive.block.the-evidence-i-cannot-show-you.p`
**The strongest examples are internal and stay that way.** Retailer selling presentations I own end to end &mdash; narrative, data slides, key visuals &mdash; plus the master template system behind the category decks, and material carried to divisional leadership and board level. **The most consequential was a divisional AI roadmap I co-authored and carried to our Science President across a multi-day workshop.** It produced a new role, a promotion, and the roadmap itself.

## `executive.outcome.1.lead`
Written, not just designed

## `executive.outcome.1.sub`
Talking points, leader messages, briefing materials, strategic narrative.

## `executive.outcome.2.lead`
Owned end to end

## `executive.outcome.2.sub`
Selling presentations and the template system the category decks are built from.

## `executive.outcome.3.lead`
Carried to a division president

## `executive.outcome.3.sub`
A 1,000+-person AI roadmap, taught across several days, not presented once.

## `executive.jd-tags`
```html
<span>executive presentations</span><span>leader messages &amp; talking points</span><span>briefing materials</span><span>business narrative</span><span>supporting senior executives</span>
```

## `change.title`
Change communications at two altitudes &mdash; and the room that had to be convinced

## `change.sub`
Two altitudes, one message &middot; a champion network across six disciplines &middot; and the town hall I presented to a thousand people who needed to hear it

## `change.fig.1`
**One destination, so the message has somewhere to live.** Internal communications fail quietly when they are only ever events. This is the standing surface every briefing and recap points back to.

## `change.fig.2`
**Commitments in public, with their status attached.** Publishing the status is the communication &mdash; it is what stops a transformation program becoming an announcement people stopped believing.

## `change.fig.3`
**Internal programs need identities too.** A town hall series, a curiosity program, a think tank, an awards program, the tour. Employees experience named things, not &ldquo;internal communications&rdquo;.

## `change.block.the-problem.label`
The problem

## `change.block.the-problem.p`
**A 115-person organization across six disciplines had to change how it worked**, inside a roadmap covering more than a thousand people. Nobody could be ordered to. No budget line for compliance, no manager who could enforce it &mdash; **the normal condition of change communications, and the reason most of it fails.**

## `change.block.what-i-ran.label`
What I ran, and where

## `change.block.what-i-ran.p`
**Inside the organization I own the whole program** &mdash; strategy, cadence, channels and audience: daily briefings, executive leadership decks, weekly recaps, town halls, internal campaigns and intranet, and a **change-champion network with a named person in each of the six disciplines**. **Above it, I represent that organization on the division&rsquo;s science-wide AI program**, where the audience is leadership. Keeping those two the same message is most of the job.

## `change.block.the-town-hall-and-the-thing-no.label`
The town hall — and the thing nobody wants to say out loud

## `thesis.p-2`
The most recent one I presented myself: our AI roadmap, to **close to a thousand colleagues**. The honest problem with that room is that a good number of the people in it suspect this technology is coming for their craft, and no amount of roadmap defuses that. So the message was stated plainly and up front rather than left to be inferred: **the goal is to amplify our people, not replace them.** I collaborated on producing it and helped craft the strategy for delivering it.

## `change.block.the-town-hall-and-the-thing-no.p2`
**Then I built participation in rather than talking at people for an hour** &mdash; a live segment called &ldquo;Is it AI?&rdquo;, where the audience guesses which work was machine-made. It does in ninety seconds what no slide can: **it lets a skeptical creative audience test the technology on itself** instead of being argued at by someone with an initiative to defend.

## `change.block.what-made-it-stick-and-how-i-k.label`
What made it stick, and how I know

## `change.block.what-made-it-stick-and-how-i-k.p`
**I stopped asking people to adopt things and started removing the trip.** Tools shipped into the places people already worked, and every pilot went first to the team with the nearest real deadline &mdash; not the team that asked politely, and not my own function. **The number I watch is not attendance or opens. It is usage that repeats.**

## `change.outcome.1.lead`
Zero to six disciplines, twelve months

## `change.outcome.1.sub`
Measured as repeat usage, not attendance.

## `change.outcome.2.lead`
Five 90-day commitments

## `change.outcome.2.sub`
From one leadership workshop, by leaders who do not report to me.

## `change.outcome.3.lead`
A champion in every discipline

## `change.outcome.3.sub`
Change carried by people inside the team, not broadcast at them.

## `change.jd-tags`
```html
<span>internal &amp; change communications</span><span>town halls</span><span>employee engagement</span><span>internal campaigns</span><span>intranet</span><span>enterprise strategy</span><span>influence without authority</span>
```

## `events.title`
High-impact business events &mdash; the industry show, and the room where the customer sits

## `events.sub`
The NACDS trade-show program, four consecutive years, two formats &middot; expo-floor island booths and a roughly 20&times;30-ft executive meeting suite &middot; six-figure budget &middot; plus a 200-plus-attendee internal event across three formats

## `events.fig.1`
**Judged in the same frame as the competition.** Every major consumer-health company is within a few hundred feet, and buyers compare presences the way shoppers compare a shelf.

## `events.fig.2`
**Corporate messaging at architectural scale.** The lines on those walls are the enterprise narrative, sized so a customer reads them from the aisle.

## `events.fig.3`
**Where the meetings actually happen.** At the Annual Meeting the open floor becomes a 360&deg; suite built around senior buyer conversations, not foot traffic.

## `events.fig.4`
**The room is planned before it is decorated.** 17&prime;8 &times; 32&prime;1 at The Breakers &mdash; table centered for the conversation, screen wall at the focal end. Nothing here was the vendor&rsquo;s decision.

## `events.fig.5`
**The brief, before any vendor work began.** My direction page for one booth side: two key messages and the moves allowed against them. **Messaging hierarchy is decided here, in words.**

## `events.block.the-problem.label`
The problem

## `events.block.the-problem.p`
**Business events are the one channel with no second draft.** The date does not move, the room is either full or it is not, and narrative, agenda, stage content and environment all have to arrive finished on the same morning.

## `events.block.what-i-owned.label`
What I owned

## `events.block.what-i-owned.p`
**Bayer&rsquo;s NACDS presence, four consecutive years, two formats** &mdash; Total Store Expo island booths (30&times;40 ft, then 30&times;30 ft) and the **executive meeting suite**, roughly 20&times;30 ft, rebuilt in a different resort room each year, on a **six-figure budget**. **I wrote the creative brief before any vendor touched it** &mdash; brand zones, messaging hierarchy, lighting direction &mdash; then took the production vendor through **six-plus proof rounds**.

## `events.block.why-the-craft-half-matters-to.label`
Why the craft half matters to a communications team

## `events.block.why-the-craft-half-matters-to.p`
**When the narrative changes four days out &mdash; and it always does &mdash; I redraw the frame, rewrite the card and re-cut the film myself.** That is not a claim about taste. It is a claim about **latency under a fixed date**, on a calendar of customer engagements, sales meetings and industry events.

## `events.block.bold.label`
And the same muscle, pointed inward &mdash; the BOLD Ambition Tour

## `events.block.bold.p`
**A 200-plus-attendee internal event, three consecutive years, three formats** &mdash; virtual, hybrid, in person &mdash; on one design system spanning identity, 3D, motion, live stage and merchandise. I drew the storyboards by hand and animated the stage films from them. **Surviving three formats is a harder test than surviving three dates.**

## `events.fig.6`
**I draw the frames, then animate them.** The stage-opener storyboard &mdash; and the film that ran in the room came from these panels, by the same hand.

## `events.outcome.1.lead`
Four years, two formats

## `events.outcome.1.sub`
Expo floor and executive suite, six-figure build, one graphic system.

## `events.outcome.2.lead`
Brief first, vendor second

## `events.outcome.2.sub`
Zoning and messaging hierarchy set before production; six-plus proof rounds.

## `events.outcome.3.lead`
Three years, three formats

## `events.outcome.3.sub`
The internal event ran virtual, hybrid, in person &mdash; one system, held.

## `events.jd-tags`
```html
<span>industry events</span><span>customer engagements</span><span>sales meetings</span><span>event branding</span><span>video content</span><span>agency &amp; vendor direction</span>
```

## `toolkits.title`
Toolkits, best practices and standards &mdash; consistency that does not depend on me

## `toolkits.sub`
A brand book made the single standard every partner worked from &middot; a shared vocabulary used across decks, pre-reads and internal tools &middot; an accessibility standard with a check written into the gate

## `toolkits.fig.1`
**A shared vocabulary, stated once.** One set of tokens, one brand mark, one type pairing, used across decks, pre-reads and internal tools. **Consistency is a supply problem before it is a discipline problem.**

## `toolkits.block.the-problem.label`
The problem

## `toolkits.block.the-problem.p`
Guidance that lives in a document nobody opens is not a standard. Across a global portfolio, multiple agencies and local markets, consistency was being maintained by review &mdash; catching drift after it happened, one asset at a time, forever.

## `toolkits.block.what-i-built.label`
What I built

## `toolkits.block.what-i-built.p`
I **digitized a brand book into the single standard every agency accessed and worked from**; authored a **fifteen-page visual brief** defining content specifications across three major retailers; and maintain **master-and-adaptation template systems** and reusable regulated-copy modules that global and local teams build from rather than around.

## `toolkits.block.and-the-one-i-am-proudest-of.label`
And the one I am proudest of

## `toolkits.block.and-the-one-i-am-proudest-of.p`
**I co-authored our inclusive-design and accessibility standard** &mdash; WCAG AA across print, web, mobile, packaging and point-of-sale, with named validation tooling and representation checklists. **The part that made it real was not the document. It was putting the contrast check into the QC gate**, so the standard is enforced at the moment of the decision rather than remembered afterward.

## `toolkits.outcome.1.lead`
One standard, every partner

## `toolkits.outcome.1.sub`
A brand book digitized into the source agencies actually work from.

## `toolkits.outcome.2.lead`
WCAG AA, written and gated

## `toolkits.outcome.2.sub`
Co-authored, with the check placed inside QC rather than beside it.

## `toolkits.outcome.3.lead`
Masters teams adapt from

## `toolkits.outcome.3.sub`
Template systems and reusable modules, global and local on the same base.

## `toolkits.jd-tags`
```html
<span>communication toolkits</span><span>best practices &amp; resources</span><span>brand standards</span><span>accessibility &amp; inclusion</span><span>editorial consistency</span>
```

## `sustainability.title`
SunBird &mdash; a corporate sustainability claim, made watchable

## `sustainability.sub`
Sustainability team owned the science &middot; communications owned the message &middot; I made every frame of it &middot; live on Bayer&rsquo;s global channel

## `sustainability.fig.1`
**The problem, named in three words.** PVC with a foil backing &mdash; opaque, multi-material, effectively unsortable at the recycling stage. Naming what is being removed is more legible than naming what replaces it.

## `sustainability.fig.2`
**The whole argument in one frame.** A hard split down the middle &mdash; opaque on the left, transparent on the right. No copy required. This is the frame the campaign is built around.

## `sustainability.fig.3`
**The shot I am proudest of.** Two blisters edge-on, so an eighteen percent weight reduction stops being a number and becomes a thickness you can see. Nobody reads a percentage. They do look at a silhouette.

## `sustainability.fig.4`
**Four claims, four comparators.** Carbon &minus;38%, water &minus;78%, land &minus;53%, weight &minus;18% &mdash; every one footnoted against the packaging it replaces, because a sustainability number without its baseline is not a claim, it is a liability.

## `sustainability.fig.5`
**And the same story in print, where nothing moves.** The film reveals the claims in sequence; a page has to land all four at once without becoming a table. Same icons, same system, different physics.

## `sustainability.block.the-problem.label`
The problem

## `thesis.p-2.2`
Bayer had replaced the PVC in a blister pack with mono-material PET &mdash; the kind of change that is genuinely significant and almost impossible to feel. The whole story lives in a material nobody looks at, on a product people open without thinking, and it is carried by four life-cycle-assessment percentages that mean nothing on their own.

## `sustainability.block.how-it-was-actually-made.label`
How it was actually made

## `sustainability.block.how-it-was-actually-made.p`
I worked with the **sustainability team**, who owned the science, and then with **communications**, to craft the message &mdash; and then I built the entire thing: 3D creative, lighting, rendering, animation, type animation. It ran across **social and in print**, alongside the press release.

## `sustainability.block.why-this-is-the-case-that-matt.label`
Why this is the case that matters most for a communications team

## `sustainability.block.why-this-is-the-case-that-matt.p`
**Because it is the whole loop, and I was in every room of it.** A subject-matter function owns a technical truth. Communications owns what the public should understand. Usually the person between them briefs it out and waits. **Here I sat in both conversations and then made the artifact myself.**

## `sustainability.block.why-this-is-the-case-that-matt.p2`
**And it was a regulated claim, not a slogan.** I worked with the communications and sustainability teams to take the life-cycle-assessment claims through **legal, medical and regulatory review** before any of it was public &mdash; so the claim holds up because the numbers were cleared before the film was cut, not after.

## `sustainability.block.why-this-is-the-case-that-matt.p3`
```html
Bayer positioned the launch as the first PET blister in the consumer health sector, with packaging partner Liveo Research, launching first in the Netherlands. <em>That framing is Bayer&rsquo;s, and it is on the record</em> &mdash; the <a href="https://www.bayer.com/media/en-us/bayer-and-liveo-research-launch-first-of-its-kind-blister-packaging-with-improved-environmental-footprint/">30 October 2024 press release</a>, plus independent coverage in Packaging Europe, Healthcare Packaging, Packaging Digest and Recycling Today.
```

## `sustainability.outcome.1.lead`
Published, not described

## `sustainability.outcome.1.sub`
Live on Bayer&rsquo;s global corporate channel since November 2024.

## `sustainability.outcome.2.lead`
Cleared before it shipped, with me in the room

## `sustainability.outcome.2.sub`
Taken through legal, medical and regulatory review with comms and sustainability.

## `sustainability.outcome.3.lead`
Science &rarr; message &rarr; artifact

## `sustainability.outcome.3.sub`
One person across all three, so nothing was lost in a handoff.

## `sustainability.jd-tags`
```html
<span>external communications</span><span>corporate narrative</span><span>video content</span><span>visual storytelling</span><span>regulated claims</span><span>cross-functional collaboration</span>
```

## `footer.big`
The message landing is not the finish line &mdash; you find out why it stopped short, then change the situation.

## `footer.fine`
Michael Scrivana &middot; Case studies &middot; August 2026 &middot; Prepared for Stryker &middot; Senior Manager, Communications &middot; R570593  
Imagery shown is concept, pilot or shipped brand output from work at Bayer Consumer Health. No confidential business data is reproduced here.
