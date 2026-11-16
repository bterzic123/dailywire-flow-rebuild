# Growth Audit — Daily Wire

**Live:** https://bterzic123.github.io/dailywire-flow-rebuild/

Daily Wire's Google trailers each sell one show, and every install meets the same account wall and the same DW+ sheet. This audit rebuilds the first launch in Daily Wire's own design and at its own prices, so each install is greeted by the show it came for. Two views: an overview with five ranked ideas, and a clickable prototype with three phones (Real History trailer, Pendragon Cycle trailer, App Store).

## The five ideas

| # | Idea | Screen | Expected impact |
| :-- | :-- | :-- | :-- |
| 1 | Let them in before you ask for an account | Welcome | CR +5–10% · ARPU +10–17% |
| 2 | Name the show they came for in the DW+ headline | DW+ | CR +15–20% |
| 3 | Ask whose shows they want, then read it back | Loader | CR +10–15% |
| 4 | Ask for notifications after DW+, not right before it | Home | CR +10–15% |
| 5 | Put 4.5 stars from 17K ratings next to the button | DW+ | CR +10–15% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Daily Wire.

## Where the facts come from

Screens, copy, photography and prices come from the Daily Wire iOS app as recorded on 16 November 2026 (EU storefront: 17,99 €, 119,99 € then 179,00 €, 199,99 € then 299,00 €). The rating, ratings count and show lineup come from the US App Store listing; the 41 million monthly audience from get.dailywire.com; the ads and their dates from AppMagic. No trial is shown because Daily Wire does not sell one.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/. Add `?view=proto` to open the prototype directly.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
