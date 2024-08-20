## 1.52.0
### ADDED
- Support to localize data chips, which indicate to the user whether the date, total, or merchant has been successfully detected in the receipt.
- New property `pricePostfix` data found after a price, if printed on a receipt.
### FIXED
- An issue where a warning was posted by the Thread Performance Checker when entering the scan receipt view on iOS.

## 1.51.0
- Improvements to basket/product extraction for Loblaws Banners in Canada (CA)
- Improvements to date extraction in CA, US
- Improvements to Last 4 CC extraction in US
- Improvements to merchant detection in UK

# 1.50.0
- Improvements to Last 4 CC extraction

# 1.49.0
- Improvements to Tax extraction for Ahold Banners in the US
- Improvements to Last 4 CC extraction
- Improvements to basket/product extraction in US and ZA for various merchants
- Improvements to phone number extraction in DE

# 1.48.0
- Improvements to date accuracy in CA
- Improvements to QTY and weighed product extraction for H-E-B, Walgreens and various US merchants
- Improvements to long_transaction_id extraction for Walmart in US

# 1.46.0
- Overall extraction improvements in the UK
- Add German localization
- Added support for extracting loyalty member number via new property, if found on a receipt

# 1.45.0
- Product QTY improvements in the US
- Improvements to tip extraction
- Overall extraction improvements
- Improvements to long_transaction_id extraction

# 1.44.0
- Product QTY improvements for Albertsons banners in the US
- Merchant detection improvements in US, UK and DE
- Overall extraction improvements
- Improvements to long_transaction_id extraction
- Resolved main thread error related crash

# 1.43.0
- Merchant detection improvements in DE, ZA
- Total extraction improvements for M&S in the UK
- Improved support for extracting longTransactionId for Walmart, Costco, Target, Walgreens and Sam’s Club US receipts
- Gas product extraction improvements in the US
- Overall extraction improvements
- Added support for extracting cashback via new property, if found on a receipt

# 1.42.0
- Fuel product improvements (Upside)
- Last 4 CC digits fixes (Upside)
- Germany (DE) improvement
- General basket & trip fixes

# 1.41.0
- Binary optimizations

# 1.40.0
- Basket and trip improvements for Germany
- Merchant detection improvements in Germany, US, UK
- Added support for `rawTripHeaderText`, `rawBasketText` and `rawTripFooterText` properties in `BRScanResults`

# 1.39.0
- Binary optimizations

# 1.38.0
- Capture manufacturer coupons below products