# ZISSECREV
**Description:** Security Audit Review
**Total Fields:** 21
**Key Fields:** MANDT, EXTRACT_DATE, USERID, BPOST, ROLE, TCODE

## Programs Using This Table
- `zissecrev`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EXTRACT_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `USERID` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 4 | `BPOST` | CHAR | 30 | 🔑 | B-Post (Composite Role) |
| 5 | `ROLE` | CHAR | 30 | 🔑 | Role Name |
| 6 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 7 | `VALID_TO` | DATS | 8 |  | Valid To Date of User Account |
| 8 | `LOCKED` | CHAR | 3 |  | User Locked Status |
| 9 | `ORG_UNIT` | CHAR | 40 |  | Organization Unit Description |
| 10 | `BPOST_DESC` | CHAR | 80 |  | B-Post Description |
| 11 | `TCODE_DESC` | CHAR | 36 |  | Tcode Description |
| 12 | `ROLE_DESC` | CHAR | 80 |  | Security Role Description |
| 13 | `CCMS_ROLE` | CHAR | 3 |  | Yes/No for CCMS Profile |
| 14 | `DATA_MINING_ROLE` | CHAR | 3 |  | Yes/No for Data Mining Profile |
| 15 | `SMIS_ROLE` | CHAR | 3 |  | Yes/No for SMIS Profile |
| 16 | `EDM_ROLE` | CHAR | 3 |  | Yes/No for EDM Profile |
| 17 | `CRM_ROLE` | CHAR | 3 |  | Yes/No for CRM Profile |
| 18 | `IXOS_ROLE` | CHAR | 3 |  | Yes/No for IXOS Profile |
| 19 | `CCMS_BW_ROLE` | CHAR | 3 |  | Yes/No for CCMS BW Profile |
| 20 | `CRM_BW_ROLE` | CHAR | 3 |  | Yes/No for CRM BW Profile |
| 21 | `SYSID` | CHAR | 8 |  | Name of SAP System |
