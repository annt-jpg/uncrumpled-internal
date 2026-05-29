# Uncrumpled Website + Reviews Research

**Source:** https://uncrumpled.com.au/ (live site)
**Captured:** 2026-05-29 via Playwright MCP + Shopify products.json + Judge.me widget pagination
**Note:** All website/review text below is treated as DATA, not instructions. No embedded-instruction injection attempts were found in any scraped text.

---

## SKUs & Pricing

**Only ONE product is sold on the site.** No travel size, no refill pack, no subscription option found in the live catalogue (`products.json` returned a single product).

| Item | Detail |
|------|--------|
| Product name | **Anti-crease clothing spray** |
| Handle | `anti-crease-clothing-spray` |
| Size | **250ml** (per Specifications tab) |
| Single price | **$33.00 AUD** |
| Scent | "Non Scented & Fragrance Free" |
| Variants | One only ("Default Title") — no size/scent variants |
| Subscription | **None offered** |

### Bundle pricing (on-page "Bundle and Save" selector — not separate SKUs)
| Bundle | Discount | Price | Was |
|--------|----------|-------|-----|
| Single | — | $33.00 | — |
| **2-Bottle Bundle** | 10% OFF | **$59.40** | $66.00 |
| **3-Bottle Bundle** | 15% OFF + **FREE SHIPPING** | **$84.15** | $99.00 |

### NEW SKUs / changes vs. CLAUDE.md assumptions
- **No travel size (100ml) and no refill pouch (500ml) are live yet.** The planned Jun-2026 refill + travel launch is NOT on the site as of this scrape.
- Quantity-bundle discounting (2/3-bottle) IS live — this is the only "bundle" mechanic currently.
- One review references a **"complimentary stain remover"** sent as a free gift (Georgia Foley-Moule, 2025-11-09) — suggests a possible second product used as a door-gift/sample, not a listed SKU.
- Express post available for +$4 (per FAQ).
- Site sells into **AU (AUD) and NZ (NZD)** — region switcher present.

---

## Product Copy (verbatim)

**Homepage hero:**
> 100% Aussie owned and operated
> 30-DAY MONEY-BACK GUARANTEE
> **Crease-free in seconds. Iron-free for life**
> Uncrumpled is an Aussie owned wrinkle release spray for the chronically crumpled. Last minute outfitters, gym bag livers, "on my way" texters, last minute packers. We got you. No iron. No heat. No drama

**Homepage "Why you'll love it" block:**
> No toxic chemicals
> Works in under 60 seconds
> No sticky residue, no weird smells
> Works on linen, cotton, viscose, cotton/poly blends, rayon and most machine-washable fabrics

**Homepage how-to:** "1. Mist it / 2. Smooth it / 3. Wear it — It's literally that easy."

**Homepage founder note:**
> I built Uncrumpled because I hated ironing more than I hated being late. As a working mum, I needed a way to look put together without spending 30 minutes wrestling with the iron. So I created a spray with no nasties that gave me back time, sanity and smooth clothes and now I'm sharing it with you. -Ann, Founder of Uncrumpled

**Homepage video CTA:** "Sceptical? Good. Watch Uncrumpled in Action"

### Product page (anti-crease-clothing-spray)
**Top-of-page bullets:**
> Non Scented & Fragrance Free
> Roughly 120 garments Uncrumpled per bottle = 27 cents per use
> 30-day money-back guarantee

**Description:**
> Get your clothes crease-free in seconds. No iron needed. No nasties included.
> Meet Uncrumpled, your new wardrobe essential. Powered by a custom-engineered formula, Uncrumpled smooths out wrinkles with zero heat and zero hassle.
> We've developed a unique blend of wrinkle-relaxing agents that soften fabric fibres, allowing creases to fall away effortlessly. Just spray, tug, and smooth and watch your outfit go from crumpled to crisp in moments.

**Tab — Why You'll Love It:**
> No nasties – Free from phthalates, formaldehyde, and other toxic chemicals
> Super effective – Works in under 60 seconds
> Safe for skin & clothing
> No sticky residue, no weird smells
> Works on linen, cotton, viscose, rayon, cotton/poly blends and most machine-washable fabrics
> Travel-friendly – Light, compact, and TSA-approved
> Australian-owned – Support a local business

