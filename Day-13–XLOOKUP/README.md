# Day 13 – XLOOKUP in Excel

## What is XLOOKUP?

XLOOKUP is a modern replacement for VLOOKUP that allows flexible data searching.

## Syntax

=XLOOKUP(lookup_value, lookup_array, return_array)

## Advantages

- Works in both directions
- No need for column index
- Handles errors better
- More flexible than VLOOKUP

## Example

=XLOOKUP(A2, D2:D5, E2:E5)

## XLOOKUP simplifies data lookup operations in Excel.

=XLOOKUP(A2, Sheet2!A2:A5, Sheet2!B2:B5)


## 🔧 Handling Not Found (Important)

=XLOOKUP(A2, Sheet2!A2:A5, Sheet2!B2:B5, "Not Found")


## XLOOKUP with Multiple Sheets

=XLOOKUP(A2, Sheet2!A2:A5, Sheet2!B2:B5, "Not Found")

This allows you to fetch data from another sheet dynamically.


## 🔁 Bonus (Reverse Lookup – Impossible in VLOOKUP)

If your table is:

Price	Product

You can still do:

=XLOOKUP(55000, Sheet2!B2:B5, Sheet2!A2:A5)

👉 This fetches Product from Price
👉 VLOOKUP cannot do this ❌
