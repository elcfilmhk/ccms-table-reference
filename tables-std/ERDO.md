# `ERDO`

**Description:** Move-Out Contract — end of contract
**Category:** Standard SAP Table
**References:** 9 SELECT statements across 6 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/erdo/) — validated 2026-05-30, schema v1.0
**Schema fields:** 10 fields | **Data types:** CHAR(7), DATS(1), DEC(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `VALIDAT_IN` | VALIDAT_IN | TE008 | CHAR | 10 | 0 | Name of Invoicing Validation |
| `MANOUTS_IN` | MANOUTS_IN | TE128 | CHAR | 8 | 0 | Reason for manual outsorting in invoicing |
| `FREI_AM` | FREI_AM | — | DATS | 8 | 0 | Document Release Date |
| `FREI_VON` | FREI_VON | — | CHAR | 12 | 0 | Name of user who released the document |
| `DEVIATION` | DEVIATION | — | DEC | 13 | 2 | Deviation |
| `SIMULATION` | SIMULATION | — | CHAR | 2 | 0 | Indicator: billing simulation |
| `OUTCOUNT` | OUTCOUNT | — | NUMC | 2 | 0 | Number of manual outsortings to be carried out yet |
| `OUTSORT_IN` | OUTSORT_IN | — | CHAR | 1 | 0 | Documents outsorted in invoicing |
| `OUTSORT_PR` | OUTSORT_PR | — | CHAR | 1 | 0 | Documents Outsorted in Bill Printing |
| `BGRD_RELEASE` | E_BACKGROUND_RELEASE | — | CHAR | 1 | 0 | Background release of document |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANOUTS_IN` | SYST | MANDT | TE128 |  | |
| `MANOUTS_IN` | ERDO | MANOUTS_IN | TE128 |  | |
| `VALIDAT_IN` | SYST | MANDT | TE008 |  | |
| `VALIDAT_IN` | ERDO | VALIDAT_IN | TE008 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0041.txt`
- `zisbi0042.txt`
- `zisbi0042_ami.txt`
- `zisbi0042_newfm.txt`
- `zisbi0045.txt`
- `zreaexcep.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_