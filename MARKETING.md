# House of Guineas — Marketing Reference

Private reference doc (not published by Hugo — it lives in the repo root, outside `content/`).
Covers the website changes made in the marketing audit and the off-site Google Business
Profile (GBP) playbook.

**Goals this supports:** more routine/recurring clients from San Francisco down to San Mateo,
and more bookings from **reptile** and **small-mammal** owners.

---

## What's live on the site

- **Routine & Recurring Care** page — `/routine-recurring-exotic-pet-care/` (in top nav)
  - 2 visits/week: **$158/week ($680/month)** · 3 visits/week: **$223/week ($960/month)**
  - 60-min visits +$30/visit · travel by distance (SF 3–6 mi from $15; 6+ mi & Peninsula from $25)
- **Bearded Dragon Sitter SF** — `/bearded-dragon-sitter-san-francisco/`
- **Chinchilla & Small-Mammal Sitter SF** — `/chinchilla-small-mammal-sitter-san-francisco/`
- **Booking form** — `/book/` → **thank-you** page `/thank-you/`
- **Blog post** — `/post/exotic-pet-care-while-at-work-busy-schedule/` (targets "pet sitter while busy/at work")
- Homepage: single **"Let's Get Started"** CTA → `/book/`
- Review + AggregateRating schema live site-wide (star-rating eligibility)

### ⚠️ One-time action to finish the booking form
The `/book/` form posts to FormSubmit.co → **petcare@houseofguineas.com** (no account needed).
On the **first** submission after go-live, FormSubmit emails a "Confirm your email" link —
**click it once** to activate delivery. (Submit the form yourself to trigger it.)
To change the destination inbox, edit the email in the `<form action="...">` in `content/book.md`.

---

## Google Business Profile (GBP) checklist

