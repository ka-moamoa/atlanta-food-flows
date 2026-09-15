# Atlanta Food Flows

Interactive map of food and cash grants between Atlanta-area food nonprofits, their partner agencies, and the national networks that supply them, reconstructed from IRS Form 990 Schedule I and 990-PF filings.

**Live:** <https://ka-moamoa.github.io/atlanta-food-flows/>

Permalinks: [/network](https://ka-moamoa.github.io/atlanta-food-flows/network), [/sankey](https://ka-moamoa.github.io/atlanta-food-flows/sankey), [/map](https://ka-moamoa.github.io/atlanta-food-flows/map), [/food-security](https://ka-moamoa.github.io/atlanta-food-flows/food-security), [/takeaways](https://ka-moamoa.github.io/atlanta-food-flows/takeaways), [/about](https://ka-moamoa.github.io/atlanta-food-flows/about). Each route folder holds a copy of the same page; the page reads the route from its path.

## Credits

A project of the Ka Moamoa lab, Georgia Institute of Technology, with the Brook Byers Institute for Sustainable Systems (BBISS).

- **Dr. Josiah Hester**, Lab Director, Ka Moamoa
- **Dr. Nicole Kennard**, BBISS Assistant Director of Community Engaged Research
- **Tristan Daniel**, Ph.D. student, Ka Moamoa Lab

The page's "About the data" tab documents sources, methods, assumptions and known gaps.

This repo holds only the deployable page (`index.html`, data inlined). The pipeline that produces it lives in the private `ka-moamoa/food-flows-990` repo.

Source data: IRS Tax Exempt Organization Search e-file XML (2025–2026 releases), IRS Business Master File, ProPublica Nonprofit Explorer. Schedule I itemizes recipients of $5,000 or more only; noncash values are as reported by the giver.
