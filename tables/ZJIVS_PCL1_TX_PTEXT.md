# ZJIVS_PCL1_TX_PTEXT
**Description:** JiVS-Package: Output structure ZJIVS_PCL1_TX_PTEXT
**Total Fields:** 4
**Key Fields:** CLIENT, SRTFD, LINE_NUMBER

## Programs Using This Table
- `zjivs_export_pclx`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `SRTFD` | CHAR | 40 | 🔑 | PCLx key |
| 3 | `LINE_NUMBER` | NUMC | 15 | 🔑 | JiVS Line Number |
| 4 | `LINE` | CHAR | 78 |  | PCL1(TX)-PTEXT-LINE |
