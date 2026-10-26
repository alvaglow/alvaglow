# Ember & Bloom: business plan and launch checklist

Working name: **Ember & Bloom**. Hero product: **Ember Calm**. Both are placeholders. Run a trademark search before any spend.

## 1. Decisions from the brief

| Question | Decision |
| --- | --- |
| Target audience | US women in perimenopause and post-menopause, roughly 45 to 65+ |
| Offer shape | One hero product, plus bundle and subscription versions of the same product |
| Avatar direction | "The wise woman": a grounded, believable, mature woman who looks like she knows something, not a cartoon or a glamour model |

## 2. Hero product

**Ember Calm**: a daily standardized ashwagandha root extract capsule, taken with dinner.

Why ashwagandha as the hero:

- It is widely sold in the US, so many contract manufacturers and ingredient suppliers can produce it.
- The strongest research signal is for stress and sleep. Menopause-specific evidence is smaller and mixed, so the marketing must not promise relief from hot flashes or other menopause symptoms.
- It fits the "evening ritual" positioning and the calm, wise-woman brand.

Known safety considerations, which must appear on the product page and in the label review:

- Pregnancy and breastfeeding: avoid.
- Thyroid conditions and thyroid medication: may interact.
- Autoimmune conditions and immune-suppressing drugs: may interact.
- Sedatives, sleep aids and anti-anxiety drugs: additive effects possible.
- Diabetes medication: may lower blood sugar.
- Liver: there are published reports of liver injury with ashwagandha products. Require a liver-safety disclaimer and a stop-use warning.

### Sourcing criteria (verify each item before ordering)

Ember Calm should only go live with a supplier that can show all of the following:

1. Manufacturing facility registered with the FDA and following current good manufacturing practices (cGMP) for dietary supplements.
2. A certificate of analysis for each batch covering identity, potency (withanolide percentage), heavy metals and microbes.
3. Third-party testing you can name and reference on the page.
4. US-based stock or a US fulfillment partner, so orders ship within 1 to 3 business days.
5. Private-label capability with a minimum order quantity you can afford, plus a sample run.

Sourcing channels to compare: US private-label contract manufacturers, and 3PL or dropship fulfillment partners that hold stock in the US. I have not contacted or verified any supplier in this repo. Shortlist and quotes are a manual next step.

## 3. Offer

| Option | Price | Notes |
| --- | --- | --- |
| One bottle | $49 | 30-day supply, 60 capsules |
| Three bottles | $119 | 90-day supply, best value |
| Subscribe and save | $41.65 per bottle | Save 15%, every 30 days, skip or cancel anytime |

Prices are placeholders. Set them once landed cost, fulfillment and ad cost are known. Target a gross margin you can fund paid acquisition from before setting the final prices.

Guarantee: 30-day money-back guarantee, minus shipping. This is a business decision you should confirm.

Upsell path (after the core product is working):

- Bundle and subscription already on the page.
- Second SKU from a complementary, reviewed supplier only after the hero product is validated. Do not add it before then.

## 4. Avatar brief (for the three mock-ups)

Use this brief for image generation or for a casting brief. Approve a visual before building ads.

- **Person**: a woman in her 50s to early 60s, silver or salt-and-pepper hair.
- **Look**: natural and attractive, with visible age: fine lines around the eyes, real skin texture, no heavy retouching.
- **Expression**: calm, self-assured, a faint knowing look. Not smiling for the camera.
- **Setting**: warm, uncluttered, natural light. Soft earth tones, cream and ember accents.
- **Avoid**: cartoon or illustrated styling, plastic or airbrushed skin, monk or spiritual costumes, glowing auras, anything that looks like a stock "wellness" model.
- **Believability check**: would a woman her age recognise this as a real person she could meet? If not, it is too polished.

Test every candidate on three questions: does she look like a real customer, does she look like an authority rather than an influencer, and would a 55-year-old woman trust her with a health decision?

## 5. Compliance (required before launch)

Dietary supplements in the US are regulated under DSHEA. The rules that matter most here:

- **No disease claims.** Do not say the product treats, cures, prevents or relieves menopause, hot flashes, osteoporosis or any other disease. Use structure and function language only, such as "supports a calm evening routine", and pair it with the required disclaimer.
- **Required disclaimer.** The "not evaluated by the FDA" statement and the "not intended to diagnose, treat, cure or prevent" statement appear on every page and in ads where the claim appears.
- **Substantiation.** Each claim needs competent and reliable scientific evidence. Keep a claims file that links each claim to a study. The claims on the current page are deliberately modest; review them against your file.
- **Testimonials.** Use only real, consented testimonials. Do not use invented reviews, fake "doctor" endorsements or the founder's name as a health authority unless that person is qualified and agrees.
- **Labeling.** Supplement Facts panel, net quantity, manufacturer and distributor information, and the warning statements a supplement label needs. Have the label reviewed before printing.
- **Ad platforms.** Meta, Google and TikTok have strict health and supplement ad policies, and personal-attribute targeting is restricted. Expect ad rejections and plan creative around them.
- **State rules.** Check California Proposition 65 warnings if you sell there. Confirm sales-tax registration for the states you ship to.
- **Professional review.** Have a US regulatory or supplement attorney review the final copy and label before paid traffic goes live.

## 6. Launch plan

1. **Validate the avatar.** Approve one of the three mock-ups against the brief in section 4.
2. **Source and test.** Get quotes from at least three suppliers, order samples, and send one to a third-party lab.
3. **Finalize claims and label.** Build the claims file, then have the label and copy reviewed (section 5).
4. **Set up checkout and fulfillment.** Connect a store platform (for example Shopify or Stripe Checkout) and a US fulfillment partner. Replace the `#checkout` link in `index.html` with the real product URL.
5. **Deploy the site.** Host the static files (`index.html`, `styles.css`) on any static host, and add a custom domain once it is secured.
6. **Build traffic.** Start with organic content from a real or consented creator, then test small paid campaigns once creative and claims are approved.
7. **Retention.** Add an email welcome sequence, a day-25 refill reminder, and a subscription upsell.
8. **Review weekly.** Track conversion rate, cost per acquisition, refund rate, and customer questions. Customer questions often reveal copy that needs fixing.

## 7. Open items for you to decide

- Brand name and trademark clearance.
- Final hero product formula, dose and supplier (after sourcing).
- Final prices and guarantee terms.
- Whether to build the avatar mock-ups with an image tool, or use a human photo shoot or casting.
- Checkout and fulfillment platform.
- Domain name and hosting.

## 8. Files in this repo

- `index.html`: single-page sales site with hero, offer, ingredient, safety and FAQ sections.
- `styles.css`: layout and styling. Responsive from phone width up, with no horizontal scroll.
- `docs/BUSINESS-PLAN.md`: this document.

Before going live, replace the `[XXX]` placeholders in the supplement facts, the avatar placeholder image, the prices, and the `#checkout` link.
