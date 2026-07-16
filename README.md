# Daily Dashboard Analysis (Ignite)

Upload settlement Excel exports (one month or multiple months) and see **mismatch-only** results:

- Difference bar chart
- Difference table

## Live dashboard

After GitHub Pages is enabled:

https://rvravii.github.io/settlement-balance-check/

## How to use

1. Open the live link
2. Upload `.xlsx` settlement export(s)
3. Review mismatch chart + table
4. Filter by month if needed

## Check formula

`Starting Balance + Collected + Collections + Refunds + Chargeback + Returns + Deduction + Reimbursement + Less: Payments at Club + Deposit`  
should equal **Ending Balance** (± $0.02).

## Local

Open `index.html` in a browser (internet needed for the Excel parser CDN).
