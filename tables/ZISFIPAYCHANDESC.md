# ZISFIPAYCHANDESC
**Description:** New Payment Channels DocType and Description Table
**Total Fields:** 7
**Key Fields:** MANDT, OFFIC_EX

## Programs Using This Table
- `zisfi0129`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 3 | `BLART` | CHAR | 2 |  | Document Type |
| 4 | `PYMTCHNL` | CHAR | 2 |  | Payment Channel |
| 5 | `DESC_S` | CHAR | 7 |  | Short Description |
| 6 | `DESC_M` | CHAR | 12 |  | Medium Description |
| 7 | `DESC_L` | CHAR | 30 |  | Long Description |
