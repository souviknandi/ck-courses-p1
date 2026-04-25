# CATKing P1 Wireframes - Courses Portal Purchase Journey Upgrade

Phase 1 wireframe set for **courses.catking.in** purchase journey redesign. Built for leadership review and developer handover.

## Live Demo

Once GitHub Pages is enabled, the wireframes will be live at:
`https://<your-github-username>.github.io/<repo-name>/`

## What's Inside

| File | Screen | Description |
|------|--------|-------------|
| `index.html` | Landing | Project overview, links to all 5 wireframes, locked rules summary |
| `01_homepage_sticky_nav.html` | Homepage | Sticky 6-tab nav with category dropdowns, course cards, trust signals |
| `02_course_detail_alt_gateways.html` | Course Detail | Sticky pricing card, variant switcher, slide-over checkout, **alternate payment gateways** (Razorpay + CCAvenue) |
| `03_cart_redesign.html` | Cart | 2-column layout, live recalculation via trySet(), 6-day money-back guarantee |
| `04_post_purchase_redesign.html` | Post-Purchase | Welcome tick, on-page credentials, address capture, 3-CTA bar, induction video |
| `05_mobile_views.html` | Mobile | Sticky bottom bar, mobile guest checkout (390x844), 2-tap signed-in checkout |

## Target Metrics

- 3-click purchase path (down from 7+)
- Cart abandonment: -30%
- Post-purchase support tickets: -85%
- Revenue: 2x via conversion optimization

## Locked Design Tokens

```css
--orange: #FEA82F;   /* Primary CTA, batch fee tooltip */
--blue:   #2385F4;   /* Secondary actions, links */
--green:  #4CAF50;   /* Buy Now, success states, money-back guarantee */
```

## Tech Notes

- All wireframes are **self-contained HTML** with inline CSS (no build step required)
- No external dependencies, no npm install, no API calls
- Works in any modern browser (Chrome, Safari, Firefox, Edge)
- `.nojekyll` file disables Jekyll processing on GitHub Pages

## Deployment

See the deployment guide shared alongside this repo for step-by-step instructions to publish on GitHub Pages.

## Team

- **Souvik Nandi** - Product Owner (MLP 11.0)
- **Sumit Singh** - CEO (SP Jain + Harvard PMNO)
- **Utpal Upadhyay** - Tech Lead
- **Surbhi** - Design

---

Built for CATKing Educare, April 2026.
