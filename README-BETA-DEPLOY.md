# Hospitality Boss — Beta Showcase (separate public repo)

This is the PUBLIC-FACING showcase. It contains NO real data — everything is the
fictional "Cedar & Vine Catering." Safe to deploy public. Keep this in a SEPARATE
GitHub repo from your private operating tools.

## Files (deploy all to the beta repo)
| File | Role |
|------|------|
| `index.html` | Landing page — entry point |
| `story.html` | Founder story (attributed to "Our Founder", no name) |
| `demo-router.html` | Visitor picks business type → routed to matching dashboard |
| `dashboard.html` | Restaurant Intelligence demo (parchment, dark rail) |
| `fast-casual.html` | Fast Casual / Café demo — **YOU ADD THIS** (see below) |
| `beta-intake.html` | Beta application form (preview — doesn't collect yet) |

## ONE thing you need to add: fast-casual.html
You already have the Fast Casual dashboard file. Apply the 2 small fixes in
`_FIXES-TO-APPLY.md`, save it as `fast-casual.html`, and drop it in. The
demo-router already links to it.

## Flow
index → "See the Demo" → demo-router → pick type → dashboard or fast-casual
index → "Apply for Beta" → beta-intake → success screen → "explore demo"

## Everything is clearly marked PREVIEW
- Dark banner on every page: "Preview Site / Not Yet Live"
- Pricing section notes "preliminary, for preview purposes only"
- Intake form notes "submissions are not yet collected"
- Dashboards note "sample data / not financial advice"

So your friends understand it's a mockup to react to, not a live product.

## Deploy
Separate repo (e.g. "hospitality-boss-beta"), upload all files, enable GitHub Pages.
Public is fine — no real data. index.html is the landing page automatically.
