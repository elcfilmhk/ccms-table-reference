# ZBANKNAME
**Description:** Table of the bank name New Postal Address
**Total Fields:** 5
**Key Fields:** MANDT, SEQNUM, BANKCODE

## Programs Using This Table
- `ziscs0500`
- `ziscsbnka`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQNUM` | NUMC | 4 | 🔑 | Bank key sequence number |
| 3 | `BANKCODE` | CHAR | 15 | 🔑 | Bank Keys |
| 4 | `ENGNAME` | CHAR | 60 |  | Bank Name in English |
| 5 | `CHINAME` | CHAR | 60 |  | Bank Name in Chinese |
