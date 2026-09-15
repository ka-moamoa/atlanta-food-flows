# Atlanta Food Flows

Interactive map of food and cash grants between Atlanta-area food nonprofits, their partner agencies, and the national networks that supply them, reconstructed from IRS Form 990 Schedule I and 990-PF filings.

**Live:** <https://ka-moamoa.github.io/atlanta-food-flows/>

This repo holds only the deployable page (`index.html`, data inlined). The pipeline that produces it lives in the private `ka-moamoa/food-flows-990` repo.

Source data: IRS Tax Exempt Organization Search e-file XML (2025–2026 releases), IRS Business Master File, ProPublica Nonprofit Explorer. Schedule I itemizes recipients of $5,000 or more only; noncash values are as reported by the giver.
