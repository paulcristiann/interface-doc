---
slug: /poscreators/middleware-doc/austria/reference-tables
title: Type of Signature: ftSignatureFormat
---

### Type of Signature: ftSignatureFormat

This table expands on the values provided in the table ["Format of Signature: ftSignatureFormat"](../../general/reference-tables/reference-tables.md#t-type-of-signature-ftsignatureformat-112) with values applicable to the Austrian market.

According to the RKSV, there is one exception: if the fiskaltrust.SecurityMechanism responds with a QR code but the printer, through which the receipt is supposed to be printed (or electronically issued), cannot display QR codes, it is allowed to convert the signature value and display it as bar code, link, or in OCR typeface on the receipt. This requirement and a sample code can be found in the Chapter ["Printing of QR-Code not supported"](#printing-of-qr-code-not-supported).

| **Value** | **Description**                             |
|-----------|---------------------------------------------|
| `0x00`    | unknown / without                           |
| `0x01`    | Text                                        |
| `0x02`    | Link                                        |
| `0x03`    | QR code (2D code)                           |
| `0x04`    | Code128 (bar code)                          |
| `0x05`    | OCR-A (text recognition, Base32 compatible) |
| `0x06`    | PDF417-(2D code)                            |
| `0x07`    | DATAMATRIX-(2D code)                        |
| `0x08`    | AZTEC-(2D Code)                             |
| `0x09`    | EAN-8 (bar code)                            |
| `0x0A`    | EAN-13 (bar code)                           |
| `0x0B`    | UPC-A (bar code)                            |
| `0x0C`    | Code39 (bar code, Base32 compatible)        |

<span id="_Toc527986678" class="anchor"></span>

*Table 26. Type of Signature: ftSignatureFormat (AT - RKSVO)*