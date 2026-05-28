# ZISCS_SSR_CUST
**Description:** SSR Customer data from Inbound Autogrid interface
**Total Fields:** 35
**Key Fields:** MANDT, VKONT, EVENT_ID, COUNTER

## Programs Using This Table
- `ziscs_migration_contopt_mc3_5`
- `zisdm0368`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisdm0371`
- `zisdm0372`
- `zisdm0375`
- `zisdm0396`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `EVENT_ID` | CHAR | 50 | 🔑 | Event ID from Autogrid |
| 4 | `COUNTER` | NUMC | 5 | 🔑 | Counter for SSR records |
| 5 | `PARTICIPATIO_STAT` | CHAR | 2 |  | Participation status |
| 6 | `DURATION` | NUMC | 3 |  | Participation Duration |
| 7 | `PART_START_DT` | DATS | 8 |  | Participation Start date |
| 8 | `PART_START_TIME` | TIMS | 6 |  | Participation start time |
| 9 | `PART_END_DT` | DATS | 8 |  | Participation End date |
| 10 | `PART_END_TIME` | TIMS | 6 |  | Participation End Time |
| 11 | `ACTUAL_USE` | DEC | 31 |  | Actual Demand (kWh) |
| 12 | `ACTUAL_USE_STATUS` | CHAR | 2 |  | Use Status |
| 13 | `BASELINE_USE` | DEC | 31 |  | Baseline (kWh) |
| 14 | `BASELINE_USE_STATUS` | CHAR | 2 |  | Use Status |
| 15 | `REDUCTION_ACIEVED_1` | DEC | 31 |  | Reduction Achieved1 (kWh) |
| 16 | `REDUCTION_ACIEVED_2` | DEC | 31 |  | Reduction Achieved2 (kW) |
| 17 | `CAPACITY_COMMITMENT` | DEC | 31 |  | Capacity Commitment (kWh) |
| 18 | `BASELINE_METHOD` | CHAR | 2 |  | Baseline method |
| 19 | `ACTUAL_SHED_KWH` | DEC | 31 |  | Actual Shed KWH |
| 20 | `QUALIFIED_SHED_KWH` | DEC | 31 |  | Qualified Shed KWH |
| 21 | `SETTLEMENT_TYPE` | CHAR | 3 |  | Settlement Type |
| 22 | `SETTLEMENT_DETERMINANT` | DEC | 16 |  | Unit Rate |
| 23 | `INCENTIVE` | DEC | 16 |  | Incentive Payment |
| 24 | `APPROVAL_STAT` | CHAR | 2 |  | Approval Status for DR incentive |
| 25 | `ADJUSTMENT` | CHAR | 1 |  | Adjustment Status |
| 26 | `REMARKS` | RAW | 16 |  | Remarks identifier |
| 27 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 28 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 29 | `CREATED_AT` | TIMS | 6 |  | Time |
| 30 | `CHANGED_BY` | CHAR | 12 |  | Name of person who changed object |
| 31 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 32 | `CHANGED_AT` | TIMS | 6 |  | Time |
| 33 | `PROCESSED_ON` | DATS | 8 |  | Incentive Posting Processe on Date |
| 34 | `IMPORTED_ON` | DATS | 8 |  | Result Import Date |
| 35 | `IMPORTED_AT` | TIMS | 6 |  | Result Import Time |
