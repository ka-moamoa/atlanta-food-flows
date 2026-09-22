# Atlanta Food Flows

Interactive map of food and cash grants between Atlanta-area food nonprofits, their partner agencies, and the national networks that supply them, reconstructed from IRS Form 990 Schedule I and 990-PF filings.

**Live:** <https://ka-moamoa.github.io/atlanta-food-flows/>

The Priority areas tab also draws the project team's Atlanta food systems map (the Kumu map at <https://kumu.io/nicolejjk/atlanta-food-systems-map>, 793 organizations and 1,261 typed relationships from the 2026-08-18 export) as its own interactive visualization, with a permalink at [/system-map](https://ka-moamoa.github.io/atlanta-food-flows/system-map).

Permalinks: [/network](https://ka-moamoa.github.io/atlanta-food-flows/network), [/sankey](https://ka-moamoa.github.io/atlanta-food-flows/sankey), [/map](https://ka-moamoa.github.io/atlanta-food-flows/map), [/food-security](https://ka-moamoa.github.io/atlanta-food-flows/food-security), [/system-map](https://ka-moamoa.github.io/atlanta-food-flows/system-map), [/takeaways](https://ka-moamoa.github.io/atlanta-food-flows/takeaways), [/priority-areas](https://ka-moamoa.github.io/atlanta-food-flows/priority-areas), [/about](https://ka-moamoa.github.io/atlanta-food-flows/about). Each route folder holds a copy of the same page; the page reads the route from its path.

The Food security tab sets Feeding America's Map the Meal Gap county estimates (2024, modeled) beside the charitable food the filings record in each county, as an upper bound on coverage; the Takeaways county table carries the same estimates, the Map layout can shade counties by them, and the network can be tinted by county food insecurity. Data for every release (2009 to 2024) shared by Feeding America Research in September 2026.

## Credits

A project of the Ka Moamoa lab, Georgia Institute of Technology, with the Brook Byers Institute for Sustainable Systems (BBISS).

- **Dr. Josiah Hester**, Lab Director, Ka Moamoa
- **Dr. Nicole Kennard**, BBISS Assistant Director of Community Engaged Research
- **Tristan Daniel**, Ph.D. student, Ka Moamoa Lab

The page's "About the data" tab documents sources, methods, assumptions and known gaps.

This repo holds only the deployable page (`index.html`, data inlined). The pipeline that produces it lives in the private `ka-moamoa/food-flows-990` repo.

Source data: IRS Tax Exempt Organization Search e-file XML (2025–2026 releases), IRS Business Master File, ProPublica Nonprofit Explorer. Schedule I itemizes recipients of $5,000 or more only; noncash values are as reported by the giver.
