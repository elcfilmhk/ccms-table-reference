# ZISCSMASKCFG
**Description:** CEP: Config table of source data masking
**Total Fields:** 24
**Key Fields:** MANDT, SOURCEFROM, SOURCE, SOURCENAME, FIELDNAME

## Programs Using This Table
- `ziscs0099`
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `SOURCE` | CHAR | 1 | 🔑 | Data Source (D: Database, F: File) |
| 4 | `SOURCENAME` | CHAR | 100 | 🔑 | File name or Table name |
| 5 | `FIELDNAME` | CHAR | 40 | 🔑 | Field name |
| 6 | `DELIMITED` | CHAR | 5 |  | Field Delimited Character |
| 7 | `FIELDLENGTH` | NUMC | 4 |  | Number of characters of the field in the source file |
| 8 | `FIELDDATATYPE` | CHAR | 1 |  | Field Data Type |
| 9 | `FIELDSEQ` | NUMC | 3 |  | Field Sequence |
| 10 | `METHOD` | CHAR | 1 |  | Handling Method (M: Mask, S: Substitution) |
| 11 | `MASKPATTERN` | CHAR | 40 |  | Mask Pattern |
| 12 | `DEFMASKCHAR` | CHAR | 10 |  | Mask value if cannot identify by mask pattern |
| 13 | `MASKCHAR` | CHAR | 1 |  | Masking Character |
| 14 | `SUBMETHOD` | CHAR | 10 |  | Substitution Method |
| 15 | `SUBFROMTABLE` | CHAR | 40 |  | Substitution table |
| 16 | `SUBFROMFIELD` | CHAR | 20 |  | Substitution field |
| 17 | `SUBRANDOM` | CHAR | 20 |  | Random generation function module |
| 18 | `SUBSUBFIX` | CHAR | 20 |  | Subfix for substitution |
| 19 | `RANDOM_LEN_MIN` | INT2 | 5 |  | Minimum length of random generation |
| 20 | `RANDOM_LEN_MAX` | INT2 | 5 |  | Maximum length of random generation |
| 21 | `RANDOM_CHAR_MIN` | INT2 | 5 |  | Minimum character of random generation |
| 22 | `RANDOM_CHAR_MAX` | INT2 | 5 |  | Maximum character of random generation |
| 23 | `RANDOM_CHARSET` | CHAR | 30 |  | Charset for random number generation |
| 24 | `GEN_SEQ` | CHAR | 1 |  | Flag to indicate generate seq.no. for masking with uniq.seq |
