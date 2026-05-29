# Uncrumpled — Own Meta Ads (Last 90 Days)

**Source:** Meta Ads MCP, account `act_1554534928747226` (Uncrumpled, AUD, AU market, Page 756626794197409). Window = last 90 days (2026-02-28 → 2026-05-28). Pulled 2026-05-29.

> Method note: account-level insights pulled directly. Ad-level insights pulled per active campaign (3 active campaigns) and aggregated by ad name across campaigns (same ad runs in multiple campaigns/ad sets). 70 unique ads after dedupe; ~$30.7K of the $51.9K account spend is attributable to named ads in the 3 active campaigns (remainder = paused/legacy campaigns + DPA/catalog in the window). Copy pulled via `get_ad_creatives` for the top performers.

---

## Account snapshot (last 90d)

| Metric | Value |
|--------|-------|
| Spend | **A$51,900.80** |
| Impressions | 2,563,656 |
| Reach | 513,870 (freq 4.99) |
| Clicks (all) | 58,288 |
| Link clicks | 32,024 |
| CTR | **2.27%** |
| CPC (all) | A$0.89 |
| CPM | A$20.24 |
| Purchases | **3,126** |
| Revenue (purchase value) | **A$163,670.67** |
| **Purchase ROAS** | **3.15x** |
| **CPA (cost/purchase)** | **A$16.60** |
| Add-to-cart | 5,167 (ATC value A$184,338) |
| Initiate checkout | 5,835 |
| Landing page views | 31,485 (A$1.65 ea) |

Account is healthy and consistent with the CLAUDE.md baseline (3.25x ROAS / $16.23 CPA at last 30d ending 2026-04-14). 90d sits at 3.15x / $16.60 — steady, slightly softer than the March peak, in line with the documented dip.

**3 active campaigns** (all OUTCOME_SALES, AUCTION):
- `SCALING | Winners | Lowest Cost` (120242125886720452) — Lowest cost no cap, A$310/day CBO. Live since 2026-05-05.
- `COLD | TOF | ABO | Master` (120240638816050452) — biggest spend bucket, holds most named creatives.
- `COLD | Manual Bid | Scaling` (120234784313590452) — Bid cap, A$300/day CBO.

(All BFCM/Gifting/Leads/giveaway/ASC campaigns are PAUSED.)

---

## Top ads by ROAS (spend ≥ A$300)

| # | Ad (hook code + name) | Format | Copy excerpt (PT hook / headline) | ROAS | CTR | CPA | Spend |
|---|----------------------|--------|-----------------------------------|------|-----|-----|-------|
| 1 | **V1 \| Hi I am Ann** | Video (founder) | PT: "Ironing? Haven't got time for that…" · HL: "Smooth clothes - no iron" | **4.35x** | **4.55%** | $12.68 | $4,576 |
| 2 | **V7 \| Ann black dress** | Video | PT: standard "Ironing? Haven't got time…" + free stain-pen line · HL: "Smooth clothes- No iron" | **4.24x** | 3.50% | $12.49 | $4,346 |
| 3 | **V2 \| TT reply \| Linen shirt on** | Video (TikTok-reply demo) | HL rotation: "Smooth clothes - no iron" / "Say Goodbye to Ironing" / "Wrinkle-Free in Seconds" | **4.12x** | 2.68% | $12.61 | $3,305 |
| 4 | **V4 \| Drawer to bed \| Cream Jaggad shirt** | Video (real-time demo) | PT: standard hook · HL: "Smooth clothes - no iron" | **4.01x** | 1.65% | $13.45 | $377 |
| 5 | **V7 \| Pull up text \| White shirt** | Video (pull-up reveal) | HL: "Smooth clothes - no iron" | **3.48x** | 1.80% | $15.32 | $720 |
| 6 | **V4 \| Real time \| Checkered shirt** | Video (real-time demo) | HL: "Smooth clothes - no iron" | **3.24x** | 1.80% | $15.03 | $872 |
| 7 | **S3 \| Not the only one who hates ironing** | Static image | "30 Day Money Back Guarantee" angle / "Still on the fence about Uncrumpled?" | **3.07x** | 1.43% | $17.06 | $4,198 |
| 8 | **V3 \| Type B Travellers (Shortened) Copy** | Video (identity/travel) | PT: "Type B/Cs, you know who you are…" · HL: "Travel hack" | 2.57x | 2.57% | $20.16 | $1,794 |
| 9 | V4 \| Denim shirt (Winners) | Video (demo, non-linen) | standard hook · HL: "Smooth clothes - no iron" | 2.17x | **3.59%** | $23.65 | $2,980 |

