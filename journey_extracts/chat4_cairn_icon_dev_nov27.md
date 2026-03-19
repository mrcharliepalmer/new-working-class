# Chat 4: STEADMAN: Cairn & Icon Development
**Date:** Nov 27, 2025
**URL:** https://gemini.google.com/app/6b5459524e0c9080

## Summary
This is the BIG creative development chat — 37 messages total. It starts with Charlie defining the visual style he wants, iterating through cairn illustrations, then moving to icons, and culminating in the creation of a reusable Gemini "Gem" (AI persona). This chat shows the full arc from "using AI" to "building AI-powered systems."

## Key Moments

### Phase 1: Defining the Style (PREVIOUSLY MISSING — Messages 1-19)
- **Charlie opens with a clear goal:** "My ultimate goal is to create a family of graphics that we can use for our business, Steadman.ai, inspired by the attached cairn icon. Let's begin by defining what it is I like about it. What are its key features?"
- **Identifying what he likes:** "there's something about it that feels human/real. It's not perfect."
- Shares reference images: "I really like these for their very hand-drawn quality. And the fact that they feel alive - there's a motion to them, even though they're static"
- **Key creative decision:** "I think we're hobbling ourselves by saying we need a hand every time" — recognises the hand illustration feels forced
- **Major pivot:** "Let's stop and go back to the start... I think I like the hand drawn element but that could easily be applied to the navy version, but with white lines adding the three-dimension to it. Or maybe we think Ralph Steadman style. What I think we can lose is the hand. It's the bit that feels least authentic."
- Then iterates on the cairn illustration itself through multiple rounds:
  - "not quite right. I feel like you're keeping the shape of the original logo but we could just do something more natural / 3D"
  - **"hmmm - looks a bit like a massive poo"** (brilliant honest feedback)
  - "almost there. Like the attached but with the top stone actually resting on the others"
  - "again almost there. the top one maybe needs to feel a bit thinner"
  - "haha now it feels too round on top. like unnaturally so"
- Asks about vectorisation: "do you think such a drawing could be vectorised?"

### Phase 2: Icon Development (Messages 20-37)
- Charlie generates icons on various backgrounds, learns transparent backgrounds don't work in AI
- Iterates on specific icons: "the flame and node need to feel more hand-drawn sketchy, like the other two"
- Gets granular: "Less fill on Sustained Partnership please. More like we drawing the circles of the nodes, but not filling them"
- Shows Charlie learning to give increasingly precise creative direction

### The Gem Creation (MAJOR TURNING POINT)
- **Charlie asks: "Do you think we could create a Gem that captures the style of these icons and the original Cairn, such that I can use it to turn around other graphics, LinkedIn banners, etc?"**
- This is the moment Charlie realises he can systematise AI — not just use it once, but build a reusable tool
- Gemini provides comprehensive instructions for creating the Gem
- Charlie and Gemini iterate on the Gem instructions THREE times:
  1. Initial version
  2. Updated with correct hex colours from the website CSS
  3. Updated to fix "everything looks like rocks" problem
  4. Final version with "Fineliner" pen specification

### The "Everything is Rocks" Problem
- Charlie tests the Gem and reports: "the instruction to use stones etc is too dominant. The style is important but it doesn't always need to be 'rustic'. It's really about the hand-drawn style, rather than stones all the time."
- This is a crucial insight about AI prompting: being too specific about one aspect contaminates everything
- Gemini revises to focus on the TECHNIQUE (hand-drawn quality) rather than the SUBJECT (stones)

### Quality Control & Consistency
- Charlie uploads a batch of generated graphics and asks: "Are we achieving a good consistency? Do we need to do more to define the style? Like specify the type of pen, say?"
- Shows Charlie thinking like a brand designer — concerned with consistency across assets
- Gemini audits the work: identifies the variance is in the "pen" used (chalk vs marker vs ballpoint)
- Solution: specify "Ink Fineliner" as the standard tool

### Technical Learning
- Learns about transparent backgrounds in AI generation
- Suggests practical workaround: "black background... easier to remove using Mac Preview"
- Learns about Figma and vectorisation
- Extracts brand colours from website HTML

## Emotional Beats
- **Realisation** — "I've accidentally built something powerful" — creating the Gem is the moment Charlie goes from making individual things to building a SYSTEM
- **Empowerment** — "Maybe I could turn this into an actual product" — he now has a reusable design tool

## Notable Quotes from Charlie
- "My ultimate goal is to create a family of graphics"
- "there's something about it that feels human/real. It's not perfect"
- "I think we're hobbling ourselves by saying we need a hand every time"
- "Let's stop and go back to the start"
- "hmmm - looks a bit like a massive poo"
- "Do you think we could create a Gem that captures the style?"
- "the instruction to use stones etc is too dominant. The style is important but it doesn't always need to be 'rustic'"
- "Are we achieving a good consistency? Do we need to do more to define the style?"

## Prompting Evolution
- MASSIVE leap in sophistication
- Charlie goes from simple requests to writing complex multi-line prompts with specific hex codes, style references, and constraints
- He's now debugging and iterating on SYSTEM PROMPTS (the Gem instructions) — meta-level AI work
- He understands the difference between specifying subject vs technique
- He's thinking about consistency and scalability, not just individual outputs

## Workshop Significance
This chat demonstrates the "compounding capability" theme perfectly:
1. Start with one icon → iterate to get it right
2. Make four icons → learn about consistency
3. Create a Gem → systematise the entire process
4. Test and refine the Gem → debug at the system level
Each step builds on the last. By the end, Charlie has a reusable AI design tool.