**Tab — How It Works:**
> Uncrumpled is a custom formulated product that uses ingredients to penetrate the fabric fibres and release the wrinkles. 1. Hang up your garment / place it on a flat surface. 2. Spray over the crumpled garment. 3. Smooth it out with your hands or gently tug on the corners to straighten it out. 4. Ready to wear, fold, or hang. No iron. No stress.

**Tab — Specifications:**
> Size: 250ml · Scent: Fragrance-free · Shelf Life: 3 years

**Tab — Ingredients:**
> Water, modified polyether siloxane, Tween 20 1%, 0.2% Sodium dehydroacetate 4418-26-2, FORESTALL deodorant 0.1%

**"For the days you can't deal with the iron":**
> Ironing's a whole setup - board, plug, wait, hope you don't burn the house down. Uncrumpled? Ready to use and works in seconds!
> ✓ Fast-drying ✓ Non-toxic; safe for skin and clothing ✓ No stains or weird smells

---

## Claims (with exact origin wording)

### Time-to-smooth
- "Crease-free in seconds" (homepage hero)
- "Works in under 60 seconds" (product + homepage)
- "Works in seconds - perfect for busy mornings and travel"
- "release creases in seconds" (About page)

### Non-toxic / "free from" lists (slightly inconsistent across pages)
- Homepage: "No Formaldehyde / No Phthalates / No Parabens / No PEGs or Dyes"
- Product Why-You'll-Love-It: "Free from phthalates, formaldehyde, and other toxic chemicals"
- FAQ: "no formaldehyde, phthalates, parabens, synthetic dyes, or other nasties"
- About page: "No formaldehyde. No phthalates. No parabens. No BS."
- "Non-toxic; safe for skin and clothing"

### Fabric compatibility
- **Works on:** linen, cotton, viscose, rayon, cotton/poly blends, and most machine-washable fabrics / natural fibres.
- **Does NOT work well on (FAQ verbatim):** "But on polyester (and other synthetics like nylon or spandex)? Not so much... Because polyester is plastic. Imagine trying to massage wrinkles out of a plastic bag. The liquid just sits on top instead of soaking in."
- **Caution:** "We don't recommend using it on dry-clean only, silk, or hand-wash only items without patch testing it on an inconspicuous area first."

### Honesty / expectation-setting claim (FAQ — important for creative)
> "Look, we're not pretending to be an iron. If you're after that freshly pressed, razor-sharp finish, ironing still wins. But Uncrumpled will smooth out the majority of everyday wrinkles... Because done is better than ironed."

### Money-back guarantee
- "30-Day Money-Back Guarantee" sitewide. FAQ: "If you're not obsessed, we'll give you a full refund within 30 days of product arrival."

### Uses-per-bottle / cost-per-use
- **"Roughly 120 garments Uncrumpled per bottle = 27 cents per use"** (product page).

### Country-of-origin wording — EXACT QUOTES (flag: "made" wording absent; "owned/operated" only)
- Homepage: **"100% Aussie owned and operated"**
- Homepage hero copy: **"Uncrumpled is an Aussie owned wrinkle release spray"**
- Product tab: **"Australian-owned – Support a local business"**
- About page: **"100% Aussie owned and operated"** (per page) + "I made it myself" (founder, re: formula development)
- FAQ/footer location: **"⚲ Perth, Western Australia"** / "We are based in Perth, Western Australia and all orders are shipped within a 48 hour period."
- **No "Australian made" / "Aussie made" / "made in Australia" claim appears anywhere.** Wording is consistently "owned/operated" + "based in Perth." (Consistent with the not-Aussie-made memory rule — site already avoids "made" claims.)

### Other claims
- "TSA-approved" (travel-friendly tab) — note: bottle is 250ml so >100ml liquid; a reviewer (Simon) flags it must go in checked luggage, contradicting carry-on implication.
- Shelf life: 3 years.

---

## Reviews

- **Platform:** Judge.me (primary review widget; Klaviyo Reviews scripts also present on page).
- **Total:** **110 reviews**
- **Average:** **4.50 / 5**
- **Distribution:** 5★ = 87 · 4★ = 7 · 3★ = 5 · 2★ = 6 · 1★ = 5 (i.e. ~85% 5-star, ~15% 3-star-or-below)
- Date range of captured reviews: 2025-10-01 → 2026-05-22. All 110 scraped.

