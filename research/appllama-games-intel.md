# Appllama Intel: Replicable Games & Gamified Apps

**Source:** Appllama MCP (revenue-ranked iOS library), pulled 2026-10-12. Revenue and download figures are Appllama's monthly estimates as of 2026-09-01.
**Spend:** about 22 credits (1,398 remaining this month).

## Read this first: what the data can and can't tell you

1. **Appllama is a library of subscription apps, not a games tracker.** Searching "game" turns up only about 10 real games. Most of the money in this catalog sits in *gamified subscription apps* (brain training, IQ tests, kids learning, cozy pet and focus apps). That is the useful finding here.
2. **Revenue counts App Store in-app purchases only. Ad revenue isn't included.** Block Blast shows $5K/mo while ranking #13 in US Games, because its money comes from ads. Don't read low revenue on an ad-driven game as a sign it doesn't earn.
3. The estimates come in rounded tiers ($100K, $1M, …), so treat them as order of magnitude.
4. **RPD = monthly revenue ÷ monthly downloads.** It roughly shows how much each install is worth, which caps what you can pay to acquire a user.

---

## The ranked board

| # | App | Launched | Rev/mo | DL/mo | RPD | Model | Replicable? |
|---|-----|----------|--------|-------|-----|-------|-------------|
| 1 | **IQ Masters** (DEEP FLOW, UAE) | Mar 2024 | $400K | 70K | **$5.7** | Weekly $7.99 sub, hard paywall | **YES: top pick** |
| 2 | **Clever: Brain Training** (DPM Apps) | Apr 2022 | $200K | 30K | **$6.7** | Weekly $7.99, lifetime $39.99 | YES |
| 3 | **Impulse: Brain Training** (GMRD) | 2019 | $900K | 200K | $4.5 | Weekly $6.99–9.99 | YES (ceiling proof) |
| 4 | **Solitaire Associations Journey** (Hitapps) | **Sep 2025** | **$4M** | 2M | $2.0 | Coins + No-Ads + ads | Mechanic yes, scale is hard |
| 5 | **Keiki Learning (kids)** | 2020 | $1M | 90K | **$11** | Weekly $7.99–9.99 | YES (kids rules apply) |
| 6 | **Focus Friend** (Hank Green) | Jul 2025 | $100K | 40K | $2.5 | Sub $3.99 + cosmetic IAP | YES (cozy) |
| 7 | **Focustown** | **Feb 2026** | $50K | 100K | $0.5 | Sub + bean currency | YES (cozy) |
| 8 | **Cat On Chair** (*solo dev*, Ryan Yao) | Aug 2025 | $10K | 20K | $0.5 | Sub $2.99 + decor IAP | YES (indie proof) |
| 9 | **Catzy: Self-Care** (CN studio) | Nov 2024 | $30K | 30K | $1.0 | Weekly $4.99 | YES |
| 10 | Finch: Self-Care Pet | 2021 | $1M | 300K | $3.3 | Annual $39.99 | Category ceiling |
| 11 | Color by Number (Wildlife) | 2017 | $1M | 1M | $1.0 | Weekly $9.99 + coins | Saturated |
| 12 | Lake Coloring | 2017 | $100K | 40K | $2.5 | Weekly $2.99 | Long tail |
| 13 | Math Learner (Wildlife) | 2018 | $40K | 9K | $4.4 | Weekly $9.99 | **Not updated since Dec 2023 and still earning** |
| 14 | Jawaker (MENA card games) | 2014 | $900K | 100K | $9.0 | Token IAP | Regional-niche template |
| 15 | Beat Maker Pro (MWM) | 2018 | $400K | 200K | $2.0 | Weekly $7.99 | Yes, but crowded |
| — | Phase 10 / Skip-Bo (Mattel) | — | $1M / $300K | — | $10 / $4.3 | Gem IAP | **NO: licensed IP** |
| — | Block Blast | 2022 | ads | 4M | n/a | Ads | Ad game, data blind |

---

## Top 3 plays, with my honest take

### Play 1: brain and IQ test subscription app (clone IQ Masters and Clever)

**Why it's #1:** a small UAE studio launched in March 2024 and was earning $400K/mo within 2.5 years, with one of the highest per-install values in the catalog ($5.7). Clever is the same model. Impulse ($900K) shows how far it can go. None of this is new technology. It's a playbook.

**What the product actually is:**
- 6–10 simple mini-games: Towers of Hanoi, Draw One Line, Connect the Dots, a sort puzzle ("Smoothie"), Chasing Fireflies, Arrow Away.
- "Tests" that are really styled quiz forms: IQ, ADHD, anxiety type, EQ, "dominant brain type", male archetypes. These cost almost nothing to make and give you most of your ad hooks.
- Streak, progress charts, leaderboard.

**How the funnel works (from Appllama screens):**
1. **26-screen onboarding** built around a mascot: goal → test selection → anxiety reason → gender → age → … The long quiz builds personalization and sunk cost.
2. **A playable mini-game inside onboarding**, with confetti and a score pill, then a **scratch card** promo, all before the paywall.
3. **Hard paywall with a trial timeline** ("3-step trial timeline", "price due" panel, payment shield badge, social-proof pill).
4. **Exit offer: "92% OFF" coupon** (struck-through weekly price, yearly billing).
5. Plan picker: trial-then-weekly vs. yearly, with "Save 90%".
- Clever runs the **same 92% exit-offer structure** with a lifetime option. That points to a shared paywall vendor or a shared playbook, so it's well tested.
- Pricing: **weekly $7.99 (up to $9.99) is the main product**. Annual $19.99–39.99 is the anchor and lifetime $49.99 catches people who won't subscribe.
- Localized into **15 languages**. Top markets are **US, Brazil and Mexico**, so cheap LatAm installs carry volume.

