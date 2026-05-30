# `FKKMAZE`

**Description:** CA Line Item — FI-CA document line items
**Category:** Standard SAP Table
**References:** 46 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkkmaze/) — validated 2026-05-30, schema v1.0
**Schema fields:** 28 fields | **Data types:** CHAR(19), CUKY(1), CURR(2), DATS(3), DEC(1), NUMC(2)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `MBETM` | MBETM_KK | — | CURR | 13 | 2 | Dunned amount in transaction currency |
| `MBETH` | UNUSED_KK | — | DEC | 13 | 2 | Not used (formerly dunned amount in local currency) |
| `FAEDN` | FAEDN_KK | — | DATS | 8 | 0 | Due date for net payment |
| `MINTM` | MINTM_KK | — | CURR | 13 | 2 | Dunning interest in transaction currency |
| `MAHNS` | MAHNS_KK | TFK047B | NUMC | 2 | 0 | Dunning Level |
| `MSTYP` | MSTYP_KK | TFK047G | CHAR | 2 | 0 | Dunning Level Category |
| `MAHNN` | MAHNN_KK | TFK047B | NUMC | 2 | 0 | New dunning level |
| `MANSP` | MANSP_KK | TFK047S | CHAR | 1 | 0 | Dunning Lock Reason |
| `XMFAK` | XMFAK_KK | — | CHAR | 1 | 0 | Dunning Level is Optional |
| `XMSUS` | XMSUS_KK | — | CHAR | 1 | 0 | Entry in Dunning History only Technically Conditional |
| `XMSTO` | XMSTO_KK | — | CHAR | 1 | 0 | Dunning Notice Reversed |
| `XINFO` | XINFO_KK | — | CHAR | 1 | 0 | Information: Item Not Due for Dunning |
| `MDRKD` | MDRKD_KK | — | DATS | 8 | 0 | Execution Date of Dunning Notice |
| `STAKZ` | STAKZ_KK | — | CHAR | 1 | 0 | Type of statistical item |
| `XMVKT` | XMVKT_KK | — | CHAR | 1 | 0 | Contract Account Not Unique |
| `VTREF` | VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `SUBAP` | SUBAP_KK | — | CHAR | 1 | 0 | Subapplication in Contract Accounts Receivable and Payable |
| `SEGMENT` | SEGMT_KK | — | CHAR | 10 | 0 | Segment for Segmental Reporting |
| `PRCTR` | PRCTR | — | CHAR | 10 | 0 | Profit Center |
| `MAHNV` | MAHNV_KK | — | CHAR | 2 | 0 | Dunning Procedure |
| `AUSDT` | AUSDT_KK | — | DATS | 8 | 0 | Date of issue |
| `SPART` | SPART_KK | — | CHAR | 2 | 0 | Division |
| `XTAUS` | XTAUS_KK | — | CHAR | 1 | 0 | Item Split |
| `MOPUPZ` | MOPUPZ_KK | — | CHAR | 3 | 0 | Maximum Subitem Number for Creation of Table Lines |
| `HIGHERDL` | HIGHERDL_KK | — | CHAR | 1 | 0 | Item has higher dunning level than dunning notice |
| `DALIN` | DALIN_KK | — | CHAR | 1 | 0 | Dunning Item Created by Dunning Activity Run |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MAHNN` | FKKMAZE | MAHNV | TFK047B |  | |
| `MAHNN` | FKKMAZE | MAHNN | TFK047B |  | |
| `MAHNN` | FKKMAZE | MANDT | TFK047B |  | |
| `MAHNS` | FKKMAZE | MANDT | TFK047B |  | |
| `MAHNS` | FKKMAZE | MAHNV | TFK047B |  | |
| `MAHNS` | FKKMAZE | MAHNS | TFK047B |  | |
| `MANDT` | FKKMAZE | MANDT | T000 |  | |
| `MANSP` | FKKMAZE | MANDT | TFK047S |  | |
| `MANSP` | FKKMAZE | MANSP | TFK047S |  | |
| `MSTYP` | FKKMAZE | MANDT | TFK047G |  | |
| `MSTYP` | FKKMAZE | MSTYP | TFK047G |  | |
| `OPBEL` | FKKMAZE | MANDT | DFKKKO |  | |
| `OPBEL` | FKKMAZE | OPBEL | DFKKKO |  | |
| `WAERS` | FKKMAZE | MANDT | TCURC |  | |
| `WAERS` | FKKMAZE | WAERS | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `gpart`, `laufd`, `laufi`, `mahns`, `opbel`, `opupk`, `opupw`, `opupz`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `laufd`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0079.txt`
- `zisbi0224forms.txt`
- `ziscs0065.txt`
- `zisdm0282.txt`
- `zisfi0005_dun.txt`
- `zisfi0038.txt`
- `zisfi0040.txt`
- `zisfi0040_perf_tuning.txt`
- `zisfi0042.txt`
- `zisfi0101.txt`
- `zisfi0106.txt`
- `zisfi0111.txt`
- `zisfi0139.txt`
- `zisfi0146.txt`
- `zisfi0148f01.txt`
- `zisfi0152.txt`
- `zisfi0190.txt`
- `zisfi0214.txt`
- `zisfi0215.txt`
- `zisfi0243_d.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_