# ZISFIRECKY
**Description:** Naming conversion
**Total Fields:** 4
**Key Fields:** MANDT, HERKF, ZWELS

## Programs Using This Table
- `zisdmupld`
- `zisfi0006`
- `zisfi0197`
- `zisfi0197_smis`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HERKF` | CHAR | 2 | 🔑 | Document Origin Key |
| 3 | `ZWELS` | CHAR | 20 | 🔑 | List of Payment Methods that Should be Used in a Payment Run |
| 4 | `POST_ABB` | CHAR | 5 |  | Text key |
