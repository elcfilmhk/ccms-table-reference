# ZISDISC
**Description:** Disconnect Service Order
**Total Fields:** 9
**Key Fields:** MANDT, LAUFD, LAUFI, DISCNO, VERTRAG

## Programs Using This Table
- `zisfi0005`
- `zisfi0005_dun`
- `zisfi0009`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LAUFD` | DATS | 8 | 🔑 | Date ID |
| 3 | `LAUFI` | CHAR | 6 | 🔑 | Additional Identification Characteristic |
| 4 | `DISCNO` | CHAR | 12 | 🔑 | Disconnection document number |
| 5 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 6 | `MSALM` | CURR | 13 |  | Dunning Balance |
| 7 | `DOC_TYPE` | CHAR | 2 |  | Document type for dunning |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `MAHNV` | CHAR | 2 |  | Dunning Procedure |
