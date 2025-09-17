# Mobile Checklist

| ID | Check item | Expected result | Android | iOS | Comment |
| --- | --- | --- | --- | --- | --- |
| MBL-001 | Page loads | First view loads without blank screen >3s | ✅ | ✅ | |
| MBL-002 | Header/menu | Header visible; burger opens/closes; no overlay trap | ✅ | ✅ | |
| MBL-003 | Phone input | Input masked `+380…`; blocks letters; caret works | ✅ | ✅ | |
| MBL-004 | Keyboard | On focus, keyboard does not overlap CTA | N/A | N/A | DevTools limitation |
| MBL-005 | Login CTA state | CTA disabled with empty field; no request sent | ✅ | ✅ | Number must be more than 12 characters |
| MBL-006 | Error text | Invalid phone → message = "Unknown operator code" | ✅ | ✅ | "Unknown operator code" |
| MBL-007 | Add to cart | Item added; header counter increases | ✅ | ✅ | |
| MBL-008 | Cart total | Increasing qty updates total immediately (2 decimals) | ✅ | ✅ | |
| MBL-009 | Orientation | Portrait ↔ Landscape: header/cart layout not broken | ✅ | ✅ | |
| MBL-010 | Back behavior | Back from cart returns to PLP without blank screen | ✅ | ✅ | |