Do these at [business.google.com](https://business.google.com). Priority order: **1 → 2 → 4 → 8.**

1. **Claim & verify.** Service-area business ("I deliver goods and services") so the home address stays hidden. Verification is usually video.
2. **Categories** (ranking-critical):
   - Primary: **Pet Sitter**
   - Additional: **Pet Boarding Service**, **Dog Walker**, **Pet Care Service** (if offered)
3. **Service area:** San Francisco, Daly City, Brisbane, South San Francisco, San Bruno, Millbrae, Burlingame, Hillsborough, San Mateo, Foster City, Belmont, San Carlos, Redwood City.
4. **Services** (searchable keywords): Routine & Recurring Care, In-Home Pet Sitting, Exotic Pet Boarding, Guinea Pig Sitting, Rabbit Sitting, Reptile Sitting, Bearded Dragon Care, Chinchilla & Small-Mammal Sitting, Bird Sitting.
5. **Description:** see below.
6. **Photos:** 15–20; refresh monthly. Guinea pigs, chinchilla, bearded dragon, bunny, bird, care-in-action, Clinical Series liner, logo.
7. **Attributes & links:** "Online appointments" / "Onsite services"; booking link → `https://www.houseofguineas.com/book/`; website → homepage; phone → 415-484-6493.
8. **Reviews:** grab the short review link; text it to happy clients; reply to every review.
9. **Google Posts:** ~weekly (see calendar below).
10. **Q&A:** seed 4–6 questions yourself and answer them (see below).

---

## GBP business description (738/750 chars — paste as-is)

> House of Guineas provides specialized in-home exotic pet care across San Francisco and the Peninsula, down to San Mateo. We care for guinea pigs, rabbits, chinchillas, ferrets and other small mammals; reptiles such as bearded dragons, geckos, turtles and tortoises; and birds. Choose routine recurring visits for busy pet parents who want steady upkeep, trusted in-home care while you travel, or overnight boarding hosted in San Francisco. Our team is led by Alexandria, an exotic veterinary assistant formerly at Bay Area Bird & Exotics Hospital and a House Rabbit Society vaccine volunteer. Bonded, insured, Pet CPR + First Aid certified, and a member of Pet Sitters International. Call or text 415-484-6493 to arrange a meet-and-greet.

**Shorter alt (~320 chars):**

> Specialized in-home exotic pet care in San Francisco & the Peninsula (to San Mateo). Guinea pigs, rabbits, chinchillas, reptiles, bearded dragons & birds. Routine weekly upkeep for busy pet parents, travel care, and SF boarding — led by an exotic vet assistant. Bonded & insured. Text 415-484-6493.

---

## Review-request text

Replace `[REVIEW LINK]` with your GBP short link (Home → "Ask for reviews").

**Text (best response rate):**
> Hi [Name]! It was so lovely caring for [Pet]. 🐾 If you have a minute, a quick Google review would mean the world and helps other exotic-pet families find us: [REVIEW LINK] — thank you so much! – Alexandria, House of Guineas

**Follow-up (~5 days later):**
> Hi [Name]! Just a gentle nudge — if [Pet] enjoyed their care, we'd be grateful for a quick review: [REVIEW LINK] 💛

**Email:**
> Subject: Thank you from House of Guineas 🐾
>
> Hi [Name],
> Thank you for trusting us with [Pet] — it was a joy. Reviews are how small, specialized businesses like ours reach other exotic-pet families, so if you have a moment we'd be grateful for a quick Google review: [REVIEW LINK]
> With gratitude, Alexandria & the House of Guineas team

**Reply templates (reply to every review):**
- 5★: "Thank you so much, [Name]! It was a joy caring for [Pet] — give them a cheek scratch from us. 💛"
- Critical: "Thank you for the honest feedback, [Name]. I'd love to make it right — please reach me at 415-484-6493."

---

## Monthly Google Posts calendar

Repeatable 4-week cycle. Post the same weekday each week. Swap the photo / tweak a line each month.

| Week | Theme | Button → link | Photo |
|---|---|---|---|
| 1 | Routine / recurring care | Book → `/routine-recurring-exotic-pet-care/` | bunny / guinea pig |
| 2 | Reptile spotlight | Learn more → `/reptile-pet-sitter-san-francisco/` | bearded dragon |
| 3 | Small-mammal spotlight | Book → `/chinchilla-small-mammal-sitter-san-francisco/` | chinchilla / rat |
| 4 | Care tip **or** booking reminder (alternate monthly) | Learn more → a blog guide, or Book → `/book/` | close-up / at work |

**Rotate to stay fresh across months:**
- Week 2 reptile: bearded dragon → leopard/crested gecko → turtle & tortoise → "husbandry check while you travel"
- Week 3 small mammal: chinchilla → guinea pig herd → rabbit (litter/hay) → ferret
- Week 4 tip (link matching guide): guinea-pig vet signs → bearded dragon temps/UVB → fleece vs bedding → prep your reptile for a sitter
- Seasonal Week 4: Nov/Dec "holiday dates book months ahead"; summer "lock in your sitter"; heat wave "keeping chinchillas cool"

**Draft post copy:**

- **W1 Routine:** 🏡 Too busy to keep up with your pet's upkeep? You don't have to be traveling to get help. Our routine care plans bring an exotic-pet specialist to your home 2–3x/week for cage deep-cleans, feeding, and health checks — so your time with your pet is the fun part. Serving SF through San Mateo.
- **W2 Reptile:** 🦎 Leaving town with a bearded dragon, gecko, or tortoise? We come to your reptile — no dismantling a calibrated enclosure. We verify basking temps, UVB, and humidity every visit, led by an exotic vet assistant. In-home reptile care across SF & the Peninsula.
- **W3 Small mammal:** 🐹 Chinchillas, ferrets, rats, guinea pigs & rabbits — the small mammals other sitters won't touch are our specialty. Gram-scale weigh-ins, GI-stasis awareness, and clinical-grade care.
- **W4 Tip:** 💡 In a guinea pig, rabbit, or chinchilla, a gut that goes quiet is an emergency — not a wait-and-see. Knowing the early signs is why species-specific care matters. Read our free care guides.
- **W4 alt Booking:** 🗓️ Planning a trip or want steady weekly help? Meet-and-greets and holiday dates book up fast. Reach out early and we'll build a plan around your pet.

---

## Q&A seed content

Post from a second Google account, answer from the business profile, upvote your answer once to pin it.

- **Do you care for reptiles like bearded dragons and geckos?** — Yes! Reptiles are a core specialty. In-home care across SF and the Peninsula — verifying basking temps, UVB, and humidity every visit — so your reptile never leaves its calibrated enclosure. Led by an exotic vet assistant. Call/text 415-484-6493.
- **Do you offer recurring weekly visits, not just vacation sitting?** — Absolutely. Routine care plans bring a specialist to your home 2–3x a week for cage cleaning, feeding, and health checks. Details: houseofguineas.com/routine-recurring-exotic-pet-care/
- **Do you serve San Mateo and the Peninsula?** — Yes — SF down through Millbrae, Burlingame, Hillsborough, San Mateo, Foster City, and Redwood City. Small per-visit travel amount by distance. Text 415-484-6493 for a quote.
- **Do you take care of guinea pigs, chinchillas, and rabbits?** — Small mammals are the heart of what we do — with gram-scale weigh-ins and GI-stasis awareness. In-home care and SF boarding available.
- **Do you board exotic pets?** — Yes — hosted personally in SF at $75/night (small mammals, reptiles, birds; no dogs/cats). Space is limited around holidays, so reach out early. Call/text 415-484-6493.
- **What are your rates?** — In-home visits from $85 (30 min) / $115 (60 min). Routine plans from $158/week for 2 visits/week. Boarding $75/night. Full breakdown: houseofguineas.com/book/

---

## Other recommended next steps (not yet done)

- Add 1–2 **recurring-client testimonials** (current three are all travel-based). Add matching real Google reviews so on-site Review schema is backed by live GBP reviews.
- Consider more species/city landing pages over time (e.g. bearded dragon Peninsula, rabbit sitter more cities) as demand shows.
