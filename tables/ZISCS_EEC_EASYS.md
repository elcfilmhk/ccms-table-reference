# ZISCS_EEC_EASYS
**Description:** EA Application System Information
**Total Fields:** 23
**Key Fields:** MANDT, EA_APP_NO

## Programs Using This Table
- `ziscs0526`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EA_APP_NO` | CHAR | 12 | 🔑 | Energy Audit Application |
| 3 | `MAJOR_AC_SYS` | CHAR | 3 |  | Major Air Conditioning System |
| 4 | `MAJOR_AC_SYS_OTH` | CHAR | 50 |  | Major Air Conditioning Others |
| 5 | `ANN_TOWNGAS_CONS` | DEC | 25 |  | Annual Towngas Consumption |
| 6 | `CENT_HEAT_SYS` | CHAR | 2 |  | Centralized Heating Provided |
| 7 | `CENT_HEAT_SYS_OTH` | CHAR | 50 |  | Centralized Heating Provided Others |
| 8 | `CEN_AC_OLD` | DEC | 3 |  | Centralized AC Old |
| 9 | `LOC_AC_OLD` | DEC | 3 |  | Local AC Old |
| 10 | `ANN_ELE_CONS` | DEC | 25 |  | Annual Electricity Consumption (kWh) |
| 11 | `ELEC_BENCHMARK` | DEC | 25 |  | Electricity BenchMark |
| 12 | `COM_LIGHT_EQUIP` | CHAR | 200 |  | Common Lighting Equipment |
| 13 | `COM_LIGHT_EQUIP_OTH` | CHAR | 50 |  | Common Lighting Equipment Others |
| 14 | `CHI_COM_YR` | CHAR | 4 |  | Chiller Commissioned in Year |
| 15 | `CHI_REP_YR` | CHAR | 4 |  | Chiller Replaced in Year |
| 16 | `CHI_TYP` | CHAR | 70 |  | Chiller Type |
| 17 | `CHI_SIZE` | CHAR | 30 |  | Chiller Size |
| 18 | `CHI_MORE_DET` | CHAR | 200 |  | Chiller More Details |
| 19 | `REMARKS` | CHAR | 150 |  | Remarks |
| 20 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 21 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 22 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 23 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
