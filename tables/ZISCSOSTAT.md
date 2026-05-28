# ZISCSOSTAT
**Description:** Statistics of service order
**Total Fields:** 23
**Key Fields:** MANDT, BGDAT, EDDAT, SECTN, GRPBY, MAING, ILART

## Programs Using This Table
- `ziscs0014`
- `ziscs0014_adj`
- `ziscs0021`
- `zisdm0420`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BGDAT` | DATS | 8 | 🔑 | Valid-from date - in current Release only 00010101 possible |
| 3 | `EDDAT` | DATS | 8 | 🔑 | Valid-to date in current Release only 99991231 possible |
| 4 | `SECTN` | CHAR | 2 | 🔑 | Section of report |
| 5 | `GRPBY` | CHAR | 8 | 🔑 | Group by key |
| 6 | `MAING` | CHAR | 5 | 🔑 | Main group |
| 7 | `ILART` | CHAR | 3 | 🔑 | Maintenance activity type |
| 8 | `BFCUR` | DEC | 12 |  | B/F (current month) |
| 9 | `CRCUR` | DEC | 12 |  | Create (current month) |
| 10 | `CACUR` | DEC | 12 |  | Cancelled (current month) |
| 11 | `COCUR` | DEC | 12 |  | Completed (Current month) |
| 12 | `RCACUR` | DEC | 12 |  | Reversed Cancellation (current month) |
| 13 | `RCOCUR` | DEC | 12 |  | Reversed Completion (Current month) |
| 14 | `PCACUR` | DEC | 12 |  | Partial Reversed Cancellation (current month) |
| 15 | `CFCUR` | DEC | 12 |  | C/F (current month) |
| 16 | `MSCUR` | DEC | 12 |  | Mass (current month) |
| 17 | `CRYTD` | DEC | 12 |  | Create (Year-to-date) |
| 18 | `CAYTD` | DEC | 12 |  | Cancelled (Year-to-date) |
| 19 | `COYTD` | DEC | 12 |  | Completed (Year-to-date) |
| 20 | `RCAYTD` | DEC | 12 |  | Reversed Cancellation (Year-to-date) |
| 21 | `RCOYTD` | DEC | 12 |  | Reversed Completion (Year-to-date) |
| 22 | `PCAYTD` | DEC | 12 |  | Partial Reversed Cancellation (Year-to-date) |
| 23 | `MSYTD` | DEC | 12 |  | Mass (Year-to-date) |
