# Electric by Design, LLC: homepage (Atlanta, GA)

Free homepage rebuild of uselectricbydesign.com (Wix). `index.html` is self-contained (CSS and images inlined). Edit `index.src.html` / `styles.css`, then run `python build.py`.

## Real data used
- **Their own site:** name, phone 855-424-4255, email info@uselectricbydesign.com, "Contact us 24/7", "Get a free quote", three markets (Metro Atlanta GA, Greater Los Angeles CA, Charlotte NC), Residential / Commercial / EVs page content, Instagram and Yelp links.
- **Badges from their homepage:** HomeAdvisor Top Rated, Angi Super Service Award 2023, BBB Accredited A+ rating, Tesla Wall Connector Approved Electrician. Used as-is, not verified with the issuers.
- **Google Business Profile (read Sept 2026):** 5.0 across 21 reviews, "Open 24 hours". Six reviews are verbatim on the page and in the JSON-LD (Peter Mbugua, Ronnie Thomason, Elvira B Hawkins, Sasha Curry, Rita H, Jess Skubi). "Electic" is the customer's own typo. Reviews are one month to a year old.
- **Service copy beyond their pages** (lighting, outlets/rewiring, cameras and TV mounting) restates work the Google reviews describe. Atlanta-area towns (Atlanta, East Point, Cumming) come from the reviews.
- **Logo and colors:** logo downloaded from their Wix site; blue #1860a0 and yellow #f0c008 sampled from its pixels.

## Placeholders / to confirm
- **Phone conflict:** their site says 855-424-4255; their Google listing says 404-649-3377. The page uses the site number. Confirm which is primary.
- **Hero photo** (modern house at dusk) is from their own Wix site but looks like stock. Confirm it is theirs or swap in a real job photo.
- **About photo and all four Recent Work tiles are Pexels stock** (credited in HTML comments). Recent Work is the riskiest; replace first.
- **No street address, license number, years in business, owner name or hours** are published. None invented. Reviewers call the owner Keenan, Kenny and Murray, so the name is only used inside the quotes.
- **Free quote** is their own site's claim ("Get a Free Quote"); confirm.
- Badges and the 2023 Angi award may be stale; confirm current.
- Logo is a portrait mark on a white tile; a wide horizontal version would sit better in the header.
- Domain (canonical / og:url / og:image) for launch. Nav links are inert (homepage-only teaser).
