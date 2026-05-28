# ZISFIBW_WRITEOFF
**Description:** BW Data Extraction: write-off / write-in
**Total Fields:** 28
**Key Fields:** MANDT, AKLASSE, TARIFTYP, AUSZDAT, GPART, VKONT, RPT_FM, RPT_TO, ERDAT, ERZET, ERNAM

## Programs Using This Table
- `zisfi0016`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AKLASSE` | CHAR | 4 | 🔑 | Billing class |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `AUSZDAT` | DATS | 8 | 🔑 | Move-Out Date |
| 5 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 6 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 7 | `RPT_FM` | DATS | 8 | 🔑 | Report Date From |
| 8 | `RPT_TO` | DATS | 8 | 🔑 | Report Date To |
| 9 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 10 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 11 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 12 | `CNAME` | CHAR | 40 |  | Customer Name |
| 13 | `CADDR1` | CHAR | 40 |  | Customer Address 1 |
| 14 | `CADDR2` | CHAR | 40 |  | Customer Address 2 |
| 15 | `CADDR3` | CHAR | 40 |  | Customer Address 3 |
| 16 | `CADDR4` | CHAR | 40 |  | Customer Address 4 |
| 17 | `CADDR5` | CHAR | 40 |  | Customer Address 5 |
| 18 | `CADDR6` | CHAR | 40 |  | Customer Address 6 |
| 19 | `BPKIND` | CHAR | 4 |  | Business Partner Type |
| 20 | `AUGBTOFF` | CURR | 13 |  | Clearing amount in clearing currency |
| 21 | `AUGBTIN` | CURR | 13 |  | Clearing amount in clearing currency |
| 22 | `DOCTYPE` | CHAR | 9 |  | Document Type |
| 23 | `WOFFIND` | CHAR | 1 |  | Write Off Indicator |
| 24 | `AUGRD` | CHAR | 2 |  | Clearing Reason |
| 25 | `AUGBD` | DATS | 8 |  | Clearing document posting date |
| 26 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 27 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 28 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