Smaller-spend high-ROAS notables: **V7 \| Love linen \| Linen shorts** (4.52x, 3.36% CTR, $243 spend) and **V2 \| Hate making ads \| White tube top** (2.94x, 2.51% CTR, $228 spend) — both strong efficiency, low volume.

---

## Top ads by CTR (spend ≥ A$300)

| Ad | CTR | ROAS | CPA | Spend |
|----|-----|------|-----|-------|
| **V1 \| Hi I am Ann** | **4.55%** | 4.35x | $12.68 | $4,576 |
| V4 \| Denim shirt (Winners) | 3.59% | 2.17x | $23.65 | $2,980 |
| V7 \| Ann black dress | 3.50% | 4.24x | $12.49 | $4,346 |
| V3 \| Type B Travellers (Copy 2) | 3.16% | 2.39x | $21.00 | $1,995 |
| V2 \| TT reply \| Linen shirt on | 2.68% | 4.12x | $12.61 | $3,305 |
| V3 \| Type B Travellers (Copy) | 2.57% | 2.57x | $20.16 | $1,794 |

Top-CTR list is dominated by **founder face-to-camera (V1)** and **identity-led video (V3 Type B Travellers, V4 Denim)**. The very best CTR + ROAS combined is **V1 Hi I am Ann** — the strongest single ad in the account on both axes.

---

## Winning hook patterns (what repeats in the best ads)

1. **Founder face-to-camera intro — "Hi, I'm Ann."** (V1) — #1 ad in the account on BOTH ROAS (4.35x) and CTR (4.55%). Personal, founder-led, first-person opener. Highest scroll-stop in the account by a clear margin.
2. **Real-time "spray → smooth → done" demo, visible wrinkle drop** (V4 series: Drawer-to-bed, Real-time Checkered, Denim) — consistent 3–4x ROAS. The proof-on-camera format. Non-linen garments (Denim, Checkered) show contrast better and pull higher CTR than flat linen.
3. **TikTok-reply / native-social format** (V2 TT reply) — 4.12x at scale ($3.3K spend). Mimics organic UGC; reply-comment framing reads native.
4. **Pull-up text reveal** (V7: Pull up text White shirt, Ann black dress) — 3.5–4.2x. Curiosity/reveal mechanic over the demo; text builds across the clip.
5. **Identity callout opener — "Type B/Cs, you know who you are…"** (V3 Type B Travellers) — best CTR among identity ads (3.16%), 2.4–2.6x ROAS. Lists relatable chaos behaviours (sprinting to the terminal, "wing it when you get there", packed 14 outfits) then nests the spray. Note: this is the live, working version of the Type C / Certified Chaos identity angle — it converts in cold at a softer ROAS than founder/demo, so position as volume not efficiency.

**Body-copy (primary text) finding:** almost every video ad runs the SAME standard primary-text block —
> *"Ironing? Haven't got time for that. After months of testing (and 15 failed samples later), we finally perfected a wrinkle-release spray that actually works. Meet Uncrumpled. Simply spray, smooth, and you're done. No heat, no ironing."* + ✅ checklist (non-toxic / no heat / works on most fabrics / Australian owned & operated / free stain-remover pen) + Shop Now.

The performance differentiation lives in the **video creative (the hook) and the headline rotation**, NOT the primary text. Headlines rotate across: "Smooth clothes - no iron" / "Say Goodbye to Ironing" / "Wrinkle-Free in Seconds" / "Spray, Smooth, Done in Seconds" / "Travel hack" / "30 Day Money Back Guarantee".