**Rough build:** 6–8 weeks for one solid engineer plus a designer (Expo or Swift, 8 mini-games, 10 quiz "tests", RevenueCat or Superwall).

**The real moat is paid acquisition, not code.** This business runs on Meta and TikTok ads, and $5–7 RPD only works if you buy installs well under $3. Budget at least $10–20K for creative testing before you'll know whether it works.

**Risks:**
- Apple review on medical-sounding claims (ADHD, anxiety): keep them framed as "for fun, not a diagnosis".
- Weekly-plus-trial pricing brings refund and chargeback risk.
- Brand trust is low across the category.

**How to beat them:**
- Pick a sharper angle: "Brain Age for 50+", "IQ for parents to play with kids", or a regional-language-first app in markets they cover poorly.
- Build better games. Their games are generic, so the bar is low.

### Play 2: cozy companion and focus timer (Focus Friend, Cat On Chair, Focustown, Finch)

**Why:** this is the best category for building on organic reach and getting started cheaply.
- A **solo developer** (Cat On Chair) reached about $10K/mo in 13 months with a 4.92★ rating, mostly from Asia (CN, TW, TH).
- **Focustown launched February 2026** and already gets 100K downloads a month.
- Focus Friend made $100K/mo in its first year.
- Finch shows the top of the category at **$1M/mo**.

**The loop:** start a focus session → your pet "works" alongside you → complete it and get a gift, fail and get trash (loss aversion) → spend currency on room decor → the room becomes a shareable wallpaper or post.

**Money comes from two places:** a subscription at $2.99–3.99/mo or $19.99/yr, with **lifetime at $29.99–39.99**, plus **cosmetic IAP** (pet skins at $2.99–4.99, currency packs). That mix catches buyers who won't subscribe.

**Honest take:** per-install value is lower ($0.5–2.5), so you can't profit from paid ads early. It works through TikTok and Reels virality, which depends on art. **A distinctive art style plus a lovable character is the whole product.** If you can't commission great art, skip this one.

### Play 3: word-solitaire hybrid casual game (Solitaire Associations Journey)

**Why it matters:** it **launched September 2025 and makes $4M/mo** from IAP alone (ad revenue comes on top), with 2M downloads a month and a #21 rank in US Games. The mechanic is simple: NYT Connections-style word categories played on a solitaire layout.

**How it makes money:** a coin shop, a No-Ads bundle at $9.99–19.99, a **Revive offer at $1.99**, Starter Pack, Coin Bank (a piggy bank), and **rewarded-ad coins** on the shop screen. Hint, Undo and Joker boosters spend coins. The weekend "Corgi Race" is a LiveOps event.

**Honest take:** fast-follow clones of this mechanic are definitely coming (that's how casual gaming works). But winning takes **ongoing level design, LiveOps, and a large acquisition budget (well into six figures)**. Don't make this your first bet unless you have that capital. It could be your second or third, once Play 1 is funding things.

---

## Long-tail intel (money that keeps coming)

- **Math Learner (Wildlife Studios)** hasn't shipped an update since December 2023 and still makes about **$40K/mo** at $9.99 weekly. **Recolor** (last update December 2025) makes $20K/mo on about 1K downloads. Subscription apps keep paying from existing users for years after work stops. A portfolio of 5–10 small subscription apps at $10–40K/mo each is a real business.
- **Kids learning carries the highest per-install value in the set ($11, Keiki).** The catch is Apple's Kids Category rules (parental gates, no third-party ad tracking) and that the paywall has to sell to the parent. Speech Blubs ($500K) and Hooked on Phonics ($300K) confirm the demand.
- **Regional card games:** Jawaker earns $900K/mo from MENA-specific games (Tarneeb, Trix) at about $9 per install. Under-served regional classics are a niche with a defensible audience. Use **virtual currency only, with no cash-out**, to stay clear of real-money gaming law in markets like India.

## Cross-app patterns to copy

1. **Weekly pricing ($6.99–9.99) dominates** brain, IQ, kids and music apps. Annual is the price anchor; lifetime catches the holdouts.
2. **Long onboarding converts.** Finch uses 42 screens, Keiki 39, Lumosity 27, IQ Masters 26, Elevate 25. A quiz builds investment before the paywall.
3. **Let people play before you ask for money:** a mini-game, then confetti, then a scratch card, then the paywall.
4. **The paywall sequence:** trial timeline → exit discount ("92% off") → plan picker.
5. **Mental-health and identity hooks** (ADHD, anxiety, IQ, "brain type") are where users come from. The games are what keep them.
6. **Hybrid monetization (subscription plus cosmetic IAP)** in cozy apps converts people who won't subscribe.

## Next intel moves

- **Fill the ad-revenue gap:** Appllama can't see ad-funded games. Before committing to Play 3, get Sensor Tower or AppMagic data on hybrid-casual games.
- **Look at the ads:** check Meta Ad Library for IQ Masters, Clever and Impulse. Their running ads show which hooks are scaling right now.
- **Walk the full screens:** go through IQ Masters' remaining 16 onboarding screens and its mini-game screens on Appllama (about 10 credits) before building.