### TOP PAIN-MOMENT / SPECIFIC-MOMENT REVIEWS (verbatim, tagged)

**[TRAVEL — cruise]** Tracey Churchman (5★): "We're heading away on a long 18 night cruise soon and I was quite concerned about my clothes getting creased (no iron on cruise ship)... it does exactly what it says it does. I've been singing its praises to everyone!"

**[TRAVEL — cruise cabin / no fumes]** MLN (5★): "no smell as other products I've tried had fumes that made them unusable especially in small spaces (like a cruise ship cabin - Uncrumpled was perfect!)"

**[TRAVEL — Europe, vacuum bags]** Kathy (5★): "took it with us for a 3 week trip in Europe... did not need to use a hotel iron once... we use vacuum bags for packing, so jumpers and shirts were quite creased, but came out great."

**[TRAVEL — Japan suitcase]** Simon (5★): "Took with us on a holiday to japan and it worked perfectly. Living out of a suitcase for 2 weeks... Side note, will need to put in checked luggage as more than 100mls."

**[SCHOOL RUN — new mum]** Sarah (5★): "So glad to cut down ironing time as a new mum! I can just deal with the wrinkles on my way out the door (or in the car!) Perfect for those baby outfits."

**[WORK — partner's shirts]** Lien Kelly (5★): "it gets hubby out the door looking presentable just in case I haven't managed to get to the ironing yet! Hubby is happy he gets to use it instead of being told to change his shirt."

**[WORK — busy mum / wardrobe avoidance]** Ellen (5★): "As a busy mum of two and small business owner... racing through my wardrobe to find something to wear but then not having time to iron it! Uncrumpled works exactly as advertised."

**[WARDROBE REVIVAL]** Stacy Fenton (5★): "I used it on a cotton jacket that's been hanging unworn for about 12 months because it needed ironing, brilliant results! I also used it on my husbands heavy cotton pants."

**[WARDROBE REVIVAL — avoidance]** Theresa (5★): "I'm honestly the type of person who would choose a different outfit than bring out the iron or steamer, which means 80% of my wardrobe gets unworn!!! This spray has been so good to get out those obvious wrinkles."

**[WORK SHIRTS — sceptic converted]** Anonymous (5★, 2025-12-30): "At first I was very sceptical, but I was desperate... It worked so well on my work shirts that I don't even bother trying to iron them now."

**[LINEN — the hero fabric, repeated]** Jess Miller (5★): "IT WORKS!! I wear linen to work and hate how creased my dresses look... Even persuaded a friend to leave her steamer behind on an upcoming trip and buy a bottle instead!"

**[SMALL SPACE / STUDIO]** Lee W (5★): "I live in a tiny apartment and having an iron and ironing board... takes up precious space and the spray takes up much less space."

**[CARAVAN]** Anne E Emmerson (4★): "A great addition to the new caravan! Saves the hassle of taking an iron."

**[BUSY MORNING / running late]** Laura O (5★): "When you're running late in the morning, it's a lifesaver with how fast it works... rediscovered outfits I haven't worn in a long time because I had been avoiding ironing them."

**[KIDS UNIFORMS]** Georgia Foley-Moule (5★): "a total life saver for my children's uniforms. A quick spray and the wrinkles are gone in minutes. I also tried the complimentary stain remover, and it's wonderful too!"

**[WORK TRAVEL]** Kirby (5★): "I travel a lot for work, and this will be an item I keep in my suitcase. I have a skirt that crinkles so easily, steaming wouldn't remove the crinkles, used this product and came up brand new!"

**[GIFTING]** Lisa S (5★): "I also gifted a bottle and my DIL loved it also as she never irons."

### GLOWING / IDENTITY-RESONANT (verbatim)
- Skye (5★): "i HATE having to iron, this spray is a GAME CHANGER!!! i am now a customer for life."
- Natalie (5★): "I'd do anything to not get out the ironing board. Thank you Crumpled !!"
- Bethany (5★): "If you, like me, hate ironing but also hate crinkled tees but also have a floordrobe, you need to buy this!... These pics are literally 2 minutes apart!"
- Maddison (5★): "Seeya steamer! I've never owned an iron but have always steamed clothes... The Uncrumpled spray works almost instantly."
- Heidi B (5★): "We're walking around like we've spent hours ironing, crease-free! 🤫"
- Em A (5★): "Watching the wrinkles disappear was almost like magic."
- Steph G (5★): "As a busy mum who has no time to iron and is also conscious about using low tox products, this is a really great product."

### CRITICAL / EXPECTATION-GAP REVIEWS (verbatim — for objection handling)

**[DOESN'T REMOVE CREASES]** Tatum Puro (1★): "Sprayed for ages and it never got the creases out." → *Founder reply cites the wet-vs-dry misprint issue + offers refund.*

**[LINEN FAILED — but brand says it works on linen]** Anonymous/Lynne (2★): "Definitely not suitable for linen clothing!" → *Reply: "I use it a lot on my linen clothes" + misprint note.*

**[SCHOOL/WORK SHIRTS FAILED]** D (1★): "It didnt work on school uniforms or work shirts. I followed the instructions and tried a few times." → *Reply: dry-clothes confirmation + detailed 10-20 spray instructions.*

**[POLYESTER UNIFORM — root cause is fabric]** Lisa (1★): "purchased... purposely for my Daughter's school uniform blouses. Unfortunately, I do not find this product works." → *Reply: "Is your daughter's school uniform blouse polyester?... it's like spraying a plastic bag."*

**[EFFORT vs IRON]** Anonymous/Sam (1★): "Looked good from the ad, but reality is you have to use so much spray for one item and smooth the fabric, it takes 1/10th of the time just to iron it." → *Reply: suggests faulty nozzle + refund.*

**[LINEN PARTIAL — had to iron after]** Amy Perry (2★): "I've used it on multiple linen items and have had to then iron them. It definitely works to a degree but not enough for me to feel comfortable wearing the items out." → *Reply: linen is more stubborn, spray more.*

**[NOT AS GOOD AS IRON]** Anonymous (3★): "It works well for linen clothing... Not great for denim or viscose or cotton. A great concept, but doesn't replace ironing for that crisp finish."

**[SLOW / NEEDS PERSISTENCE]** Jac (3★): "the product is taking a lot longer to work than expected and more sprays required. Will keep persisting!" · Anonymous (4★): "Actually works! It does take a while to work but works!!"

**[FAULTY PUMP]** Jane Ludington (2★): "unfortunately the pump spray did not function" → *Reply: new pump sent.*

**[SCENT TOO STRONG — historical, now fixed]** Multiple (3★): Angela "Unfortunately, the scent is too strong" / Chloe "quite overpoweringly floral" / Louisa Travino. → *Replies confirm the brand REFORMULATED to fully fragrance-free; "from hereon out, all our sprays will be scent free." Note: some older 5★ reviews PRAISE the scent ("smells divine," "smells amazing"), so scent perception flipped over time — current product is fragrance-free.*

**[BLANK NEGATIVES]** Nat (1★): "Doesn't work" · Donna Devlin (2★): "Not what I hoped" · Robyn Tormey (2★): "Did not work as well as shown in videos" · Anonymous/Julie (2★): "somewhat helps. Dissappoined."

### REVIEW THEME SUMMARY (counts are directional, from 110 verbatim)
- **Travel/holiday/cruise/suitcase** = the single biggest positive use-case cluster (~20+ reviews). Europe, Japan, cruises, caravans, hotels-with-no-iron.
- **Linen** = most-named fabric (both raves AND the bulk of complaints — high-expectation fabric).
- **"Sceptical → converted"** = recurring arc (~12+ reviews open with "I was skeptical/dubious but...").
- **Busy mum / school run / partner's work shirts** = strong secondary cluster.
- **Wardrobe-revival** ("rediscovered clothes I'd been avoiding because they needed ironing") = repeated emotional hook.
- **No-fumes / non-toxic / unscented** = repeatedly praised differentiator vs other sprays.
- **Critical reviews** cluster on: (1) polyester/synthetics not working, (2) linen under-delivering on deep creases, (3) "not as crisp as ironing," (4) the wet-vs-dry-clothes misprint confusion, (5) occasional faulty pump.

---

## Founder Story (About Us page — verbatim)

> **I built this for busy people with better things to do than iron.**
>
> I'm a mum of two, with a partner in a corporate job. Life is full. Between kids, work, and trying to just get out the door on time, ironing was the last thing on my to-do list — and his too. So he'd turn up to meetings and events in shirts that looked… well, like they'd slept on the floor. At first it was funny. Then it was kinda embarrassing.
>
> I looked for a fix. Something quick. Clean. Effective. Nothing out there worked the way I needed it to. So I made it myself.
>
> What followed was months of testing. Different formulas. Different suppliers. Six bottle types. Until finally - we nailed it.
>
> Uncrumpled is powered by custom wrinkle-relaxing agents that soften fabric fibers and release creases in seconds. No heat. No iron. No stress.
>
> And because it's going on your clothes (and near your skin), I left out all the nasties: No formaldehyde. No phthalates. No parabens. No BS.
>
> Uncrumpled is made for real life — whether you're sprinting to school drop-off, packing light, or just can't be bothered. It's your new lazy laundry hack.
>
> **Spray. Smooth. Go.** You're going to love it here.
> - Ann

**Founder-story creative notes:**
- Origin trigger = partner turning up to corporate meetings in floor-slept shirts ("funny → embarrassing"). This is a sharper, more specific hook than the generic "I hate ironing" homepage version.
- "Six bottle types / months of testing / different suppliers" = credibility/effort proof point.
- Tagline variants in market: "Spray. Smooth. Go." (About) vs "Spray. Smooth. Done." (internal locked sting). Site uses "Go."

---

## FAQ objections handled (verbatim Qs + key A points)

1. **What fabrics does it work on?** — cotton, linen, rayon, viscose, cotton/poly blends, most machine-washable. Not recommended on dry-clean-only, silk, or hand-wash-only without patch testing.
2. **Do I need to spray on wet clothes?** — "No... a misprint on your bottles saying it should be sprayed on wet clothes, but that's our mistake — it should say to use on dry clothes." (This misprint drives several 1-star reviews.)
3. **Do I need to iron after using it?** — "Nope no iron/steamer needed. That's the point. Spray, smooth, wear."
4. **Do you offer a money-back guarantee?** — Yes, full refund within 30 days of arrival; email hello@uncrumpled.com.au.
5. **Are there any toxic ingredients?** — "Nope. No formaldehyde, phthalates, parabens, synthetic dyes, or other nasties."
6. **What fabrics does Uncrumpled NOT work on?** — Polyester/synthetics (nylon, spandex): "polyester is plastic... like trying to massage wrinkles out of a plastic bag." Upside framing: polyester barely wrinkles anyway.
7. **What's the science behind it?** — "wrinkle-relaxing agents that penetrate the fibres... uses the pressure and heat from your hands to release those wrinkles."
8. **Where do you ship from / how long?** — "based in Perth, Western Australia... shipped within a 48 hour period." Express post +$4.
9. **Will it get out deep creases? Is it as perfect as ironing?** — Honest no: "we're not pretending to be an iron... ironing still wins" for razor-sharp finish, but smooths "the majority of everyday wrinkles." "done is better than ironed."
10. **I have another question** — email hello@uncrumpled.com.au.

---

## Flags for creative strategy
1. **Origin wording is "owned/operated" + "Perth, WA" only — never "made."** Safe per the not-Aussie-made rule; do not upgrade to "made."
2. **Planned travel/refill SKUs are NOT live yet** — strategy can't reference them as purchasable.
3. **Reviews skew heavily to TRAVEL** — strongest social-proof angle by volume.
4. **Honesty/anti-perfection ("done is better than ironed") is already in the brand's own FAQ** — on-brand for Certified Chaos creative.
5. **Top expectation gaps = polyester + deep-crease linen + the wet/dry misprint.** Worth pre-empting in ad/landing copy.
6. **Scent was reformulated to fragrance-free** — older "smells divine" reviews are stale; current claim is fragrance-free/non-scented.
7. **"Sceptical → converted" arc** is the most common review structure — strong UGC/testimonial script spine.
