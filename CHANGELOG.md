# Changelog

All notable changes to this project are documented here.

---

## v2.0 — 6-Person Support

**Expanded capacity**
- Increased maximum group size from 4 to 6 people
- Added two new person columns with full formula and checkbox coverage
- Updated all SUBTOTAL, TAX, and TOTAL formulas to include new columns
- Expanded validation checks (✅/❌) to cover all 6 shares

**"Who Paid" system**
- Updated dropdown to support all 6 people
- Added two additional "owes" output rows for the expanded group
- Color-coded each person's dropdown option for faster visual identification

**Structural improvements**
- Cleaned up legacy scratch data and intermediate calculation tables that were left in below the main sheet
- Standardized column layout and label positioning

---

## v1.0 — Initial Build

- Built to solve a real problem: splitting Costco runs with roommates where not everyone buys every item
- Per-item checkbox splitting across up to 4 people
- Automatic tax calculation — taxable items flagged separately, tax applied only to those rows
- "Who Paid" dropdown to select whoever fronted the bill, with auto-calculated owe amounts for everyone else
- Built-in ✅/❌ validation to confirm individual shares sum to the correct total
- Designed to be duplicated per trip and stacked in one file for a running history
