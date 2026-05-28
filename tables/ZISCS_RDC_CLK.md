# ZISCS_RDC_CLK
**Description:** RAW data from Radica - Email Clicks
**Total Fields:** 7
**Key Fields:** MANDT, EVNT_RDCDT, RCPT_EML_TOKEN, REQ_RDCDT

## Programs Using This Table
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVNT_RDCDT` | CHAR | 30 | 🔑 | Radica Event Timestamp |
| 3 | `RCPT_EML_TOKEN` | CHAR | 32 | 🔑 | Recipient Email Address Token |
| 4 | `REQ_RDCDT` | CHAR | 30 | 🔑 | Radica Timestamp - send Request time |
| 5 | `EML_GUID` | CHAR | 32 |  | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 6 | `COL_HEADER_ID` | INT4 | 10 |  | Natural number |
| 7 | `RAW_STR` | STRG | 0 |  | Raw String of a row of CSV |
