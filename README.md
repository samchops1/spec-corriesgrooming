# Corrie's Pet Grooming — spec-site preview

- **Suggested slug:** `corriesgrooming`
- **Target host (not live, do not claim it is):** corriesgrooming.capitalreconsulting.com
- **Current public site:** https://4storeysgrooming.wixsite.com/corriesgrooming
- **Site path:** `/workspace/previews/corriesgrooming/index.html`
- **One-line note (Outreach):** Replaced the default Wix brochure — leftover Planned Pethood Plus title chrome and a 4storeysgrooming host name — with a Wheat Ridge Harlan Street wash card for Corrie's Pet Grooming: cats a specialty, dogs / rabbits / guinea pigs, no-sedation difficult pets, click-to-call (303) 433-2499.

This folder is a static preview only. Do not treat the target host as live. Architect/PM own CNAME + HTTPS kick.

## What changed vs their current site

Stripped the Wix “This site was designed with the .com website builder” chrome, the leftover browser title “Planned Pethood Plus,” unnamed Wix media (sign tile tagged Planned Pethood Plus), and the template one-pager. Rebuilt a mobile-first four-page shop as a Harlan Street wash card: enamel cream `#f3ebe0`, clay rust `#9c3f2c`, wheat gold `#c9a15a`, deep ink `#1f1b16`, sage `#5f7358`, Cormorant Garamond + Nunito Sans, a sticky call/email dock on phones, and type + original SVG instead of Wix frames.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **Corrie's Pet Grooming** / **Corrie's** | Homepage / Wix title |
| Lockup **Corries ○ Grooming ○** | Homepage visible text |
| City **Wheat Ridge, CO 80033** | Homepage address + JSON-LD |
| Street **4595 Harlan Street, Wheat Ridge, Colorado 80033** | Homepage CONTACT / ADDRESS (printed “4595 HARLAN STREET”) |
| Phone **(303) 433-2499** / `tel:+13034332499` | Homepage Phone Number; also printed 303-433-2499 |
| Email **4storeysgrooming@gmail.com** | Visible mailto on page |
| Owner **Corrie** (first name only) | Shop name Corrie's; no last name printed |
| Facebook **https://www.facebook.com/Corries-Pet-Grooming-1125382540939950/** | “Visit Our Facebook Page!” link |
| Current site **https://4storeysgrooming.wixsite.com/corriesgrooming** | Live host |
| Services: bath, brush, haircuts/trims, ear cleaning, nail trims (including ingrown and broken), teeth brushing | OUR SERVICES |
| Specialize in cats; also dogs, cats, rabbits, guinea pigs | OUR SERVICES |
| Able to handle difficult dogs and cats without sedation | OUR SERVICES |
| Nail trimming: dogs **$15.00**, cats **$18.00**. *Price will rise if your pet is difficult. | PRICES / Nail Trimming |
| Grooming: Small dogs **$50–$55**; Medium dogs **$60–$65**; Large dogs depending on breed, **$65 and up**; All cats **$80 and up** | PRICES / Grooming |
| **Prices vary based on size and difficulty of animal.** | PRICES |
| Unlabeled **Tuesday–Saturday 8–5** block (no heading in HTML) sitting under grooming prices | Homepage rich text under Grooming prices |
| **Daily Hours:** Tuesday–Saturday 10–2 | Homepage heading Daily Hours |
| **Walk-in Nail Trims:** Tuesday–Saturday 9–12 | Homepage heading Walk-in Nail Trims |
| **Walk-in Grooming:** heading only, no times | Homepage heading Walk-in Grooming |

## Facts deliberately omitted / stale

- **“Planned Pethood Plus”** — leftover browser title and image alt (“Corrie's Pet Grooming sign at Planned Pethood Plus”). Not printed on customer pages.
- **4 Storeys / 4storeysgrooming as a brand** — leftover Wix account / mailbox / host name. Used only as the live URL and the printed email. Shop is not renamed 4 Storeys.
- **Corrie last name** — not printed. Not invented. Owner is Corrie only.
- **Unlabeled 8–5 heading** — no “Shop Hours” / “Business Hours” in the HTML. Shown as Tuesday–Saturday 8–5 because the rows are clearly hours (same day:time pattern as Daily Hours). Not given an invented heading. Not merged with Daily Hours or walk-in lists.
- **Walk-in Grooming times** — heading exists, no times printed. Not invented.
- **Closed Sunday / Monday** — implied by Tuesday–Saturday lists only. Pages say Tuesday–Saturday. Do not print “closed Sunday.”
- **JSON-LD openingHours merge** — the three lists are not reconciled. JSON-LD uses only the labeled Daily Hours (`Tu-Sa 10:00-14:00`).
- **Wix JSON-LD name “Corries' Pet Grooming”** and street “4595 Harlan St” — leftover schema punctuation. Customer copy uses Corrie's Pet Grooming and 4595 Harlan Street.
- **Insurance, years in business, reviews, extra cities, extra animals, extra prices, extra services, sedation alternatives** — not printed. Not invented.
- **Wix builder banner**, template chrome, unnamed Wix media. Not treated as job photos.
- **Any claim this preview is live** at corriesgrooming.capitalreconsulting.com.

## Pages

- `index.html` — Corrie's, cats a specialty, also dogs/rabbits/guinea pigs, no-sedation difficult pets, primary call (303) 433-2499, mailto, address, walk-in nail hours, price snapshot
- `services.html` — services + full printed price list
- `about.html` — Corrie (first name only), Wheat Ridge / Harlan Street, cat specialty
- `contact.html` — phone, email, 4595 Harlan Street Wheat Ridge CO 80033, labeled hours, Facebook link, mailto draft form

Forms open a mail draft to 4storeysgrooming@gmail.com. They do not post to Wix.

## Images

No real job photo. Live Wix frames are leftover default media (sign tile tagged Planned Pethood Plus). Hero is `assets/hero.svg` (wash table, enamel basin, cat and dog). Logo is an enamel-basin SVG plus an SVG favicon. No 1MB+ files. No fat original.

## JSON-LD

`LocalBusiness` + `PetGrooming` on the homepage only, verified fields: name, telephone, email, live Wix URL, street address 4595 Harlan Street, Wheat Ridge CO 80033, description, founder Person name Corrie (no last name), openingHours only the labeled Daily Hours `Tu-Sa 10:00-14:00`. No aggregateRating, no invented geo, no merged hours.

## Blockers

- Three different hour lists on one homepage; 8–5 block has no heading.
- Walk-in Grooming heading with no times.
- Leftover Planned Pethood Plus title chrome.
- Thin default Wix brochure.
