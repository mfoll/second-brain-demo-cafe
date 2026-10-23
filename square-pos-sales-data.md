---
type: Source
source_type: Internal dataset
date_accessed: 2026-10-19
belongs_to: "[[run-daily-operations]]"
related_to:
  - "[[savoury-lunch-trim]]"
  - "[[end-of-day-waste-log]]"
  - "[[christmas-preorders-2026]]"
  - "[[early-shift-production-schedule]]"
_organized: true
---

# Square POS Sales Data

The sales exports from Square Point of Sale, our till since 2021. Everything we know about when people buy and what they buy comes from here. Kept as monthly exports plus the live dashboard.

## Summary

Two exports matter. **Takings by hour**: gross sales, transactions and average ticket for each hour of each trading day. **Item sales**: units and gross sales for each item and modifier, by day. Both are exported on the first Monday of the month into a spreadsheet, one tab per month, from January 2023. Only aggregates are kept; no customer or card data leaves Square.

## Why It Matters

Most of our bigger decisions rest on these tables:

- The lunch cut and its partial reversal: takings between 11:30 and 14:30 before and after 2026-02-23 ([[savoury-lunch-trim]], [[team-meeting-2026-02-05]], [[menu-review-2026-04-09]]).
- Waste: matching late bakes to sales after 14:00, with the [[end-of-day-waste-log]].
- Christmas: last year's preorder items and collection days ([[christmas-preorders-2026]]).
- The bake plan: Kofi's quantities by day of the week ([[early-shift-production-schedule]]).
- Pavement covers: the share of takings from May to September ([[pavement-seating-licence]]).

## Key Details

Figures for 2025, the first full year with both exports clean:

| Measure | Tuesday to Friday | Saturday | Sunday |
|---|---|---|---|
| Transactions per day | 245 | 390 | 260 |
| Average ticket | 7.60 | 8.70 | 8.10 |
| Busiest hour | 08:00-09:00 | 10:00-11:00 | 10:00-11:00 |
| Share of takings after 14:00 | 11% | 14% | 9% (to 14:00 close) |

- Coffee drinks are about 34% of units and 24% of gross sales.
- Croissants and pains au chocolat are the top two items by units every month.
- Pavement months: May to September 2025 takings were 9% higher per day than April, most of it on Saturdays.

## Caveats

- Square records gross takings including VAT; for margins use the Xero figures ([[bookkeeping-move-to-xero]]).
- Item names changed when the menu changed; the export from February 2026 has a new item list, so year-on-year item comparisons need a mapping.
- Wholesale sales from June to October 2025 were invoiced in Xero and are not in Square.
- Hourly figures on days with a till outage (2025-08-12, 2026-01-17) are incomplete.

## Source Location

Square dashboard (Odile's login) and the spreadsheet `Sales / Square exports` in the shared drive, one tab per month.

See also [[point-of-sale]] for the general idea.
