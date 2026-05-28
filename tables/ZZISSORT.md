# ZZISSORT
**Description:** Sort Criteria for bills includes the sort key
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `zis_batch_insert_message======ft`
- `zis_new_batch_criteria========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `FORM_TYPE` | CHAR | 1 |  | Pre printed Form Type |
| 2 | `LOCATION` | CHAR | 10 |  | Dispatch Location |
| 3 | `PRIORITY` | NUMC | 6 |  | Priority |
| 4 | `BATCH_NO` | NUMC | 10 |  | Batch Number |
| 5 | `SORTKEY` | CHAR | 255 |  | The sort key |
