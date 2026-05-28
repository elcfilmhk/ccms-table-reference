# ZEV_CONS
**Description:** EV related consumption per RFID card
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0132`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VENDOR_ID` | CHAR | 4 |  | Vendor ID |
| 2 | `RFID_NO` | CHAR | 20 |  | RFID number |
| 3 | `EV_PRICE_KEY` | CHAR | 10 |  | EV Price key |
| 4 | `EV_VALID_TO` | DATS | 8 |  | Valid to |
| 5 | `EV_UNIT_PRICE` | DEC | 17 |  | EV Unit price |
| 6 | `EV_QUANTITY` | DEC | 13 |  | EV Quantity |
