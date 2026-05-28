# ZISCRMSEGLABEL
**Description:** Segment Label - Customer Segment
**Total Fields:** 7
**Key Fields:** MANDT, CA

## Programs Using This Table
- `zisbi0170`
- `zisbi0171_ptr`
- `zisbi0172_ptr`
- `ziscrm0312`
- `ziscs0476_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `SEGMENTLABEL` | CHAR | 3 |  | Segment Label - Customer Segment |
| 4 | `STRATEGICLABEL` | CHAR | 3 |  | Segment Label - Strategic |
| 5 | `SMELABEL` | CHAR | 3 |  | Segment Label - SME |
| 6 | `PSYCHOGRAPHICLABEL` | CHAR | 16 |  | Segment Label V Psychographic |
| 7 | `EECLABEL` | CHAR | 10 |  | EE&C Segment Label |
