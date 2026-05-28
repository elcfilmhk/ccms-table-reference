# ZBAGUIVERSION
**Description:** Log SAP GUI patch level of user
**Total Fields:** 8
**Key Fields:** BNAME, TERMINAL

## Programs Using This Table
- `z_blocking_lock`
- `z_waiting_lock`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BNAME` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 2 | `TERMINAL` | CHAR | 36 | 🔑 | Terminal |
| 3 | `IPADDRESS` | CHAR | 16 |  | Physical address (Internet address) |
| 4 | `FILENAME` | CHAR | 128 |  | Local file for upload/download |
| 5 | `VERSION` | CHAR | 30 |  | 30 Characters |
| 6 | `TRDAT` | DATS | 8 |  | Last Logon Date |
| 7 | `LTIME` | TIMS | 6 |  | Last Logon Time |
| 8 | `WINVERSION` | CHAR | 12 |  | Character Field of Length 12 |
