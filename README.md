# Duda

Duda is a professional website builder platform designed for agencies, SaaS companies, and web professionals who build and manage websites at scale. The platform offers a robust REST API enabling programmatic site creation, content management, white-label branding, and eCommerce integration.

## Overview

- **Website**: https://www.duda.co
- **Developer Portal**: https://developer.duda.co
- **API Reference**: https://developer.duda.co/reference/introduction
- **Pricing**: https://www.duda.co/pricing
- **Status Page**: https://status.duda.co
- **Blog**: https://blog.duda.co
- **GitHub**: https://github.com/dudadev
- **LinkedIn**: https://www.linkedin.com/company/duda
- **X (Twitter)**: https://twitter.com/buildwithduda

## Partner API

The Duda Partner API is a REST API with JSON responses that allows partners to:

- Create and manage websites and pages
- Apply and manage templates
- Inject and update content and collections
- Manage eCommerce stores, products, and orders
- Create and publish blog posts
- Manage SSO for white-label client portal access
- Configure webhooks for event-driven integrations
- Generate sites using Duda's AI stack
- Manage memberships, bookings, and navigation

**Base URL**: `https://api.duda.co/api`

**Authentication**: HTTP Basic Auth using API credentials from the Duda dashboard under Business Tools > API Access.

**Rate Limits**: 10 requests per second (hard limit); 8 requests per second recommended for batch processes.

## Plans

| Plan | Monthly | Annual | Sites | Team Members |
|------|---------|--------|-------|--------------|
| Basic | $19/mo | $9.50/mo | 1 | - |
| Team | $29/mo | $14.50/mo | 1 | 3 |
| Agency | $52/mo | $26/mo | 4 | 6 |
| White Label | $149/mo | $74.50/mo | 4 | 6 |
| Custom | Contact Sales | Contact Sales | Volume | Unlimited |

Additional sites are $17-19/mo each. eCommerce add-ons range from $7-52/mo per site based on product catalog size.

## Resources

- [apis.yml](apis.yml) - APIs.json provider profile
- [plans/duda-plans-pricing.yml](plans/duda-plans-pricing.yml) - Pricing plan details
- [rate-limits/duda-rate-limits.yml](rate-limits/duda-rate-limits.yml) - API rate limit specifications
- [finops/duda-finops.yml](finops/duda-finops.yml) - FinOps cost optimization guidance
