# card-generator
Lil tool to setup RFID cards with random ID &amp; print labels for them.

HM uses H10301 format cards.

For a given 8-bit facility code, generates a 30 random 16-bit card numbers along with:
- a page of Avery 6460 labels with the card data in decimal as `<facility-code> <card-number>`
- a zip full of `.rfid` files with naming convention `<card index (padded to two digits) 01–30>_<card-number>.rfid`  for easy writing to cards using a Flipper Zero