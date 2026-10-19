# Data for the pre-doctoral exercise: what do merchants do about card fees?

Three files, in `data/`:

| File | Contents |
|---|---|
| `payments.csv.gz` | One row per payment, April 1 to September 30, 2025: payment ID, order reference, merchant ID, date, hour, tender (cash or card), card funding type (credit, debit, prepaid), and amount paid. |
| `line_items.csv.gz` | One row per line on each order's receipt: order ID, line number, description, quantity and amount. |
| `merchants.csv` | The merchant directory: merchant ID and merchant category code (MCC). |

Keep the files as they are, and write code that runs from these raw files. Part of the exercise is to join them and to explain how you know the joins are right.

## Download

```
git clone https://github.com/luluywang/predoc-card-fees-data.git
```

or download each file from the `data/` folder on GitHub (use the "Download raw file" button).
