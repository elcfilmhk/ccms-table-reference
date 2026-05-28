# ZBAICPRINT
**Description:** Print Parameter for Interface Programs
**Total Fields:** 32
**Key Fields:** MANDT, REPID, FUNCT

## Programs Using This Table
- `zbaice001`
- `zisbi0042`
- `zisbi0042_ami`
- `zisbi0042_newfm`
- `ziscs0334`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0204`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 4 | `USERID` | CHAR | 12 |  | Background User Name for Authorization Check |
| 5 | `PDEST` | CHAR | 4 |  | Spool Output Device |
| 6 | `PRCOP` | NUMC | 3 |  | Number of Spool Copies |
| 7 | `PLIST` | CHAR | 12 |  | Spool Request |
| 8 | `PRTXT` | CHAR | 68 |  | Spool Description |
| 9 | `PRIMM` | CHAR | 1 |  | Immediate Spool Print |
| 10 | `PRREL` | CHAR | 1 |  | Immediate Spool Deletion |
| 11 | `PRNEW` | CHAR | 1 |  | New Spool Request |
| 12 | `PEXPI` | NUMC | 1 |  | Spool Retention Period |
| 13 | `LINCT` | INT4 | 10 |  | Page Length of List |
| 14 | `LINSZ` | INT4 | 10 |  | Line width of list |
| 15 | `PAART` | CHAR | 16 |  | Spool Format |
| 16 | `PRBIG` | CHAR | 1 |  | Spool Cover Sheet |
| 17 | `PRSAP` | CHAR | 1 |  | Print: SAP cover page |
| 18 | `PRREC` | CHAR | 12 |  | Spool Recipient Name |
| 19 | `PRABT` | CHAR | 12 |  | Spool Department Name |
| 20 | `PRBER` | CHAR | 12 |  | Print: Authorization |
| 21 | `PRDSN` | CHAR | 6 |  | Spool File |
| 22 | `PTYPE` | CHAR | 12 |  | Print: Type of spool request |
| 23 | `ARMOD` | CHAR | 1 |  | Print: Archiving mode |
| 24 | `FOOTL` | CHAR | 1 |  | Print: Output footer |
| 25 | `PRIOT` | NUMC | 1 |  | PRINT: Spool request priority |
| 26 | `PRUNX` | CHAR | 1 |  | PRINT: Host spool cover page |
| 27 | `SAP_OBJECT` | CHAR | 10 |  | SAP ArchiveLink: Object type of business object |
| 28 | `AR_OBJECT` | CHAR | 10 |  | Document type |
| 29 | `INFO` | CHAR | 3 |  | SAP ArchiveLink: Info field |
| 30 | `ARCTEXT` | CHAR | 40 |  | SAP ArchiveLink: Text information field |
| 31 | `ARCID` | CHAR | 2 |  | SAP ArchiveLink: Target storage system |
| 32 | `ARCREP` | CHAR | 40 |  | SAP ArchiveLink Report Name |
