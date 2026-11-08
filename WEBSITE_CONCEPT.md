# ONYX DESIGN — Website Concept

## Project status
Concept brief for an independent website proposal, based on the supplied business flyer, logo, vehicle photographs and Facebook screenshots. This document is not a deployed website or an assertion that the business has approved the proposal. Repository name: ONYX-Designs. Customer-facing brand: ONYX DESIGN.

## Objective
Present ONYX DESIGN as a premium detailing and vehicle-protection studio in Reading. Help visitors explore services, view supplied work photographs and request a tailored quote by phone, WhatsApp or email. Do not position the business as a vehicle-design or manufacturing company.

## Visual direction: black and silver
Match the supplied circular black-and-silver logo. Use deep black backgrounds, charcoal panels, brushed-silver borders and silver-to-white typography. The finish should feel restrained and automotive, not like a colourful generic agency template.

### Design tokens
- Background: #08090B
- Alternate background: #101215
- Card surface: #17191D
- Primary text: #F3F4F5
- Secondary text: #B9BDC4
- Silver accent: #CDD1D7
- Decorative border: #34383F
- Metallic gradient: linear-gradient(135deg, #777E88 0%, #F1F3F5 45%, #A6ADB7 75%, #D6DAE0 100%)
- Primary button: silver gradient with near-black text
- Secondary button: transparent charcoal with silver border and white text
- Focus indicator: solid #F3F4F5 outline with visible offset

Use gradients on short headings, buttons and decorative rules only; body text must remain solid and legible. No gold, purple, neon blue or rainbow accents. Colour within authentic vehicle photographs is welcome. Avoid excessive chrome effects, glowing text, heavy shadows or busy marble textures behind copy.

### Typography and layout
Use a clean system sans-serif stack initially: Arial, Helvetica, sans-serif. Use bold uppercase display headings, modest letter spacing on labels, and comfortable sentence-case body text. Keep content within an approximately 1200px container. Use generous spacing, fine dividers, restrained corners and large photography. Build mobile-first with stacked cards, wrapping navigation and no horizontal overflow.

### Logo and photography
Use the supplied original logo without redrawing the car silhouette or changing the business name. Place it against black or charcoal and retain its proportions. Use the supplied black Mercedes or blue Audi as the hero image, with a dark overlay for text contrast. Use vehicle, snow-foam, headlight and interior images in the gallery. Do not use the entire promotional flyer as the homepage.

The source images have been supplied in the project conversation but are not included in this documentation commit. Add optimised image assets separately before implementation; do not reference nonexistent assets as if they are available. Confirm permission for publication, including vehicle registration plates and any customer-identifiable material. Headlight and interior photos are potential before/after material: confirm matching pairs and labels before presenting them as a documented transformation.

## Navigation
Home | Services | Our Work | Protection | Contact
Primary action: Request a quote.

## Homepage content and section order

### 1. Hero
Eyebrow: DETAILING · PROTECTION · PERFECTION
Headline: We don't just clean. We protect & perfect.
Supporting copy: Premium vehicle detailing, paint correction and ceramic protection in Reading.
Primary CTA: Request a quote
Secondary CTA: Explore services
Use the business slogan as the central message, supported by supplied vehicle photography.

### 2. Services
Heading: Every detail. Considered.
Intro: Explore detailing and protection options for your vehicle. Contact the studio to discuss its condition, your goals and a tailored quote.

Service cards based on the supplied flyer:
- Full valet — Interior and exterior cleaning.
- Paint correction and polishing — Discuss a treatment tailored to the condition of your paintwork.
- Ceramic coating packages — Explore paint protection options and aftercare requirements with the studio.
- Interior care and protection — Leather and fabric care options.
- Wheel and caliper protection — Dedicated wheel and caliper treatment options.
- Glass coating — Ask about the advertised Invisible Wiper glass treatment.
- Engine bay detailing — Dedicated engine bay cleaning and detailing.

Each card should lead to a quote enquiry, not a fabricated price or booking slot. Headlight restoration appears in the supplied photographs; confirm it as a currently offered service before adding it to the service list.

### 3. Our work
Heading: The finish speaks for itself.
Use a responsive gallery of supplied vehicle and process photographs. Give every image useful alt text based on what is actually visible. Avoid invented vehicle specifications, treatment histories or dates. Include a before/after component only once image pairs are verified; provide accessible controls and clear labels.

### 4. Ceramic protection
Heading: A finish worth protecting.
Copy: Discover ceramic coating options for your vehicle. Speak to ONYX DESIGN about preparation, treatment selection and aftercare.
The flyer advertises two-, three- and five-year packages. Confirm products, terms, maintenance requirements, availability and any warranty before presenting these durations as current offers. Do not promise scratch-proof paint, guaranteed resale gains or permanent protection.

### 5. Specialist detailing
Heading: Beyond the everyday drive.
The flyer advertises care for daily cars, luxury vehicles, sports cars, boats and aircraft. Present boats and aircraft as specialist enquiries, with mobile service described only for those categories pending confirmation. Do not imply that all car services are mobile. Confirm service scope and suitability before publishing specialist claims.

### 6. Customer recommendations
The supplied Facebook screenshot shows 100% recommended based on the opinions of 12 people. Attribute this explicitly to Facebook and treat it as a screenshot-time observation, not a live rating or a five-star score. Verify before publication. Do not invent testimonial text, reviewer identities or full quotations from truncated snippets.

### 7. Contact
Heading: Let's talk about your vehicle.
Copy: Tell us about your vehicle, the service you are interested in and the finish you have in mind.
- Phone: 07387 424933
- Telephone link: tel:+447387424933
- WhatsApp: https://wa.me/447387424933
- Email: onyxdesign2026@gmail.com
- Email link: mailto:onyxdesign2026@gmail.com
- Location: Reading, United Kingdom

Contact details are transcribed from supplied Facebook screenshots and must be confirmed before launch. The flyer also lists 07713 894786; do not publish it as a second current number without confirmation.

For the initial concept, use direct contact links rather than a nonfunctional form. If a form is implemented later, label fields, validate input, provide honest success/error states, and connect a real submission destination before enabling it. Do not collect data in a pretend booking flow.

## Interaction and accessibility requirements
- Responsive navigation with labelled keyboard-operable mobile controls.
- Visible keyboard focus, semantic headings, a skip link and descriptive link labels.
- Maintain readable contrast; silver styling must not make text faint.
- Respect reduced-motion preferences; no autoplay video or compulsory animation.
- Optional mobile contact bar must not cover content or keyboard focus.
- Optimise photographs and reserve image dimensions to prevent layout shifts.
- No invented availability, customer counts, accreditations, awards or guarantees.

## Implementation scope
First version: a responsive single-page concept with services, work gallery, protection information and direct contact actions. A lightweight static implementation is sufficient; no paid booking system, login or payment integration is required for the concept. Final stack and hosting remain undecided. This commit only adds the brief and does not enable GitHub Pages or deploy a site.

## Outstanding business checks
- Obtain the expanded pinned Important Notice before finalising operational copy.
- Confirm the full street address; the screenshot address is incomplete. Do not create a precise map pin from it.
- Confirm appointment hours; Facebook's Always open must not become a promise of 24-hour appointments.
- Confirm Instagram: Facebook shows onyxdesign2026, while the flyer shows a different handle.
- Confirm current services, package terms, prices and specialist/mobile coverage.
- Confirm contact details and photography/logo publication permission.
- Verify recommendation statistics and obtain complete review text before quoting.
- Keep a public preview clearly identified as an independent concept until business approval.

## Acceptance criteria
The finished concept should visibly match the black-and-silver logo, use authentic supplied imagery where authorised, work on mobile and desktop, provide clear contact paths, and contain no fabricated business details. All uncertain operational information must remain omitted or clearly marked for confirmation until verified.
