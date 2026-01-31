# 🛡️ ScopeShield

**Scope creep protection for freelancers, tradies, and service pros.**

Stop losing money on "quick extras." ScopeShield tracks every change request so you get paid for every job — with a paper trail that protects your reviews.

## The Problem

Service professionals — from plumbers to web developers — lose **15–20% of revenue** to untracked scope creep. The pattern is universal:

- **Tradies**: "While you're here, can you also look at…"
- **Freelancers**: "Can you just add one more page / feature / revision…"
- **Agencies**: Verbal requests pile up with no documentation, no sign-off, no billing

When you finally push back, you get a bad review. No paper trail to prove the extras were never in scope.

### Research Context

Validated through Reddit research — multiple posts with 800+ upvotes about scope creep destroying freelancer and tradie businesses. Common themes:
- Free work becoming expected over time
- Clients using reviews as leverage for more free work
- No simple tool to formalize change requests without "being a jerk about it"

## What's Here

- **Landing page** with embedded **Scope Creep Calculator** (the hook — shows users how much they're losing annually)
- **Waitlist signup** via Formspree
- **Plausible analytics** for privacy-friendly tracking

## Tech Stack

- Pure HTML / CSS / JS — no framework, no build step
- Formspree for waitlist form handling
- Plausible for analytics
- Designed for GitHub Pages deployment

## Status

🟡 **Validation** — Landing page + waitlist live. Collecting signups to validate demand before building the product.

### Planned Product Features

1. Project scope definition (what's in, what's not)
2. Client-facing change request portal
3. Auto-pricing based on your rates
4. Approval workflow before work begins
5. Paper trail / audit log for dispute protection

## Related Projects

Part of the [Original Solutions](https://originalsolutions.com.au) product portfolio:

- **[YardPilot](https://yardpilot.io)** — Business management for lawn & garden pros
- **[LeadScouts](https://github.com/original-solutions/leadscouts)** — Automated lead generation
- **[ReplyMate](https://github.com/original-solutions/replymate)** — AI-powered review response tool

## Development

No build step required. Just open `index.html` in a browser.

```bash
# Local dev
open index.html

# Or use any static file server
python3 -m http.server 8000
```

## License

© 2025 Original Solutions Pty Ltd. All rights reserved.
