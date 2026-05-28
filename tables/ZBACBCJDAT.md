# ZBACBCJDAT
**Description:** Structure for job information
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zbacbe026`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BTCSYSTEM` | CHAR | 32 |  | Target System to Run Background Job |
| 2 | `PROGNAME` | CHAR | 40 |  | ABAP Program Name |
| 3 | `VARIANT1` | CHAR | 14 |  | ABAP: Name of variant (without program name) |
| 4 | `FILEINTERN` | CHAR | 60 |  | Logical file name |
| 5 | `GROUPID` | CHAR | 12 |  | Group name: Batch input session name |
| 6 | `QID` | CHAR | 20 |  | Queue Identification (Unique Key) |
| 7 | `PRDMINS` | NUMC | 2 |  | Duration period (in minutes) for a batch job |
| 8 | `USEGEN` | CHAR | 1 |  | Identifier use general data |
