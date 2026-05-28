# ZISCSCT_OUT_CONT
**Description:** Outgoing Contacts for Call taking
**Total Fields:** 6
**Key Fields:** MANDT, SOURCE, SOURCE_REF_NO, ID

## Programs Using This Table
- `ziscs0372`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCE` | CHAR | 10 | 🔑 | Source Call-taking System |
| 3 | `SOURCE_REF_NO` | CHAR | 80 | 🔑 | Reference number to refer back to source system |
| 4 | `ID` | INT1 | 3 | 🔑 | Artificial Key for Out-Going Contacts |
| 5 | `DISPATCH` | CHAR | 1 |  | Dispatch |
| 6 | `CONTACT` | CHAR | 300 |  | Contact ID (eg. A tel#, an email addr, WeChatOpenID, etc...) |
