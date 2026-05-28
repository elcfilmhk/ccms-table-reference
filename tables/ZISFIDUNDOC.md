# ZISFIDUNDOC
**Description:** Documents from dunning
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, OPBEL, OPUPW, OPUPK, OPUPZ

## Programs Using This Table
- `zisfi0005_dun`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 4 | `OPUPW` | NUMC | 3 | 🔑 | Repetition Item in Contract Account Document |
| 5 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 6 | `OPUPZ` | NUMC | 3 | 🔑 | Subitem for a Partial Clearing in Document |
