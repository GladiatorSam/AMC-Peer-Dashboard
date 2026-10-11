# AMC-Peer-Dashboard
# Indian Listed AMC Peer Analysis (FY2022-FY2026)

An Excel dashboard comparing four listed Indian asset management companies on growth, profitability, returns, dividends and valuation, built from public financial data.

**Companies:** HDFC AMC, Nippon Life India Asset Management, Aditya Birla Sun Life AMC, UTI AMC

## Objective
Show which listed AMCs earn the best returns and margins, how consistent that has been over five years, and how the market prices the difference.

## Key findings (FY2026)

| Company | Revenue (₹ cr) | Net profit (₹ cr) | Net margin | ROE | P/E | Div. yield |
|---|---|---|---|---|---|---|
| HDFC AMC | 4,611 | 2,859 | 62.0% | 32.9% | 34.0x | 2.4% |
| Nippon India AMC | 2,924 | 1,529 | 52.3% | 34.5% | 43.7x | 2.1% |
| Aditya Birla Sun Life AMC | 2,056 | 975 | 47.4% | 25.1% | 29.8x | 2.5% |
| UTI AMC | 1,705 | 404 | 23.7% | 8.9% | 27.9x | 4.6% |

- **HDFC AMC** is the largest and most efficient, with an 82% EBITDA margin.
- **Nippon India** has the highest ROE and the fastest 5-year profit growth (17.6% a year, FY21-FY26).
- **UTI** is the outlier: FY2026 profit fell about 45%, mainly because of a ₹176 cr fair-value loss on investments in Q4 (company press release, 23 Apr 2026), while core income grew. It also paid out 127% of profit as dividends.
- Valuation follows quality: the highest ROE companies trade at the highest P/E, and UTI is the cheapest.
- All four are nearly debt-free and hold 73% to 94% of assets as investments.

## What is in the workbook
| Sheet | Purpose |
|---|---|
| Dashboard | FY2026 snapshot, draft insights and 4 trend charts |
| Ratios | Revenue growth, EBITDA and net margin, ROE, dividend payout, cash conversion, investments % of assets |
| Data | Raw figures from the Screener.in exports and market data |
| AUM Add-on | Revenue and profit per unit of AUM (basis stated on the sheet) |
| Guide | Definitions, colour code and caveats |

## Method
- Data: Screener.in Excel exports (consolidated), FY2017-FY2026, with market price and market cap as at the export date (Oct 2026).
- EBITDA = Sales less operating expenses. ROE = net profit / average shareholders' equity. Payout = dividend / net profit. P/E and P/B use FY2026 profit and equity.
- A reconciliation check rebuilds profit before tax from the expense lines and compares it to the reported figure. It equals zero for all companies and years.
- All calculations are live Excel formulas linked to the Data sheet.

## Limitations
- Screener's annual "Sales" for AMCs appears to include investment gains and losses, so revenue moves with markets.
- The four AMCs differ in size and business mix (equity, debt, passive, alternatives), so they are not perfectly like-for-like.
- AUM-based metrics are approximate: the AUM basis and the consolidated revenue may not match exactly.
- This is an educational analysis, not investment advice.

## Tools
Excel (formulas, conditional formatting, charts), Screener.in data

## Author
Satyam Arora | [LinkedIn](https://www.linkedin.com/in/satyam-arorab83a3648)
