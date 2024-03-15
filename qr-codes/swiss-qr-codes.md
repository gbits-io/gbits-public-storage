## This page shows various flavors of Swiss QR Codes for Gbits Pay

There are many variations of official Swiss QR bills and modified Swiss QR bills for Gbits Pay
1. content of currency field: **valid** official Swiss QR codes (CHF and EUR only) vs. similar but **invalid** Swiss QR codes (USD, USDC, EURC, VCHF, CHFC, USDX, EURX)
3. account number (IBAN): **valid** vs, **invalid**
4. account number (IBAN): **synthetic** vs. **productive**,
5. account number (IBAN): **on allow-list** (subdomain) vs. **not on allow-list** (no subdomain)
6. Solana address: **lookup based on subdomain** vs. **available in field 'additional info'**
7. Normal **IBAN** vs. **QR-IBAN**
8. reference: **unstructured** vs. **structured** (either QRR or SCOR)
9. amount field: **empty** vs. **non-empty**

### #1 Ideal, main case with Swiss Francs (CHF)
| CHF | QR-IBAN | [IBAN on allow-list](https://www.sns.id/domain?domain=ch9430700114900892402.verified-iban) | QR reference | semi-productive | amount field not empty |

![Swiss QR bill 01 - CHF](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/Swiss-QR-bill-01-CHF.svg)

### #2 Ideal, main case with Euros (EUR)
| EUR | QR-IBAN | [IBAN on allow-list](https://www.sns.id/domain?domain=ch9430700114900892402.verified-iban) | QR reference | semi-productive | amount field not empty |

![Swiss QR bill 01 - CHF](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/Swiss-QR-bill-02-EUR.svg)

### #3 Solana address in 'additional info' (IBAN not as subdomain available)
| CHF | QR-IBAN | [IBAN not on allow-list | QR reference | semi-productive | amount field not empty |

![Swiss QR bill 03 - CHF](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/Swiss-QR-bill-03-CHF.svg)

### #4 Solana domain .sol in 'additional info' (IBAN not as subdomain available)
| CHF | QR-IBAN | [IBAN not on allow-list | QR reference | semi-productive | amount field not empty |

![Swiss QR bill 03 - CHF](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/Swiss-QR-bill-04-CHF.svg)

### #5 not valid Swiss QR code due to currency = USDC
| USDC | QR-IBAN | [IBAN not on allow-list | Domain in addtl info | semi-productive | amount field not empty |

![invalid Swiss QR bill - USDC](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/USDC%20with%20IBAN%20as%20subdomain%20of%20verified-iban.s.png)

### #6 not valid Swiss QR code due to currency = CHFC
| CHFC | QR-IBAN | [IBAN on allow-list | QR reference | semi-productive | amount field not empty |

![invalid Swiss QR bill - CHFC]([CHFC and IBAN on allow-list.png"](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/CHFC%20and%20IBAN%20on%20allow-list.png))

### #7 not valid Swiss QR code due to currency = USDX
| SOL | QR-IBAN | QR reference | semi-productive | with sub-domain in additional info | amount field with tiny amount |

![invalid Swiss QR bill - USDC](https://github.com/gbits-io/gbits-public-storage/blob/main/qr-codes/USDX%20and%20subdomain%20in%20addtl%20info.png)
