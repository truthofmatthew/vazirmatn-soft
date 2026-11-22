# Changelog

## 1.1.2

- Latin combining accents added (U+0302, U+0304, U+0306, U+0307, U+0308, U+030A, U+030B, U+030C, U+0326, U+0327, U+0328), so decomposed Latin text in Czech, German, Turkish, Polish, Romanian and others shapes correctly
- Latin combining accents attach to the dotted circle ◌
- Latin Core letters added: Ẁ ẁ Ẃ ẃ Ẅ ẅ ẞ Ỳ ỳ (Welsh, German)
- Roboto's tabular digits renamed from `.tnum` to `.tf` (no visual change)
- `hhea.advanceWidthMax` matches the glyph widths
- Font sources are now in this repo: the three masters as UFO + designspace, built with `gftools builder`

## 1.1.1

- Compact تومان / ریال now also work on pages and documents set to Persian, Kurdish or Arabic (1.1.0 only applied them for the default language)

## 1.1.0

- Compact تومان and ریال: type «تومان» or «ریال» followed by «ء». Three تومان forms (inline, two-line with `ss02`, condensed via `salt`), also on U+E000–U+E003
- `ss03` lowered digits
- `ss04` Nastaliq-style final ه
- Stylistic sets have readable names in design apps

## 1.0.1

- Round ends and softened corners on punctuation and symbols: brackets, braces, parentheses, quotes, guillemets, underscore, slashes, asterisk, hash, math signs and the ellipsis
- CDN links in the README point to v1.0.1

## 1.0.0

First release of Vazirmatn Soft, based on Vazirmatn 33.003.

- Round dots, round stroke ends, and softened outer and inner corners in all 9 weights and the variable font
- Smooth junction where bowls meet the baseline; join edges stay square, with a deeper overlap at joins
- Lower bowl-tail tips for س ش ص ض ن ی ل ق; the second bar of گ is a pill
- Digits and punctuation softened to match
- Family name "Vazirmatn Soft", installs next to Vazirmatn; UI, Non-Latin and Farsi-Digits editions included
