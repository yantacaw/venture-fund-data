---
license: cc-by-4.0
pretty_name: US Venture Fund Values from SEC Form ADV
tags: [finance, venture-capital, private-equity, sec-filings, form-adv]
---
# US venture fund values from SEC Form ADV

Year-end gross asset value for 16,516 US venture capital funds, as each fund's adviser reported it to the
SEC on Form ADV, Schedule D 7.B.(1), with fund sizes from Form D. Compiled by
[Yantacaw Capital](https://www.yantacawcapital.com/). Updated 2026-10-13.

## Files

- `venture-funds.csv`: one row per fund (16,516 rows): private fund ID, name, firm, vintage, size,
  latest and peak reported value, and a link to the fund's page.
- `venture-fund-values.csv`: one row per fund and fiscal year-end (89,717 rows), 2011 to 2025.

## How to read it

- Gross asset value includes the GP's own commitment and is before carried interest. It is not the LPs' net
  return, and it does not show cash already distributed. A fall in value can mean distributions, markdowns or both.
- Fund size is the amount sold on Form D, which for some funds reflects only a first close.
- Filings made 2012 to 2024 come from the SEC's bulk Form ADV data; year-end 2025 values come from current IAPD
  filings; rows marked `archived IAPD copy` are year-end 2024 values from archived copies of IAPD filings.
- Values are in US dollars. The `private_fund_id` (805-…) is the SEC's private fund identifier and is stable
  across years.

## Coverage

Funds managed by venture firms that file Form ADV with the SEC (registered or exempt reporting advisers).
Single-deal SPV platforms and fund-of-funds managers are excluded.

## License and citation

The underlying filings are public. This compilation is released under CC BY 4.0. Please cite as:
"Analysis of SEC Form ADV filings by Yantacaw Capital" with a link to https://www.yantacawcapital.com/data.html.
