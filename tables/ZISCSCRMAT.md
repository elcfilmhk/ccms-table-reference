# ZISCSCRMAT
**Description:** SMIS Product type and CRM Attribute Mapping
**Total Fields:** 5
**Key Fields:** MANDT, KONDM

## Programs Using This Table
- `ziscs0040`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KONDM` | CHAR | 2 | 🔑 | Material Pricing Group |
| 3 | `ATTRIBSET` | CHAR | 18 |  | CRM Marketing: Target Group Selection - Attribute Set |
| 4 | `ATTRIBID` | CHAR | 30 |  | CRM Marketing: Attribute Name |
| 5 | `ATTRIBVAL` | CHAR | 30 |  | CRM Marketing: Attribute Value |
