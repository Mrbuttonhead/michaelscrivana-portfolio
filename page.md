---
slug: baseten
url: https://baseten.michaelscrivana.com
role: Design Engineer (Brand Team) — Baseten
posting: https://jobs.ashbyhq.com/baseten/81d573b6-741c-4140-a36b-6892456eca73
branch: baseten
worktree: ~/Documents/ms-baseten
packet: ~/Documents/Vaults/Life/Job Search/Applications/Baseten_DesignEngineerBrandTeam
corpus: ~/Documents/Vaults/Life/Job Search/Master/Master_Corpus.md
accent: "#00693d"      # Baseten green darkened to clear WCAG AA on their #f5f8f4 paper
subpages: [vat/, pearl/, gloss/, lab/]
status: application filled, NOT submitted (2026-08-27)
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

   `check` is safe to run any time. `pull` after editing the HTML; `push` after
   editing copy here. Round-trip is byte-exact — a no-op push changes nothing.

5. **Regions too complex for the markdown subset are stored verbatim** in a
   ```` ```html ```` fence. Edit them as HTML; they round-trip untouched.

# Claims — what each assertion rests on

⛔ **Rule (Corpus §8.26): a third-party ranking is a citation, not a description.**
Anything of the form *"[ranking] [company]"* needs a source before it goes on the page.
"Fortune 100" was false and reached seven packets before anyone checked it.

| Handle | Claim | Corpus anchor | Status |
|---|---|---|---|
| `hero.lede` | 115-person organization | §8.6 settled | ✅ canonical |
| `hero.lede` | seven years / two years building | §1, §8.2 | ✅ canonical |
| `hero.who` | Senior Designer – AI Lead | §8.7 official title | ✅ canonical |
| `surface.block.what-i-did.p` | five internal tools in twelve months | §3 | ✅ canonical |
| `surface.block.what-i-did.p` | read the infra docs rather than wait | §3 self-taught infra | ✅ canonical |
| `surface.outcome.*` | zero to six craft disciplines in 12 months | §5 rollup | ✅ canonical |
| `system.block.*` | Figma library + token base, both sides | §3 PX Design System | ⚠️ never quantify (open Q#5) |
| `system.block.*` | WCAG AA written into a QC gate | §2 inclusive design standard | ✅ canonical |
| `webgl.block.about-the-nabu-work-above.p` | at home, ~three weeks, household users | §3 honesty frame · §8.13 | ⚠️ frame is mandatory |
| `webgl.block.the-parts-worth-judging.p` | 40k-point sphere, quality ladder, R3F port | §6 · §3 | ✅ canonical |
| `webgl.cap.3` | 1,617 pts · 180 frames · 2.40 MB | §6 VAT rig (from its README) | ✅ canonical |
| `clarity.metric.*` | ~$79MM+ combined MULO+ | §5 rollup | ✅ canonical, primary |
| `clarity.block.*` | A/B + conversion on the digital shelf | §2 (added 2026-08-27) | ⚠️ no lift %, no retailer |
| — | *Bayer is Fortune **Global** 500* | §8.26 | ⛔ never "Fortune 100" |

⚠️ **Not claimable on this page:** headless CMS of any kind (§6, confirmed negative) ·
a publicly-owned marketing site (§3 — PX Hub is internal; brand sites were agency-built) ·
Next.js beyond the bare name (open Q#14) · shader work beyond Nabu (open, not denied).

# Copy

> Regions are addressed by `data-k` in index.html. Reword freely —
> the handles do not depend on the prose. Run `sync.mjs check` after editing either side.

## `hero.kicker`
```html
<span class="dot"></span>Michael Scrivana &nbsp;·&nbsp; for Baseten · Design Engineer (Brand Team)
```

## `hero.h1`
You are hiring one person to do both halves. *I have been doing both halves for years — they were just filed under different job titles.*

## `hero.lede`
Seven years designing brand systems that had to hold at volume: identity, packaging, motion, live stage, the digital shelf. Two years designing *and building* the software a 115-person organization now works through every day — React and TypeScript, written by me, deployed by me, still being shipped into. This page is four cases at that seam — and the third one runs live, three ways, rather than being described.

## `hero.who`
```html
<strong>Michael Scrivana</strong> — Senior Designer &amp; AI Lead, Product Experience, Bayer Consumer Health. &nbsp;<a href="https://design.michaelscrivana.com">design &amp; motion portfolio</a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/michaelscrivana89/">linkedin</a>
```

## `thesis.p`
```html
Most organizations split this role in two and then spend the difference on handoffs. The reason I can hold both is not talent, it is stubbornness: when the deploy queue ran in weeks, I <span class="hl">read the infrastructure documentation until I could ship it myself</span>.
```

## `surface.title`
A live surface I own end to end — designed, built, deployed, still changing

## `surface.sub`
Vite + React + TypeScript · Azure Static Web Apps behind SSO · a year of continuous shipping, not a relaunch

## `surface.block.the-problem.label`
The problem

## `surface.block.the-problem.p`
A 115-person creative organization had no front door for any of this. Every tool that existed lived somewhere different, and the internal path to deploying anything ran through a queue measured in weeks. The usual answer is to file a ticket and wait, or to brief an agency and wait longer.

## `surface.block.what-i-did.label`
What I did

## `surface.block.what-i-did.p`
I read the enterprise infrastructure and platform documentation myself until I understood exactly what I was permitted to deploy, where, and under which controls — and then built **PX Hub**: a Vite + React + TypeScript monorepo on Azure Static Web Apps behind enterprise SSO, hosting five tools. I designed it, I wrote it, I deploy it. **That is the only reason there are five tools and not one.**

## `surface.block.why-it-matters-for-this-role.label`
Why it matters for this role

## `surface.block.why-it-matters-for-this-role.p`
Your posting asks for a site treated as *a product that&rsquo;s constantly evolving rather than something we redesign every few years*. That is not an aspiration I am agreeing to — it is how this thing has run for a year. New tools, new sections, new patterns, shipped continuously into a surface that never went dark for a redesign. The organization went from **zero AI literacy to active use across all six craft disciplines in twelve months**, and the front door is the reason.

## `surface.outcome.1.lead`
Designed, built and deployed by one person

## `surface.outcome.1.sub`
Figma to production, including the auth, the access control and the pipeline.

## `surface.outcome.2.lead`
A year of continuous shipping

## `surface.outcome.2.sub`
Five tools live on it; no relaunch cycle, no redesign freeze.

## `surface.outcome.3.lead`
Days, not four-to-six weeks

## `surface.outcome.3.sub`
The internal cycle against the typical agency turnaround it replaced.

## `surface.jd-tags`
```html
<span>own the site day to day</span><span>concept through production</span><span>react + typescript</span><span>constantly evolving</span><span>ship without waiting</span>
```

## `system.title`
A design system that exists in Figma *and* in code, maintained by the same person

## `system.sub`
One token base, two visual dialects · a Figma library others build from · DM Sans + JetBrains Mono

## `system.fig.1`
**One token base, two dialects.** CSS custom properties carrying a dark chrome voice and a light paper voice from the same source. Change the token, change every surface — which is what stops a system from quietly forking into six.

## `system.fig.2`
**The second dialect, same system.** A different audience and a different product, wearing the same bones. This page is the third: the tokens below are Baseten&rsquo;s palette dropped into the same base.

## `system.block.both-sides-of-the-line.label`
Both sides of the line

## `system.block.both-sides-of-the-line.p`
I built and maintain the **Figma library** — components, variants and styles the wider organization designs from — *and* the CSS custom-property token base the applications are actually built on. Designers pull from the first, apps compile the second, and one person keeps them honest with each other. In my experience that is the entire difference between a design system and a folder of screenshots.

## `system.block.and-the-standard-underneath-it.label`
And the standard underneath it

## `system.block.and-the-standard-underneath-it.p`
I co-authored the organization&rsquo;s **inclusive design standard**: WCAG AA adopted across print, web, mobile, packaging and point of sale, with named validation tooling and — the part that made it real — **the contrast check written into the QC gate** rather than left to goodwill. Accessibility that depends on remembering is not a standard, it is a hope.

## `system.block.a-small-demonstration.label`
A small demonstration

## `system.block.a-small-demonstration.p`
```html
This page is dressed in your palette. Your signal green — <span class="swatch" style="background:#19e76e"></span><span class="code">#19E76E</span> — sits at about <strong>2.4:1</strong> against your off-white — beautiful as a signal, unusable as text. So the text accent here is a darkened relative — <span class="swatch" style="background:#00693d"></span><span class="code">#00693D</span> — at <strong>6.4:1</strong>, and the bright green is reserved for things that are not read. That took two minutes and it is the whole job in miniature: know the rule, keep the brand, do not make the reader pay for it.
```

## `system.jd-tags`
```html
<span>reusable components and patterns</span><span>systems thinking</span><span>design tokens</span><span>typography</span><span>figma to code</span>
```

## `webgl.title`
Web 3D and motion — shaders by hand, and a pipeline from a 3D package into the browser

## `webgl.sub`
Seven hand-written GLSL looks &middot; three.js and React Three Fiber &middot; vertex animation textures &middot; storyboard to finished film

## `webgl.cap.1`
```html
<span><strong>Seven shader looks, cycling. Each one is a fragment shader I wrote.</strong> The lab behind them runs the avatar&rsquo;s real renderer with its GLSL open for live editing &mdash; every control changes what the thing <em>is</em>, not a preview of it. Audio is an input: bass drives the swell, highs drive the churn.</span>
          <span class="spec">7 hand-written fragment shaders &middot; 11 presets &middot; live recompile &middot; mic or tab audio</span>
          <a href="lab/" target="_blank" rel="noopener">open the lab &nearr;</a>
