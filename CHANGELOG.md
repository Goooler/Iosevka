## Modifications since version 2.x

### 20.0.0

* \[**Breaking**\] The ligation sets are now more fine grained to support languages with limited set of ligations (like C++) (#1555).
* Add characters:
  - COMBINING CYRILLIC LETTER UKRAINIAN IE (`U+A674`) ... COMBINING CYRILLIC LETTER OMEGA (`U+A67B`).
  - MODIFIER LETTER CYRILLIC HARD SIGN (`U+A69C`) ... COMBINING CYRILLIC LETTER IOTIFIED E (`U+A69F`).
  - MODIFIER LETTER CYRILLIC SMALL A (`U+1E030`) ... MODIFIER LETTER CYRILLIC SMALL YU (`U+1E049`).
  - MODIFIER LETTER CYRILLIC SMALL SCHWA (`U+1E04B`) ... MODIFIER LETTER CYRILLIC SMALL ES WITH DESCENDER (`U+1E06B`).
  - MODIFIER LETTER CYRILLIC SMALL STRAIGHT U WITH STROKE (`U+1E06D`).
  - COMBINING CYRILLIC SMALL LETTER BYELORUSSIAN-UKRAINIAN I (`U+1E08F`).
* Add variants for partial differential symbol (#1503).
* Prevent pathological geometry produced in phonetic ligatures (#1562, #1565, #1566, #1568, #1569, # 1570, #1571).
* Improve shape of Cyrillic Yat (#1573).

