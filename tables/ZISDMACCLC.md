# ZISDMACCLC
**Description:** Account Level Consumption Table
**Total Fields:** 13
**Key Fields:** MANDT, VKONT, VERTRAG, ADAT

## Programs Using This Table
- `z_isdm_actual_demand==========ft`
- `zbacbdb11`
- `zbacbdb12`
- `zbacbdb13`
- `zisbi0044`
- `zisbw0002`
- `zisdm0017`
- `zisdm0019`
- `zisdm0020`
- `zisdm0021`
- `zisdm0029`
- `zisdm0039`
- `zisdm0056`
- `zisdm0057`
- `zisdm0058`
- `zisdm0059`
- `zisdm0060`
- `zisdm0067`
- `zisdm0075`
- `zisdm0080`
- `zisdm0081`
- `zisdm0090`
- `zisdm0091`
- `zisdm0098`
- `zisdm0120`
- `zisfi0031`
- `zisfi0043`
- `zisfi0076`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 4 | `ADAT` | DATS | 8 | 🔑 | Meter reading date relevant to billing |
| 5 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `ZZONPEAKCON` | CHAR | 36 |  | On Peak Consumption |
| 8 | `ZZOFFPEAKCON` | CHAR | 36 |  | Off Peak Consumption |
| 9 | `ZZONDEMAND` | CHAR | 36 |  | On Peak Demand |
| 10 | `ZZOFFDEMAND` | CHAR | 36 |  | Off Peak Demand |
| 11 | `ZZMONTHYEAR` | CHAR | 6 |  | Date - YearMonth (YYYYMM) |
| 12 | `ZZCMETER` | CHAR | 1 |  | Indicator |
| 13 | `ZZSHPEAKCON` | CHAR | 36 |  | Shoulder Peak Consumption |