```

## `webgl.cap.2`
```html
<strong>The same renderer, doing its day job.</strong> idle &rarr; listening &rarr; thinking &rarr; speaking, cycling. One visual vocabulary so the character reads the same on a TV, a wall tablet and a phone. <a href="pearl/" target="_blank" rel="noopener">full screen &nearr;</a>
```

## `webgl.cap.3`
```html
<span><strong>This is running now, in your browser.</strong> Drag to orbit, scroll to zoom, and move the cursor across the cloth — that push is live, layered on top of the baked solve.</span>
          <span class="spec">1,617 points · 3,072 triangles · 180 baked frames @ 24fps · 2.40 MB</span>
          <a href="vat/" target="_blank" rel="noopener">open full screen &nearr;</a>
```

## `webgl.fig.1`
**The other end of the same instinct.** I storyboarded the stage opener myself, in Cinema 4D &mdash; shot by shot, to sell the direction before anything was built.

## `webgl.fig.2`
```html
<strong>And the film built from them.</strong> Same hand, same system: identity into 3D into the motion that ran the room. The frames and the finished films sit together on <a href="https://design.michaelscrivana.com">design.michaelscrivana.com</a>.
```

## `webgl.block.about-the-nabu-work-above.label`
About the Nabu work above

## `webgl.block.about-the-nabu-work-above.p`
A voice assistant I built **at home, over about three weeks of evenings**, starting in late July. The users are my own household. I am flagging that plainly because the scale matters: this is personal practice, not shipped product work, and it sits below everything else on this page. What it is good evidence *of* is narrower and, I think, more useful — that I write shaders by hand, design a state vocabulary that survives three very different screens, and build myself an instrument rather than editing constants and reloading.

## `webgl.block.the-parts-worth-judging.label`
The parts worth judging

## `webgl.block.the-parts-worth-judging.p`
The character is **GLSL written directly**: fbm noise, a 40,000-point particle sphere, a two-pass ping-pong feedback buffer for the rim trail. Five states — idle, listening, thinking, speaking, error — each a row in a table of tint, churn and silhouette, so the language is data rather than four hand-tuned scenes. It renders on a desktop with a 3090, a wall tablet, and a Google TV Streamer whose GPU is a PowerVR GE9215, from **one codebase with a frame-rate watchdog that walks quality down** instead of shipping three builds. The same shaders were later ported to **React Three Fiber**, byte-identical, to prove the port was scaffolding rather than a rewrite.

## `webgl.block.the-cloth-demo-what-it-actuall.label`
The cloth demo — what it actually is

## `webgl.block.the-cloth-demo-what-it-actuall.p`
A **Vellum cloth solve** built in Houdini, baked into a **vertex animation texture**, and played back in a three.js vertex shader. Nothing above is video. **The mesh has no positions in its vertex buffer at all** — every vertex reads its position out of a texture, every frame, and the shader samples two frame rows and blends them by hand so sub-frame playback and slow motion work.

## `webgl.block.three-decisions-worth-defendin.label`
Three decisions worth defending

## `webgl.block.three-decisions-worth-defendin.p`
**Raw binary rather than EXR or PNG.** The standard VAT export writes EXR, which browsers cannot decode; 16-bit PNG silently collapses to 8 bits through a canvas. So the baker writes a flat half-float buffer straight into a `DataTexture` — full precision, no loader, no decode cost. **Nearest filtering, time interpolated in the shader**, because adjacent texels along x are unrelated points and hardware filtering would smear the mesh. **Neighbour indices instead of a normal texture** — 26 KB of point indices rather than another 2.3 MB of baked normals, central-differenced against the *live* positions so the normal stays correct under the cursor push, which a baked normal map could not do.

## `webgl.block.and-what-it-does-not-do.label`
And what it does not do

## `webgl.block.and-what-it-does-not-do.p`
The loop is ping-pong rather than a true cycle, and cloth played backwards is faintly uncanny at the turnaround — the honest fix is a periodic wind and exactly one exported period. It is soft-mode only, so constant topology: fluids and fracture debris change point count per frame and need a different mode. Texture width equals point count, so past roughly 8k points you wrap rows or split textures. I would rather tell you where it ends than let you find the edge yourself.

## `webgl.block.the-detail-i-would-want-to-be.label`
The detail I would want to be judged on

## `webgl.block.the-detail-i-would-want-to-be.p`
That character had a glow, and wherever the glow met the edge of its canvas it stopped in a straight line. A square, printed around a round object. The fix was not a CSS mask — it was reworking how the shader wrote coverage: **premultiplying it, letting the glow coefficients double as alpha, fading radially to zero *inside* the canvas bounds** so there was nothing left to clip by the time the edge arrived. A designer noticed it. Only someone willing to open the fragment shader could fix it. That gap is the reason this role exists.

## `webgl.jd-tags`
```html
<span>three.js</span><span>react three fiber</span><span>shaders</span><span>webgl</span><span>motion design</span><span>creative coding</span>
```

## `clarity.title`
Making something genuinely hard feel clear, without flattening it

## `clarity.sub`
Brand systems at volume · conversion on the digital shelf · two years explaining AI to people who did not ask

## `clarity.fig.1`
**Concept to design lock in three weeks**, executed in-house rather than briefed out. Now the #1 Overnight Laxative SKU and one of the fastest digestive-health launches in five years.

## `clarity.fig.2`
**The same instinct in software.** A React Flow graph editor over swappable image-generation backends, with brand rules held machine-readable so output arrives on-guideline rather than being corrected back onto it.

## `clarity.block.clarity-is-not-simplification.label`
Clarity is not simplification

## `clarity.block.clarity-is-not-simplification.p`
I have spent two years making a difficult technology legible to people with no reason to care about it — a 115-person organization taken from nothing to daily use, and multi-day sessions with a division&rsquo;s Science President. The lesson never changed: **the audience can tell when you have made something simple by removing the part that was true.** Your readers are engineers evaluating inference infrastructure. They will notice faster than most.

## `clarity.block.designing-against-a-number.label`
Designing against a number

## `clarity.block.designing-against-a-number.p`
I have run **A/B and conversion testing on the retail digital shelf** — content and creative variants tested against conversion across Amazon, Walmart and Target — alongside the fifteen-page visual brief that defined the standard and 700+ product renders syndicated into it. Not web experimentation, and I will not pretend otherwise: it is somebody else&rsquo;s platform. But it is real conversion work under real commercial pressure, and it taught me the thing your posting is careful about — *where the line sits between making a page work and turning it into a growth hack.*

## `clarity.metric.1.n`
```html
~$79<span class="unit">MM+</span>
```

## `clarity.metric.1.l`
Combined retail sales on brand systems I designed

## `clarity.metric.2.n`
115

## `clarity.metric.2.l`
Person organization, zero to active use in 12 months

## `clarity.metric.3.n`
```html
700<span class="unit">+</span>
```

## `clarity.metric.3.l`
Product renders syndicated to the digital shelf

## `clarity.jd-tags`
```html
<span>complex technical products made clear</span><span>conversion without the growth hack</span><span>brand at volume</span>
```

## `footer.big`
I would like to stop doing these two jobs in two different buildings.

## `footer.fine`
Michael Scrivana · Case studies · August 2026 · Prepared for Baseten · Design Engineer (Brand Team)  
Built for this application. Palette borrowed from baseten.co and contrast-corrected to WCAG AA. Internal tools built on Bayer-internal infrastructure; imagery shown is concept, pilot or shipped brand output. No confidential business data is reproduced here.
