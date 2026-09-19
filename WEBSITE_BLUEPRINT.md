# Website Blueprint — SLEEPY BREW HOUSE

## Research snapshot — 20 Sep 2026
- Business: Sleepy Brew House
- Type: Home-based takeaway specialty coffee + matcha
- Area: Serangoon North / Affinity @ Serangoon, Singapore
- Current evidence: Tabaous lists it as a live/reopening home business, brewing daily, available for bulk orders, with after-hours orders via Instagram DM.
- Public location evidence: Serangoon North Ave 1. HomeBoss separately lists 24 Serangoon North Ave 1, #09-37, Block 130, Singapore 554339. Treat residential-unit information as private and expose only owner-approved pickup details.
- Phone: not independently verified.
- WhatsApp: not independently verified.
- Instagram: presence evidenced; exact handle not independently verified.
- Standalone official website: none found in this research pass.
Sources: https://tabaous.com/ and https://homeboss.io/

## Product/website objective
Create a polished digital home that converts Instagram discovery into a clear menu, preorder and bulk-order journey without exposing unnecessary residential information.

## Multipage architecture
1. Home — cinematic hero, open/next-session status, signature drinks, social proof, preorder CTA.
2. Menu — coffee, matcha, seasonal drinks; ingredients, prices, availability badges.
3. Order — pickup workflow, ordering windows, bulk-order CTA.
4. About — founder/brewing story and home-cafe philosophy.
5. Visit — area-level directions and privacy-conscious pickup guidance.
6. Bulk & Events — office orders, small events, enquiry.
7. FAQ — ordering, pickup, payment, lead times, allergens, changes.
8. Contact — only verified Instagram/WhatsApp/contact methods.

## Visual direction
Professional specialty-coffee minimalism: cream, charcoal, warm coffee brown and restrained amber. Large editorial type, generous whitespace, tactile grain, subtle steam/liquid imagery. Avoid generic stock-cafe templates.

## Motion + VFX
- 1.2–1.5s logo/steam intro.
- Slow hero steam/parallax shader.
- Every section: staggered fade + translate + blur-to-sharp on enter; reverse on exit.
- Menu cards: masked image reveal, subtle 3D tilt and magnetic CTA.
- Page transitions: soft crossfade/clip-path.
- Small coffee-particle/steam accents only; no distracting effects.
- Full prefers-reduced-motion fallback.

## Functional requirements
- Sticky mobile preorder CTA.
- Data-driven menu/hours so owner can update without redesign.
- Accessible focus states and semantic headings.
- Local SEO/schema where appropriate.
- Optimized WebP/AVIF images and lazy loading.
- Never invent phone, handle, hours, payment methods or menu prices.
- Do not publish exact residential-unit details unless owner explicitly approves.

## Technical direction
Separate HTML/CSS/JS (or clearly separated framework components), GSAP + ScrollTrigger for scroll choreography, optional lightweight WebGL hero texture, no heavy 3D scene that harms mobile performance.