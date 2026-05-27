# Power BI Gateway Modernization — Hybrid Analytics Reference

A single-page reference architecture and migration plan for modernizing on-premises
Power BI Gateway infrastructure to support Microsoft Fabric and hybrid analytics.

**Live page:** https://patmeh1.github.io/powerbi-gateway-modernization/

## What's inside

- The core use case and problem statement
- **Current vs. target architecture diagrams** (SVG, server names anonymized)
- Six sub-use-cases broken down (business + technical)
- Additional considerations (security, network, HA, identity, monitoring, DR, Fabric
  capacity, cutover, training, cost)
- Phased migration roadmap
- Quick wins for the first 30 days
- Customer-facing talking points

## Notes

- All server names in the diagrams are generic placeholders (`Server1`, `Server2`, …).
- No customer identifying information is included — this is a public reference.
- Built as a single self-contained `index.html` with light/dark theme support.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
