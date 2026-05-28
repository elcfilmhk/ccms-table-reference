# ZVEE_PARAM
**Description:** VEE: Table of Variant Variables (Client-Specific)
**Total Fields:** 3
**Key Fields:** MANDT, NAME

## Programs Using This Table
- `zrvee_pre_bill_estimation`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `NAME` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 3 | `LOW` | CHAR | 255 |  | Selection Variants: Field Content (LOW/HIGH) |
