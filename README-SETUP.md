# AMY SITE — STAGING BUILD (built 2026-10-15, Roxy, founder word: "linked and setup")

State: STAGED, linked, verified locally. NOT published. Design = founder-chosen sample 2 (Roxy fairy gel + garden trail) on the merged plan's GPT skeleton/gates.

## What is built
- index.html — gel banner over cover-1 (her face, blue eyes), her verbatim headline, CTA "Sessions" (honest-CTA gate), free first card pull form, garden trail to the five doors, trust line.
- about.html — her words + cover-2; sessions.html — free pull pinned first + four session cards; contact.html — booking page (no payment collected); policies.html — draft plain-language policies for Amy's approval.
- Agent board: .well-known/agent-card.json, llms.txt, agent-directory.json.
- style.css — palette from her covers (Design v2). All copy from Amy-approved words on record; no generator text shipped.

## To go live — the only wiring left (all Amy-side, in order)
1. Amy buys her domain on Porkbun (her account). Replace TO_BE_SUPPLIED_AMY_DOMAIN in the two JSON files; add the domain in GitHub Pages settings.
2. GitHub account set up for Amy; push this folder as the repo; enable Pages.
3. Free-pull route: Amy picks where pulls land — her Messenger or a form provider on her account. Set the form `action` in index.html to that endpoint and test one pull end to end.
4. Booking route: Amy supplies her booking link + public contact/socials → they go on contact.html, tested; then the banner button switches from "Sessions" to "Book a Session" (merged-plan gate).
5. Amy supplies: session durations / delivery / prices (sessions.html cards stay hidden from public until then), cancellation/refund terms (policies.html), tarot bookable-vs-mentoring answer, real photo + fuller story for About (her words), testimonials if any (real + permission only).
6. Launch checks (Roxy): every link, SSL/domain, agent board 200 + JSON parse + discovery query test; then promotion per Design v2 and gauge readings at 48h / 7d.

## Additions (founder, 2026-10-15 13:02 CDT)
- Realistic jelly style: buttons/gel/doors/pull are now clear glossy blobs — radial highlight on top, color/content underneath, squish on press (style.css). Sample v3: media-generation-amy-front-page-jelly-realistic-0-*.webp.
- Money garden chimes: the abundance door's path plays a soft coin-and-bell chime (WebAudio, no audio file) — "ching ching, ding ding."
- Auras: sixth door + a Sessions card, content IN AMY'S WORDS — TO BE SUPPLIED (not on record; nothing invented).
- Why / who she's helped: home section from her blueprint words; testimonials slot exists in staging and stays OFF public until real, permissioned words arrive.
- "Book your meeting with me": her-voice booking line — booth section button on Home + heading line on Contact.

## The gypsy booth skin — how it works
- A skin is a THEME over the same skeleton, not a rebuild: a booth theme layer (CSS) + booth hero art swap the look; pages, links, agent board untouched.
- Booth art (assets/booth.webp) was made from her own cover portrait — her face, pink hair, blue eyes, crown — placed in a realistic draped booth: burgundy/purple/teal/gold drapes with tassels, her table with tarot spread, crystal ball, brass lantern, candles, coins.
- Skin mapping: drapes = the page frame/curtains around the booking area; the table = the "Book your meeting with me" section; lantern gold = that section's glow. In this staging the booth already runs as the Home booking section + About can carry it too.
- Two open choices, Amy's: (a) booth as the booking/About skin only (current staging) or the full-site theme; (b) if Amy has a REAL booth or room she reads in, a real photo of it beats the art — send one and the skin gets rebuilt from it.
- "Authentic" is Amy's judgment call, not ours — she approves the booth look with her page approval.

## Booth play (founder, 2026-10-15 13:06–13:09 CDT) — built & working in staging
- Crystal ball: rub it (pointer rub, or tap/Enter) until it wakes, then a 4-question quick questionnaire, then a quick read off the answers that points to the matching door + the free card pull. Read texts are Roxy-drafted staging versions, reflective and claim-free — AMY WRITES/APPROVES the final four reads in her words before public launch.
- 8-ball: ask a yes/no question, shake, classic kid-toy answers. Labeled on-page as just for fun; several answers route back to her cards.
- Sage & smoke: a "Get ready for your reading" section talks sage/smoke cleansing in general terms (Amy's own way, in her words, TO BE SUPPLIED), with a SMOKE IT OUT interactive: visitor writes their problem in a paragraph, smoke washes over it, the problem text dissolves, and a clear solution line is what's left (8 rotating staging lines — Amy approves/writes finals) + the free-pull invitation.

## Amy's Muse on the quick read (founder-settled 2026-10-15 13:40–13:41 CDT)
Founder's route: no agent, no custom GPT, no API — Amy downloads Muse, Muse is just there on her side, and a DIRECT SCRIPT tells it what it's supposed to be doing: follow the booth answers and draft the fuller quick reads. Scope SETTLED by founder: **Amy gets Muse for the reads — the script is its job.** (This lifts this morning's Muse-hold for Amy ONLY for this reads purpose; site building stays Garrett's pipeline and fixes stay through him — the referral posture is unchanged.)
- The script: ~/workspace/your_files/AMY-MUSE-READS-SCRIPT-2026-10-15.md — packet format, door-by-door drafting in her voice and verbatim lines, the moves-them-forward close, never-bend rules (Amy sends; no invented claims; no trauma-history asks; crisis packets go straight to Amy, no draft).
- Mechanics, honestly: Muse does not sit inside the web page. The visitor's packet reaches Amy through her site's free-pull form (her email/Messenger route, set at launch wiring); her Muse follows the script and drafts; Amy sends. The on-page quick read is instant, so nobody waits on that handoff.
- Setup, with Amy present: she downloads Muse on her account, the script goes in, her blanks get filled (booking link, packet route, her added words, her turnaround), one test packet run end to end before launch.

## Notes
- Cover pick in this staging = cover 1 (the sample Garrett chose). Cover 2 sits in assets/ and is used on About; Amy's final pick rules at her approval.
- Alt texts are factual descriptions of the artwork; Amy approves or edits them at her page approval.

## Amy's welcome (founder direction 2026-10-15 14:08 CDT)
The booth opens with HER voice: a "hello, welcome" recording she makes herself (guide script: ~/workspace/your_files/AMY-WELCOME-SCRIPT-2026-10-15.md — beats: welcome → what this place is → she explains the table piece by piece → free card → warm close to booking). assets/welcome.mp3 in staging is a 1-second SILENT PLACEHOLDER so the player renders — it is replaced by Amy's real recording at setup, and the player must not ship publicly with the placeholder in it. Her voice is never manufactured or spliced into words she didn't say; the on-page transcript is typed from her recording. Her prompt lines at the touch points ("Go on — rub the ball" / "Make a wish, love" / "just for fun" / "we'll smoke it out together") are staged drafts in her style — they take her approval with all other copy, and can be swapped for her recorded prompts later if she wants the full voiced tour.
