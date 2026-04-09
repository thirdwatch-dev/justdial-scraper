# JustDial Scraper

> Extract Indian business listings, ratings, and contact details from JustDial.com

[![Try on Apify](https://img.shields.io/badge/Try_on-Apify_Store-00C853?style=for-the-badge)](https://apify.com/thirdwatch)
[![Website](https://img.shields.io/badge/Website-thirdwatch.dev-000?style=for-the-badge)](https://thirdwatch.dev)

## What it does

Scrapes JustDial, India's largest local business directory, for business names, addresses, phone numbers, ratings, reviews, and service details. Covers all Indian cities with millions of verified business listings. Perfect for India market lead generation.

## Output fields

| Field | Type | Description |
|-------|------|-------------|
| name | String | Business name |
| address | String | Full address |
| phone | String | Phone number |
| rating | Number | JustDial rating |
| reviewCount | Number | Number of reviews |
| category | String | Business category |
| city | String | Indian city |
| services | Array | Services offered |
| website | String | Business website if available |
| url | String | JustDial listing URL |

## Input parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| queries | Array | Business type search (e.g., "plumbers") |
| city | String | Indian city (Mumbai, Delhi, Bangalore, etc.) |
| maxResults | Number | Maximum results per query |

## Example output

```json
{
  "name": "Kumar Electricals",
  "address": "123 MG Road, Koramangala, Bangalore 560034",
  "phone": "+91-80-1234-5678",
  "rating": 4.3,
  "reviewCount": 245,
  "category": "Electrical Contractors",
  "city": "Bangalore",
  "services": ["Home Wiring", "Industrial Electrical", "Solar Installation"],
  "website": "https://kumarelectricals.in",
  "url": "https://www.justdial.com/Bangalore/Kumar-Electricals/..."
}
```

## Pricing

| Plan | Price |
|------|-------|
| Pay per result | $0.002/result |
| Free tier | Available on Apify |

## Use cases

- India market lead generation across all cities
- Local business competitive analysis
- Service provider directory aggregation
- India B2B sales prospecting
- Market sizing for Indian local services

## Getting started

1. Go to the [Apify Store](https://apify.com/thirdwatch)
2. Find the **JustDial Scraper**
3. Enter business type and Indian city
4. Run and download results as JSON, CSV, or Excel

## Related scrapers by Thirdwatch

- [Google Maps Scraper](https://github.com/thirdwatch-dev/google-maps-scraper) -- Global business data
- [IndiaMart Scraper](https://github.com/thirdwatch-dev/indiamart-scraper) -- B2B suppliers
- [Naukri Scraper](https://github.com/thirdwatch-dev/naukri-scraper) -- India jobs
- [AmbitionBox Scraper](https://github.com/thirdwatch-dev/ambitionbox-scraper) -- India salary data
- [Trustpilot Scraper](https://github.com/thirdwatch-dev/trustpilot-scraper) -- Business reviews

## About Thirdwatch

[Thirdwatch](https://thirdwatch.dev) builds production-ready web scraping APIs. 18 scrapers for jobs, e-commerce, reviews, social media, and business data.

## License

MIT
