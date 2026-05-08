# iStock (istock)

iStock is Getty Images' royalty-free stock media brand for affordable, subscription-based image, video, illustration, and audio licensing. iStock shares Getty's underlying API platform; partner API access is gated and tied to a commercial licensing agreement.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/istock/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Stock Media, Images, Video, Illustrations, Royalty-Free, Getty

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### iStock API (Getty Platform)
Partner API access for iStock content runs on Getty's API platform. Search, asset detail, and download endpoints are namespaced to iStock content. Authentication uses an api-key header plus OAuth 2.0 client credentials. Direct iStock-only API self-service is not offered; access is granted to enterprise partners through Getty's developer program.
- **Base URL:** `https://api.gettyimages.com/v3`
- **Docs:** https://developer.gettyimages.com/docs/

## Common Properties
- [Website](https://www.istockphoto.com/)
- [Developer Portal](https://developer.gettyimages.com/)
- [Plans](plans/istock-plans-pricing.yml) — reconciled (consumer credits/subscriptions; API enterprise via Getty)
- [RateLimits](rate-limits/istock-rate-limits.yml) — reconciled (inherits Getty per-key QPS)
- [FinOps](finops/istock-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
