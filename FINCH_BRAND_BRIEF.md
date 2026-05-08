# Finch Brand Brief

> **Purpose**: Design reference for rebranding Coach Claude → **Finch**
> **Domain**: finch.coach
> **Date**: May 6, 2026
> **For**: Claude Design / whoever is updating visual identity and UI copy

---

## 1. The Name

**Finch** draws from two threads:

**Literary**: Atticus Finch — the moral compass of *To Kill a Mockingbird*. A quiet authority who sees clearly, speaks directly, and holds people to a higher standard. He doesn't grandstand; he observes, understands, and then acts with conviction. That's exactly what a coaching supervisor does. The name carries warmth, integrity, and wisdom without being preachy about it.

**Functional**: A finch has a bird's-eye view. The product's core value is pattern recognition across a coach's entire practice — seeing what the coach can't see because they're inside the session. Finch sits above the work, watching the threads, spotting the trends, and surfacing what matters. The bird metaphor is built in without being on the nose.

**Together**: Finch is a wise observer with a moral compass. It watches your practice from above, tells you the truth, and helps you grow. That's the product in a sentence.

---

## 2. Brand Personality

Finch is **not** a chatbot, not an assistant, not a tool. Finch is a **supervisor** — the experienced colleague who's seen it all, asks the hard questions, and genuinely wants you to get better.

### Personality Traits

| Trait | What it means in practice |
|-------|--------------------------|
| **Direct** | Doesn't hedge or flatter. Says "you missed that" when you missed it. |
| **Warm** | Directness comes from care, not judgment. Finch is on your side. |
| **Observant** | Notices patterns you don't. Connects session 3 to session 17. |
| **Grounded** | Rooted in frameworks (IFS, Polyvagal, Kets de Vries) but never pedantic. |
| **Confident** | Speaks with authority. Doesn't apologize for having a perspective. |

### What Finch is NOT

- Not chirpy or eager to please (no "Great question!")
- Not neutral or hedge-everything cautious
- Not clinical or cold
- Not a peer — Finch has earned its perspective

### Voice Examples

**Before (Coach Claude tone)**:
> "Based on your session notes, it seems like there might be some avoidance patterns worth exploring with this client."

**After (Finch tone)**:
> "Sarah has deflected from the leadership transition topic three sessions running. That's not coincidence — that's avoidance. Your pre-session prep should name it directly."

---

## 3. Visual Direction

### Current Foundation (notebook-b)

The existing design system is warm and grounded — keep that energy. The notebook metaphor (parchment backgrounds, serif type, handwritten feel) works well for a coaching tool. Finch should evolve it, not replace it.

### What Stays

- **Warm palette**: Parchment/cream backgrounds, warm neutrals. Coaching is human work; the UI should feel human.
- **Newsreader serif**: Keeps the literary, thoughtful quality. Pairs perfectly with "Finch" (a literary name deserves a literary typeface).
- **JetBrains Mono**: For data, analysis readouts, and anything structured. The contrast between serif warmth and mono precision mirrors the product (warm relationship + rigorous analysis).
- **coaching-700 teal**: Keep as the primary accent. It's distinctive and calm — supervision energy, not startup energy.

### What Changes

- **Logo**: Replace the current placeholder with a Finch mark. Suggestions:
  - A minimal, geometric finch silhouette — side profile, perched and observant (not flying/dynamic). The bird should look like it's watching, not performing.
  - Could be abstracted to just a few lines — a beak angle, a tail, an eye. Think Audubon sketch, not emoji bird.
  - Should work as a favicon (16x16), sidebar icon (24x24), and landing page hero element.
  - Warm palette: use coaching-700 teal or a muted warm tone. Not bright, not playful.

- **Name treatment**: "Finch" in Newsreader, medium weight. No tagline lockup needed for now. The word itself is short and strong enough to stand alone.

- **Subtle bird motifs** (use sparingly):
  - Feather texture as a background element (very faint, not illustrative)
  - "Bird's-eye" as a concept for dashboard/overview views
  - Avoid literal bird illustrations in the UI — the name does the work

### Color Refinement Ideas

Consider adding to the existing palette:

| Token | Hex | Use |
|-------|-----|-----|
| `finch-warm` | `#8B7355` | Warm brown for secondary elements, like a sparrow's plumage |
| `finch-sage` | `#7A8B6F` | Muted green for positive signals (client trending up) |
| `finch-clay` | `#C4A882` | Warm neutral for cards, surfaces |

