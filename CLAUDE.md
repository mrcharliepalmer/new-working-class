# New Working Class - Workshop Prep

## What This Is
Preparation for a workshop Charlie is delivering (week of March 9, 2026) about using AI to bridge the gap between vision and execution. The workshop uses Charlie's experience building the Steadman.ai website as the central narrative.

## The Steadman Website
- **Live site**: https://mrcharliepalmer.github.io/steadman_mockup_v3/
- **Local codebase**: This directory contains the website files
- **Key features**: Sophisticated design with tactile hover/click interactions, plus a system for generating professional graphics
- **Built entirely using AI** — Charlie is not a designer or developer

## Workshop Goals
1. **Prep slides/demo** to tell the story of building Steadman.ai
2. **Design a practical exercise** everyone can participate in
3. **Theme**: Using AI to bridge the gap between what you can envision and what you can execute

## Workshop Narrative Structure (Five Emotional Beats)
1. **Frustration** — "I didn't know what this HTML thing was"
2. **Curiosity** — "Wait, what if I could use this for other things?"
3. **Surprise** — "Holy shit, it worked"
4. **Realisation** — "I've accidentally built something powerful"
5. **Empowerment** — "Maybe I could turn this into an actual product"

## Key Quote
Charlie describes AI as "the most brilliant autistic intern you'll ever work with" — phenomenally talented, but needs clear direction and takes everything literally. Learning to work with AI is really learning to communicate clearly — a skill that applies to working with people too.

## Development History (Gemini Chats)
Charlie's AI development journey is documented in Gemini chats (Google account: Audience Strategies, PRO). Search "STEADMAN" in Gemini to find them. The 5 core chats have been extracted and verified:

1. **Steadman.ai Visual Language Development** — Nov 21, 2025 (15 msgs)
   - URL: https://gemini.google.com/app/be75ea2002d1ebcb
   - Defining aesthetic taste, pillar icons (Sprout/Leaf/Acorn), differentiator icons
2. **Brand Identity: Cairn Iconography Strategy** — Nov 21, 2025 (short)
   - URL: https://gemini.google.com/app/c83b074467975a16
   - The "Rubbish!!!" chat — frustration at the gap between vision and AI output
3. **STEADMAN: Initial Website Development** — Nov 27, 2025 (32 msgs)
   - URL: https://gemini.google.com/app/43fba2e74557274d
   - "What do I do with the html?" → "What is CSS?" → "Oh my that is gorgeous"
4. **STEADMAN: Cairn & Icon Development** — Nov 27, 2025 (37 msgs)
   - URL: https://gemini.google.com/app/6b5459524e0c9080
   - Style iteration, icon development, Gem creation (the systems thinking leap)
5. **STEADMAN: Full Website Development** — Nov 28, 2025 (26 msgs)
   - URL: https://gemini.google.com/app/c62e185f0b59938c
   - "Lead Developer and Brand Guardian" → full website build → ships to GitHub

### How to Access Gemini Chats
- Use Claude in Chrome extension to browse Gemini
- The tab group connection needs to be established first (`tabs_context_mcp` with `createIfEmpty: true`)
- Navigate to https://gemini.google.com and search for "STEADMAN"
- **IMPORTANT**: Gemini uses lazy-loading (infinite-scroller). User must manually scroll to the top of each chat before extracting, or content will be incomplete. `get_page_text` only captures what's currently loaded in the DOM.

### Extracted Files
All extracts live in `journey_extracts/`:
- `chat1_visual_language_dev_nov21.md`
- `chat2_cairn_iconography_strategy_nov21.md`
- `chat3_initial_website_dev_nov27.md`
- `chat4_cairn_icon_dev_nov27.md`
- `chat5_full_website_dev_nov28.md`
- `chat6_hero_graphic_jan10.md`
- **`JOURNEY_ANALYSIS.md`** — Full analysis with emotional beats, prompting evolution, quote reels, and suggested demo flow

## Phase 1: Map the Journey (DONE)
- ✅ Extracted text from 5 core Gemini chats chronologically
- ✅ Identified key turning points and "aha" moments
- ✅ Noted where Charlie got stuck and how he got unstuck
- ✅ Tracked prompting evolution (10 stages, from "What do I do with the html?" to role-assigning AI)
- ✅ Mapped progression from basic to sophisticated
- ✅ Full analysis written: `journey_extracts/JOURNEY_ANALYSIS.md`

## Phase 2: Build the Narrative (IN PROGRESS)
- ✅ Mapped moments onto the five emotional beats as slide structure
- ✅ Selected concrete examples and visuals for each beat
- ✅ Structured the presentation/demo flow (18 slides)
- ✅ Built as HTML slide deck: `workshop/index.html`
- ✅ Visual assets copied to `workshop/img/` (cairn originals, rejected versions, icons)
- ✅ Live embeds: Steadman button demo (interactive), steadman.ai iframe
- 🔧 Needs tweaking: layout polish, content refinement, review slide order
- Style: Red Slash Studio aesthetic (cream, Space Grotesk, Newsreader, red accent, tactile box-shadows)

## Phase 3: Design the Exercise (DONE — in same HTML)
- ✅ Three-round exercise built into slides 11-17
- ✅ Round 1: Vague prompt → generic output (the frustration)
- ✅ Round 2: Three techniques (references, specific feedback, role assignment) + better prompt + power-ups
- ✅ Round 3: Compare versions (the reveal)
- ✅ All prompts have tap-to-copy functionality
- ✅ Works on mobile (participants follow along on phones)

## Workshop Files
- **`workshop/index.html`** — The complete slide deck + exercise (18 slides, click-through with arrow keys/swipe)
- **`workshop/img/`** — Visual assets:
  - `cairn-original.png` — The flat geometric starting logo
  - `cairn-rubbish.png` — The AI-generated cairn that got "Rubbish!!!"
  - `cairn-final.png` — The finished hand-drawn cairn (not yet used in slides)
  - `icons.png` — The four differentiator icons from the Gem system
- **Visual assets source**: `/Users/belikenige/Documents/Work/Website Creator/Steadman/` (Cairn/, Icons/, HTML/ folders)
- **Dev server**: `npx serve workshop -l 8090` (configured in `.claude/launch.json`)

## The Bigger Story: Compounding Capability
Steadman was the starting point, but the real story is how that initial capability compounded. After Steadman (a solid but basic website), Charlie went on to produce increasingly sophisticated work:

1. **Steadman.ai** (Nov 2025) — The beginning. A clean, professional site with tactile interactions and icon generation system
   - https://mrcharliepalmer.github.io/steadman_mockup_v3/

2. **TPS26 Website Redesign** — A significant step up in sophistication. Charlie considers this particularly exciting
   - https://mrcharliepalmer.github.io/TPS26-website-redesign/

3. **Your ADHD Journey** — Interactive/informational site
   - https://mrcharliepalmer.github.io/Your-ADHD-journey/

4. **Still Here! Still Queer! Now What?** — For Dr Paul Taylor-Pitt
   - https://redslashstudio.github.io/still-here-still-queer-now-what

The workshop narrative should emphasise this progression: Steadman is the origin story, but the real takeaway is how learning to work with AI creates a capability that keeps growing. Each project built on the last.

## Notes
- Charlie also used Claude (not just Gemini) during development — check if conversation history is available
- The website codebase is in this working directory for reference
- Workshop should leave plenty of space for discussion
- The local project "Still Here! Still Queer! Now What?" was running on localhost:8080 during earlier sessions
