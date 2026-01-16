# Steel.ee Landing Pages (Elementor)

See repo hoiab Steel.ee müügilehtede Elementori mallid (.json) versioonihalduseks.

## Failid
- elementor/vihmaveesusteem-b2c.json — B2C müügileht (kalkulaator fookuses)
- elementor/vihmaveesusteem-b2b.json — B2B versioon (ehitajale/ettevõttele)
- elementor/vihmaveesusteem-ab-variant.json — A/B variant (alternatiivne copy + rõhuasetus)

## Import WordPressi (Elementor)
1) WordPress Admin → Templates → Saved Templates
2) Import Templates
3) Vali .json fail siit repost (download)
4) Ava leht → Edit with Elementor
5) Insert → My Templates → vali imporditud template

## Oluline
- Mallid on tehtud “safe” stiiliga (must CTA, hele taust, loetav typograafia).
- Parim viis Steel.ee brändiga klappima panna: Elementor → Site Settings → Global Colors & Fonts.
  Siis muutub stiil üle saidi automaatselt.

## Shortcode’id
Mall eeldab:
- Kalkulaator: [steel_round_rain_calc]
- Vorm: [wpforms id="3019"]

Kui vormi ID muutub, muuda malli sees see shortcode.