**Offer levers present in copy:** 30-day money-back guarantee, free stain-remover pen (limited time), same-day VIC dispatch before 1pm, "Australian owned & operated" (note: brand voice memory flags scrubbing "Aussie-made" — this copy uses "owned & operated", which is the allowed framing).

---

## Format mix

- **Video = ~90% of spend and every top-ROAS ad.** All V1/V2/V3/V4/V7 ads are video (object_type VIDEO or SHARE with `asset_feed_spec.videos`). Most use placement-customised asset feeds (separate Reels/Story cut vs feed cut).
- **Static image = the S-series** (S3 "Not the only one who hates ironing" / "30 Day Money Back Guarantee", S2/S1 Mother's Day, S6). S3 is the only high-spend static ($4.2K, 3.07x) — a solid money-back/objection-handling workhorse. Other statics are low-volume.
- **Carousel = NONE detected** in the active 90d set. No multi-card carousel creative running as paid.
- **DPA/catalog** present at account level (catalog actions in data) but no carousel-format ads among named creatives.

---

## Gaps (angles / formats absent or under-used in paid)

1. **No carousel ads at all** — despite a locked 7-carousel organic system (CLAUDE.md), zero carousels run as paid. Untested paid format.
2. **No UGC / creator video** — all video is founder (Ann) or branded demo. No third-party creator faces, no "TikTok convinced me to buy this" product-led UGC (the locked paid-UGC angles from 2026-05-01 are unbuilt/unrun).
3. **Primary-text monoculture** — one body block on ~all video ads. No tested variation in PT angle (e.g. founder story, objection-handling, identity copy in the body). All testing happens in the hook/headline only.
4. **Identity/Certified Chaos angle under-leveraged in paid** — only V3 Type B Travellers carries it, and only in travel context. The "[Type B perfect]. [Type C admit]. Same." headline pattern (locked 2026-05-01) is NOT running in any ad.
5. **No sale/promo creative live** — EOFY 30% pack and refill/travel launch assets are built but not yet in-market in this window (expected; June launch).
6. **Trendjack / cultural-moment stitch absent** — the locked trendjack approach (red-carpet/MAFS wardrobe-fail react) has no live ad.
7. **Static format thin** — only S3 carries real spend. Pain-point statics (S1 "No more ironing" type) that historically hit 4.0–4.5x are not among the current high-spend ads; the static lane is under-fed relative to its past performance.

---

## Cross-reference vs CLAUDE.md known winners

| CLAUDE.md claim | 90d live data | Verdict |
|---|---|---|
| S1 "No more ironing" 4.55x | Not in current high-spend set; S3 static is the live static workhorse at 3.07x | Stale — S1 not a current top spender |
| V7 "Pull up text White shirt" 4.08x | Live at 3.48x ($720) | Confirmed, slightly lower |
| V4 demos 3.5–4.2x | V4 Drawer-to-bed 4.01x, Real-time Checkered 3.24x, Denim 2.17x | Confirmed (range now 2.2–4.0x; non-linen demos vary) |
| V2 "Hate making ads" 2.78% CTR | Live at 2.51% CTR, 2.94x ROAS (low spend $228) | Confirmed (still strong CTR, under-funded) |
| **New finding** | **V1 "Hi I am Ann" = 4.35x ROAS + 4.55% CTR = best ad in account on both** | New #1 — founder face-to-camera is the standout |
| **New finding** | **V7 "Ann black dress" 4.24x / V2 "TT reply" 4.12x at scale ($3–4K spend each)** | New scaled winners |

**Headline takeaway for creative strategy:** the account's efficiency engine is **founder-led video (V1/V7 Ann)** + **real-time demo (V4)** + **native TikTok-reply (V2)**, all carrying a near-identical proof-led body. Biggest untapped levers: paid carousel, product-led UGC, the unrun identity headline pattern, and re-feeding the proven static lane.
