---
type: Source
source_type: Internal document
date_accessed: 2025-06-16
belongs_to: "[[bookkeeping-move-to-xero]]"
related_to:
  - "[[square-pos-sales-data]]"
  - "[[xero-chart-of-accounts-setup]]"
_organized: true
---

# Square To Xero Daily Import Settings

How the Square takings reach Xero each day, written down on 2025-06-16 after fixing the card-fee mistake.

## Summary

One summary invoice per trading day in Xero, split by Square category into the sales accounts, with card fees posted as an expense and the payout matched to the bank feed two working days later.

## Why It Matters

Without it, the reconciliation would still take hours, and sales by menu section would not exist. The item-level and hourly data stay in Square ([[square-pos-sales-data]]).

## Key Details

- Square categories mapped: Bread and viennoiserie, Cakes, Lunch, Hot drinks, Cold drinks, Preorders, Wholesale (unused since 2025-10-20).
- Card fees to "Card processing fees", not netted (this was the bug: fees were booked as negative sales for the first two weeks of June 2025).
- Cash takings entered by Lena from the cash-up sheet; the till float is not posted.
- Deposits for preorders posted to "Deposits received" until collection ([[christmas-2025-deposits-reconciliation]]).
- Monday-closed days produce no invoice; Sunday's payout lands on Tuesday.

## Caveats

Refunds appear on the day they are made, not against the original sale.

## Source Location

Settings in Xero's connected apps; this note is the only written record.
