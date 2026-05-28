# ZISCS_SUB_ITMPOS
**Description:** Subsidy Usage & Line item postings tracking table
**Total Fields:** 30
**Key Fields:** MANDT, VKONT, CPUDT, CPUTM, SEQ

## Programs Using This Table
- `zccgvt9`
- `zisbi0167`
- `zisbi0167_ami`
- `zisbi0167_bw`
- `ziscs0226`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`
- `ziscs0244`
- `ziscs0251`
- `ziscs0831`
- `zisfi0185`
- `zisfi0187`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 4 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 5 | `SEQ` | NUMC | 2 | 🔑 | Sequence number for Gov subsidy |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `TRANPROC` | CHAR | 12 |  | Transaction process |
| 9 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 10 | `BELNR` | CHAR | 12 |  | Billing document number of the invoice |
| 11 | `REFMTH` | DATS | 8 |  | Entitlement ref month |
| 12 | `INVENE` | CURR | 13 |  | Energy cons (invoice) |
| 13 | `SUBAMT` | CURR | 13 |  | Subsidy amount |
| 14 | `ERNAM` | CHAR | 12 |  | Created By |
| 15 | `PRINTDOC` | CHAR | 12 |  | Print document number |
| 16 | `REVDOC` | CHAR | 12 |  | Reversal document |
| 17 | `SENTAM` | CURR | 13 |  | Snapshot of A |
| 18 | `SENTRE` | CURR | 13 |  | Snapshot of B |
| 19 | `SENTBA` | CURR | 13 |  | Snapshot of C |
| 20 | `FIRINV` | CHAR | 1 |  | Frist Invoice |
| 21 | `FORFEI` | CURR | 13 |  | Forfeiture amount |
| 22 | `FORREA` | CHAR | 2 |  | Forfeiture reason |
| 23 | `FAEDN` | DATS | 8 |  | Invoice due date |
| 24 | `GOVINV` | DATS | 8 |  | Date on which invoice is sent to government |
| 25 | `RENOGI` | CHAR | 12 |  | Reason for no government invoice |
| 26 | `SENTD` | CURR | 13 |  | Snapshot of D (2011 Subsidy granted V total to-date) |
| 27 | `SENTE` | CURR | 13 |  | Snapshot of E (Subsidy brought forward from last bill) |
| 28 | `SENTF` | CURR | 13 |  | Snapshot of F (2011 Subsidy granted V since last bill) |
| 29 | `SENTG` | CURR | 13 |  | Snapshot of G (Subsidy used for this bill) |
| 30 | `SENTH` | CURR | 13 |  | Snapshot of H (Subsidy balance) |