These are suggestions, not prescriptions. The goal is a palette that feels like a worn leather journal, not a tech dashboard.

---

## 4. Tone of Voice (Copy Guidelines)

### Headlines and CTAs

Keep them short, confident, and benefit-first. Finch doesn't explain itself — it states what it does.

| Instead of | Write |
|------------|-------|
| "AI-Powered Coaching Analysis Platform" | "See your practice clearly" |
| "Upload your transcripts to get started" | "Bring two sessions. See what you've been missing." |
| "Sign up for a free trial" | "Try Finch free" |
| "Request a walkthrough" | "See Finch in action" |

### In-Product Copy

- Use first person sparingly: "I noticed..." is fine for analysis outputs where Finch is the supervisor voice
- Use second person for navigation: "Your clients", "Your practice"
- Avoid hedging language: not "might suggest" or "could indicate" — instead "this pattern suggests" or "pay attention to"
- Error messages should be helpful and human, not corporate

### The Supervisor Voice (AI Analysis Outputs)

This is where the brand lives most. When Finch writes session analysis, pre-session prep, or client insights, it should sound like a seasoned supervisor in a peer consultation group:

- Names specific frameworks when relevant ("through an IFS lens...")
- Points out what the coach did well AND what they missed
- Asks provocative questions ("What happens if you stop rescuing this client?")
- Tracks longitudinal patterns ("This is the third session where...")
- Never sycophantic, never cruel. Honest and invested.

---

## 5. What Needs to Change (Scope of Rebrand)

### User-Facing (P0 — must change before any public demo)

1. **All instances of "Coach Claude"** → "Finch" across:
   - Landing page: headline, subheads, CTAs, footer, meta description
   - Onboarding: welcome screen, step descriptions, sample prompts
   - Sidebar: branding area, navigation labels if any reference the product name
   - Page titles and `<title>` tags
   - Open Graph / social meta tags
   - Favicon (replace with Finch mark)
   - Any email templates

2. **Domain**: Deploy to finch.coach (Dan to purchase and configure DNS)

3. **Landing page content hierarchy** (per Ayman feedback):
   - Lead with value transformation above the fold, not privacy
   - Remove AI-generated testimonial quotes
   - Keep "Request a Walkthrough" as primary CTA for founding cohort

### Internal (P1 — can wait)

- Internal code references (variable names, file paths, repo name) do NOT need to change yet
- GitHub repo can stay `coachclaude2` for now
- Environment variables keep current names

### Design Assets Needed

- [ ] Finch logo/mark (SVG, multiple sizes)
- [ ] Updated favicon
- [ ] Landing page hero visual (if the current one references Coach Claude branding)
- [ ] Social share image (OG image for link previews)

---

## 6. Competitive Positioning

Finch occupies a unique space. For context on how the name/brand should differentiate:

- **Not a chatbot**: Finch is not "talk to AI about your coaching." It's structured analysis with a supervision lens.
- **Not a note-taker**: Otter, Fireflies, etc. transcribe. Finch analyzes — it tells you what you missed and what to do next.
- **Not a coach for the client**: Finch serves the *coach*, not the end client. It's B2B for coaching practitioners.
- **Not generic AI**: The frameworks (IFS, Polyvagal, Kets de Vries) and the supervision persona are what make it specific and valuable.

The name "Finch" should feel like a premium, opinionated product — not a feature or a utility. Think Notion, Linear, or Arc — products where the name carries taste.

---

## 7. Tagline Options (For Discussion)

A few directions to test. None are final — pick or riff:

- **"See your practice clearly."** — Simple, benefit-first. The bird's-eye view idea without saying it.
- **"The supervisor you always have access to."** — Speaks to the core value prop (supervision is expensive and hard to schedule).
- **"Pattern recognition for coaches."** — Technical but accurate. Better for a subhead than a hero.
- **"Your practice, from above."** — Evokes the bird metaphor gently.

---

## 8. Summary

Finch is a wise, warm, direct coaching supervisor with a bird's-eye view of your practice. The brand should feel like opening a well-loved notebook — warm textures, thoughtful typography, and the confidence of someone who's been doing this work for decades. The name carries literary weight (Atticus Finch) and functional meaning (bird's eye view) without needing to explain either. It's short, memorable, and finch.coach is clean.

The visual identity evolves the existing notebook-b system rather than replacing it. The biggest change is the name and logo; the design language is already in good shape.
