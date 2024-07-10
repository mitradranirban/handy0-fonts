## FontBakery report

fontbakery version: 0.12.8



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[2] handy0.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font does not contain a GSUB table.</p>
 [code: missing-gsub-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[26] handy0.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Does full font name begin with the font family name? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>On the 'name' table, the full font name 'handy0 Regular' does not begin with the font family name 'Handy0' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1.</p>
 [code: mismatch-font-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+00C6: LATIN CAPITAL LETTER AE</td>
<td align="left">U+00E6: LATIN SMALL LETTER AE</td>
</tr>
<tr>
<td align="left">U+00D0: LATIN CAPITAL LETTER ETH</td>
<td align="left">U+00F0: LATIN SMALL LETTER ETH</td>
</tr>
<tr>
<td align="left">U+010E: LATIN CAPITAL LETTER D WITH CARON</td>
<td align="left">U+010F: LATIN SMALL LETTER D WITH CARON</td>
</tr>
<tr>
<td align="left">U+0110: LATIN CAPITAL LETTER D WITH STROKE</td>
<td align="left">U+0111: LATIN SMALL LETTER D WITH STROKE</td>
</tr>
<tr>
<td align="left">U+0164: LATIN CAPITAL LETTER T WITH CARON</td>
<td align="left">U+0165: LATIN SMALL LETTER T WITH CARON</td>
</tr>
<tr>
<td align="left">U+0189: LATIN CAPITAL LETTER AFRICAN D</td>
<td align="left">U+0256: LATIN SMALL LETTER D WITH TAIL</td>
</tr>
<tr>
<td align="left">U+01E2: LATIN CAPITAL LETTER AE WITH MACRON</td>
<td align="left">U+01E3: LATIN SMALL LETTER AE WITH MACRON</td>
</tr>
<tr>
<td align="left">U+01FC: LATIN CAPITAL LETTER AE WITH ACUTE</td>
<td align="left">U+01FD: LATIN SMALL LETTER AE WITH ACUTE</td>
</tr>
<tr>
<td align="left">U+0391: GREEK CAPITAL LETTER ALPHA</td>
<td align="left">U+03B1: GREEK SMALL LETTER ALPHA</td>
</tr>
<tr>
<td align="left">U+0392: GREEK CAPITAL LETTER BETA</td>
<td align="left">U+03B2: GREEK SMALL LETTER BETA</td>
</tr>
<tr>
<td align="left">U+0395: GREEK CAPITAL LETTER EPSILON</td>
<td align="left">U+03B5: GREEK SMALL LETTER EPSILON</td>
</tr>
<tr>
<td align="left">U+0396: GREEK CAPITAL LETTER ZETA</td>
<td align="left">U+03B6: GREEK SMALL LETTER ZETA</td>
</tr>
<tr>
<td align="left">U+0397: GREEK CAPITAL LETTER ETA</td>
<td align="left">U+03B7: GREEK SMALL LETTER ETA</td>
</tr>
<tr>
<td align="left">U+0399: GREEK CAPITAL LETTER IOTA</td>
<td align="left">U+03B9: GREEK SMALL LETTER IOTA</td>
</tr>
<tr>
<td align="left">U+039A: GREEK CAPITAL LETTER KAPPA</td>
<td align="left">U+03BA: GREEK SMALL LETTER KAPPA</td>
</tr>
<tr>
<td align="left">U+039C: GREEK CAPITAL LETTER MU</td>
<td align="left">U+03BC: GREEK SMALL LETTER MU</td>
</tr>
<tr>
<td align="left">U+039D: GREEK CAPITAL LETTER NU</td>
<td align="left">U+03BD: GREEK SMALL LETTER NU</td>
</tr>
<tr>
<td align="left">U+03A4: GREEK CAPITAL LETTER TAU</td>
<td align="left">U+03C4: GREEK SMALL LETTER TAU</td>
</tr>
<tr>
<td align="left">U+03A5: GREEK CAPITAL LETTER UPSILON</td>
<td align="left">U+03C5: GREEK SMALL LETTER UPSILON</td>
</tr>
<tr>
<td align="left">U+03AA: GREEK CAPITAL LETTER IOTA WITH DIALYTIKA</td>
<td align="left">U+03CA: GREEK SMALL LETTER IOTA WITH DIALYTIKA</td>
</tr>
<tr>
<td align="left">U+03AB: GREEK CAPITAL LETTER UPSILON WITH DIALYTIKA</td>
<td align="left">U+03CB: GREEK SMALL LETTER UPSILON WITH DIALYTIKA</td>
</tr>
<tr>
<td align="left">U+0412: CYRILLIC CAPITAL LETTER VE</td>
<td align="left">U+0432: CYRILLIC SMALL LETTER VE</td>
</tr>
<tr>
<td align="left">U+041A: CYRILLIC CAPITAL LETTER KA</td>
<td align="left">U+043A: CYRILLIC SMALL LETTER KA</td>
</tr>
<tr>
<td align="left">U+041C: CYRILLIC CAPITAL LETTER EM</td>
<td align="left">U+043C: CYRILLIC SMALL LETTER EM</td>
</tr>
<tr>
<td align="left">U+041D: CYRILLIC CAPITAL LETTER EN</td>
<td align="left">U+043D: CYRILLIC SMALL LETTER EN</td>
</tr>
<tr>
<td align="left">U+0422: CYRILLIC CAPITAL LETTER TE</td>
<td align="left">U+0442: CYRILLIC SMALL LETTER TE</td>
</tr>
<tr>
<td align="left">U+0443: CYRILLIC SMALL LETTER U</td>
<td align="left">U+0423: CYRILLIC CAPITAL LETTER U</td>
</tr>
<tr>
<td align="left">U+0450: CYRILLIC SMALL LETTER IE WITH GRAVE</td>
<td align="left">U+0400: CYRILLIC CAPITAL LETTER IE WITH GRAVE</td>
</tr>
<tr>
<td align="left">U+0451: CYRILLIC SMALL LETTER IO</td>
<td align="left">U+0401: CYRILLIC CAPITAL LETTER IO</td>
</tr>
<tr>
<td align="left">U+045E: CYRILLIC SMALL LETTER SHORT U</td>
<td align="left">U+040E: CYRILLIC CAPITAL LETTER SHORT U</td>
</tr>
<tr>
<td align="left">U+04AE: CYRILLIC CAPITAL LETTER STRAIGHT U</td>
<td align="left">U+04AF: CYRILLIC SMALL LETTER STRAIGHT U</td>
</tr>
<tr>
<td align="left">U+04C0: CYRILLIC LETTER PALOCHKA</td>
<td align="left">U+04CF: CYRILLIC SMALL LETTER PALOCHKA</td>
</tr>
<tr>
<td align="left">U+04D4: CYRILLIC CAPITAL LIGATURE A IE</td>
<td align="left">U+04D5: CYRILLIC SMALL LIGATURE A IE</td>
</tr>
<tr>
<td align="left">U+04EF: CYRILLIC SMALL LETTER U WITH MACRON</td>
<td align="left">U+04EE: CYRILLIC CAPITAL LETTER U WITH MACRON</td>
</tr>
<tr>
<td align="left">U+04F1: CYRILLIC SMALL LETTER U WITH DIAERESIS</td>
<td align="left">U+04F0: CYRILLIC CAPITAL LETTER U WITH DIAERESIS</td>
</tr>
<tr>
<td align="left">U+04F3: CYRILLIC SMALL LETTER U WITH DOUBLE ACUTE</td>
<td align="left">U+04F2: CYRILLIC CAPITAL LETTER U WITH DOUBLE ACUTE</td>
</tr>
<tr>
<td align="left">U+054F: ARMENIAN CAPITAL LETTER TIWN</td>
<td align="left">U+057F: ARMENIAN SMALL LETTER TIWN</td>
</tr>
<tr>
<td align="left">U+0570: ARMENIAN SMALL LETTER HO</td>
<td align="left">U+0540: ARMENIAN CAPITAL LETTER HO</td>
</tr>
<tr>
<td align="left">U+0578: ARMENIAN SMALL LETTER VO</td>
<td align="left">U+0548: ARMENIAN CAPITAL LETTER VO</td>
</tr>
<tr>
<td align="left">U+057D: ARMENIAN SMALL LETTER SEH</td>
<td align="left">U+054D: ARMENIAN CAPITAL LETTER SEH</td>
</tr>
<tr>
<td align="left">U+0584: ARMENIAN SMALL LETTER KEH</td>
<td align="left">U+0554: ARMENIAN CAPITAL LETTER KEH</td>
</tr>
<tr>
<td align="left">U+13A0: CHEROKEE LETTER A</td>
<td align="left">U+AB70: CHEROKEE SMALL LETTER A</td>
</tr>
<tr>
<td align="left">U+13A1: CHEROKEE LETTER E</td>
<td align="left">U+AB71: CHEROKEE SMALL LETTER E</td>
</tr>
<tr>
<td align="left">U+13A2: CHEROKEE LETTER I</td>
<td align="left">U+AB72: CHEROKEE SMALL LETTER I</td>
</tr>
<tr>
<td align="left">U+13AA: CHEROKEE LETTER GO</td>
<td align="left">U+AB7A: CHEROKEE SMALL LETTER GO</td>
</tr>
<tr>
<td align="left">U+13AB: CHEROKEE LETTER GU</td>
<td align="left">U+AB7B: CHEROKEE SMALL LETTER GU</td>
</tr>
<tr>
<td align="left">U+13AC: CHEROKEE LETTER GV</td>
<td align="left">U+AB7C: CHEROKEE SMALL LETTER GV</td>
</tr>
<tr>
<td align="left">U+13B3: CHEROKEE LETTER LA</td>
<td align="left">U+AB83: CHEROKEE SMALL LETTER LA</td>
</tr>
<tr>
<td align="left">U+13B7: CHEROKEE LETTER LU</td>
<td align="left">U+AB87: CHEROKEE SMALL LETTER LU</td>
</tr>
<tr>
<td align="left">U+13BB: CHEROKEE LETTER MI</td>
<td align="left">U+AB8B: CHEROKEE SMALL LETTER MI</td>
</tr>
<tr>
<td align="left">U+13C0: CHEROKEE LETTER NAH</td>
<td align="left">U+AB90: CHEROKEE SMALL LETTER NAH</td>
</tr>
<tr>
<td align="left">U+13C2: CHEROKEE LETTER NI</td>
<td align="left">U+AB92: CHEROKEE SMALL LETTER NI</td>
</tr>
<tr>
<td align="left">U+13C3: CHEROKEE LETTER NO</td>
<td align="left">U+AB93: CHEROKEE SMALL LETTER NO</td>
</tr>
<tr>
<td align="left">U+13D9: CHEROKEE LETTER DO</td>
<td align="left">U+ABA9: CHEROKEE SMALL LETTER DO</td>
</tr>
<tr>
<td align="left">U+13DA: CHEROKEE LETTER DU</td>
<td align="left">U+ABAA: CHEROKEE SMALL LETTER DU</td>
</tr>
<tr>
<td align="left">U+13DE: CHEROKEE LETTER TLE</td>
<td align="left">U+ABAE: CHEROKEE SMALL LETTER TLE</td>
</tr>
<tr>
<td align="left">U+13DF: CHEROKEE LETTER TLI</td>
<td align="left">U+ABAF: CHEROKEE SMALL LETTER TLI</td>
</tr>
<tr>
<td align="left">U+13E2: CHEROKEE LETTER TLV</td>
<td align="left">U+ABB2: CHEROKEE SMALL LETTER TLV</td>
</tr>
<tr>
<td align="left">U+13E6: CHEROKEE LETTER TSO</td>
<td align="left">U+ABB6: CHEROKEE SMALL LETTER TSO</td>
</tr>
<tr>
<td align="left">U+13F4: CHEROKEE LETTER YV</td>
<td align="left">U+13FC: CHEROKEE SMALL LETTER YV</td>
</tr>
<tr>
<td align="left">U+1FB8: GREEK CAPITAL LETTER ALPHA WITH VRACHY</td>
<td align="left">U+1FB0: GREEK SMALL LETTER ALPHA WITH VRACHY</td>
</tr>
<tr>
<td align="left">U+1FB9: GREEK CAPITAL LETTER ALPHA WITH MACRON</td>
<td align="left">U+1FB1: GREEK SMALL LETTER ALPHA WITH MACRON</td>
</tr>
<tr>
<td align="left">U+1FBA: GREEK CAPITAL LETTER ALPHA WITH VARIA</td>
<td align="left">U+1F70: GREEK SMALL LETTER ALPHA WITH VARIA</td>
</tr>
<tr>
<td align="left">U+1FC8: GREEK CAPITAL LETTER EPSILON WITH VARIA</td>
<td align="left">U+1F72: GREEK SMALL LETTER EPSILON WITH VARIA</td>
</tr>
<tr>
<td align="left">U+1FCA: GREEK CAPITAL LETTER ETA WITH VARIA</td>
<td align="left">U+1F74: GREEK SMALL LETTER ETA WITH VARIA</td>
</tr>
<tr>
<td align="left">U+1FD8: GREEK CAPITAL LETTER IOTA WITH VRACHY</td>
<td align="left">U+1FD0: GREEK SMALL LETTER IOTA WITH VRACHY</td>
</tr>
<tr>
<td align="left">U+1FD9: GREEK CAPITAL LETTER IOTA WITH MACRON</td>
<td align="left">U+1FD1: GREEK SMALL LETTER IOTA WITH MACRON</td>
</tr>
<tr>
<td align="left">U+1FDA: GREEK CAPITAL LETTER IOTA WITH VARIA</td>
<td align="left">U+1F76: GREEK SMALL LETTER IOTA WITH VARIA</td>
</tr>
<tr>
<td align="left">U+1FE8: GREEK CAPITAL LETTER UPSILON WITH VRACHY</td>
<td align="left">U+1FE0: GREEK SMALL LETTER UPSILON WITH VRACHY</td>
</tr>
<tr>
<td align="left">U+1FE9: GREEK CAPITAL LETTER UPSILON WITH MACRON</td>
<td align="left">U+1FE1: GREEK SMALL LETTER UPSILON WITH MACRON</td>
</tr>
<tr>
<td align="left">U+1FEA: GREEK CAPITAL LETTER UPSILON WITH VARIA</td>
<td align="left">U+1F7A: GREEK SMALL LETTER UPSILON WITH VARIA</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 4547, but got 4546 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the ufo profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1638) and hhea ascent (4546) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">da_Latn (Danish)</td>
<td align="left">Some base glyphs were missing: æ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some base glyphs were missing: ß, ẞ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fr_Latn (French)</td>
<td align="left">Some base glyphs were missing: æ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hr_Latn (Croatian)</td>
<td align="left">Some base glyphs were missing: đ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">is_Latn (Icelandic)</td>
<td align="left">Some base glyphs were missing: Þ, æ, ð, þ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̨</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lt_Latn (Lithuanian)</td>
<td align="left">Some base glyphs were missing: Ą, ą, Ę, ę, Į, į, Ų, ų</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̨</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mt_Latn (Maltese)</td>
<td align="left">Some base glyphs were missing: GĦ, għ, Ħ, ħ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
<td align="left">Some base glyphs were missing: æ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pl_Latn (Polish)</td>
<td align="left">Some base glyphs were missing: Ą, ą, Ę, ę, Ł, ł</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̨</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ro_Latn (Romanian)</td>
<td align="left">Some base glyphs were missing: Ș, ș, Ț, ț</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̦</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sr_Latn (Serbian (Latin))</td>
<td align="left">Some base glyphs were missing: đ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tr_Latn (Turkish)</td>
<td align="left">Some mark glyphs were missing: ◌̦</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">da_Latn (Danish)</td>
<td align="left">Some auxiliary glyphs were missing: æ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some auxiliary glyphs were missing: ß, ẞ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fr_Latn (French)</td>
<td align="left">Some auxiliary glyphs were missing: æ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hr_Latn (Croatian)</td>
<td align="left">Some auxiliary glyphs were missing: đ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">is_Latn (Icelandic)</td>
<td align="left">Some auxiliary glyphs were missing: Þ, æ, ð, þ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lt_Latn (Lithuanian)</td>
<td align="left">Some auxiliary glyphs were missing: Ą, ą, Ę, ę, Į, į, Ų, ų</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mt_Latn (Maltese)</td>
<td align="left">Some auxiliary glyphs were missing: GĦ, għ, Ħ, ħ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
<td align="left">Some auxiliary glyphs were missing: æ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pl_Latn (Polish)</td>
<td align="left">Some auxiliary glyphs were missing: Ą, ą, Ę, ę, Ł, ł</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ro_Latn (Romanian)</td>
<td align="left">Some auxiliary glyphs were missing: Ș, ș, Ț, ț</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sr_Latn (Serbian (Latin))</td>
<td align="left">Some auxiliary glyphs were missing: đ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;handy0&quot; doesn't start with an uppercase letter.</p>
 [code: starts-with-not-uppercase]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;handy0-Regular.ttf. Got handy0.ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright (c) 2024, Dr Anirban Mitra OFL 1.1&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Handy0</strong></td>
<td align="left"><strong>handy0</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">handy0 Regular</td>
<td align="left">handy0 Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>handy0</strong></td>
<td align="left"><strong>handy0-Regular</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>handy0</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00BF (INVERTED QUESTION MARK)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x02C7 (CARON)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0328 (COMBINING OGONEK)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x20AC (EURO SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. Current version string is: &quot;Version 0.001; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;377&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;377&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 5404 when it should be at most 4096</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), hookabovecomb (U+0309), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0305 (U+0305), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni030D (U+030D), uni030E (U+030E), uni030F (U+030F), uni0310 (U+0310), uni0327 (U+0327), uni0340 (U+0340), uni0341 (U+0341) and uni0344 (U+0344)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0000	Contours detected: 2	Expected: 0

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: at	Contours detected: 1	Expected: 2

- Glyph name: B	Contours detected: 1	Expected: 2 or 3

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: bar	Contours detected: 2	Expected: 1

- Glyph name: dieresis	Contours detected: 4	Expected: 2

- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: ordmasculine	Contours detected: 1	Expected: 2 or 3

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: Adieresis	Contours detected: 6	Expected: 4

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Idieresis	Contours detected: 5	Expected: 3

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Odieresis	Contours detected: 6	Expected: 4

- Glyph name: Udieresis	Contours detected: 5	Expected: 3

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 5	Expected: 4

- Glyph name: aring	Contours detected: 2	Expected: 4

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: igrave	Contours detected: 3	Expected: 2

- Glyph name: iacute	Contours detected: 3	Expected: 2

- Glyph name: icircumflex	Contours detected: 3	Expected: 2

- Glyph name: idieresis	Contours detected: 6	Expected: 3

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 5	Expected: 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: udieresis	Contours detected: 5	Expected: 3

- Glyph name: ydieresis	Contours detected: 5	Expected: 3

- Glyph name: amacron	Contours detected: 2	Expected: 3

- Glyph name: abreve	Contours detected: 2	Expected: 3

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: Dcroat	Contours detected: 1	Expected: 2

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: itilde	Contours detected: 3	Expected: 2

- Glyph name: imacron	Contours detected: 3	Expected: 2

- Glyph name: ibreve	Contours detected: 3	Expected: 2

- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: omacron	Contours detected: 2	Expected: 3

- Glyph name: obreve	Contours detected: 2	Expected: 3

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: Uring	Contours detected: 2	Expected: 3

- Glyph name: uring	Contours detected: 2	Expected: 3

- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: uni0189	Contours detected: 1	Expected: 2

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni01C0	Contours detected: 2	Expected: 1

- Glyph name: uni01C1	Contours detected: 4	Expected: 2

- Glyph name: uni01C5	Contours detected: 3	Expected: 4

- Glyph name: uni01CE	Contours detected: 2	Expected: 3

- Glyph name: uni01D2	Contours detected: 2	Expected: 3

- Glyph name: uni01D5	Contours detected: 6	Expected: 4

- Glyph name: uni01D6	Contours detected: 6	Expected: 4

- Glyph name: uni01D7	Contours detected: 6	Expected: 4

- Glyph name: uni01D8	Contours detected: 6	Expected: 4

- Glyph name: uni01D9	Contours detected: 6	Expected: 4

- Glyph name: uni01DA	Contours detected: 6	Expected: 4

- Glyph name: uni01DB	Contours detected: 6	Expected: 4

- Glyph name: uni01DC	Contours detected: 6	Expected: 4

- Glyph name: uni01DE	Contours detected: 7	Expected: 5

- Glyph name: uni01DF	Contours detected: 6	Expected: 5

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni01F0	Contours detected: 3	Expected: 2

- Glyph name: uni01F2	Contours detected: 2	Expected: 3

- Glyph name: uni01F5	Contours detected: 2	Expected: 3

- Glyph name: aringacute	Contours detected: 3	Expected: 4 or 5

- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

- Glyph name: oslashacute	Contours detected: 3	Expected: 4

- Glyph name: uni0227	Contours detected: 2	Expected: 3

- Glyph name: uni022A	Contours detected: 7	Expected: 5

- Glyph name: uni022B	Contours detected: 6	Expected: 5

- Glyph name: uni022D	Contours detected: 3	Expected: 4

- Glyph name: uni022F	Contours detected: 2	Expected: 3

- Glyph name: uni0231	Contours detected: 3	Expected: 4

- Glyph name: uni02B7	Contours detected: 2	Expected: 1

- Glyph name: uni02B9	Contours detected: 2	Expected: 1

- Glyph name: uni02BC	Contours detected: 2	Expected: 1

- Glyph name: uni02C8	Contours detected: 2	Expected: 1

- Glyph name: ring	Contours detected: 1	Expected: 2

- Glyph name: uni0308	Contours detected: 4	Expected: 2

- Glyph name: uni030A	Contours detected: 1	Expected: 2

- Glyph name: uni0344	Contours detected: 5	Expected: 3

- Glyph name: uni0374	Contours detected: 2	Expected: 1

- Glyph name: Beta	Contours detected: 1	Expected: 3

- Glyph name: Zeta	Contours detected: 2	Expected: 1

- Glyph name: Iotadieresis	Contours detected: 5	Expected: 3

- Glyph name: Upsilondieresis	Contours detected: 5	Expected: 3

- Glyph name: omicron	Contours detected: 1	Expected: 2

- Glyph name: uni0407	Contours detected: 5	Expected: 3

- Glyph name: uni0412	Contours detected: 1	Expected: 3

- Glyph name: uni0430	Contours detected: 1	Expected: 2

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043E	Contours detected: 1	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 5	Expected: 4

- Glyph name: uni0457	Contours detected: 5	Expected: 3

- Glyph name: uni04D1	Contours detected: 2	Expected: 3

- Glyph name: uni04D2	Contours detected: 6	Expected: 4

- Glyph name: uni04D3	Contours detected: 5	Expected: 4

- Glyph name: uni04D7	Contours detected: 2	Expected: 3

- Glyph name: uni04E6	Contours detected: 6	Expected: 4

- Glyph name: uni04E7	Contours detected: 5	Expected: 4

- Glyph name: uni04F1	Contours detected: 5	Expected: 3

- Glyph name: uni1D43	Contours detected: 1	Expected: 2

- Glyph name: uni1D49	Contours detected: 1	Expected: 2

- Glyph name: uni1D4D	Contours detected: 1	Expected: 3

- Glyph name: uni1D52	Contours detected: 1	Expected: 2

- Glyph name: uni1D5B	Contours detected: 2	Expected: 1

- Glyph name: uni1DA0	Contours detected: 2	Expected: 1

- Glyph name: uni1E02	Contours detected: 2	Expected: 4

- Glyph name: uni1E0A	Contours detected: 2	Expected: 3

- Glyph name: uni1E15	Contours detected: 3	Expected: 4

- Glyph name: uni1E17	Contours detected: 3	Expected: 4

- Glyph name: uni1E1F	Contours detected: 3	Expected: 2

- Glyph name: uni1E21	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni1E2E	Contours detected: 6	Expected: 4

- Glyph name: uni1E2F	Contours detected: 7	Expected: 4

- Glyph name: uni1E4D	Contours detected: 3	Expected: 4

- Glyph name: uni1E4E	Contours detected: 7	Expected: 5

- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

- Glyph name: uni1E51	Contours detected: 3	Expected: 4

- Glyph name: uni1E53	Contours detected: 3	Expected: 4

- Glyph name: uni1E56	Contours detected: 2	Expected: 3

- Glyph name: uni1E7A	Contours detected: 6	Expected: 4

- Glyph name: uni1E7B	Contours detected: 6	Expected: 4

- Glyph name: wgrave	Contours detected: 3	Expected: 2

- Glyph name: wacute	Contours detected: 3	Expected: 2

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: wdieresis	Contours detected: 6	Expected: 3

- Glyph name: uni1E97	Contours detected: 5	Expected: 3

- Glyph name: uni1EA3	Contours detected: 2	Expected: 3

- Glyph name: uni1EA5	Contours detected: 3	Expected: 4

- Glyph name: uni1EA7	Contours detected: 3	Expected: 4

- Glyph name: uni1EA9	Contours detected: 3	Expected: 4

- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

- Glyph name: uni1EAF	Contours detected: 3	Expected: 4

- Glyph name: uni1EB1	Contours detected: 3	Expected: 4

- Glyph name: uni1EB3	Contours detected: 3	Expected: 4

- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

- Glyph name: uni1EBB	Contours detected: 2	Expected: 3

- Glyph name: uni1EBD	Contours detected: 2	Expected: 3

- Glyph name: uni1EBF	Contours detected: 3	Expected: 4

- Glyph name: uni1EC1	Contours detected: 3	Expected: 4

- Glyph name: uni1EC3	Contours detected: 3	Expected: 4

- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

- Glyph name: uni1ECF	Contours detected: 2	Expected: 3

- Glyph name: uni1ED1	Contours detected: 3	Expected: 4

- Glyph name: uni1ED3	Contours detected: 3	Expected: 4

- Glyph name: uni1ED5	Contours detected: 3	Expected: 4

- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1F78	Contours detected: 2	Expected: 3

- Glyph name: uni1FED	Contours detected: 5	Expected: 3

- Glyph name: uni2016	Contours detected: 4	Expected: 2

- Glyph name: quoteright	Contours detected: 2	Expected: 1

- Glyph name: minute	Contours detected: 2	Expected: 1

- Glyph name: second	Contours detected: 4	Expected: 2

- Glyph name: uni2034	Contours detected: 6	Expected: 3

- Glyph name: uni2076	Contours detected: 1	Expected: 2

- Glyph name: uni2078	Contours detected: 2	Expected: 3

- Glyph name: uni2079	Contours detected: 1	Expected: 2

- Glyph name: uni2086	Contours detected: 1	Expected: 2

- Glyph name: uni2088	Contours detected: 2	Expected: 3

- Glyph name: uni2089	Contours detected: 1	Expected: 2

- Glyph name: uni2102	Contours detected: 1	Expected: 2

- Glyph name: uni2105	Contours detected: 3	Expected: 4

- Glyph name: uni210A	Contours detected: 1	Expected: 2

- Glyph name: uni210D	Contours detected: 1	Expected: 2

- Glyph name: uni2113	Contours detected: 1	Expected: 2

- Glyph name: uni2115	Contours detected: 1	Expected: 2

- Glyph name: uni2116	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni2119	Contours detected: 1	Expected: 2

- Glyph name: uni211A	Contours detected: 2	Expected: 3

- Glyph name: uni211D	Contours detected: 2	Expected: 3

- Glyph name: emptyset	Contours detected: 2	Expected: 3

- Glyph name: uni2218	Contours detected: 1	Expected: 2

- Glyph name: uni2223	Contours detected: 2	Expected: 1

- Glyph name: uni2225	Contours detected: 4	Expected: 2

- Glyph name: SF110000	Contours detected: 2	Expected: 1

- Glyph name: uniFB00	Contours detected: 4	Expected: 1 or 2

- Glyph name: uniFB01	Contours detected: 4	Expected: 1, 2 or 3

- Glyph name: uniFB02	Contours detected: 3	Expected: 1 or 2

- Glyph name: uniFB03	Contours detected: 6	Expected: 1, 2, 3 or 4

- Glyph name: uniFB04	Contours detected: 5	Expected: 1, 2 or 3

- Glyph name: uniFB06	Contours detected: 2	Expected: 1

- Glyph name: Adieresis	Contours detected: 6	Expected: 4

- Glyph name: B	Contours detected: 1	Expected: 2 or 3

- Glyph name: Beta	Contours detected: 1	Expected: 3

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: Dcroat	Contours detected: 1	Expected: 2

- Glyph name: Edieresis	Contours detected: 5	Expected: 3

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Idieresis	Contours detected: 5	Expected: 3

- Glyph name: Iotadieresis	Contours detected: 5	Expected: 3

- Glyph name: OE	Contours detected: 3	Expected: 2

- Glyph name: Odieresis	Contours detected: 6	Expected: 4

- Glyph name: Oslashacute	Contours detected: 3	Expected: 4

- Glyph name: SF110000	Contours detected: 2	Expected: 1

- Glyph name: Udieresis	Contours detected: 5	Expected: 3

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: Upsilondieresis	Contours detected: 5	Expected: 3

- Glyph name: Uring	Contours detected: 2	Expected: 3

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Zeta	Contours detected: 2	Expected: 1

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: abreve	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 5	Expected: 4

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: amacron	Contours detected: 2	Expected: 3

- Glyph name: aring	Contours detected: 2	Expected: 4

- Glyph name: aringacute	Contours detected: 3	Expected: 4 or 5

- Glyph name: at	Contours detected: 1	Expected: 2

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: bar	Contours detected: 2	Expected: 1

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: dieresis	Contours detected: 4	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 5	Expected: 4

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: emptyset	Contours detected: 2	Expected: 3

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: iacute	Contours detected: 3	Expected: 2

- Glyph name: ibreve	Contours detected: 3	Expected: 2

- Glyph name: icircumflex	Contours detected: 3	Expected: 2

- Glyph name: idieresis	Contours detected: 6	Expected: 3

- Glyph name: igrave	Contours detected: 3	Expected: 2

- Glyph name: imacron	Contours detected: 3	Expected: 2

- Glyph name: itilde	Contours detected: 3	Expected: 2

- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 5	Expected: 4

- Glyph name: oe	Contours detected: 2	Expected: 3

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: omacron	Contours detected: 2	Expected: 3

- Glyph name: omicron	Contours detected: 1	Expected: 2

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

- Glyph name: ordmasculine	Contours detected: 1	Expected: 2 or 3

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: oslashacute	Contours detected: 3	Expected: 4

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: quoteright	Contours detected: 2	Expected: 1

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: ring	Contours detected: 1	Expected: 2

- Glyph name: udieresis	Contours detected: 5	Expected: 3

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: uni0189	Contours detected: 1	Expected: 2

- Glyph name: uni01C0	Contours detected: 2	Expected: 1

- Glyph name: uni01C1	Contours detected: 4	Expected: 2

- Glyph name: uni01C5	Contours detected: 3	Expected: 4

- Glyph name: uni01CE	Contours detected: 2	Expected: 3

- Glyph name: uni01D2	Contours detected: 2	Expected: 3

- Glyph name: uni01D5	Contours detected: 6	Expected: 4

- Glyph name: uni01D6	Contours detected: 6	Expected: 4

- Glyph name: uni01D7	Contours detected: 6	Expected: 4

- Glyph name: uni01D8	Contours detected: 6	Expected: 4

- Glyph name: uni01D9	Contours detected: 6	Expected: 4

- Glyph name: uni01DA	Contours detected: 6	Expected: 4

- Glyph name: uni01DB	Contours detected: 6	Expected: 4

- Glyph name: uni01DC	Contours detected: 6	Expected: 4

- Glyph name: uni01DE	Contours detected: 7	Expected: 5

- Glyph name: uni01DF	Contours detected: 6	Expected: 5

- Glyph name: uni01F0	Contours detected: 3	Expected: 2

- Glyph name: uni01F2	Contours detected: 2	Expected: 3

- Glyph name: uni0227	Contours detected: 2	Expected: 3

- Glyph name: uni022A	Contours detected: 7	Expected: 5

- Glyph name: uni022B	Contours detected: 6	Expected: 5

- Glyph name: uni022D	Contours detected: 3	Expected: 4

- Glyph name: uni022F	Contours detected: 2	Expected: 3

- Glyph name: uni0231	Contours detected: 3	Expected: 4

- Glyph name: uni02B9	Contours detected: 2	Expected: 1

- Glyph name: uni02BC	Contours detected: 2	Expected: 1

- Glyph name: uni02C8	Contours detected: 2	Expected: 1

- Glyph name: uni0308	Contours detected: 4	Expected: 2

- Glyph name: uni030A	Contours detected: 1	Expected: 2

- Glyph name: uni0344	Contours detected: 5	Expected: 3

- Glyph name: uni0374	Contours detected: 2	Expected: 1

- Glyph name: uni0407	Contours detected: 5	Expected: 3

- Glyph name: uni0412	Contours detected: 1	Expected: 3

- Glyph name: uni0430	Contours detected: 1	Expected: 2

- Glyph name: uni0435	Contours detected: 1	Expected: 2

- Glyph name: uni043E	Contours detected: 1	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 5	Expected: 4

- Glyph name: uni0457	Contours detected: 5	Expected: 3

- Glyph name: uni04D1	Contours detected: 2	Expected: 3

- Glyph name: uni04D2	Contours detected: 6	Expected: 4

- Glyph name: uni04D3	Contours detected: 5	Expected: 4

- Glyph name: uni04D7	Contours detected: 2	Expected: 3

- Glyph name: uni04E6	Contours detected: 6	Expected: 4

- Glyph name: uni04E7	Contours detected: 5	Expected: 4

- Glyph name: uni04F1	Contours detected: 5	Expected: 3

- Glyph name: uni1E02	Contours detected: 2	Expected: 4

- Glyph name: uni1E0A	Contours detected: 2	Expected: 3

- Glyph name: uni1E15	Contours detected: 3	Expected: 4

- Glyph name: uni1E17	Contours detected: 3	Expected: 4

- Glyph name: uni1E21	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni1E2E	Contours detected: 6	Expected: 4

- Glyph name: uni1E2F	Contours detected: 7	Expected: 4

- Glyph name: uni1E4D	Contours detected: 3	Expected: 4

- Glyph name: uni1E4E	Contours detected: 7	Expected: 5

- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

- Glyph name: uni1E51	Contours detected: 3	Expected: 4

- Glyph name: uni1E53	Contours detected: 3	Expected: 4

- Glyph name: uni1E56	Contours detected: 2	Expected: 3

- Glyph name: uni1E7A	Contours detected: 6	Expected: 4

- Glyph name: uni1E7B	Contours detected: 6	Expected: 4

- Glyph name: uni1E97	Contours detected: 5	Expected: 3

- Glyph name: uni1EA3	Contours detected: 2	Expected: 3

- Glyph name: uni1EA5	Contours detected: 3	Expected: 4

- Glyph name: uni1EA7	Contours detected: 3	Expected: 4

- Glyph name: uni1EA9	Contours detected: 3	Expected: 4

- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

- Glyph name: uni1EAF	Contours detected: 3	Expected: 4

- Glyph name: uni1EB1	Contours detected: 3	Expected: 4

- Glyph name: uni1EB3	Contours detected: 3	Expected: 4

- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

- Glyph name: uni1EBB	Contours detected: 2	Expected: 3

- Glyph name: uni1EBD	Contours detected: 2	Expected: 3

- Glyph name: uni1EBF	Contours detected: 3	Expected: 4

- Glyph name: uni1EC1	Contours detected: 3	Expected: 4

- Glyph name: uni1EC3	Contours detected: 3	Expected: 4

- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

- Glyph name: uni1ECF	Contours detected: 2	Expected: 3

- Glyph name: uni1ED1	Contours detected: 3	Expected: 4

- Glyph name: uni1ED3	Contours detected: 3	Expected: 4

- Glyph name: uni1ED5	Contours detected: 3	Expected: 4

- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

- Glyph name: uni1EED	Contours detected: 3	Expected: 2

- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

- Glyph name: uni1F78	Contours detected: 2	Expected: 3

- Glyph name: uni1FED	Contours detected: 5	Expected: 3

- Glyph name: uni2016	Contours detected: 4	Expected: 2

- Glyph name: uni2034	Contours detected: 6	Expected: 3

- Glyph name: uni2102	Contours detected: 1	Expected: 2

- Glyph name: uni2105	Contours detected: 3	Expected: 4

- Glyph name: uni210A	Contours detected: 1	Expected: 2

- Glyph name: uni210D	Contours detected: 1	Expected: 2

- Glyph name: uni2113	Contours detected: 1	Expected: 2

- Glyph name: uni2115	Contours detected: 1	Expected: 2

- Glyph name: uni2116	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni2119	Contours detected: 1	Expected: 2

- Glyph name: uni211A	Contours detected: 2	Expected: 3

- Glyph name: uni211D	Contours detected: 2	Expected: 3

- Glyph name: uni2218	Contours detected: 1	Expected: 2

- Glyph name: uni2223	Contours detected: 2	Expected: 1

- Glyph name: uni2225	Contours detected: 4	Expected: 2

- Glyph name: uring	Contours detected: 2	Expected: 3

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: wacute	Contours detected: 3	Expected: 2

- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

- Glyph name: wdieresis	Contours detected: 6	Expected: 3

- Glyph name: wgrave	Contours detected: 3	Expected: 2

- Glyph name: ydieresis	Contours detected: 5	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 851 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 798:
plus</p>
<p>Width = 768:
equal</p>
<p>Width = 1397:
logicalnot</p>
<p>Width = 786:
plusminus, minus</p>
<p>Width = 790:
divide</p>
<p>Width = 1028:
similar</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* minute (U+2032): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* quoteright (U+2019): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* quotesingle (U+0027): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* second (U+2033): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* second (U+2033): B&lt;&lt;3417.5,1178.0&gt;-&lt;3413.0,1177.0&gt;-&lt;3406.0,1176.0&gt;&gt;/B&lt;&lt;3406.0,1176.0&gt;-&lt;3417.0,1176.0&gt;-&lt;3424.0,1179.0&gt;&gt; = 8.13010235415596

* uni02B9 (U+02B9): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni02BC (U+02BC): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni02C8 (U+02C8): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni0374 (U+0374): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni2034 (U+2034): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni2034 (U+2034): B&lt;&lt;3417.5,1178.0&gt;-&lt;3413.0,1177.0&gt;-&lt;3406.0,1176.0&gt;&gt;/B&lt;&lt;3406.0,1176.0&gt;-&lt;3417.0,1176.0&gt;-&lt;3424.0,1179.0&gt;&gt; = 8.13010235415596

* uni2034 (U+2034): B&lt;&lt;5465.5,1178.0&gt;-&lt;5461.0,1177.0&gt;-&lt;5454.0,1176.0&gt;&gt;/B&lt;&lt;5454.0,1176.0&gt;-&lt;5465.0,1176.0&gt;-&lt;5472.0,1179.0&gt;&gt; = 8.13010235415596

* uni2057 (U+2057): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596

* uni2057 (U+2057): B&lt;&lt;3417.5,1178.0&gt;-&lt;3413.0,1177.0&gt;-&lt;3406.0,1176.0&gt;&gt;/B&lt;&lt;3406.0,1176.0&gt;-&lt;3417.0,1176.0&gt;-&lt;3424.0,1179.0&gt;&gt; = 8.13010235415596

* uni2057 (U+2057): B&lt;&lt;5465.5,1178.0&gt;-&lt;5461.0,1177.0&gt;-&lt;5454.0,1176.0&gt;&gt;/B&lt;&lt;5454.0,1176.0&gt;-&lt;5465.0,1176.0&gt;-&lt;5472.0,1179.0&gt;&gt; = 8.13010235415596

* uni2057 (U+2057): B&lt;&lt;7513.5,1178.0&gt;-&lt;7509.0,1177.0&gt;-&lt;7502.0,1176.0&gt;&gt;/B&lt;&lt;7502.0,1176.0&gt;-&lt;7513.0,1176.0&gt;-&lt;7520.0,1179.0&gt;&gt; = 8.13010235415596

* uniFF07 (U+FF07): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* A (U+0041): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Aacute (U+00C1): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Abreve (U+0102): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Acircumflex (U+00C2): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Adieresis (U+00C4): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Agrave (U+00C0): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Alpha (U+0391): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Amacron (U+0100): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Aring (U+00C5): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Aringacute (U+01FA): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Atilde (U+00C3): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* B (U+0042): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* B (U+0042): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* Beta (U+0392): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* Beta (U+0392): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* C (U+0043): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Cacute (U+0106): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Ccaron (U+010C): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Ccedilla (U+00C7): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Ccircumflex (U+0108): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Cdotaccent (U+010A): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* E (U+0045): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Ebreve (U+0114): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Ecaron (U+011A): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Epsilon (U+0395): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* F (U+0046): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* I (U+0049): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* IJ (U+0132): L&lt;&lt;1352.0,685.0&gt;--&lt;1353.0,506.0&gt;&gt;

* IJ (U+0132): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Iacute (U+00CD): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Ibreve (U+012C): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Icircumflex (U+00CE): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Idieresis (U+00CF): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Idotaccent (U+0130): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Ifraktur (U+2111): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Igrave (U+00CC): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Imacron (U+012A): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Iota (U+0399): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Iotadieresis (U+03AA): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Itilde (U+0128): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* J (U+004A): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* Jcircumflex (U+0134): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* M (U+004D): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* Mu (U+039C): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* N (U+004E): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* Nacute (U+0143): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* Ncaron (U+0147): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* Nu (U+039D): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* O (U+004F): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* OE (U+0152): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* OE (U+0152): L&lt;&lt;2363.0,115.0&gt;--&lt;1895.0,117.0&gt;&gt;

* Oacute (U+00D3): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Obreve (U+014E): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Ocircumflex (U+00D4): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Odieresis (U+00D6): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Ograve (U+00D2): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Ohorn (U+01A0): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Omacron (U+014C): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Omicron (U+039F): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Oslash (U+00D8): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Oslashacute (U+01FE): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Otilde (U+00D5): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* asterisk (U+002A): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* asteriskmath (U+2217): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;281.0,119.0&gt;--&lt;283.0,709.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;281.0,928.0&gt;--&lt;285.0,1491.0&gt;&gt;

* emptyset (U+2205): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* four (U+0034): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;123.0,899.0&gt;--&lt;700.0,895.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;701.0,997.0&gt;--&lt;123.0,1001.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;2070.0,1351.0&gt;--&lt;2210.0,1352.0&gt;&gt;

* uni01C7 (U+01C7): L&lt;&lt;1851.0,685.0&gt;--&lt;1852.0,506.0&gt;&gt;

* uni01CA (U+01CA): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni01CA (U+01CA): L&lt;&lt;2789.0,685.0&gt;--&lt;2790.0,506.0&gt;&gt;

* uni01CB (U+01CB): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni01CD (U+01CD): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni01CF (U+01CF): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni01D1 (U+01D1): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni01DE (U+01DE): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni01F8 (U+01F8): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni0226 (U+0226): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni022A (U+022A): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni022C (U+022C): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni022E (U+022E): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni0230 (U+0230): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni0406 (U+0406): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni0407 (U+0407): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni0408 (U+0408): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* uni0410 (U+0410): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni0412 (U+0412): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni0412 (U+0412): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni0415 (U+0415): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni041C (U+041C): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni041E (U+041E): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni0421 (U+0421): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni04C0 (U+04C0): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni04D0 (U+04D0): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni04D2 (U+04D2): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni04D6 (U+04D6): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni04E6 (U+04E6): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni0555 (U+0555): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni13AA (U+13AA): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni13AB (U+13AB): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* uni13AC (U+13AC): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni13B7 (U+13B7): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni13DF (U+13DF): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni13F4 (U+13F4): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni13F4 (U+13F4): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni1D2C (U+1D2C): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1D2E (U+1D2E): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni1D2E (U+1D2E): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni1D31 (U+1D31): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1D35 (U+1D35): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1D36 (U+1D36): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* uni1D39 (U+1D39): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni1D3A (U+1D3A): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni1D3C (U+1D3C): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1E02 (U+1E02): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni1E02 (U+1E02): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni1E08 (U+1E08): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni1E14 (U+1E14): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1E16 (U+1E16): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1E1E (U+1E1E): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uni1E2E (U+1E2E): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1E3E (U+1E3E): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni1E40 (U+1E40): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni1E44 (U+1E44): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni1E4C (U+1E4C): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1E4E (U+1E4E): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1E50 (U+1E50): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1E52 (U+1E52): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1EA2 (U+1EA2): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EA4 (U+1EA4): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EA6 (U+1EA6): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EA8 (U+1EA8): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EAA (U+1EAA): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EAE (U+1EAE): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EB0 (U+1EB0): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EB2 (U+1EB2): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EB4 (U+1EB4): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1EBA (U+1EBA): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EBC (U+1EBC): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EBE (U+1EBE): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EC0 (U+1EC0): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EC2 (U+1EC2): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EC4 (U+1EC4): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1EC8 (U+1EC8): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1ECE (U+1ECE): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1ED0 (U+1ED0): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1ED2 (U+1ED2): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1ED4 (U+1ED4): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1ED6 (U+1ED6): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1EDA (U+1EDA): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1EDC (U+1EDC): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1EDE (U+1EDE): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1EE0 (U+1EE0): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni1FB8 (U+1FB8): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1FB9 (U+1FB9): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1FBA (U+1FBA): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni1FC8 (U+1FC8): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni1FD8 (U+1FD8): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1FD9 (U+1FD9): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1FDA (U+1FDA): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni1FF8 (U+1FF8): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uni2074 (U+2074): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* uni2084 (U+2084): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* uni2102 (U+2102): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni2103 (U+2103): L&lt;&lt;472.0,741.0&gt;--&lt;473.0,331.0&gt;&gt;

* uni2109 (U+2109): L&lt;&lt;428.0,1123.0&gt;--&lt;427.0,975.0&gt;&gt;

* uni2110 (U+2110): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni2115 (U+2115): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni2116 (U+2116): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni2120 (U+2120): L&lt;&lt;1529.0,1351.0&gt;--&lt;1669.0,1352.0&gt;&gt;

* uni2121 (U+2121): L&lt;&lt;2552.0,115.0&gt;--&lt;2084.0,117.0&gt;&gt;

* uni212B (U+212B): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni212C (U+212C): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni212C (U+212C): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni212D (U+212D): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni2130 (U+2130): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2131 (U+2131): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uni2133 (U+2133): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni213B (U+213B): L&lt;&lt;1141.0,373.0&gt;--&lt;1142.0,488.0&gt;&gt;

* uni213B (U+213B): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uni2160 (U+2160): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni2161 (U+2161): L&lt;&lt;1027.0,685.0&gt;--&lt;1028.0,959.0&gt;&gt;

* uni2161 (U+2161): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni2162 (U+2162): L&lt;&lt;1027.0,685.0&gt;--&lt;1028.0,959.0&gt;&gt;

* uni2162 (U+2162): L&lt;&lt;1592.0,685.0&gt;--&lt;1593.0,959.0&gt;&gt;

* uni2162 (U+2162): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni2163 (U+2163): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni2165 (U+2165): L&lt;&lt;2006.0,685.0&gt;--&lt;2007.0,959.0&gt;&gt;

* uni2166 (U+2166): L&lt;&lt;2006.0,685.0&gt;--&lt;2007.0,959.0&gt;&gt;

* uni2166 (U+2166): L&lt;&lt;2571.0,685.0&gt;--&lt;2572.0,959.0&gt;&gt;

* uni2167 (U+2167): L&lt;&lt;2006.0,685.0&gt;--&lt;2007.0,959.0&gt;&gt;

* uni2167 (U+2167): L&lt;&lt;2571.0,685.0&gt;--&lt;2572.0,959.0&gt;&gt;

* uni2167 (U+2167): L&lt;&lt;3136.0,685.0&gt;--&lt;3137.0,959.0&gt;&gt;

* uni2168 (U+2168): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni216A (U+216A): L&lt;&lt;2538.0,685.0&gt;--&lt;2539.0,959.0&gt;&gt;

* uni216B (U+216B): L&lt;&lt;2538.0,685.0&gt;--&lt;2539.0,959.0&gt;&gt;

* uni216B (U+216B): L&lt;&lt;3103.0,685.0&gt;--&lt;3104.0,959.0&gt;&gt;

* uni216D (U+216D): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni216F (U+216F): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni2400 (U+2400): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni2401 (U+2401): L&lt;&lt;1140.0,664.0&gt;--&lt;1138.0,898.0&gt;&gt;

* uni2403 (U+2403): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2404 (U+2404): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2404 (U+2404): L&lt;&lt;1193.0,664.0&gt;--&lt;1191.0,898.0&gt;&gt;

* uni2405 (U+2405): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2405 (U+2405): L&lt;&lt;3022.0,1040.0&gt;--&lt;3023.0,1189.0&gt;&gt;

* uni2405 (U+2405): L&lt;&lt;3204.0,373.0&gt;--&lt;3205.0,488.0&gt;&gt;

* uni2406 (U+2406): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni2406 (U+2406): L&lt;&lt;1596.0,741.0&gt;--&lt;1597.0,331.0&gt;&gt;

* uni2407 (U+2407): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni2407 (U+2407): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni2407 (U+2407): L&lt;&lt;2556.0,115.0&gt;--&lt;2088.0,117.0&gt;&gt;

* uni2408 (U+2408): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni2408 (U+2408): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni240A (U+240A): L&lt;&lt;1126.0,1123.0&gt;--&lt;1125.0,975.0&gt;&gt;

* uni240C (U+240C): L&lt;&lt;1049.0,1123.0&gt;--&lt;1048.0,975.0&gt;&gt;

* uni240C (U+240C): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uni240D (U+240D): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni240E (U+240E): L&lt;&lt;1140.0,664.0&gt;--&lt;1138.0,898.0&gt;&gt;

* uni240F (U+240F): L&lt;&lt;1457.0,685.0&gt;--&lt;1458.0,959.0&gt;&gt;

* uni2410 (U+2410): L&lt;&lt;3648.0,115.0&gt;--&lt;3180.0,117.0&gt;&gt;

* uni2411 (U+2411): L&lt;&lt;1674.0,741.0&gt;--&lt;1675.0,331.0&gt;&gt;

* uni2412 (U+2412): L&lt;&lt;1674.0,741.0&gt;--&lt;1675.0,331.0&gt;&gt;

* uni2413 (U+2413): L&lt;&lt;1674.0,741.0&gt;--&lt;1675.0,331.0&gt;&gt;

* uni2414 (U+2414): L&lt;&lt;1674.0,741.0&gt;--&lt;1675.0,331.0&gt;&gt;

* uni2414 (U+2414): L&lt;&lt;3442.0,1223.0&gt;--&lt;3443.0,1107.0&gt;&gt;

* uni2415 (U+2415): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uni2415 (U+2415): L&lt;&lt;2156.0,373.0&gt;--&lt;2157.0,488.0&gt;&gt;

* uni2416 (U+2416): L&lt;&lt;4437.0,1040.0&gt;--&lt;4438.0,1189.0&gt;&gt;

* uni2417 (U+2417): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2417 (U+2417): L&lt;&lt;2739.0,846.0&gt;--&lt;2738.0,634.0&gt;&gt;

* uni2417 (U+2417): L&lt;&lt;4023.0,140.0&gt;--&lt;4024.0,309.0&gt;&gt;

* uni2418 (U+2418): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni2418 (U+2418): L&lt;&lt;1075.0,373.0&gt;--&lt;1076.0,488.0&gt;&gt;

* uni2418 (U+2418): L&lt;&lt;4385.0,1040.0&gt;--&lt;4386.0,1189.0&gt;&gt;

* uni2419 (U+2419): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni2419 (U+2419): L&lt;&lt;1582.0,1351.0&gt;--&lt;1722.0,1352.0&gt;&gt;

* uni241A (U+241A): L&lt;&lt;2855.0,846.0&gt;--&lt;2854.0,634.0&gt;&gt;

* uni241A (U+241A): L&lt;&lt;4139.0,140.0&gt;--&lt;4140.0,309.0&gt;&gt;

* uni241B (U+241B): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uni241B (U+241B): L&lt;&lt;2149.0,741.0&gt;--&lt;2150.0,331.0&gt;&gt;

* uni241C (U+241C): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uni2421 (U+2421): L&lt;&lt;2584.0,115.0&gt;--&lt;2116.0,117.0&gt;&gt;

* uni2477 (U+2477): L&lt;&lt;2050.0,1223.0&gt;--&lt;2051.0,1107.0&gt;&gt;

* uni2481 (U+2481): L&lt;&lt;2987.0,1223.0&gt;--&lt;2988.0,1107.0&gt;&gt;

* uni248B (U+248B): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* uni2495 (U+2495): L&lt;&lt;1890.0,1223.0&gt;--&lt;1891.0,1107.0&gt;&gt;

* uni2731 (U+2731): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* uni3250 (U+3250): L&lt;&lt;3846.0,115.0&gt;--&lt;3378.0,117.0&gt;&gt;

* uni3373 (U+3373): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uni337A (U+337A): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uni3380 (U+3380): L&lt;&lt;1096.0,373.0&gt;--&lt;1097.0,488.0&gt;&gt;

* uni3381 (U+3381): L&lt;&lt;1038.0,373.0&gt;--&lt;1039.0,488.0&gt;&gt;

* uni3383 (U+3383): L&lt;&lt;1345.0,373.0&gt;--&lt;1346.0,488.0&gt;&gt;

* uni3384 (U+3384): L&lt;&lt;954.0,373.0&gt;--&lt;955.0,488.0&gt;&gt;

* uni3385 (U+3385): L&lt;&lt;1576.0,846.0&gt;--&lt;1575.0,634.0&gt;&gt;

* uni3385 (U+3385): L&lt;&lt;2860.0,140.0&gt;--&lt;2861.0,309.0&gt;&gt;

* uni3386 (U+3386): L&lt;&lt;2477.0,846.0&gt;--&lt;2476.0,634.0&gt;&gt;

* uni3386 (U+3386): L&lt;&lt;3761.0,140.0&gt;--&lt;3762.0,309.0&gt;&gt;

* uni3386 (U+3386): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni3387 (U+3387): L&lt;&lt;1645.0,846.0&gt;--&lt;1644.0,634.0&gt;&gt;

* uni3387 (U+3387): L&lt;&lt;2929.0,140.0&gt;--&lt;2930.0,309.0&gt;&gt;

* uni338A (U+338A): L&lt;&lt;1004.0,1123.0&gt;--&lt;1003.0,975.0&gt;&gt;

* uni338B (U+338B): L&lt;&lt;946.0,1123.0&gt;--&lt;945.0,975.0&gt;&gt;

* uni3392 (U+3392): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni33AB (U+33AB): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni33B9 (U+33B9): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni33BF (U+33BF): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uni33C3 (U+33C3): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uni33C3 (U+33C3): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uni33C6 (U+33C6): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni33C7 (U+33C7): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uni33C8 (U+33C8): L&lt;&lt;1097.0,846.0&gt;--&lt;1096.0,634.0&gt;&gt;

* uni33C8 (U+33C8): L&lt;&lt;2381.0,140.0&gt;--&lt;2382.0,309.0&gt;&gt;

* uni33CE (U+33CE): L&lt;&lt;1955.0,1351.0&gt;--&lt;2095.0,1352.0&gt;&gt;

* uni33D9 (U+33D9): L&lt;&lt;3122.0,1351.0&gt;--&lt;3262.0,1352.0&gt;&gt;

* uni33DF (U+33DF): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uniFE61 (U+FE61): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* uniFF0A (U+FF0A): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* uniFF14 (U+FF14): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* uniFF21 (U+FF21): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* uniFF22 (U+FF22): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* uniFF22 (U+FF22): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* uniFF23 (U+FF23): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* uniFF25 (U+FF25): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* uniFF26 (U+FF26): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* uniFF29 (U+FF29): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* uniFF2A (U+FF2A): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* uniFF2D (U+FF2D): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* uniFF2E (U+FF2E): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* uniFF2F (U+FF2F): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* uniFFE2 (U+FFE2): L&lt;&lt;123.0,899.0&gt;--&lt;700.0,895.0&gt;&gt;

* uniFFE2 (U+FFE2): L&lt;&lt;701.0,997.0&gt;--&lt;123.0,1001.0&gt;&gt;

* uniFFE4 (U+FFE4): L&lt;&lt;281.0,119.0&gt;--&lt;283.0,709.0&gt;&gt;

* uniFFE4 (U+FFE4): L&lt;&lt;281.0,928.0&gt;--&lt;285.0,1491.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* A (U+0041) has a counter-clockwise outer contour

* AE (U+00C6) has a counter-clockwise outer contour

* AEacute (U+01FC) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Alpha (U+0391) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aringacute (U+01FA) has a counter-clockwise outer contour

* Aringacute (U+01FA) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* B (U+0042) has a counter-clockwise outer contour

* Beta (U+0392) has a counter-clockwise outer contour

* C (U+0043) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* Ccircumflex (U+0108) has a counter-clockwise outer contour

* Ccircumflex (U+0108) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* Cdotaccent (U+010A) has a counter-clockwise outer contour

* Chi (U+03A7) has a counter-clockwise outer contour

* D (U+0044) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* Dcroat (U+0110) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ebreve (U+0114) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Epsilon (U+0395) has a counter-clockwise outer contour

* Eta (U+0397) has a counter-clockwise outer contour

* Eth (U+00D0) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* G (U+0047) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gcaron (U+01E6) has a counter-clockwise outer contour

* Gcaron (U+01E6) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gcircumflex (U+011C) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* H (U+0048) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* Hcircumflex (U+0124) has a counter-clockwise outer contour

* I (U+0049) has a counter-clockwise outer contour

* IJ (U+0132) has a counter-clockwise outer contour

* IJ (U+0132) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Ibreve (U+012C) has a counter-clockwise outer contour

* Ibreve (U+012C) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Ifraktur (U+2111) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Iota (U+0399) has a counter-clockwise outer contour

* Iotadieresis (U+03AA) has a counter-clockwise outer contour

* Itilde (U+0128) has a counter-clockwise outer contour

* Itilde (U+0128) has a counter-clockwise outer contour

* J (U+004A) has a counter-clockwise outer contour

* Jcircumflex (U+0134) has a counter-clockwise outer contour

* Jcircumflex (U+0134) has a counter-clockwise outer contour

* K (U+004B) has a counter-clockwise outer contour

* Kappa (U+039A) has a counter-clockwise outer contour

* L (U+004C) has a counter-clockwise outer contour

* Lacute (U+0139) has a counter-clockwise outer contour

* Ldot (U+013F) has a counter-clockwise outer contour

* M (U+004D) has a counter-clockwise outer contour

* Mu (U+039C) has a counter-clockwise outer contour

* N (U+004E) has a counter-clockwise outer contour

* Nacute (U+0143) has a counter-clockwise outer contour

* Ncaron (U+0147) has a counter-clockwise outer contour

* Ncaron (U+0147) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* Nu (U+039D) has a counter-clockwise outer contour

* O (U+004F) has a counter-clockwise outer contour

* OE (U+0152) has a counter-clockwise outer contour

* OE (U+0152) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Obreve (U+014E) has a counter-clockwise outer contour

* Obreve (U+014E) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ohorn (U+01A0) has a counter-clockwise outer contour

* Omacron (U+014C) has a counter-clockwise outer contour

* Omacron (U+014C) has a counter-clockwise outer contour

* Omicron (U+039F) has a counter-clockwise outer contour

* Oslash (U+00D8) has a counter-clockwise outer contour

* Oslashacute (U+01FE) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* P (U+0050) has a counter-clockwise outer contour

* Q (U+0051) has a counter-clockwise outer contour

* R (U+0052) has a counter-clockwise outer contour

* Racute (U+0154) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* Rfraktur (U+211C) has a counter-clockwise outer contour

* Rho (U+03A1) has a counter-clockwise outer contour

* S (U+0053) has a counter-clockwise outer contour

* SF100000 (U+2500) has a counter-clockwise outer contour

* SF110000 (U+2502) has a counter-clockwise outer contour

* SF110000 (U+2502) has a counter-clockwise outer contour

* Sacute (U+015A) has a counter-clockwise outer contour

* Scaron (U+0160) has a counter-clockwise outer contour

* Scaron (U+0160) has a counter-clockwise outer contour

* Scircumflex (U+015C) has a counter-clockwise outer contour

* Scircumflex (U+015C) has a counter-clockwise outer contour

* T (U+0054) has a counter-clockwise outer contour

* Tau (U+03A4) has a counter-clockwise outer contour

* Tcaron (U+0164) has a counter-clockwise outer contour

* Tcaron (U+0164) has a counter-clockwise outer contour

* U (U+0055) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Ubreve (U+016C) has a counter-clockwise outer contour

* Ubreve (U+016C) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Uhorn (U+01AF) has a counter-clockwise outer contour

* Umacron (U+016A) has a counter-clockwise outer contour

* Umacron (U+016A) has a counter-clockwise outer contour

* Upsilon (U+03A5) has a counter-clockwise outer contour

* Upsilon1 (U+03D2) has a counter-clockwise outer contour

* Upsilondieresis (U+03AB) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* Utilde (U+0168) has a counter-clockwise outer contour

* Utilde (U+0168) has a counter-clockwise outer contour

* V (U+0056) has a counter-clockwise outer contour

* W (U+0057) has a counter-clockwise outer contour

* Wacute (U+1E82) has a counter-clockwise outer contour

* Wcircumflex (U+0174) has a counter-clockwise outer contour

* Wcircumflex (U+0174) has a counter-clockwise outer contour

* Wdieresis (U+1E84) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* Y (U+0059) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Ycircumflex (U+0176) has a counter-clockwise outer contour

* Ycircumflex (U+0176) has a counter-clockwise outer contour

* Ydieresis (U+0178) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* Z (U+005A) has a counter-clockwise outer contour

* Zacute (U+0179) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zdotaccent (U+017B) has a counter-clockwise outer contour

* Zdotaccent (U+017B) has a counter-clockwise outer contour

* Zeta (U+0396) has a counter-clockwise outer contour

* a (U+0061) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* ampersand (U+0026) has a counter-clockwise outer contour

* anoteleia (U+0387) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* aringacute (U+01FB) has a counter-clockwise outer contour

* aringacute (U+01FB) has a counter-clockwise outer contour

* asciicircum (U+005E) has a counter-clockwise outer contour

* asciitilde (U+007E) has a counter-clockwise outer contour

* asterisk (U+002A) has a counter-clockwise outer contour

* asteriskmath (U+2217) has a counter-clockwise outer contour

* at (U+0040) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* b (U+0062) has a counter-clockwise outer contour

* backslash (U+005C) has a counter-clockwise outer contour

* bar (U+007C) has a counter-clockwise outer contour

* bar (U+007C) has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* braceright (U+007D) has a counter-clockwise outer contour

* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* breve (U+02D8) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* c (U+0063) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* ccedilla (U+00E7) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* ccircumflex (U+0109) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cdotaccent (U+010B) has a counter-clockwise outer contour

* cedilla (U+00B8) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* chi (U+03C7) has a counter-clockwise outer contour

* circumflex (U+02C6) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* comma (U+002C) has a counter-clockwise outer contour

* copyright (U+00A9) has a counter-clockwise outer contour

* currency (U+00A4) has a counter-clockwise outer contour

* d (U+0064) has a counter-clockwise outer contour

* degree (U+00B0) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* dollar (U+0024) has a counter-clockwise outer contour

* dotaccent (U+02D9) has a counter-clockwise outer contour

* dotlessi (U+0131) has a counter-clockwise outer contour

* dotmath (U+22C5) has a counter-clockwise outer contour

* e (U+0065) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* ebreve (U+0115) has a counter-clockwise outer contour

* ebreve (U+0115) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* edotaccent (U+0117) has a counter-clockwise outer contour

* edotaccent (U+0117) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* eight (U+0038) has a counter-clockwise outer contour

* ellipsis (U+2026) has a counter-clockwise outer contour

* ellipsis (U+2026) has a counter-clockwise outer contour

* ellipsis (U+2026) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* emdash (U+2014) has a counter-clockwise outer contour

* emptyset (U+2205) has a counter-clockwise outer contour

* endash (U+2013) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdbl (U+203C) has a counter-clockwise outer contour

* exclamdbl (U+203C) has a counter-clockwise outer contour

* exclamdbl (U+203C) has a counter-clockwise outer contour

* exclamdbl (U+203C) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* f (U+0066) has a counter-clockwise outer contour

* figuredash (U+2012) has a counter-clockwise outer contour

* five (U+0035) has a counter-clockwise outer contour

* four (U+0034) has a counter-clockwise outer contour

* g (U+0067) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* gcaron (U+01E7) has a counter-clockwise outer contour

* gcaron (U+01E7) has a counter-clockwise outer contour

* gcircumflex (U+011D) has a counter-clockwise outer contour

* gcircumflex (U+011D) has a counter-clockwise outer contour

* gdotaccent (U+0121) has a counter-clockwise outer contour

* gdotaccent (U+0121) has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* gravecomb (U+0300) has a counter-clockwise outer contour

* greater (U+003E) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* h (U+0068) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hcircumflex (U+0125) has a counter-clockwise outer contour

* hookabovecomb (U+0309) has a counter-clockwise outer contour

* hyphen (U+002D) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* ibreve (U+012D) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* itilde (U+0129) has a counter-clockwise outer contour

* itilde (U+0129) has a counter-clockwise outer contour

* itilde (U+0129) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* jcircumflex (U+0135) has a counter-clockwise outer contour

* jcircumflex (U+0135) has a counter-clockwise outer contour

* jcircumflex (U+0135) has a counter-clockwise outer contour

* k (U+006B) has a counter-clockwise outer contour

* l (U+006C) has a counter-clockwise outer contour

* lacute (U+013A) has a counter-clockwise outer contour

* ldot (U+0140) has a counter-clockwise outer contour

* ldot (U+0140) has a counter-clockwise outer contour

* less (U+003C) has a counter-clockwise outer contour

* logicalnot (U+00AC) has a counter-clockwise outer contour

* longs (U+017F) has a counter-clockwise outer contour

* m (U+006D) has a counter-clockwise outer contour

* macron (U+00AF) has a counter-clockwise outer contour

* minus (U+2212) has a counter-clockwise outer contour

* minute (U+2032) has a counter-clockwise outer contour

* minute (U+2032) has a counter-clockwise outer contour

* mu (U+00B5) has a counter-clockwise outer contour

* n (U+006E) has a counter-clockwise outer contour

* nacute (U+0144) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* numbersign (U+0023) has a counter-clockwise outer contour

* o (U+006F) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* obreve (U+014F) has a counter-clockwise outer contour

* obreve (U+014F) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* oe (U+0153) has a counter-clockwise outer contour

* oe (U+0153) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ohorn (U+01A1) has a counter-clockwise outer contour

* ohorn (U+01A1) has a counter-clockwise outer contour

* omacron (U+014D) has a counter-clockwise outer contour

* omacron (U+014D) has a counter-clockwise outer contour

* omicron (U+03BF) has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* onedotenleader (U+2024) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* openbullet (U+25E6) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

* oslashacute (U+01FF) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* p (U+0070) has a counter-clockwise outer contour

* paragraph (U+00B6) has a counter-clockwise outer contour

* parenleft (U+0028) has a counter-clockwise outer contour

* parenright (U+0029) has a counter-clockwise outer contour

* percent (U+0025) has a counter-clockwise outer contour

* period (U+002E) has a counter-clockwise outer contour

* periodcentered (U+00B7) has a counter-clockwise outer contour

* plus (U+002B) has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* q (U+0071) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quoteleft (U+2018) has a counter-clockwise outer contour

* quoteright (U+2019) has a counter-clockwise outer contour

* quoteright (U+2019) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* r (U+0072) has a counter-clockwise outer contour

* racute (U+0155) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* registered (U+00AE) has a counter-clockwise outer contour

* rho (U+03C1) has a counter-clockwise outer contour

* ring (U+02DA) has a counter-clockwise outer contour

* s (U+0073) has a counter-clockwise outer contour

* sacute (U+015B) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* scircumflex (U+015D) has a counter-clockwise outer contour

* scircumflex (U+015D) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* second (U+2033) has a counter-clockwise outer contour

* section (U+00A7) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* similar (U+223C) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* slash (U+002F) has a counter-clockwise outer contour

* sterling (U+00A3) has a counter-clockwise outer contour

* t (U+0074) has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* tilde (U+02DC) has a counter-clockwise outer contour

* tildecomb (U+0303) has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

* two (U+0032) has a counter-clockwise outer contour

* twodotenleader (U+2025) has a counter-clockwise outer contour

* twodotenleader (U+2025) has a counter-clockwise outer contour

* u (U+0075) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* ubreve (U+016D) has a counter-clockwise outer contour

* ubreve (U+016D) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* uhorn (U+01B0) has a counter-clockwise outer contour

* uhorn (U+01B0) has a counter-clockwise outer contour

* umacron (U+016B) has a counter-clockwise outer contour

* umacron (U+016B) has a counter-clockwise outer contour

* underscore (U+005F) has a counter-clockwise outer contour

* uni0000 (U+0000) has a counter-clockwise outer contour

* uni00AD (U+00AD) has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* uni0189 (U+0189) has a counter-clockwise outer contour

* uni01C0 (U+01C0) has a counter-clockwise outer contour

* uni01C0 (U+01C0) has a counter-clockwise outer contour

* uni01C1 (U+01C1) has a counter-clockwise outer contour

* uni01C1 (U+01C1) has a counter-clockwise outer contour

* uni01C1 (U+01C1) has a counter-clockwise outer contour

* uni01C1 (U+01C1) has a counter-clockwise outer contour

* uni01C4 (U+01C4) has a counter-clockwise outer contour

* uni01C4 (U+01C4) has a counter-clockwise outer contour

* uni01C4 (U+01C4) has a counter-clockwise outer contour

* uni01C5 (U+01C5) has a counter-clockwise outer contour

* uni01C5 (U+01C5) has a counter-clockwise outer contour

* uni01C5 (U+01C5) has a counter-clockwise outer contour

* uni01C6 (U+01C6) has a counter-clockwise outer contour

* uni01C6 (U+01C6) has a counter-clockwise outer contour

* uni01C6 (U+01C6) has a counter-clockwise outer contour

* uni01C7 (U+01C7) has a counter-clockwise outer contour

* uni01C7 (U+01C7) has a counter-clockwise outer contour

* uni01C8 (U+01C8) has a counter-clockwise outer contour

* uni01C8 (U+01C8) has a counter-clockwise outer contour

* uni01C8 (U+01C8) has a counter-clockwise outer contour

* uni01C9 (U+01C9) has a counter-clockwise outer contour

* uni01C9 (U+01C9) has a counter-clockwise outer contour

* uni01C9 (U+01C9) has a counter-clockwise outer contour

* uni01CA (U+01CA) has a counter-clockwise outer contour

* uni01CA (U+01CA) has a counter-clockwise outer contour

* uni01CB (U+01CB) has a counter-clockwise outer contour

* uni01CB (U+01CB) has a counter-clockwise outer contour

* uni01CB (U+01CB) has a counter-clockwise outer contour

* uni01CC (U+01CC) has a counter-clockwise outer contour

* uni01CC (U+01CC) has a counter-clockwise outer contour

* uni01CC (U+01CC) has a counter-clockwise outer contour

* uni01CD (U+01CD) has a counter-clockwise outer contour

* uni01CD (U+01CD) has a counter-clockwise outer contour

* uni01CE (U+01CE) has a counter-clockwise outer contour

* uni01CE (U+01CE) has a counter-clockwise outer contour

* uni01CF (U+01CF) has a counter-clockwise outer contour

* uni01CF (U+01CF) has a counter-clockwise outer contour

* uni01D0 (U+01D0) has a counter-clockwise outer contour

* uni01D0 (U+01D0) has a counter-clockwise outer contour

* uni01D1 (U+01D1) has a counter-clockwise outer contour

* uni01D1 (U+01D1) has a counter-clockwise outer contour

* uni01D2 (U+01D2) has a counter-clockwise outer contour

* uni01D2 (U+01D2) has a counter-clockwise outer contour

* uni01D3 (U+01D3) has a counter-clockwise outer contour

* uni01D3 (U+01D3) has a counter-clockwise outer contour

* uni01D4 (U+01D4) has a counter-clockwise outer contour

* uni01D4 (U+01D4) has a counter-clockwise outer contour

* uni01D5 (U+01D5) has a counter-clockwise outer contour

* uni01D5 (U+01D5) has a counter-clockwise outer contour

* uni01D6 (U+01D6) has a counter-clockwise outer contour

* uni01D6 (U+01D6) has a counter-clockwise outer contour

* uni01D7 (U+01D7) has a counter-clockwise outer contour

* uni01D8 (U+01D8) has a counter-clockwise outer contour

* uni01D9 (U+01D9) has a counter-clockwise outer contour

* uni01D9 (U+01D9) has a counter-clockwise outer contour

* uni01DA (U+01DA) has a counter-clockwise outer contour

* uni01DA (U+01DA) has a counter-clockwise outer contour

* uni01DB (U+01DB) has a counter-clockwise outer contour

* uni01DB (U+01DB) has a counter-clockwise outer contour

* uni01DC (U+01DC) has a counter-clockwise outer contour

* uni01DC (U+01DC) has a counter-clockwise outer contour

* uni01DE (U+01DE) has a counter-clockwise outer contour

* uni01DE (U+01DE) has a counter-clockwise outer contour

* uni01DF (U+01DF) has a counter-clockwise outer contour

* uni01DF (U+01DF) has a counter-clockwise outer contour

* uni01E2 (U+01E2) has a counter-clockwise outer contour

* uni01E2 (U+01E2) has a counter-clockwise outer contour

* uni01E8 (U+01E8) has a counter-clockwise outer contour

* uni01E8 (U+01E8) has a counter-clockwise outer contour

* uni01E9 (U+01E9) has a counter-clockwise outer contour

* uni01E9 (U+01E9) has a counter-clockwise outer contour

* uni01F0 (U+01F0) has a counter-clockwise outer contour

* uni01F0 (U+01F0) has a counter-clockwise outer contour

* uni01F0 (U+01F0) has a counter-clockwise outer contour

* uni01F1 (U+01F1) has a counter-clockwise outer contour

* uni01F1 (U+01F1) has a counter-clockwise outer contour

* uni01F2 (U+01F2) has a counter-clockwise outer contour

* uni01F2 (U+01F2) has a counter-clockwise outer contour

* uni01F3 (U+01F3) has a counter-clockwise outer contour

* uni01F3 (U+01F3) has a counter-clockwise outer contour

* uni01F4 (U+01F4) has a counter-clockwise outer contour

* uni01F5 (U+01F5) has a counter-clockwise outer contour

* uni01F8 (U+01F8) has a counter-clockwise outer contour

* uni01F8 (U+01F8) has a counter-clockwise outer contour

* uni01F9 (U+01F9) has a counter-clockwise outer contour

* uni01F9 (U+01F9) has a counter-clockwise outer contour

* uni021E (U+021E) has a counter-clockwise outer contour

* uni021E (U+021E) has a counter-clockwise outer contour

* uni021F (U+021F) has a counter-clockwise outer contour

* uni021F (U+021F) has a counter-clockwise outer contour

* uni0226 (U+0226) has a counter-clockwise outer contour

* uni0226 (U+0226) has a counter-clockwise outer contour

* uni0227 (U+0227) has a counter-clockwise outer contour

* uni0227 (U+0227) has a counter-clockwise outer contour

* uni022A (U+022A) has a counter-clockwise outer contour

* uni022A (U+022A) has a counter-clockwise outer contour

* uni022B (U+022B) has a counter-clockwise outer contour

* uni022B (U+022B) has a counter-clockwise outer contour

* uni022C (U+022C) has a counter-clockwise outer contour

* uni022C (U+022C) has a counter-clockwise outer contour

* uni022C (U+022C) has a counter-clockwise outer contour

* uni022D (U+022D) has a counter-clockwise outer contour

* uni022D (U+022D) has a counter-clockwise outer contour

* uni022D (U+022D) has a counter-clockwise outer contour

* uni022E (U+022E) has a counter-clockwise outer contour

* uni022E (U+022E) has a counter-clockwise outer contour

* uni022F (U+022F) has a counter-clockwise outer contour

* uni022F (U+022F) has a counter-clockwise outer contour

* uni0230 (U+0230) has a counter-clockwise outer contour

* uni0230 (U+0230) has a counter-clockwise outer contour

* uni0230 (U+0230) has a counter-clockwise outer contour

* uni0231 (U+0231) has a counter-clockwise outer contour

* uni0231 (U+0231) has a counter-clockwise outer contour

* uni0231 (U+0231) has a counter-clockwise outer contour

* uni0232 (U+0232) has a counter-clockwise outer contour

* uni0232 (U+0232) has a counter-clockwise outer contour

* uni0233 (U+0233) has a counter-clockwise outer contour

* uni0233 (U+0233) has a counter-clockwise outer contour

* uni0237 (U+0237) has a counter-clockwise outer contour

* uni02B0 (U+02B0) has a counter-clockwise outer contour

* uni02B2 (U+02B2) has a counter-clockwise outer contour

* uni02B2 (U+02B2) has a counter-clockwise outer contour

* uni02B3 (U+02B3) has a counter-clockwise outer contour

* uni02B7 (U+02B7) has a counter-clockwise outer contour

* uni02B7 (U+02B7) has a counter-clockwise outer contour

* uni02B7 (U+02B7) has a path with no bounds (probably a single point)

* uni02B8 (U+02B8) has a counter-clockwise outer contour

* uni02B9 (U+02B9) has a counter-clockwise outer contour

* uni02B9 (U+02B9) has a counter-clockwise outer contour

* uni02BA (U+02BA) has a counter-clockwise outer contour

* uni02BA (U+02BA) has a counter-clockwise outer contour

* uni02BC (U+02BC) has a counter-clockwise outer contour

* uni02BC (U+02BC) has a counter-clockwise outer contour

* uni02C4 (U+02C4) has a counter-clockwise outer contour

* uni02C8 (U+02C8) has a counter-clockwise outer contour

* uni02C8 (U+02C8) has a counter-clockwise outer contour

* uni02E1 (U+02E1) has a counter-clockwise outer contour

* uni02E2 (U+02E2) has a counter-clockwise outer contour

* uni02E3 (U+02E3) has a counter-clockwise outer contour

* uni0302 (U+0302) has a counter-clockwise outer contour

* uni0304 (U+0304) has a counter-clockwise outer contour

* uni0305 (U+0305) has a counter-clockwise outer contour

* uni0306 (U+0306) has a counter-clockwise outer contour

* uni0307 (U+0307) has a counter-clockwise outer contour

* uni030A (U+030A) has a counter-clockwise outer contour

* uni030C (U+030C) has a counter-clockwise outer contour

* uni030D (U+030D) has a counter-clockwise outer contour

* uni030E (U+030E) has a counter-clockwise outer contour

* uni030E (U+030E) has a counter-clockwise outer contour

* uni030F (U+030F) has a counter-clockwise outer contour

* uni030F (U+030F) has a counter-clockwise outer contour

* uni0310 (U+0310) has a counter-clockwise outer contour

* uni0327 (U+0327) has a counter-clockwise outer contour

* uni0340 (U+0340) has a counter-clockwise outer contour

* uni0374 (U+0374) has a counter-clockwise outer contour

* uni0374 (U+0374) has a counter-clockwise outer contour

* uni037E (U+037E) has a counter-clockwise outer contour

* uni037E (U+037E) has a counter-clockwise outer contour

* uni03D4 (U+03D4) has a counter-clockwise outer contour

* uni03F1 (U+03F1) has a counter-clockwise outer contour

* uni0405 (U+0405) has a counter-clockwise outer contour

* uni0406 (U+0406) has a counter-clockwise outer contour

* uni0407 (U+0407) has a counter-clockwise outer contour

* uni0408 (U+0408) has a counter-clockwise outer contour

* uni0410 (U+0410) has a counter-clockwise outer contour

* uni0412 (U+0412) has a counter-clockwise outer contour

* uni0415 (U+0415) has a counter-clockwise outer contour

* uni041A (U+041A) has a counter-clockwise outer contour

* uni041C (U+041C) has a counter-clockwise outer contour

* uni041D (U+041D) has a counter-clockwise outer contour

* uni041E (U+041E) has a counter-clockwise outer contour

* uni0420 (U+0420) has a counter-clockwise outer contour

* uni0421 (U+0421) has a counter-clockwise outer contour

* uni0422 (U+0422) has a counter-clockwise outer contour

* uni0425 (U+0425) has a counter-clockwise outer contour

* uni0430 (U+0430) has a counter-clockwise outer contour

* uni0435 (U+0435) has a counter-clockwise outer contour

* uni043E (U+043E) has a counter-clockwise outer contour

* uni0440 (U+0440) has a counter-clockwise outer contour

* uni0441 (U+0441) has a counter-clockwise outer contour

* uni0443 (U+0443) has a counter-clockwise outer contour

* uni0445 (U+0445) has a counter-clockwise outer contour

* uni0450 (U+0450) has a counter-clockwise outer contour

* uni0450 (U+0450) has a counter-clockwise outer contour

* uni0451 (U+0451) has a counter-clockwise outer contour

* uni0455 (U+0455) has a counter-clockwise outer contour

* uni0456 (U+0456) has a counter-clockwise outer contour

* uni0456 (U+0456) has a counter-clockwise outer contour

* uni0457 (U+0457) has a counter-clockwise outer contour

* uni0458 (U+0458) has a counter-clockwise outer contour

* uni0458 (U+0458) has a counter-clockwise outer contour

* uni045E (U+045E) has a counter-clockwise outer contour

* uni045E (U+045E) has a counter-clockwise outer contour

* uni04AE (U+04AE) has a counter-clockwise outer contour

* uni04C0 (U+04C0) has a counter-clockwise outer contour

* uni04D0 (U+04D0) has a counter-clockwise outer contour

* uni04D0 (U+04D0) has a counter-clockwise outer contour

* uni04D1 (U+04D1) has a counter-clockwise outer contour

* uni04D1 (U+04D1) has a counter-clockwise outer contour

* uni04D2 (U+04D2) has a counter-clockwise outer contour

* uni04D3 (U+04D3) has a counter-clockwise outer contour

* uni04D4 (U+04D4) has a counter-clockwise outer contour

* uni04D6 (U+04D6) has a counter-clockwise outer contour

* uni04D6 (U+04D6) has a counter-clockwise outer contour

* uni04D7 (U+04D7) has a counter-clockwise outer contour

* uni04D7 (U+04D7) has a counter-clockwise outer contour

* uni04E6 (U+04E6) has a counter-clockwise outer contour

* uni04E7 (U+04E7) has a counter-clockwise outer contour

* uni04EF (U+04EF) has a counter-clockwise outer contour

* uni04EF (U+04EF) has a counter-clockwise outer contour

* uni04F1 (U+04F1) has a counter-clockwise outer contour

* uni04F3 (U+04F3) has a counter-clockwise outer contour

* uni054F (U+054F) has a counter-clockwise outer contour

* uni0555 (U+0555) has a counter-clockwise outer contour

* uni0570 (U+0570) has a counter-clockwise outer contour

* uni0578 (U+0578) has a counter-clockwise outer contour

* uni057D (U+057D) has a counter-clockwise outer contour

* uni0584 (U+0584) has a counter-clockwise outer contour

* uni0585 (U+0585) has a counter-clockwise outer contour

* uni0589 (U+0589) has a counter-clockwise outer contour

* uni0589 (U+0589) has a counter-clockwise outer contour

* uni066A (U+066A) has a counter-clockwise outer contour

* uni066C (U+066C) has a counter-clockwise outer contour

* uni06D4 (U+06D4) has a counter-clockwise outer contour

* uni13A0 (U+13A0) has a counter-clockwise outer contour

* uni13A1 (U+13A1) has a counter-clockwise outer contour

* uni13A2 (U+13A2) has a counter-clockwise outer contour

* uni13AA (U+13AA) has a counter-clockwise outer contour

* uni13AB (U+13AB) has a counter-clockwise outer contour

* uni13AC (U+13AC) has a counter-clockwise outer contour

* uni13B3 (U+13B3) has a counter-clockwise outer contour

* uni13B7 (U+13B7) has a counter-clockwise outer contour

* uni13BB (U+13BB) has a counter-clockwise outer contour

* uni13C0 (U+13C0) has a counter-clockwise outer contour

* uni13C2 (U+13C2) has a counter-clockwise outer contour

* uni13C3 (U+13C3) has a counter-clockwise outer contour

* uni13D9 (U+13D9) has a counter-clockwise outer contour

* uni13DA (U+13DA) has a counter-clockwise outer contour

* uni13DE (U+13DE) has a counter-clockwise outer contour

* uni13DF (U+13DF) has a counter-clockwise outer contour

* uni13E2 (U+13E2) has a counter-clockwise outer contour

* uni13E6 (U+13E6) has a counter-clockwise outer contour

* uni13F4 (U+13F4) has a counter-clockwise outer contour

* uni1D2C (U+1D2C) has a counter-clockwise outer contour

* uni1D2D (U+1D2D) has a counter-clockwise outer contour

* uni1D2E (U+1D2E) has a counter-clockwise outer contour

* uni1D30 (U+1D30) has a counter-clockwise outer contour

* uni1D31 (U+1D31) has a counter-clockwise outer contour

* uni1D33 (U+1D33) has a counter-clockwise outer contour

* uni1D34 (U+1D34) has a counter-clockwise outer contour

* uni1D35 (U+1D35) has a counter-clockwise outer contour

* uni1D36 (U+1D36) has a counter-clockwise outer contour

* uni1D37 (U+1D37) has a counter-clockwise outer contour

* uni1D38 (U+1D38) has a counter-clockwise outer contour

* uni1D39 (U+1D39) has a counter-clockwise outer contour

* uni1D3A (U+1D3A) has a counter-clockwise outer contour

* uni1D3C (U+1D3C) has a counter-clockwise outer contour

* uni1D3E (U+1D3E) has a counter-clockwise outer contour

* uni1D3F (U+1D3F) has a counter-clockwise outer contour

* uni1D40 (U+1D40) has a counter-clockwise outer contour

* uni1D41 (U+1D41) has a counter-clockwise outer contour

* uni1D42 (U+1D42) has a counter-clockwise outer contour

* uni1D43 (U+1D43) has a counter-clockwise outer contour

* uni1D47 (U+1D47) has a counter-clockwise outer contour

* uni1D48 (U+1D48) has a counter-clockwise outer contour

* uni1D49 (U+1D49) has a counter-clockwise outer contour

* uni1D4D (U+1D4D) has a counter-clockwise outer contour

* uni1D4F (U+1D4F) has a counter-clockwise outer contour

* uni1D50 (U+1D50) has a counter-clockwise outer contour

* uni1D52 (U+1D52) has a counter-clockwise outer contour

* uni1D56 (U+1D56) has a counter-clockwise outer contour

* uni1D57 (U+1D57) has a counter-clockwise outer contour

* uni1D58 (U+1D58) has a counter-clockwise outer contour

* uni1D5B (U+1D5B) has a counter-clockwise outer contour

* uni1D5B (U+1D5B) has a counter-clockwise outer contour

* uni1D5B (U+1D5B) has a path with no bounds (probably a single point)

* uni1D61 (U+1D61) has a counter-clockwise outer contour

* uni1D62 (U+1D62) has a counter-clockwise outer contour

* uni1D62 (U+1D62) has a counter-clockwise outer contour

* uni1D63 (U+1D63) has a counter-clockwise outer contour

* uni1D64 (U+1D64) has a counter-clockwise outer contour

* uni1D65 (U+1D65) has a counter-clockwise outer contour

* uni1D65 (U+1D65) has a counter-clockwise outer contour

* uni1D65 (U+1D65) has a path with no bounds (probably a single point)

* uni1D68 (U+1D68) has a counter-clockwise outer contour

* uni1D6A (U+1D6A) has a counter-clockwise outer contour

* uni1D9C (U+1D9C) has a counter-clockwise outer contour

* uni1DA0 (U+1DA0) has a counter-clockwise outer contour

* uni1DBB (U+1DBB) has a counter-clockwise outer contour

* uni1E02 (U+1E02) has a counter-clockwise outer contour

* uni1E02 (U+1E02) has a counter-clockwise outer contour

* uni1E03 (U+1E03) has a counter-clockwise outer contour

* uni1E03 (U+1E03) has a counter-clockwise outer contour

* uni1E08 (U+1E08) has a counter-clockwise outer contour

* uni1E09 (U+1E09) has a counter-clockwise outer contour

* uni1E0A (U+1E0A) has a counter-clockwise outer contour

* uni1E0A (U+1E0A) has a counter-clockwise outer contour

* uni1E0B (U+1E0B) has a counter-clockwise outer contour

* uni1E0B (U+1E0B) has a counter-clockwise outer contour

* uni1E10 (U+1E10) has a counter-clockwise outer contour

* uni1E10 (U+1E10) has a counter-clockwise outer contour

* uni1E11 (U+1E11) has a counter-clockwise outer contour

* uni1E11 (U+1E11) has a counter-clockwise outer contour

* uni1E14 (U+1E14) has a counter-clockwise outer contour

* uni1E14 (U+1E14) has a counter-clockwise outer contour

* uni1E14 (U+1E14) has a counter-clockwise outer contour

* uni1E15 (U+1E15) has a counter-clockwise outer contour

* uni1E15 (U+1E15) has a counter-clockwise outer contour

* uni1E15 (U+1E15) has a counter-clockwise outer contour

* uni1E16 (U+1E16) has a counter-clockwise outer contour

* uni1E16 (U+1E16) has a counter-clockwise outer contour

* uni1E17 (U+1E17) has a counter-clockwise outer contour

* uni1E17 (U+1E17) has a counter-clockwise outer contour

* uni1E1E (U+1E1E) has a counter-clockwise outer contour

* uni1E1E (U+1E1E) has a counter-clockwise outer contour

* uni1E1F (U+1E1F) has a counter-clockwise outer contour

* uni1E1F (U+1E1F) has a counter-clockwise outer contour

* uni1E20 (U+1E20) has a counter-clockwise outer contour

* uni1E20 (U+1E20) has a counter-clockwise outer contour

* uni1E21 (U+1E21) has a counter-clockwise outer contour

* uni1E21 (U+1E21) has a counter-clockwise outer contour

* uni1E22 (U+1E22) has a counter-clockwise outer contour

* uni1E22 (U+1E22) has a counter-clockwise outer contour

* uni1E23 (U+1E23) has a counter-clockwise outer contour

* uni1E23 (U+1E23) has a counter-clockwise outer contour

* uni1E26 (U+1E26) has a counter-clockwise outer contour

* uni1E27 (U+1E27) has a counter-clockwise outer contour

* uni1E28 (U+1E28) has a counter-clockwise outer contour

* uni1E28 (U+1E28) has a counter-clockwise outer contour

* uni1E29 (U+1E29) has a counter-clockwise outer contour

* uni1E29 (U+1E29) has a counter-clockwise outer contour

* uni1E2E (U+1E2E) has a counter-clockwise outer contour

* uni1E2F (U+1E2F) has a counter-clockwise outer contour

* uni1E2F (U+1E2F) has a counter-clockwise outer contour

* uni1E30 (U+1E30) has a counter-clockwise outer contour

* uni1E31 (U+1E31) has a counter-clockwise outer contour

* uni1E3E (U+1E3E) has a counter-clockwise outer contour

* uni1E3F (U+1E3F) has a counter-clockwise outer contour

* uni1E40 (U+1E40) has a counter-clockwise outer contour

* uni1E40 (U+1E40) has a counter-clockwise outer contour

* uni1E41 (U+1E41) has a counter-clockwise outer contour

* uni1E41 (U+1E41) has a counter-clockwise outer contour

* uni1E44 (U+1E44) has a counter-clockwise outer contour

* uni1E44 (U+1E44) has a counter-clockwise outer contour

* uni1E45 (U+1E45) has a counter-clockwise outer contour

* uni1E45 (U+1E45) has a counter-clockwise outer contour

* uni1E4C (U+1E4C) has a counter-clockwise outer contour

* uni1E4C (U+1E4C) has a counter-clockwise outer contour

* uni1E4D (U+1E4D) has a counter-clockwise outer contour

* uni1E4D (U+1E4D) has a counter-clockwise outer contour

* uni1E4E (U+1E4E) has a counter-clockwise outer contour

* uni1E4E (U+1E4E) has a counter-clockwise outer contour

* uni1E4F (U+1E4F) has a counter-clockwise outer contour

* uni1E4F (U+1E4F) has a counter-clockwise outer contour

* uni1E50 (U+1E50) has a counter-clockwise outer contour

* uni1E50 (U+1E50) has a counter-clockwise outer contour

* uni1E50 (U+1E50) has a counter-clockwise outer contour

* uni1E51 (U+1E51) has a counter-clockwise outer contour

* uni1E51 (U+1E51) has a counter-clockwise outer contour

* uni1E51 (U+1E51) has a counter-clockwise outer contour

* uni1E52 (U+1E52) has a counter-clockwise outer contour

* uni1E52 (U+1E52) has a counter-clockwise outer contour

* uni1E53 (U+1E53) has a counter-clockwise outer contour

* uni1E53 (U+1E53) has a counter-clockwise outer contour

* uni1E54 (U+1E54) has a counter-clockwise outer contour

* uni1E55 (U+1E55) has a counter-clockwise outer contour

* uni1E56 (U+1E56) has a counter-clockwise outer contour

* uni1E56 (U+1E56) has a counter-clockwise outer contour

* uni1E57 (U+1E57) has a counter-clockwise outer contour

* uni1E57 (U+1E57) has a counter-clockwise outer contour

* uni1E58 (U+1E58) has a counter-clockwise outer contour

* uni1E58 (U+1E58) has a counter-clockwise outer contour

* uni1E59 (U+1E59) has a counter-clockwise outer contour

* uni1E59 (U+1E59) has a counter-clockwise outer contour

* uni1E60 (U+1E60) has a counter-clockwise outer contour

* uni1E60 (U+1E60) has a counter-clockwise outer contour

* uni1E61 (U+1E61) has a counter-clockwise outer contour

* uni1E61 (U+1E61) has a counter-clockwise outer contour

* uni1E64 (U+1E64) has a counter-clockwise outer contour

* uni1E64 (U+1E64) has a counter-clockwise outer contour

* uni1E65 (U+1E65) has a counter-clockwise outer contour

* uni1E65 (U+1E65) has a counter-clockwise outer contour

* uni1E66 (U+1E66) has a counter-clockwise outer contour

* uni1E66 (U+1E66) has a counter-clockwise outer contour

* uni1E66 (U+1E66) has a counter-clockwise outer contour

* uni1E67 (U+1E67) has a counter-clockwise outer contour

* uni1E67 (U+1E67) has a counter-clockwise outer contour

* uni1E67 (U+1E67) has a counter-clockwise outer contour

* uni1E6A (U+1E6A) has a counter-clockwise outer contour

* uni1E6A (U+1E6A) has a counter-clockwise outer contour

* uni1E6B (U+1E6B) has a counter-clockwise outer contour

* uni1E6B (U+1E6B) has a counter-clockwise outer contour

* uni1E78 (U+1E78) has a counter-clockwise outer contour

* uni1E78 (U+1E78) has a counter-clockwise outer contour

* uni1E79 (U+1E79) has a counter-clockwise outer contour

* uni1E79 (U+1E79) has a counter-clockwise outer contour

* uni1E7A (U+1E7A) has a counter-clockwise outer contour

* uni1E7A (U+1E7A) has a counter-clockwise outer contour

* uni1E7B (U+1E7B) has a counter-clockwise outer contour

* uni1E7B (U+1E7B) has a counter-clockwise outer contour

* uni1E7C (U+1E7C) has a counter-clockwise outer contour

* uni1E7C (U+1E7C) has a counter-clockwise outer contour

* uni1E7D (U+1E7D) has a counter-clockwise outer contour

* uni1E7D (U+1E7D) has a counter-clockwise outer contour

* uni1E7D (U+1E7D) has a counter-clockwise outer contour

* uni1E7D (U+1E7D) has a path with no bounds (probably a single point)

* uni1E86 (U+1E86) has a counter-clockwise outer contour

* uni1E86 (U+1E86) has a counter-clockwise outer contour

* uni1E87 (U+1E87) has a counter-clockwise outer contour

* uni1E87 (U+1E87) has a counter-clockwise outer contour

* uni1E87 (U+1E87) has a counter-clockwise outer contour

* uni1E87 (U+1E87) has a path with no bounds (probably a single point)

* uni1E8A (U+1E8A) has a counter-clockwise outer contour

* uni1E8A (U+1E8A) has a counter-clockwise outer contour

* uni1E8B (U+1E8B) has a counter-clockwise outer contour

* uni1E8B (U+1E8B) has a counter-clockwise outer contour

* uni1E8C (U+1E8C) has a counter-clockwise outer contour

* uni1E8D (U+1E8D) has a counter-clockwise outer contour

* uni1E8E (U+1E8E) has a counter-clockwise outer contour

* uni1E8E (U+1E8E) has a counter-clockwise outer contour

* uni1E8F (U+1E8F) has a counter-clockwise outer contour

* uni1E8F (U+1E8F) has a counter-clockwise outer contour

* uni1E90 (U+1E90) has a counter-clockwise outer contour

* uni1E90 (U+1E90) has a counter-clockwise outer contour

* uni1E91 (U+1E91) has a counter-clockwise outer contour

* uni1E91 (U+1E91) has a counter-clockwise outer contour

* uni1E97 (U+1E97) has a counter-clockwise outer contour

* uni1E98 (U+1E98) has a counter-clockwise outer contour

* uni1E98 (U+1E98) has a counter-clockwise outer contour

* uni1E98 (U+1E98) has a counter-clockwise outer contour

* uni1E98 (U+1E98) has a path with no bounds (probably a single point)

* uni1E99 (U+1E99) has a counter-clockwise outer contour

* uni1E99 (U+1E99) has a counter-clockwise outer contour

* uni1E9B (U+1E9B) has a counter-clockwise outer contour

* uni1E9B (U+1E9B) has a counter-clockwise outer contour

* uni1EA2 (U+1EA2) has a counter-clockwise outer contour

* uni1EA2 (U+1EA2) has a counter-clockwise outer contour

* uni1EA3 (U+1EA3) has a counter-clockwise outer contour

* uni1EA3 (U+1EA3) has a counter-clockwise outer contour

* uni1EA4 (U+1EA4) has a counter-clockwise outer contour

* uni1EA4 (U+1EA4) has a counter-clockwise outer contour

* uni1EA5 (U+1EA5) has a counter-clockwise outer contour

* uni1EA5 (U+1EA5) has a counter-clockwise outer contour

* uni1EA6 (U+1EA6) has a counter-clockwise outer contour

* uni1EA6 (U+1EA6) has a counter-clockwise outer contour

* uni1EA6 (U+1EA6) has a counter-clockwise outer contour

* uni1EA7 (U+1EA7) has a counter-clockwise outer contour

* uni1EA7 (U+1EA7) has a counter-clockwise outer contour

* uni1EA7 (U+1EA7) has a counter-clockwise outer contour

* uni1EA8 (U+1EA8) has a counter-clockwise outer contour

* uni1EA8 (U+1EA8) has a counter-clockwise outer contour

* uni1EA8 (U+1EA8) has a counter-clockwise outer contour

* uni1EA9 (U+1EA9) has a counter-clockwise outer contour

* uni1EA9 (U+1EA9) has a counter-clockwise outer contour

* uni1EA9 (U+1EA9) has a counter-clockwise outer contour

* uni1EAA (U+1EAA) has a counter-clockwise outer contour

* uni1EAA (U+1EAA) has a counter-clockwise outer contour

* uni1EAA (U+1EAA) has a counter-clockwise outer contour

* uni1EAB (U+1EAB) has a counter-clockwise outer contour

* uni1EAB (U+1EAB) has a counter-clockwise outer contour

* uni1EAB (U+1EAB) has a counter-clockwise outer contour

* uni1EAE (U+1EAE) has a counter-clockwise outer contour

* uni1EAE (U+1EAE) has a counter-clockwise outer contour

* uni1EAF (U+1EAF) has a counter-clockwise outer contour

* uni1EAF (U+1EAF) has a counter-clockwise outer contour

* uni1EB0 (U+1EB0) has a counter-clockwise outer contour

* uni1EB0 (U+1EB0) has a counter-clockwise outer contour

* uni1EB0 (U+1EB0) has a counter-clockwise outer contour

* uni1EB1 (U+1EB1) has a counter-clockwise outer contour

* uni1EB1 (U+1EB1) has a counter-clockwise outer contour

* uni1EB1 (U+1EB1) has a counter-clockwise outer contour

* uni1EB2 (U+1EB2) has a counter-clockwise outer contour

* uni1EB2 (U+1EB2) has a counter-clockwise outer contour

* uni1EB2 (U+1EB2) has a counter-clockwise outer contour

* uni1EB3 (U+1EB3) has a counter-clockwise outer contour

* uni1EB3 (U+1EB3) has a counter-clockwise outer contour

* uni1EB3 (U+1EB3) has a counter-clockwise outer contour

* uni1EB4 (U+1EB4) has a counter-clockwise outer contour

* uni1EB4 (U+1EB4) has a counter-clockwise outer contour

* uni1EB4 (U+1EB4) has a counter-clockwise outer contour

* uni1EB5 (U+1EB5) has a counter-clockwise outer contour

* uni1EB5 (U+1EB5) has a counter-clockwise outer contour

* uni1EB5 (U+1EB5) has a counter-clockwise outer contour

* uni1EBA (U+1EBA) has a counter-clockwise outer contour

* uni1EBA (U+1EBA) has a counter-clockwise outer contour

* uni1EBB (U+1EBB) has a counter-clockwise outer contour

* uni1EBB (U+1EBB) has a counter-clockwise outer contour

* uni1EBC (U+1EBC) has a counter-clockwise outer contour

* uni1EBC (U+1EBC) has a counter-clockwise outer contour

* uni1EBD (U+1EBD) has a counter-clockwise outer contour

* uni1EBD (U+1EBD) has a counter-clockwise outer contour

* uni1EBE (U+1EBE) has a counter-clockwise outer contour

* uni1EBE (U+1EBE) has a counter-clockwise outer contour

* uni1EBF (U+1EBF) has a counter-clockwise outer contour

* uni1EBF (U+1EBF) has a counter-clockwise outer contour

* uni1EC0 (U+1EC0) has a counter-clockwise outer contour

* uni1EC0 (U+1EC0) has a counter-clockwise outer contour

* uni1EC0 (U+1EC0) has a counter-clockwise outer contour

* uni1EC1 (U+1EC1) has a counter-clockwise outer contour

* uni1EC1 (U+1EC1) has a counter-clockwise outer contour

* uni1EC1 (U+1EC1) has a counter-clockwise outer contour

* uni1EC2 (U+1EC2) has a counter-clockwise outer contour

* uni1EC2 (U+1EC2) has a counter-clockwise outer contour

* uni1EC2 (U+1EC2) has a counter-clockwise outer contour

* uni1EC3 (U+1EC3) has a counter-clockwise outer contour

* uni1EC3 (U+1EC3) has a counter-clockwise outer contour

* uni1EC3 (U+1EC3) has a counter-clockwise outer contour

* uni1EC4 (U+1EC4) has a counter-clockwise outer contour

* uni1EC4 (U+1EC4) has a counter-clockwise outer contour

* uni1EC4 (U+1EC4) has a counter-clockwise outer contour

* uni1EC5 (U+1EC5) has a counter-clockwise outer contour

* uni1EC5 (U+1EC5) has a counter-clockwise outer contour

* uni1EC5 (U+1EC5) has a counter-clockwise outer contour

* uni1EC8 (U+1EC8) has a counter-clockwise outer contour

* uni1EC8 (U+1EC8) has a counter-clockwise outer contour

* uni1EC9 (U+1EC9) has a counter-clockwise outer contour

* uni1EC9 (U+1EC9) has a counter-clockwise outer contour

* uni1ECE (U+1ECE) has a counter-clockwise outer contour

* uni1ECE (U+1ECE) has a counter-clockwise outer contour

* uni1ECF (U+1ECF) has a counter-clockwise outer contour

* uni1ECF (U+1ECF) has a counter-clockwise outer contour

* uni1ED0 (U+1ED0) has a counter-clockwise outer contour

* uni1ED0 (U+1ED0) has a counter-clockwise outer contour

* uni1ED1 (U+1ED1) has a counter-clockwise outer contour

* uni1ED1 (U+1ED1) has a counter-clockwise outer contour

* uni1ED2 (U+1ED2) has a counter-clockwise outer contour

* uni1ED2 (U+1ED2) has a counter-clockwise outer contour

* uni1ED2 (U+1ED2) has a counter-clockwise outer contour

* uni1ED3 (U+1ED3) has a counter-clockwise outer contour

* uni1ED3 (U+1ED3) has a counter-clockwise outer contour

* uni1ED3 (U+1ED3) has a counter-clockwise outer contour

* uni1ED4 (U+1ED4) has a counter-clockwise outer contour

* uni1ED4 (U+1ED4) has a counter-clockwise outer contour

* uni1ED4 (U+1ED4) has a counter-clockwise outer contour

* uni1ED5 (U+1ED5) has a counter-clockwise outer contour

* uni1ED5 (U+1ED5) has a counter-clockwise outer contour

* uni1ED5 (U+1ED5) has a counter-clockwise outer contour

* uni1ED6 (U+1ED6) has a counter-clockwise outer contour

* uni1ED6 (U+1ED6) has a counter-clockwise outer contour

* uni1ED6 (U+1ED6) has a counter-clockwise outer contour

* uni1ED7 (U+1ED7) has a counter-clockwise outer contour

* uni1ED7 (U+1ED7) has a counter-clockwise outer contour

* uni1ED7 (U+1ED7) has a counter-clockwise outer contour

* uni1EDA (U+1EDA) has a counter-clockwise outer contour

* uni1EDB (U+1EDB) has a counter-clockwise outer contour

* uni1EDB (U+1EDB) has a counter-clockwise outer contour

* uni1EDC (U+1EDC) has a counter-clockwise outer contour

* uni1EDC (U+1EDC) has a counter-clockwise outer contour

* uni1EDD (U+1EDD) has a counter-clockwise outer contour

* uni1EDD (U+1EDD) has a counter-clockwise outer contour

* uni1EDD (U+1EDD) has a counter-clockwise outer contour

* uni1EDE (U+1EDE) has a counter-clockwise outer contour

* uni1EDE (U+1EDE) has a counter-clockwise outer contour

* uni1EDF (U+1EDF) has a counter-clockwise outer contour

* uni1EDF (U+1EDF) has a counter-clockwise outer contour

* uni1EDF (U+1EDF) has a counter-clockwise outer contour

* uni1EE0 (U+1EE0) has a counter-clockwise outer contour

* uni1EE0 (U+1EE0) has a counter-clockwise outer contour

* uni1EE1 (U+1EE1) has a counter-clockwise outer contour

* uni1EE1 (U+1EE1) has a counter-clockwise outer contour

* uni1EE1 (U+1EE1) has a counter-clockwise outer contour

* uni1EE6 (U+1EE6) has a counter-clockwise outer contour

* uni1EE6 (U+1EE6) has a counter-clockwise outer contour

* uni1EE7 (U+1EE7) has a counter-clockwise outer contour

* uni1EE7 (U+1EE7) has a counter-clockwise outer contour

* uni1EE8 (U+1EE8) has a counter-clockwise outer contour

* uni1EE9 (U+1EE9) has a counter-clockwise outer contour

* uni1EE9 (U+1EE9) has a counter-clockwise outer contour

* uni1EEA (U+1EEA) has a counter-clockwise outer contour

* uni1EEA (U+1EEA) has a counter-clockwise outer contour

* uni1EEB (U+1EEB) has a counter-clockwise outer contour

* uni1EEB (U+1EEB) has a counter-clockwise outer contour

* uni1EEB (U+1EEB) has a counter-clockwise outer contour

* uni1EEC (U+1EEC) has a counter-clockwise outer contour

* uni1EEC (U+1EEC) has a counter-clockwise outer contour

* uni1EED (U+1EED) has a counter-clockwise outer contour

* uni1EED (U+1EED) has a counter-clockwise outer contour

* uni1EED (U+1EED) has a counter-clockwise outer contour

* uni1EEE (U+1EEE) has a counter-clockwise outer contour

* uni1EEE (U+1EEE) has a counter-clockwise outer contour

* uni1EEF (U+1EEF) has a counter-clockwise outer contour

* uni1EEF (U+1EEF) has a counter-clockwise outer contour

* uni1EEF (U+1EEF) has a counter-clockwise outer contour

* uni1EF6 (U+1EF6) has a counter-clockwise outer contour

* uni1EF6 (U+1EF6) has a counter-clockwise outer contour

* uni1EF7 (U+1EF7) has a counter-clockwise outer contour

* uni1EF7 (U+1EF7) has a counter-clockwise outer contour

* uni1EF8 (U+1EF8) has a counter-clockwise outer contour

* uni1EF8 (U+1EF8) has a counter-clockwise outer contour

* uni1EF9 (U+1EF9) has a counter-clockwise outer contour

* uni1EF9 (U+1EF9) has a counter-clockwise outer contour

* uni1F78 (U+1F78) has a counter-clockwise outer contour

* uni1F78 (U+1F78) has a counter-clockwise outer contour

* uni1FB8 (U+1FB8) has a counter-clockwise outer contour

* uni1FB8 (U+1FB8) has a counter-clockwise outer contour

* uni1FB9 (U+1FB9) has a counter-clockwise outer contour

* uni1FB9 (U+1FB9) has a counter-clockwise outer contour

* uni1FBA (U+1FBA) has a counter-clockwise outer contour

* uni1FBA (U+1FBA) has a counter-clockwise outer contour

* uni1FC8 (U+1FC8) has a counter-clockwise outer contour

* uni1FC8 (U+1FC8) has a counter-clockwise outer contour

* uni1FCA (U+1FCA) has a counter-clockwise outer contour

* uni1FD8 (U+1FD8) has a counter-clockwise outer contour

* uni1FD8 (U+1FD8) has a counter-clockwise outer contour

* uni1FD9 (U+1FD9) has a counter-clockwise outer contour

* uni1FD9 (U+1FD9) has a counter-clockwise outer contour

* uni1FDA (U+1FDA) has a counter-clockwise outer contour

* uni1FDA (U+1FDA) has a counter-clockwise outer contour

* uni1FE8 (U+1FE8) has a counter-clockwise outer contour

* uni1FE8 (U+1FE8) has a counter-clockwise outer contour

* uni1FE9 (U+1FE9) has a counter-clockwise outer contour

* uni1FE9 (U+1FE9) has a counter-clockwise outer contour

* uni1FEA (U+1FEA) has a counter-clockwise outer contour

* uni1FED (U+1FED) has a counter-clockwise outer contour

* uni1FEF (U+1FEF) has a counter-clockwise outer contour

* uni1FF8 (U+1FF8) has a counter-clockwise outer contour

* uni2010 (U+2010) has a counter-clockwise outer contour

* uni2011 (U+2011) has a counter-clockwise outer contour

* uni2015 (U+2015) has a counter-clockwise outer contour

* uni2016 (U+2016) has a counter-clockwise outer contour

* uni2016 (U+2016) has a counter-clockwise outer contour

* uni2016 (U+2016) has a counter-clockwise outer contour

* uni2016 (U+2016) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2034 (U+2034) has a counter-clockwise outer contour

* uni2035 (U+2035) has a counter-clockwise outer contour

* uni2036 (U+2036) has a counter-clockwise outer contour

* uni2036 (U+2036) has a counter-clockwise outer contour

* uni2037 (U+2037) has a counter-clockwise outer contour

* uni2037 (U+2037) has a counter-clockwise outer contour

* uni2037 (U+2037) has a counter-clockwise outer contour

* uni203E (U+203E) has a counter-clockwise outer contour

* uni2047 (U+2047) has a counter-clockwise outer contour

* uni2047 (U+2047) has a counter-clockwise outer contour

* uni2047 (U+2047) has a counter-clockwise outer contour

* uni2047 (U+2047) has a counter-clockwise outer contour

* uni2048 (U+2048) has a counter-clockwise outer contour

* uni2048 (U+2048) has a counter-clockwise outer contour

* uni2048 (U+2048) has a counter-clockwise outer contour

* uni2048 (U+2048) has a counter-clockwise outer contour

* uni2049 (U+2049) has a counter-clockwise outer contour

* uni2049 (U+2049) has a counter-clockwise outer contour

* uni2049 (U+2049) has a counter-clockwise outer contour

* uni2049 (U+2049) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2057 (U+2057) has a counter-clockwise outer contour

* uni2070 (U+2070) has a counter-clockwise outer contour

* uni2071 (U+2071) has a counter-clockwise outer contour

* uni2071 (U+2071) has a counter-clockwise outer contour

* uni2074 (U+2074) has a counter-clockwise outer contour

* uni2075 (U+2075) has a counter-clockwise outer contour

* uni2076 (U+2076) has a counter-clockwise outer contour

* uni2077 (U+2077) has a counter-clockwise outer contour

* uni2078 (U+2078) has a counter-clockwise outer contour

* uni2079 (U+2079) has a counter-clockwise outer contour

* uni207A (U+207A) has a counter-clockwise outer contour

* uni207C (U+207C) has a counter-clockwise outer contour

* uni207C (U+207C) has a counter-clockwise outer contour

* uni207D (U+207D) has a counter-clockwise outer contour

* uni207E (U+207E) has a counter-clockwise outer contour

* uni207F (U+207F) has a counter-clockwise outer contour

* uni2080 (U+2080) has a counter-clockwise outer contour

* uni2081 (U+2081) has a counter-clockwise outer contour

* uni2082 (U+2082) has a counter-clockwise outer contour

* uni2083 (U+2083) has a counter-clockwise outer contour

* uni2084 (U+2084) has a counter-clockwise outer contour

* uni2085 (U+2085) has a counter-clockwise outer contour

* uni2086 (U+2086) has a counter-clockwise outer contour

* uni2087 (U+2087) has a counter-clockwise outer contour

* uni2088 (U+2088) has a counter-clockwise outer contour

* uni2089 (U+2089) has a counter-clockwise outer contour

* uni208A (U+208A) has a counter-clockwise outer contour

* uni208C (U+208C) has a counter-clockwise outer contour

* uni208C (U+208C) has a counter-clockwise outer contour

* uni208D (U+208D) has a counter-clockwise outer contour

* uni208E (U+208E) has a counter-clockwise outer contour

* uni2090 (U+2090) has a counter-clockwise outer contour

* uni2091 (U+2091) has a counter-clockwise outer contour

* uni2092 (U+2092) has a counter-clockwise outer contour

* uni2093 (U+2093) has a counter-clockwise outer contour

* uni2095 (U+2095) has a counter-clockwise outer contour

* uni2096 (U+2096) has a counter-clockwise outer contour

* uni2097 (U+2097) has a counter-clockwise outer contour

* uni2098 (U+2098) has a counter-clockwise outer contour

* uni2099 (U+2099) has a counter-clockwise outer contour

* uni209A (U+209A) has a counter-clockwise outer contour

* uni209B (U+209B) has a counter-clockwise outer contour

* uni209C (U+209C) has a counter-clockwise outer contour

* uni20A8 (U+20A8) has a counter-clockwise outer contour

* uni20A8 (U+20A8) has a counter-clockwise outer contour

* uni2100 (U+2100) has a counter-clockwise outer contour

* uni2100 (U+2100) has a counter-clockwise outer contour

* uni2100 (U+2100) has a counter-clockwise outer contour

* uni2101 (U+2101) has a counter-clockwise outer contour

* uni2101 (U+2101) has a counter-clockwise outer contour

* uni2101 (U+2101) has a counter-clockwise outer contour

* uni2102 (U+2102) has a counter-clockwise outer contour

* uni2103 (U+2103) has a counter-clockwise outer contour

* uni2103 (U+2103) has a counter-clockwise outer contour

* uni2105 (U+2105) has a counter-clockwise outer contour

* uni2105 (U+2105) has a counter-clockwise outer contour

* uni2105 (U+2105) has a counter-clockwise outer contour

* uni2106 (U+2106) has a counter-clockwise outer contour

* uni2106 (U+2106) has a counter-clockwise outer contour

* uni2106 (U+2106) has a counter-clockwise outer contour

* uni2109 (U+2109) has a counter-clockwise outer contour

* uni2109 (U+2109) has a counter-clockwise outer contour

* uni210A (U+210A) has a counter-clockwise outer contour

* uni210B (U+210B) has a counter-clockwise outer contour

* uni210C (U+210C) has a counter-clockwise outer contour

* uni210D (U+210D) has a counter-clockwise outer contour

* uni210E (U+210E) has a counter-clockwise outer contour

* uni2110 (U+2110) has a counter-clockwise outer contour

* uni2112 (U+2112) has a counter-clockwise outer contour

* uni2113 (U+2113) has a counter-clockwise outer contour

* uni2115 (U+2115) has a counter-clockwise outer contour

* uni2116 (U+2116) has a counter-clockwise outer contour

* uni2116 (U+2116) has a counter-clockwise outer contour

* uni2119 (U+2119) has a counter-clockwise outer contour

* uni211A (U+211A) has a counter-clockwise outer contour

* uni211B (U+211B) has a counter-clockwise outer contour

* uni211D (U+211D) has a counter-clockwise outer contour

* uni2120 (U+2120) has a counter-clockwise outer contour

* uni2120 (U+2120) has a counter-clockwise outer contour

* uni2121 (U+2121) has a counter-clockwise outer contour

* uni2121 (U+2121) has a counter-clockwise outer contour

* uni2121 (U+2121) has a counter-clockwise outer contour

* uni2124 (U+2124) has a counter-clockwise outer contour

* uni2128 (U+2128) has a counter-clockwise outer contour

* uni212A (U+212A) has a counter-clockwise outer contour

* uni212B (U+212B) has a counter-clockwise outer contour

* uni212B (U+212B) has a counter-clockwise outer contour

* uni212C (U+212C) has a counter-clockwise outer contour

* uni212D (U+212D) has a counter-clockwise outer contour

* uni212F (U+212F) has a counter-clockwise outer contour

* uni2130 (U+2130) has a counter-clockwise outer contour

* uni2131 (U+2131) has a counter-clockwise outer contour

* uni2133 (U+2133) has a counter-clockwise outer contour

* uni2134 (U+2134) has a counter-clockwise outer contour

* uni2139 (U+2139) has a counter-clockwise outer contour

* uni2139 (U+2139) has a counter-clockwise outer contour

* uni213B (U+213B) has a counter-clockwise outer contour

* uni213B (U+213B) has a counter-clockwise outer contour

* uni213B (U+213B) has a counter-clockwise outer contour

* uni2145 (U+2145) has a counter-clockwise outer contour

* uni2146 (U+2146) has a counter-clockwise outer contour

* uni2147 (U+2147) has a counter-clockwise outer contour

* uni2148 (U+2148) has a counter-clockwise outer contour

* uni2148 (U+2148) has a counter-clockwise outer contour

* uni2149 (U+2149) has a counter-clockwise outer contour

* uni2149 (U+2149) has a counter-clockwise outer contour

* uni2160 (U+2160) has a counter-clockwise outer contour

* uni2161 (U+2161) has a counter-clockwise outer contour

* uni2161 (U+2161) has a counter-clockwise outer contour

* uni2162 (U+2162) has a counter-clockwise outer contour

* uni2162 (U+2162) has a counter-clockwise outer contour

* uni2162 (U+2162) has a counter-clockwise outer contour

* uni2163 (U+2163) has a counter-clockwise outer contour

* uni2163 (U+2163) has a counter-clockwise outer contour

* uni2164 (U+2164) has a counter-clockwise outer contour

* uni2165 (U+2165) has a counter-clockwise outer contour

* uni2165 (U+2165) has a counter-clockwise outer contour

* uni2166 (U+2166) has a counter-clockwise outer contour

* uni2166 (U+2166) has a counter-clockwise outer contour

* uni2166 (U+2166) has a counter-clockwise outer contour

* uni2167 (U+2167) has a counter-clockwise outer contour

* uni2167 (U+2167) has a counter-clockwise outer contour

* uni2167 (U+2167) has a counter-clockwise outer contour

* uni2167 (U+2167) has a counter-clockwise outer contour

* uni2168 (U+2168) has a counter-clockwise outer contour

* uni2168 (U+2168) has a counter-clockwise outer contour

* uni2169 (U+2169) has a counter-clockwise outer contour

* uni216A (U+216A) has a counter-clockwise outer contour

* uni216A (U+216A) has a counter-clockwise outer contour

* uni216B (U+216B) has a counter-clockwise outer contour

* uni216B (U+216B) has a counter-clockwise outer contour

* uni216B (U+216B) has a counter-clockwise outer contour

* uni216C (U+216C) has a counter-clockwise outer contour

* uni216D (U+216D) has a counter-clockwise outer contour

* uni216E (U+216E) has a counter-clockwise outer contour

* uni216F (U+216F) has a counter-clockwise outer contour

* uni2170 (U+2170) has a counter-clockwise outer contour

* uni2170 (U+2170) has a counter-clockwise outer contour

* uni2171 (U+2171) has a counter-clockwise outer contour

* uni2171 (U+2171) has a counter-clockwise outer contour

* uni2171 (U+2171) has a counter-clockwise outer contour

* uni2171 (U+2171) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2172 (U+2172) has a counter-clockwise outer contour

* uni2173 (U+2173) has a counter-clockwise outer contour

* uni2173 (U+2173) has a counter-clockwise outer contour

* uni2173 (U+2173) has a counter-clockwise outer contour

* uni2173 (U+2173) has a counter-clockwise outer contour

* uni2173 (U+2173) has a path with no bounds (probably a single point)

* uni2174 (U+2174) has a counter-clockwise outer contour

* uni2174 (U+2174) has a counter-clockwise outer contour

* uni2174 (U+2174) has a path with no bounds (probably a single point)

* uni2175 (U+2175) has a counter-clockwise outer contour

* uni2175 (U+2175) has a counter-clockwise outer contour

* uni2175 (U+2175) has a counter-clockwise outer contour

* uni2175 (U+2175) has a counter-clockwise outer contour

* uni2175 (U+2175) has a path with no bounds (probably a single point)

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a counter-clockwise outer contour

* uni2176 (U+2176) has a path with no bounds (probably a single point)

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a counter-clockwise outer contour

* uni2177 (U+2177) has a path with no bounds (probably a single point)

* uni2178 (U+2178) has a counter-clockwise outer contour

* uni2178 (U+2178) has a counter-clockwise outer contour

* uni2178 (U+2178) has a counter-clockwise outer contour

* uni2179 (U+2179) has a counter-clockwise outer contour

* uni217A (U+217A) has a counter-clockwise outer contour

* uni217A (U+217A) has a counter-clockwise outer contour

* uni217A (U+217A) has a counter-clockwise outer contour

* uni217B (U+217B) has a counter-clockwise outer contour

* uni217B (U+217B) has a counter-clockwise outer contour

* uni217B (U+217B) has a counter-clockwise outer contour

* uni217B (U+217B) has a counter-clockwise outer contour

* uni217B (U+217B) has a counter-clockwise outer contour

* uni217C (U+217C) has a counter-clockwise outer contour

* uni217D (U+217D) has a counter-clockwise outer contour

* uni217E (U+217E) has a counter-clockwise outer contour

* uni217F (U+217F) has a counter-clockwise outer contour

* uni2215 (U+2215) has a counter-clockwise outer contour

* uni2216 (U+2216) has a counter-clockwise outer contour

* uni2218 (U+2218) has a counter-clockwise outer contour

* uni2219 (U+2219) has a counter-clockwise outer contour

* uni2223 (U+2223) has a counter-clockwise outer contour

* uni2223 (U+2223) has a counter-clockwise outer contour

* uni2225 (U+2225) has a counter-clockwise outer contour

* uni2225 (U+2225) has a counter-clockwise outer contour

* uni2225 (U+2225) has a counter-clockwise outer contour

* uni2225 (U+2225) has a counter-clockwise outer contour

* uni2236 (U+2236) has a counter-clockwise outer contour

* uni2236 (U+2236) has a counter-clockwise outer contour

* uni226A (U+226A) has a counter-clockwise outer contour

* uni226A (U+226A) has a counter-clockwise outer contour

* uni226B (U+226B) has a counter-clockwise outer contour

* uni226B (U+226B) has a counter-clockwise outer contour

* uni22EF (U+22EF) has a counter-clockwise outer contour

* uni22EF (U+22EF) has a counter-clockwise outer contour

* uni22EF (U+22EF) has a counter-clockwise outer contour

* uni2303 (U+2303) has a counter-clockwise outer contour

* uni2374 (U+2374) has a counter-clockwise outer contour

* uni2400 (U+2400) has a counter-clockwise outer contour

* uni2400 (U+2400) has a counter-clockwise outer contour

* uni2400 (U+2400) has a counter-clockwise outer contour

* uni2401 (U+2401) has a counter-clockwise outer contour

* uni2401 (U+2401) has a counter-clockwise outer contour

* uni2401 (U+2401) has a counter-clockwise outer contour

* uni2402 (U+2402) has a counter-clockwise outer contour

* uni2402 (U+2402) has a counter-clockwise outer contour

* uni2402 (U+2402) has a counter-clockwise outer contour

* uni2403 (U+2403) has a counter-clockwise outer contour

* uni2403 (U+2403) has a counter-clockwise outer contour

* uni2403 (U+2403) has a counter-clockwise outer contour

* uni2404 (U+2404) has a counter-clockwise outer contour

* uni2404 (U+2404) has a counter-clockwise outer contour

* uni2404 (U+2404) has a counter-clockwise outer contour

* uni2405 (U+2405) has a counter-clockwise outer contour

* uni2405 (U+2405) has a counter-clockwise outer contour

* uni2405 (U+2405) has a counter-clockwise outer contour

* uni2406 (U+2406) has a counter-clockwise outer contour

* uni2406 (U+2406) has a counter-clockwise outer contour

* uni2406 (U+2406) has a counter-clockwise outer contour

* uni2407 (U+2407) has a counter-clockwise outer contour

* uni2407 (U+2407) has a counter-clockwise outer contour

* uni2407 (U+2407) has a counter-clockwise outer contour

* uni2408 (U+2408) has a counter-clockwise outer contour

* uni2408 (U+2408) has a counter-clockwise outer contour

* uni2409 (U+2409) has a counter-clockwise outer contour

* uni2409 (U+2409) has a counter-clockwise outer contour

* uni240A (U+240A) has a counter-clockwise outer contour

* uni240A (U+240A) has a counter-clockwise outer contour

* uni240B (U+240B) has a counter-clockwise outer contour

* uni240B (U+240B) has a counter-clockwise outer contour

* uni240C (U+240C) has a counter-clockwise outer contour

* uni240C (U+240C) has a counter-clockwise outer contour

* uni240D (U+240D) has a counter-clockwise outer contour

* uni240D (U+240D) has a counter-clockwise outer contour

* uni240E (U+240E) has a counter-clockwise outer contour

* uni240E (U+240E) has a counter-clockwise outer contour

* uni240F (U+240F) has a counter-clockwise outer contour

* uni240F (U+240F) has a counter-clockwise outer contour

* uni2410 (U+2410) has a counter-clockwise outer contour

* uni2410 (U+2410) has a counter-clockwise outer contour

* uni2410 (U+2410) has a counter-clockwise outer contour

* uni2411 (U+2411) has a counter-clockwise outer contour

* uni2411 (U+2411) has a counter-clockwise outer contour

* uni2411 (U+2411) has a counter-clockwise outer contour

* uni2412 (U+2412) has a counter-clockwise outer contour

* uni2412 (U+2412) has a counter-clockwise outer contour

* uni2412 (U+2412) has a counter-clockwise outer contour

* uni2413 (U+2413) has a counter-clockwise outer contour

* uni2413 (U+2413) has a counter-clockwise outer contour

* uni2413 (U+2413) has a counter-clockwise outer contour

* uni2414 (U+2414) has a counter-clockwise outer contour

* uni2414 (U+2414) has a counter-clockwise outer contour

* uni2414 (U+2414) has a counter-clockwise outer contour

* uni2415 (U+2415) has a counter-clockwise outer contour

* uni2415 (U+2415) has a counter-clockwise outer contour

* uni2415 (U+2415) has a counter-clockwise outer contour

* uni2416 (U+2416) has a counter-clockwise outer contour

* uni2416 (U+2416) has a counter-clockwise outer contour

* uni2416 (U+2416) has a counter-clockwise outer contour

* uni2417 (U+2417) has a counter-clockwise outer contour

* uni2417 (U+2417) has a counter-clockwise outer contour

* uni2417 (U+2417) has a counter-clockwise outer contour

* uni2418 (U+2418) has a counter-clockwise outer contour

* uni2418 (U+2418) has a counter-clockwise outer contour

* uni2418 (U+2418) has a counter-clockwise outer contour

* uni2419 (U+2419) has a counter-clockwise outer contour

* uni2419 (U+2419) has a counter-clockwise outer contour

* uni241A (U+241A) has a counter-clockwise outer contour

* uni241A (U+241A) has a counter-clockwise outer contour

* uni241A (U+241A) has a counter-clockwise outer contour

* uni241B (U+241B) has a counter-clockwise outer contour

* uni241B (U+241B) has a counter-clockwise outer contour

* uni241B (U+241B) has a counter-clockwise outer contour

* uni241C (U+241C) has a counter-clockwise outer contour

* uni241C (U+241C) has a counter-clockwise outer contour

* uni241D (U+241D) has a counter-clockwise outer contour

* uni241D (U+241D) has a counter-clockwise outer contour

* uni241E (U+241E) has a counter-clockwise outer contour

* uni241E (U+241E) has a counter-clockwise outer contour

* uni241F (U+241F) has a counter-clockwise outer contour

* uni241F (U+241F) has a counter-clockwise outer contour

* uni2420 (U+2420) has a counter-clockwise outer contour

* uni2420 (U+2420) has a counter-clockwise outer contour

* uni2421 (U+2421) has a counter-clockwise outer contour

* uni2421 (U+2421) has a counter-clockwise outer contour

* uni2421 (U+2421) has a counter-clockwise outer contour

* uni2474 (U+2474) has a counter-clockwise outer contour

* uni2474 (U+2474) has a counter-clockwise outer contour

* uni2474 (U+2474) has a counter-clockwise outer contour

* uni2475 (U+2475) has a counter-clockwise outer contour

* uni2475 (U+2475) has a counter-clockwise outer contour

* uni2475 (U+2475) has a counter-clockwise outer contour

* uni2476 (U+2476) has a counter-clockwise outer contour

* uni2476 (U+2476) has a counter-clockwise outer contour

* uni2476 (U+2476) has a counter-clockwise outer contour

* uni2477 (U+2477) has a counter-clockwise outer contour

* uni2477 (U+2477) has a counter-clockwise outer contour

* uni2477 (U+2477) has a counter-clockwise outer contour

* uni2478 (U+2478) has a counter-clockwise outer contour

* uni2478 (U+2478) has a counter-clockwise outer contour

* uni2478 (U+2478) has a counter-clockwise outer contour

* uni2479 (U+2479) has a counter-clockwise outer contour

* uni2479 (U+2479) has a counter-clockwise outer contour

* uni2479 (U+2479) has a counter-clockwise outer contour

* uni247A (U+247A) has a counter-clockwise outer contour

* uni247A (U+247A) has a counter-clockwise outer contour

* uni247A (U+247A) has a counter-clockwise outer contour

* uni247B (U+247B) has a counter-clockwise outer contour

* uni247B (U+247B) has a counter-clockwise outer contour

* uni247B (U+247B) has a counter-clockwise outer contour

* uni247C (U+247C) has a counter-clockwise outer contour

* uni247C (U+247C) has a counter-clockwise outer contour

* uni247C (U+247C) has a counter-clockwise outer contour

* uni247D (U+247D) has a counter-clockwise outer contour

* uni247D (U+247D) has a counter-clockwise outer contour

* uni247D (U+247D) has a counter-clockwise outer contour

* uni247D (U+247D) has a counter-clockwise outer contour

* uni247E (U+247E) has a counter-clockwise outer contour

* uni247E (U+247E) has a counter-clockwise outer contour

* uni247E (U+247E) has a counter-clockwise outer contour

* uni247E (U+247E) has a counter-clockwise outer contour

* uni247F (U+247F) has a counter-clockwise outer contour

* uni247F (U+247F) has a counter-clockwise outer contour

* uni247F (U+247F) has a counter-clockwise outer contour

* uni247F (U+247F) has a counter-clockwise outer contour

* uni2480 (U+2480) has a counter-clockwise outer contour

* uni2480 (U+2480) has a counter-clockwise outer contour

* uni2480 (U+2480) has a counter-clockwise outer contour

* uni2480 (U+2480) has a counter-clockwise outer contour

* uni2481 (U+2481) has a counter-clockwise outer contour

* uni2481 (U+2481) has a counter-clockwise outer contour

* uni2481 (U+2481) has a counter-clockwise outer contour

* uni2481 (U+2481) has a counter-clockwise outer contour

* uni2482 (U+2482) has a counter-clockwise outer contour

* uni2482 (U+2482) has a counter-clockwise outer contour

* uni2482 (U+2482) has a counter-clockwise outer contour

* uni2482 (U+2482) has a counter-clockwise outer contour

* uni2483 (U+2483) has a counter-clockwise outer contour

* uni2483 (U+2483) has a counter-clockwise outer contour

* uni2483 (U+2483) has a counter-clockwise outer contour

* uni2483 (U+2483) has a counter-clockwise outer contour

* uni2484 (U+2484) has a counter-clockwise outer contour

* uni2484 (U+2484) has a counter-clockwise outer contour

* uni2484 (U+2484) has a counter-clockwise outer contour

* uni2484 (U+2484) has a counter-clockwise outer contour

* uni2485 (U+2485) has a counter-clockwise outer contour

* uni2485 (U+2485) has a counter-clockwise outer contour

* uni2485 (U+2485) has a counter-clockwise outer contour

* uni2485 (U+2485) has a counter-clockwise outer contour

* uni2486 (U+2486) has a counter-clockwise outer contour

* uni2486 (U+2486) has a counter-clockwise outer contour

* uni2486 (U+2486) has a counter-clockwise outer contour

* uni2486 (U+2486) has a counter-clockwise outer contour

* uni2487 (U+2487) has a counter-clockwise outer contour

* uni2487 (U+2487) has a counter-clockwise outer contour

* uni2487 (U+2487) has a counter-clockwise outer contour

* uni2487 (U+2487) has a counter-clockwise outer contour

* uni2488 (U+2488) has a counter-clockwise outer contour

* uni2488 (U+2488) has a counter-clockwise outer contour

* uni2489 (U+2489) has a counter-clockwise outer contour

* uni2489 (U+2489) has a counter-clockwise outer contour

* uni248A (U+248A) has a counter-clockwise outer contour

* uni248A (U+248A) has a counter-clockwise outer contour

* uni248B (U+248B) has a counter-clockwise outer contour

* uni248B (U+248B) has a counter-clockwise outer contour

* uni248C (U+248C) has a counter-clockwise outer contour

* uni248C (U+248C) has a counter-clockwise outer contour

* uni248D (U+248D) has a counter-clockwise outer contour

* uni248D (U+248D) has a counter-clockwise outer contour

* uni248E (U+248E) has a counter-clockwise outer contour

* uni248E (U+248E) has a counter-clockwise outer contour

* uni248F (U+248F) has a counter-clockwise outer contour

* uni248F (U+248F) has a counter-clockwise outer contour

* uni2490 (U+2490) has a counter-clockwise outer contour

* uni2490 (U+2490) has a counter-clockwise outer contour

* uni2491 (U+2491) has a counter-clockwise outer contour

* uni2491 (U+2491) has a counter-clockwise outer contour

* uni2491 (U+2491) has a counter-clockwise outer contour

* uni2492 (U+2492) has a counter-clockwise outer contour

* uni2492 (U+2492) has a counter-clockwise outer contour

* uni2492 (U+2492) has a counter-clockwise outer contour

* uni2493 (U+2493) has a counter-clockwise outer contour

* uni2493 (U+2493) has a counter-clockwise outer contour

* uni2493 (U+2493) has a counter-clockwise outer contour

* uni2494 (U+2494) has a counter-clockwise outer contour

* uni2494 (U+2494) has a counter-clockwise outer contour

* uni2494 (U+2494) has a counter-clockwise outer contour

* uni2495 (U+2495) has a counter-clockwise outer contour

* uni2495 (U+2495) has a counter-clockwise outer contour

* uni2495 (U+2495) has a counter-clockwise outer contour

* uni2496 (U+2496) has a counter-clockwise outer contour

* uni2496 (U+2496) has a counter-clockwise outer contour

* uni2496 (U+2496) has a counter-clockwise outer contour

* uni2497 (U+2497) has a counter-clockwise outer contour

* uni2497 (U+2497) has a counter-clockwise outer contour

* uni2497 (U+2497) has a counter-clockwise outer contour

* uni2498 (U+2498) has a counter-clockwise outer contour

* uni2498 (U+2498) has a counter-clockwise outer contour

* uni2498 (U+2498) has a counter-clockwise outer contour

* uni2499 (U+2499) has a counter-clockwise outer contour

* uni2499 (U+2499) has a counter-clockwise outer contour

* uni2499 (U+2499) has a counter-clockwise outer contour

* uni249A (U+249A) has a counter-clockwise outer contour

* uni249A (U+249A) has a counter-clockwise outer contour

* uni249A (U+249A) has a counter-clockwise outer contour

* uni249B (U+249B) has a counter-clockwise outer contour

* uni249B (U+249B) has a counter-clockwise outer contour

* uni249B (U+249B) has a counter-clockwise outer contour

* uni249C (U+249C) has a counter-clockwise outer contour

* uni249C (U+249C) has a counter-clockwise outer contour

* uni249C (U+249C) has a counter-clockwise outer contour

* uni249D (U+249D) has a counter-clockwise outer contour

* uni249D (U+249D) has a counter-clockwise outer contour

* uni249D (U+249D) has a counter-clockwise outer contour

* uni249E (U+249E) has a counter-clockwise outer contour

* uni249E (U+249E) has a counter-clockwise outer contour

* uni249E (U+249E) has a counter-clockwise outer contour

* uni249F (U+249F) has a counter-clockwise outer contour

* uni249F (U+249F) has a counter-clockwise outer contour

* uni249F (U+249F) has a counter-clockwise outer contour

* uni24A0 (U+24A0) has a counter-clockwise outer contour

* uni24A0 (U+24A0) has a counter-clockwise outer contour

* uni24A0 (U+24A0) has a counter-clockwise outer contour

* uni24A1 (U+24A1) has a counter-clockwise outer contour

* uni24A1 (U+24A1) has a counter-clockwise outer contour

* uni24A1 (U+24A1) has a counter-clockwise outer contour

* uni24A2 (U+24A2) has a counter-clockwise outer contour

* uni24A2 (U+24A2) has a counter-clockwise outer contour

* uni24A2 (U+24A2) has a counter-clockwise outer contour

* uni24A3 (U+24A3) has a counter-clockwise outer contour

* uni24A3 (U+24A3) has a counter-clockwise outer contour

* uni24A3 (U+24A3) has a counter-clockwise outer contour

* uni24A4 (U+24A4) has a counter-clockwise outer contour

* uni24A4 (U+24A4) has a counter-clockwise outer contour

* uni24A4 (U+24A4) has a counter-clockwise outer contour

* uni24A4 (U+24A4) has a counter-clockwise outer contour

* uni24A5 (U+24A5) has a counter-clockwise outer contour

* uni24A5 (U+24A5) has a counter-clockwise outer contour

* uni24A5 (U+24A5) has a counter-clockwise outer contour

* uni24A5 (U+24A5) has a counter-clockwise outer contour

* uni24A6 (U+24A6) has a counter-clockwise outer contour

* uni24A6 (U+24A6) has a counter-clockwise outer contour

* uni24A6 (U+24A6) has a counter-clockwise outer contour

* uni24A7 (U+24A7) has a counter-clockwise outer contour

* uni24A7 (U+24A7) has a counter-clockwise outer contour

* uni24A7 (U+24A7) has a counter-clockwise outer contour

* uni24A8 (U+24A8) has a counter-clockwise outer contour

* uni24A8 (U+24A8) has a counter-clockwise outer contour

* uni24A8 (U+24A8) has a counter-clockwise outer contour

* uni24A9 (U+24A9) has a counter-clockwise outer contour

* uni24A9 (U+24A9) has a counter-clockwise outer contour

* uni24A9 (U+24A9) has a counter-clockwise outer contour

* uni24AA (U+24AA) has a counter-clockwise outer contour

* uni24AA (U+24AA) has a counter-clockwise outer contour

* uni24AA (U+24AA) has a counter-clockwise outer contour

* uni24AB (U+24AB) has a counter-clockwise outer contour

* uni24AB (U+24AB) has a counter-clockwise outer contour

* uni24AB (U+24AB) has a counter-clockwise outer contour

* uni24AC (U+24AC) has a counter-clockwise outer contour

* uni24AC (U+24AC) has a counter-clockwise outer contour

* uni24AC (U+24AC) has a counter-clockwise outer contour

* uni24AD (U+24AD) has a counter-clockwise outer contour

* uni24AD (U+24AD) has a counter-clockwise outer contour

* uni24AD (U+24AD) has a counter-clockwise outer contour

* uni24AE (U+24AE) has a counter-clockwise outer contour

* uni24AE (U+24AE) has a counter-clockwise outer contour

* uni24AE (U+24AE) has a counter-clockwise outer contour

* uni24AF (U+24AF) has a counter-clockwise outer contour

* uni24AF (U+24AF) has a counter-clockwise outer contour

* uni24AF (U+24AF) has a counter-clockwise outer contour

* uni24B0 (U+24B0) has a counter-clockwise outer contour

* uni24B0 (U+24B0) has a counter-clockwise outer contour

* uni24B0 (U+24B0) has a counter-clockwise outer contour

* uni24B1 (U+24B1) has a counter-clockwise outer contour

* uni24B1 (U+24B1) has a counter-clockwise outer contour

* uni24B1 (U+24B1) has a counter-clockwise outer contour

* uni24B1 (U+24B1) has a counter-clockwise outer contour

* uni24B1 (U+24B1) has a path with no bounds (probably a single point)

* uni24B2 (U+24B2) has a counter-clockwise outer contour

* uni24B2 (U+24B2) has a counter-clockwise outer contour

* uni24B2 (U+24B2) has a counter-clockwise outer contour

* uni24B2 (U+24B2) has a counter-clockwise outer contour

* uni24B2 (U+24B2) has a path with no bounds (probably a single point)

* uni24B3 (U+24B3) has a counter-clockwise outer contour

* uni24B3 (U+24B3) has a counter-clockwise outer contour

* uni24B3 (U+24B3) has a counter-clockwise outer contour

* uni24B4 (U+24B4) has a counter-clockwise outer contour

* uni24B4 (U+24B4) has a counter-clockwise outer contour

* uni24B4 (U+24B4) has a counter-clockwise outer contour

* uni24B5 (U+24B5) has a counter-clockwise outer contour

* uni24B5 (U+24B5) has a counter-clockwise outer contour

* uni24B5 (U+24B5) has a counter-clockwise outer contour

* uni2731 (U+2731) has a counter-clockwise outer contour

* uni2758 (U+2758) has a counter-clockwise outer contour

* uni2758 (U+2758) has a counter-clockwise outer contour

* uni2762 (U+2762) has a counter-clockwise outer contour

* uni2762 (U+2762) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A74 (U+2A74) has a counter-clockwise outer contour

* uni2A75 (U+2A75) has a counter-clockwise outer contour

* uni2A75 (U+2A75) has a counter-clockwise outer contour

* uni2A75 (U+2A75) has a counter-clockwise outer contour

* uni2A75 (U+2A75) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2A76 (U+2A76) has a counter-clockwise outer contour

* uni2C7C (U+2C7C) has a counter-clockwise outer contour

* uni2C7C (U+2C7C) has a counter-clockwise outer contour

* uni2C7D (U+2C7D) has a counter-clockwise outer contour

* uni3001 (U+3001) has a counter-clockwise outer contour

* uni3008 (U+3008) has a counter-clockwise outer contour

* uni3009 (U+3009) has a counter-clockwise outer contour

* uni300A (U+300A) has a counter-clockwise outer contour

* uni300A (U+300A) has a counter-clockwise outer contour

* uni300B (U+300B) has a counter-clockwise outer contour

* uni300B (U+300B) has a counter-clockwise outer contour

* uni3250 (U+3250) has a counter-clockwise outer contour

* uni3250 (U+3250) has a counter-clockwise outer contour

* uni3250 (U+3250) has a counter-clockwise outer contour

* uni32CC (U+32CC) has a counter-clockwise outer contour

* uni32CC (U+32CC) has a counter-clockwise outer contour

* uni32CD (U+32CD) has a counter-clockwise outer contour

* uni32CD (U+32CD) has a counter-clockwise outer contour

* uni32CD (U+32CD) has a counter-clockwise outer contour

* uni32CE (U+32CE) has a counter-clockwise outer contour

* uni32CE (U+32CE) has a counter-clockwise outer contour

* uni32CF (U+32CF) has a counter-clockwise outer contour

* uni32CF (U+32CF) has a counter-clockwise outer contour

* uni32CF (U+32CF) has a counter-clockwise outer contour

* uni3371 (U+3371) has a counter-clockwise outer contour

* uni3371 (U+3371) has a counter-clockwise outer contour

* uni3371 (U+3371) has a counter-clockwise outer contour

* uni3372 (U+3372) has a counter-clockwise outer contour

* uni3372 (U+3372) has a counter-clockwise outer contour

* uni3373 (U+3373) has a counter-clockwise outer contour

* uni3373 (U+3373) has a counter-clockwise outer contour

* uni3374 (U+3374) has a counter-clockwise outer contour

* uni3374 (U+3374) has a counter-clockwise outer contour

* uni3374 (U+3374) has a counter-clockwise outer contour

* uni3375 (U+3375) has a counter-clockwise outer contour

* uni3375 (U+3375) has a counter-clockwise outer contour

* uni3376 (U+3376) has a counter-clockwise outer contour

* uni3376 (U+3376) has a counter-clockwise outer contour

* uni3377 (U+3377) has a counter-clockwise outer contour

* uni3377 (U+3377) has a counter-clockwise outer contour

* uni3378 (U+3378) has a counter-clockwise outer contour

* uni3378 (U+3378) has a counter-clockwise outer contour

* uni3378 (U+3378) has a counter-clockwise outer contour

* uni3379 (U+3379) has a counter-clockwise outer contour

* uni3379 (U+3379) has a counter-clockwise outer contour

* uni3379 (U+3379) has a counter-clockwise outer contour

* uni337A (U+337A) has a counter-clockwise outer contour

* uni337A (U+337A) has a counter-clockwise outer contour

* uni3380 (U+3380) has a counter-clockwise outer contour

* uni3380 (U+3380) has a counter-clockwise outer contour

* uni3381 (U+3381) has a counter-clockwise outer contour

* uni3381 (U+3381) has a counter-clockwise outer contour

* uni3383 (U+3383) has a counter-clockwise outer contour

* uni3383 (U+3383) has a counter-clockwise outer contour

* uni3384 (U+3384) has a counter-clockwise outer contour

* uni3384 (U+3384) has a counter-clockwise outer contour

* uni3385 (U+3385) has a counter-clockwise outer contour

* uni3385 (U+3385) has a counter-clockwise outer contour

* uni3386 (U+3386) has a counter-clockwise outer contour

* uni3386 (U+3386) has a counter-clockwise outer contour

* uni3387 (U+3387) has a counter-clockwise outer contour

* uni3387 (U+3387) has a counter-clockwise outer contour

* uni3388 (U+3388) has a counter-clockwise outer contour

* uni3388 (U+3388) has a counter-clockwise outer contour

* uni3388 (U+3388) has a counter-clockwise outer contour

* uni3389 (U+3389) has a counter-clockwise outer contour

* uni3389 (U+3389) has a counter-clockwise outer contour

* uni3389 (U+3389) has a counter-clockwise outer contour

* uni3389 (U+3389) has a counter-clockwise outer contour

* uni338A (U+338A) has a counter-clockwise outer contour

* uni338A (U+338A) has a counter-clockwise outer contour

* uni338B (U+338B) has a counter-clockwise outer contour

* uni338B (U+338B) has a counter-clockwise outer contour

* uni338E (U+338E) has a counter-clockwise outer contour

* uni338E (U+338E) has a counter-clockwise outer contour

* uni338F (U+338F) has a counter-clockwise outer contour

* uni338F (U+338F) has a counter-clockwise outer contour

* uni3390 (U+3390) has a counter-clockwise outer contour

* uni3390 (U+3390) has a counter-clockwise outer contour

* uni3391 (U+3391) has a counter-clockwise outer contour

* uni3391 (U+3391) has a counter-clockwise outer contour

* uni3391 (U+3391) has a counter-clockwise outer contour

* uni3392 (U+3392) has a counter-clockwise outer contour

* uni3392 (U+3392) has a counter-clockwise outer contour

* uni3392 (U+3392) has a counter-clockwise outer contour

* uni3393 (U+3393) has a counter-clockwise outer contour

* uni3393 (U+3393) has a counter-clockwise outer contour

* uni3393 (U+3393) has a counter-clockwise outer contour

* uni3394 (U+3394) has a counter-clockwise outer contour

* uni3394 (U+3394) has a counter-clockwise outer contour

* uni3394 (U+3394) has a counter-clockwise outer contour

* uni3396 (U+3396) has a counter-clockwise outer contour

* uni3396 (U+3396) has a counter-clockwise outer contour

* uni3397 (U+3397) has a counter-clockwise outer contour

* uni3397 (U+3397) has a counter-clockwise outer contour

* uni3398 (U+3398) has a counter-clockwise outer contour

* uni3398 (U+3398) has a counter-clockwise outer contour

* uni3399 (U+3399) has a counter-clockwise outer contour

* uni3399 (U+3399) has a counter-clockwise outer contour

* uni339A (U+339A) has a counter-clockwise outer contour

* uni339A (U+339A) has a counter-clockwise outer contour

* uni339C (U+339C) has a counter-clockwise outer contour

* uni339C (U+339C) has a counter-clockwise outer contour

* uni339D (U+339D) has a counter-clockwise outer contour

* uni339D (U+339D) has a counter-clockwise outer contour

* uni339E (U+339E) has a counter-clockwise outer contour

* uni339E (U+339E) has a counter-clockwise outer contour

* uni339F (U+339F) has a counter-clockwise outer contour

* uni339F (U+339F) has a counter-clockwise outer contour

* uni339F (U+339F) has a counter-clockwise outer contour

* uni33A0 (U+33A0) has a counter-clockwise outer contour

* uni33A0 (U+33A0) has a counter-clockwise outer contour

* uni33A0 (U+33A0) has a counter-clockwise outer contour

* uni33A1 (U+33A1) has a counter-clockwise outer contour

* uni33A1 (U+33A1) has a counter-clockwise outer contour

* uni33A2 (U+33A2) has a counter-clockwise outer contour

* uni33A2 (U+33A2) has a counter-clockwise outer contour

* uni33A2 (U+33A2) has a counter-clockwise outer contour

* uni33A3 (U+33A3) has a counter-clockwise outer contour

* uni33A3 (U+33A3) has a counter-clockwise outer contour

* uni33A3 (U+33A3) has a counter-clockwise outer contour

* uni33A4 (U+33A4) has a counter-clockwise outer contour

* uni33A4 (U+33A4) has a counter-clockwise outer contour

* uni33A4 (U+33A4) has a counter-clockwise outer contour

* uni33A5 (U+33A5) has a counter-clockwise outer contour

* uni33A5 (U+33A5) has a counter-clockwise outer contour

* uni33A6 (U+33A6) has a counter-clockwise outer contour

* uni33A6 (U+33A6) has a counter-clockwise outer contour

* uni33A6 (U+33A6) has a counter-clockwise outer contour

* uni33A7 (U+33A7) has a counter-clockwise outer contour

* uni33A7 (U+33A7) has a counter-clockwise outer contour

* uni33A7 (U+33A7) has a counter-clockwise outer contour

* uni33A8 (U+33A8) has a counter-clockwise outer contour

* uni33A8 (U+33A8) has a counter-clockwise outer contour

* uni33A8 (U+33A8) has a counter-clockwise outer contour

* uni33A8 (U+33A8) has a counter-clockwise outer contour

* uni33A9 (U+33A9) has a counter-clockwise outer contour

* uni33A9 (U+33A9) has a counter-clockwise outer contour

* uni33AA (U+33AA) has a counter-clockwise outer contour

* uni33AA (U+33AA) has a counter-clockwise outer contour

* uni33AA (U+33AA) has a counter-clockwise outer contour

* uni33AB (U+33AB) has a counter-clockwise outer contour

* uni33AB (U+33AB) has a counter-clockwise outer contour

* uni33AB (U+33AB) has a counter-clockwise outer contour

* uni33AC (U+33AC) has a counter-clockwise outer contour

* uni33AC (U+33AC) has a counter-clockwise outer contour

* uni33AC (U+33AC) has a counter-clockwise outer contour

* uni33AD (U+33AD) has a counter-clockwise outer contour

* uni33AD (U+33AD) has a counter-clockwise outer contour

* uni33AD (U+33AD) has a counter-clockwise outer contour

* uni33AE (U+33AE) has a counter-clockwise outer contour

* uni33AE (U+33AE) has a counter-clockwise outer contour

* uni33AE (U+33AE) has a counter-clockwise outer contour

* uni33AE (U+33AE) has a counter-clockwise outer contour

* uni33AE (U+33AE) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33AF (U+33AF) has a counter-clockwise outer contour

* uni33B0 (U+33B0) has a counter-clockwise outer contour

* uni33B0 (U+33B0) has a counter-clockwise outer contour

* uni33B1 (U+33B1) has a counter-clockwise outer contour

* uni33B1 (U+33B1) has a counter-clockwise outer contour

* uni33B3 (U+33B3) has a counter-clockwise outer contour

* uni33B3 (U+33B3) has a counter-clockwise outer contour

* uni33B4 (U+33B4) has a counter-clockwise outer contour

* uni33B4 (U+33B4) has a counter-clockwise outer contour

* uni33B5 (U+33B5) has a counter-clockwise outer contour

* uni33B5 (U+33B5) has a counter-clockwise outer contour

* uni33B7 (U+33B7) has a counter-clockwise outer contour

* uni33B7 (U+33B7) has a counter-clockwise outer contour

* uni33B8 (U+33B8) has a counter-clockwise outer contour

* uni33B8 (U+33B8) has a counter-clockwise outer contour

* uni33B9 (U+33B9) has a counter-clockwise outer contour

* uni33B9 (U+33B9) has a counter-clockwise outer contour

* uni33BA (U+33BA) has a counter-clockwise outer contour

* uni33BA (U+33BA) has a counter-clockwise outer contour

* uni33BB (U+33BB) has a counter-clockwise outer contour

* uni33BB (U+33BB) has a counter-clockwise outer contour

* uni33BD (U+33BD) has a counter-clockwise outer contour

* uni33BD (U+33BD) has a counter-clockwise outer contour

* uni33BE (U+33BE) has a counter-clockwise outer contour

* uni33BE (U+33BE) has a counter-clockwise outer contour

* uni33BF (U+33BF) has a counter-clockwise outer contour

* uni33BF (U+33BF) has a counter-clockwise outer contour

* uni33C2 (U+33C2) has a counter-clockwise outer contour

* uni33C2 (U+33C2) has a counter-clockwise outer contour

* uni33C2 (U+33C2) has a counter-clockwise outer contour

* uni33C2 (U+33C2) has a counter-clockwise outer contour

* uni33C3 (U+33C3) has a counter-clockwise outer contour

* uni33C3 (U+33C3) has a counter-clockwise outer contour

* uni33C4 (U+33C4) has a counter-clockwise outer contour

* uni33C4 (U+33C4) has a counter-clockwise outer contour

* uni33C5 (U+33C5) has a counter-clockwise outer contour

* uni33C5 (U+33C5) has a counter-clockwise outer contour

* uni33C6 (U+33C6) has a counter-clockwise outer contour

* uni33C6 (U+33C6) has a counter-clockwise outer contour

* uni33C6 (U+33C6) has a counter-clockwise outer contour

* uni33C6 (U+33C6) has a counter-clockwise outer contour

* uni33C7 (U+33C7) has a counter-clockwise outer contour

* uni33C7 (U+33C7) has a counter-clockwise outer contour

* uni33C7 (U+33C7) has a counter-clockwise outer contour

* uni33C8 (U+33C8) has a counter-clockwise outer contour

* uni33C8 (U+33C8) has a counter-clockwise outer contour

* uni33C9 (U+33C9) has a counter-clockwise outer contour

* uni33C9 (U+33C9) has a counter-clockwise outer contour

* uni33CA (U+33CA) has a counter-clockwise outer contour

* uni33CA (U+33CA) has a counter-clockwise outer contour

* uni33CB (U+33CB) has a counter-clockwise outer contour

* uni33CB (U+33CB) has a counter-clockwise outer contour

* uni33CC (U+33CC) has a counter-clockwise outer contour

* uni33CC (U+33CC) has a counter-clockwise outer contour

* uni33CC (U+33CC) has a counter-clockwise outer contour

* uni33CD (U+33CD) has a counter-clockwise outer contour

* uni33CD (U+33CD) has a counter-clockwise outer contour

* uni33CE (U+33CE) has a counter-clockwise outer contour

* uni33CE (U+33CE) has a counter-clockwise outer contour

* uni33CF (U+33CF) has a counter-clockwise outer contour

* uni33CF (U+33CF) has a counter-clockwise outer contour

* uni33D0 (U+33D0) has a counter-clockwise outer contour

* uni33D0 (U+33D0) has a counter-clockwise outer contour

* uni33D1 (U+33D1) has a counter-clockwise outer contour

* uni33D1 (U+33D1) has a counter-clockwise outer contour

* uni33D2 (U+33D2) has a counter-clockwise outer contour

* uni33D2 (U+33D2) has a counter-clockwise outer contour

* uni33D2 (U+33D2) has a counter-clockwise outer contour

* uni33D3 (U+33D3) has a counter-clockwise outer contour

* uni33D3 (U+33D3) has a counter-clockwise outer contour

* uni33D4 (U+33D4) has a counter-clockwise outer contour

* uni33D4 (U+33D4) has a counter-clockwise outer contour

* uni33D5 (U+33D5) has a counter-clockwise outer contour

* uni33D5 (U+33D5) has a counter-clockwise outer contour

* uni33D5 (U+33D5) has a counter-clockwise outer contour

* uni33D5 (U+33D5) has a counter-clockwise outer contour

* uni33D6 (U+33D6) has a counter-clockwise outer contour

* uni33D6 (U+33D6) has a counter-clockwise outer contour

* uni33D6 (U+33D6) has a counter-clockwise outer contour

* uni33D7 (U+33D7) has a counter-clockwise outer contour

* uni33D7 (U+33D7) has a counter-clockwise outer contour

* uni33D8 (U+33D8) has a counter-clockwise outer contour

* uni33D8 (U+33D8) has a counter-clockwise outer contour

* uni33D8 (U+33D8) has a counter-clockwise outer contour

* uni33D8 (U+33D8) has a counter-clockwise outer contour

* uni33D9 (U+33D9) has a counter-clockwise outer contour

* uni33D9 (U+33D9) has a counter-clockwise outer contour

* uni33D9 (U+33D9) has a counter-clockwise outer contour

* uni33DA (U+33DA) has a counter-clockwise outer contour

* uni33DA (U+33DA) has a counter-clockwise outer contour

* uni33DB (U+33DB) has a counter-clockwise outer contour

* uni33DB (U+33DB) has a counter-clockwise outer contour

* uni33DC (U+33DC) has a counter-clockwise outer contour

* uni33DC (U+33DC) has a counter-clockwise outer contour

* uni33DC (U+33DC) has a counter-clockwise outer contour

* uni33DC (U+33DC) has a path with no bounds (probably a single point)

* uni33DD (U+33DD) has a counter-clockwise outer contour

* uni33DD (U+33DD) has a counter-clockwise outer contour

* uni33DE (U+33DE) has a counter-clockwise outer contour

* uni33DE (U+33DE) has a counter-clockwise outer contour

* uni33DE (U+33DE) has a counter-clockwise outer contour

* uni33DF (U+33DF) has a counter-clockwise outer contour

* uni33DF (U+33DF) has a counter-clockwise outer contour

* uni33DF (U+33DF) has a counter-clockwise outer contour

* uni33FF (U+33FF) has a counter-clockwise outer contour

* uni33FF (U+33FF) has a counter-clockwise outer contour

* uni33FF (U+33FF) has a counter-clockwise outer contour

* uniA7F9 (U+A7F9) has a counter-clockwise outer contour

* uniA7F9 (U+A7F9) has a counter-clockwise outer contour

* uniF6BE (U+F6BE) has a counter-clockwise outer contour

* uniFB00 (U+FB00) has a counter-clockwise outer contour

* uniFB00 (U+FB00) has a counter-clockwise outer contour

* uniFB01 (U+FB01) has a counter-clockwise outer contour

* uniFB01 (U+FB01) has a counter-clockwise outer contour

* uniFB01 (U+FB01) has a counter-clockwise outer contour

* uniFB02 (U+FB02) has a counter-clockwise outer contour

* uniFB02 (U+FB02) has a counter-clockwise outer contour

* uniFB03 (U+FB03) has a counter-clockwise outer contour

* uniFB03 (U+FB03) has a counter-clockwise outer contour

* uniFB03 (U+FB03) has a counter-clockwise outer contour

* uniFB03 (U+FB03) has a counter-clockwise outer contour

* uniFB04 (U+FB04) has a counter-clockwise outer contour

* uniFB04 (U+FB04) has a counter-clockwise outer contour

* uniFB04 (U+FB04) has a counter-clockwise outer contour

* uniFB05 (U+FB05) has a counter-clockwise outer contour

* uniFB05 (U+FB05) has a counter-clockwise outer contour

* uniFB06 (U+FB06) has a counter-clockwise outer contour

* uniFB06 (U+FB06) has a counter-clockwise outer contour

* uniFB29 (U+FB29) has a counter-clockwise outer contour

* uniFE10 (U+FE10) has a counter-clockwise outer contour

* uniFE11 (U+FE11) has a counter-clockwise outer contour

* uniFE13 (U+FE13) has a counter-clockwise outer contour

* uniFE13 (U+FE13) has a counter-clockwise outer contour

* uniFE14 (U+FE14) has a counter-clockwise outer contour

* uniFE14 (U+FE14) has a counter-clockwise outer contour

* uniFE15 (U+FE15) has a counter-clockwise outer contour

* uniFE15 (U+FE15) has a counter-clockwise outer contour

* uniFE16 (U+FE16) has a counter-clockwise outer contour

* uniFE16 (U+FE16) has a counter-clockwise outer contour

* uniFE19 (U+FE19) has a counter-clockwise outer contour

* uniFE19 (U+FE19) has a counter-clockwise outer contour

* uniFE19 (U+FE19) has a counter-clockwise outer contour

* uniFE30 (U+FE30) has a counter-clockwise outer contour

* uniFE30 (U+FE30) has a counter-clockwise outer contour

* uniFE31 (U+FE31) has a counter-clockwise outer contour

* uniFE32 (U+FE32) has a counter-clockwise outer contour

* uniFE33 (U+FE33) has a counter-clockwise outer contour

* uniFE34 (U+FE34) has a counter-clockwise outer contour

* uniFE35 (U+FE35) has a counter-clockwise outer contour

* uniFE36 (U+FE36) has a counter-clockwise outer contour

* uniFE37 (U+FE37) has a counter-clockwise outer contour

* uniFE38 (U+FE38) has a counter-clockwise outer contour

* uniFE3D (U+FE3D) has a counter-clockwise outer contour

* uniFE3D (U+FE3D) has a counter-clockwise outer contour

* uniFE3E (U+FE3E) has a counter-clockwise outer contour

* uniFE3E (U+FE3E) has a counter-clockwise outer contour

* uniFE3F (U+FE3F) has a counter-clockwise outer contour

* uniFE40 (U+FE40) has a counter-clockwise outer contour

* uniFE47 (U+FE47) has a counter-clockwise outer contour

* uniFE48 (U+FE48) has a counter-clockwise outer contour

* uniFE49 (U+FE49) has a counter-clockwise outer contour

* uniFE4A (U+FE4A) has a counter-clockwise outer contour

* uniFE4B (U+FE4B) has a counter-clockwise outer contour

* uniFE4C (U+FE4C) has a counter-clockwise outer contour

* uniFE4D (U+FE4D) has a counter-clockwise outer contour

* uniFE4E (U+FE4E) has a counter-clockwise outer contour

* uniFE4F (U+FE4F) has a counter-clockwise outer contour

* uniFE50 (U+FE50) has a counter-clockwise outer contour

* uniFE51 (U+FE51) has a counter-clockwise outer contour

* uniFE52 (U+FE52) has a counter-clockwise outer contour

* uniFE54 (U+FE54) has a counter-clockwise outer contour

* uniFE54 (U+FE54) has a counter-clockwise outer contour

* uniFE55 (U+FE55) has a counter-clockwise outer contour

* uniFE55 (U+FE55) has a counter-clockwise outer contour

* uniFE56 (U+FE56) has a counter-clockwise outer contour

* uniFE56 (U+FE56) has a counter-clockwise outer contour

* uniFE57 (U+FE57) has a counter-clockwise outer contour

* uniFE57 (U+FE57) has a counter-clockwise outer contour

* uniFE58 (U+FE58) has a counter-clockwise outer contour

* uniFE59 (U+FE59) has a counter-clockwise outer contour

* uniFE5A (U+FE5A) has a counter-clockwise outer contour

* uniFE5B (U+FE5B) has a counter-clockwise outer contour

* uniFE5C (U+FE5C) has a counter-clockwise outer contour

* uniFE5F (U+FE5F) has a counter-clockwise outer contour

* uniFE60 (U+FE60) has a counter-clockwise outer contour

* uniFE61 (U+FE61) has a counter-clockwise outer contour

* uniFE62 (U+FE62) has a counter-clockwise outer contour

* uniFE63 (U+FE63) has a counter-clockwise outer contour

* uniFE64 (U+FE64) has a counter-clockwise outer contour

* uniFE65 (U+FE65) has a counter-clockwise outer contour

* uniFE66 (U+FE66) has a counter-clockwise outer contour

* uniFE66 (U+FE66) has a counter-clockwise outer contour

* uniFE68 (U+FE68) has a counter-clockwise outer contour

* uniFE69 (U+FE69) has a counter-clockwise outer contour

* uniFE6A (U+FE6A) has a counter-clockwise outer contour

* uniFE6B (U+FE6B) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF02 (U+FF02) has a counter-clockwise outer contour

* uniFF02 (U+FF02) has a counter-clockwise outer contour

* uniFF03 (U+FF03) has a counter-clockwise outer contour

* uniFF04 (U+FF04) has a counter-clockwise outer contour

* uniFF05 (U+FF05) has a counter-clockwise outer contour

* uniFF06 (U+FF06) has a counter-clockwise outer contour

* uniFF07 (U+FF07) has a counter-clockwise outer contour

* uniFF07 (U+FF07) has a counter-clockwise outer contour

* uniFF08 (U+FF08) has a counter-clockwise outer contour

* uniFF09 (U+FF09) has a counter-clockwise outer contour

* uniFF0A (U+FF0A) has a counter-clockwise outer contour

* uniFF0B (U+FF0B) has a counter-clockwise outer contour

* uniFF0C (U+FF0C) has a counter-clockwise outer contour

* uniFF0D (U+FF0D) has a counter-clockwise outer contour

* uniFF0E (U+FF0E) has a counter-clockwise outer contour

* uniFF0F (U+FF0F) has a counter-clockwise outer contour

* uniFF10 (U+FF10) has a counter-clockwise outer contour

* uniFF11 (U+FF11) has a counter-clockwise outer contour

* uniFF12 (U+FF12) has a counter-clockwise outer contour

* uniFF13 (U+FF13) has a counter-clockwise outer contour

* uniFF14 (U+FF14) has a counter-clockwise outer contour

* uniFF15 (U+FF15) has a counter-clockwise outer contour

* uniFF16 (U+FF16) has a counter-clockwise outer contour

* uniFF17 (U+FF17) has a counter-clockwise outer contour

* uniFF18 (U+FF18) has a counter-clockwise outer contour

* uniFF19 (U+FF19) has a counter-clockwise outer contour

* uniFF1A (U+FF1A) has a counter-clockwise outer contour

* uniFF1A (U+FF1A) has a counter-clockwise outer contour

* uniFF1B (U+FF1B) has a counter-clockwise outer contour

* uniFF1B (U+FF1B) has a counter-clockwise outer contour

* uniFF1C (U+FF1C) has a counter-clockwise outer contour

* uniFF1D (U+FF1D) has a counter-clockwise outer contour

* uniFF1D (U+FF1D) has a counter-clockwise outer contour

* uniFF1E (U+FF1E) has a counter-clockwise outer contour

* uniFF1F (U+FF1F) has a counter-clockwise outer contour

* uniFF1F (U+FF1F) has a counter-clockwise outer contour

* uniFF20 (U+FF20) has a counter-clockwise outer contour

* uniFF21 (U+FF21) has a counter-clockwise outer contour

* uniFF22 (U+FF22) has a counter-clockwise outer contour

* uniFF23 (U+FF23) has a counter-clockwise outer contour

* uniFF24 (U+FF24) has a counter-clockwise outer contour

* uniFF25 (U+FF25) has a counter-clockwise outer contour

* uniFF26 (U+FF26) has a counter-clockwise outer contour

* uniFF27 (U+FF27) has a counter-clockwise outer contour

* uniFF28 (U+FF28) has a counter-clockwise outer contour

* uniFF29 (U+FF29) has a counter-clockwise outer contour

* uniFF2A (U+FF2A) has a counter-clockwise outer contour

* uniFF2B (U+FF2B) has a counter-clockwise outer contour

* uniFF2C (U+FF2C) has a counter-clockwise outer contour

* uniFF2D (U+FF2D) has a counter-clockwise outer contour

* uniFF2E (U+FF2E) has a counter-clockwise outer contour

* uniFF2F (U+FF2F) has a counter-clockwise outer contour

* uniFF30 (U+FF30) has a counter-clockwise outer contour

* uniFF31 (U+FF31) has a counter-clockwise outer contour

* uniFF32 (U+FF32) has a counter-clockwise outer contour

* uniFF33 (U+FF33) has a counter-clockwise outer contour

* uniFF34 (U+FF34) has a counter-clockwise outer contour

* uniFF35 (U+FF35) has a counter-clockwise outer contour

* uniFF36 (U+FF36) has a counter-clockwise outer contour

* uniFF37 (U+FF37) has a counter-clockwise outer contour

* uniFF38 (U+FF38) has a counter-clockwise outer contour

* uniFF39 (U+FF39) has a counter-clockwise outer contour

* uniFF3A (U+FF3A) has a counter-clockwise outer contour

* uniFF3B (U+FF3B) has a counter-clockwise outer contour

* uniFF3C (U+FF3C) has a counter-clockwise outer contour

* uniFF3D (U+FF3D) has a counter-clockwise outer contour

* uniFF3E (U+FF3E) has a counter-clockwise outer contour

* uniFF3F (U+FF3F) has a counter-clockwise outer contour

* uniFF40 (U+FF40) has a counter-clockwise outer contour

* uniFF41 (U+FF41) has a counter-clockwise outer contour

* uniFF42 (U+FF42) has a counter-clockwise outer contour

* uniFF43 (U+FF43) has a counter-clockwise outer contour

* uniFF44 (U+FF44) has a counter-clockwise outer contour

* uniFF45 (U+FF45) has a counter-clockwise outer contour

* uniFF46 (U+FF46) has a counter-clockwise outer contour

* uniFF47 (U+FF47) has a counter-clockwise outer contour

* uniFF48 (U+FF48) has a counter-clockwise outer contour

* uniFF49 (U+FF49) has a counter-clockwise outer contour

* uniFF49 (U+FF49) has a counter-clockwise outer contour

* uniFF4A (U+FF4A) has a counter-clockwise outer contour

* uniFF4A (U+FF4A) has a counter-clockwise outer contour

* uniFF4B (U+FF4B) has a counter-clockwise outer contour

* uniFF4C (U+FF4C) has a counter-clockwise outer contour

* uniFF4D (U+FF4D) has a counter-clockwise outer contour

* uniFF4E (U+FF4E) has a counter-clockwise outer contour

* uniFF4F (U+FF4F) has a counter-clockwise outer contour

* uniFF50 (U+FF50) has a counter-clockwise outer contour

* uniFF51 (U+FF51) has a counter-clockwise outer contour

* uniFF52 (U+FF52) has a counter-clockwise outer contour

* uniFF53 (U+FF53) has a counter-clockwise outer contour

* uniFF54 (U+FF54) has a counter-clockwise outer contour

* uniFF55 (U+FF55) has a counter-clockwise outer contour

* uniFF56 (U+FF56) has a counter-clockwise outer contour

* uniFF56 (U+FF56) has a counter-clockwise outer contour

* uniFF56 (U+FF56) has a path with no bounds (probably a single point)

* uniFF57 (U+FF57) has a counter-clockwise outer contour

* uniFF57 (U+FF57) has a counter-clockwise outer contour

* uniFF57 (U+FF57) has a path with no bounds (probably a single point)

* uniFF58 (U+FF58) has a counter-clockwise outer contour

* uniFF59 (U+FF59) has a counter-clockwise outer contour

* uniFF5A (U+FF5A) has a counter-clockwise outer contour

* uniFF5B (U+FF5B) has a counter-clockwise outer contour

* uniFF5C (U+FF5C) has a counter-clockwise outer contour

* uniFF5C (U+FF5C) has a counter-clockwise outer contour

* uniFF5D (U+FF5D) has a counter-clockwise outer contour

* uniFF5E (U+FF5E) has a counter-clockwise outer contour

* uniFF64 (U+FF64) has a counter-clockwise outer contour

* uniFFE0 (U+FFE0) has a counter-clockwise outer contour

* uniFFE1 (U+FFE1) has a counter-clockwise outer contour

* uniFFE2 (U+FFE2) has a counter-clockwise outer contour

* uniFFE3 (U+FFE3) has a counter-clockwise outer contour

* uniFFE4 (U+FFE4) has a counter-clockwise outer contour

* uniFFE4 (U+FFE4) has a counter-clockwise outer contour

* uniFFE5 (U+FFE5) has a counter-clockwise outer contour

* uniFFE8 (U+FFE8) has a counter-clockwise outer contour

* uniFFE8 (U+FFE8) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* utilde (U+0169) has a counter-clockwise outer contour

* utilde (U+0169) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a path with no bounds (probably a single point)

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a path with no bounds (probably a single point)

* wacute (U+1E83) has a counter-clockwise outer contour

* wacute (U+1E83) has a counter-clockwise outer contour

* wacute (U+1E83) has a path with no bounds (probably a single point)

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a path with no bounds (probably a single point)

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a path with no bounds (probably a single point)

* wgrave (U+1E81) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* wgrave (U+1E81) has a path with no bounds (probably a single point)

* x (U+0078) has a counter-clockwise outer contour

* y (U+0079) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* yen (U+00A5) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* z (U+007A) has a counter-clockwise outer contour

* zacute (U+017A) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zdotaccent (U+017C) has a counter-clockwise outer contour

* zdotaccent (U+017C) has a counter-clockwise outer contour

* zero (U+0030) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ j̀ j́ j̃ j̄ j̈ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ i̎ ȉ i̧̅ i̧̇ i̧̊ i̧̋ i̧̍ i̧̎ ȉ̧ i̧̐ j̅ j̆ j̇ j̉ j̊ j̋ j̍ j̎</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mfumte (Latn, 79,000 speakers), Ejagham (Latn, 120,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Fur (Latn, 1,230,163 speakers), Southern Kisi (Latn, 360,000 speakers), Dii (Latn, 71,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Bafut (Latn, 158,146 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kom (Latn, 360,685 speakers), Ebira (Latn, 2,200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mundani (Latn, 34,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Aghem (Latn, 38,843 speakers), Vute (Latn, 21,000 speakers), Yala (Latn, 200,000 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Dan (Latn, 1,099,244 speakers), Lithuanian (Latn, 2,357,094 speakers), Basaa (Latn, 332,940 speakers), Gulay (Latn, 250,478 speakers), Mango (Latn, 77,000 speakers), Bete-Bendi (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition</li>
<li>U+02B2 MODIFIER LETTER SMALL J: not included in any glyphset definition</li>
<li>U+02B3 MODIFIER LETTER SMALL R: not included in any glyphset definition</li>
<li>U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition</li>
<li>U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition</li>
<li>U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition</li>
<li>U+02BA MODIFIER LETTER DOUBLE PRIME: not included in any glyphset definition</li>
<li>U+02C4 MODIFIER LETTER UP ARROWHEAD: not included in any glyphset definition</li>
<li>U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02E1 MODIFIER LETTER SMALL L: not included in any glyphset definition</li>
<li>U+02E2 MODIFIER LETTER SMALL S: not included in any glyphset definition</li>
<li>U+02E3 MODIFIER LETTER SMALL X: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: math, coptic, elbasan, gothic, glagolitic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, coptic, old-permic, tifinagh, tai-le, syriac, canadian-aboriginal, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: not included in any glyphset definition</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0344 COMBINING GREEK DIALYTIKA TONOS: not included in any glyphset definition</li>
<li>U+054F ARMENIAN CAPITAL LETTER TIWN: try adding armenian</li>
<li>U+0555 ARMENIAN CAPITAL LETTER OH: try adding armenian</li>
<li>U+0570 ARMENIAN SMALL LETTER HO: try adding armenian</li>
<li>U+0578 ARMENIAN SMALL LETTER VO: try adding armenian</li>
<li>U+057D ARMENIAN SMALL LETTER SEH: try adding armenian</li>
<li>U+0584 ARMENIAN SMALL LETTER KEH: try adding armenian</li>
<li>U+0585 ARMENIAN SMALL LETTER OH: try adding armenian</li>
<li>U+0589 ARMENIAN FULL STOP: try adding one of: georgian, armenian</li>
<li>U+066A ARABIC PERCENT SIGN: try adding one of: arabic, thaana, nko, syriac</li>
<li>U+066C ARABIC THOUSANDS SEPARATOR: try adding one of: arabic, thaana, syriac</li>
<li>U+06D4 ARABIC FULL STOP: try adding one of: arabic, yezidi, hanifi-rohingya</li>
<li>U+13A0 CHEROKEE LETTER A: try adding cherokee</li>
<li>U+13A1 CHEROKEE LETTER E: try adding cherokee</li>
<li>U+13A2 CHEROKEE LETTER I: try adding cherokee</li>
<li>U+13AA CHEROKEE LETTER GO: try adding cherokee</li>
<li>U+13AB CHEROKEE LETTER GU: try adding cherokee</li>
<li>U+13AC CHEROKEE LETTER GV: try adding cherokee</li>
<li>U+13B3 CHEROKEE LETTER LA: try adding cherokee</li>
<li>U+13B7 CHEROKEE LETTER LU: try adding cherokee</li>
<li>U+13BB CHEROKEE LETTER MI: try adding cherokee</li>
<li>U+13C0 CHEROKEE LETTER NAH: try adding cherokee</li>
<li>U+13C2 CHEROKEE LETTER NI: try adding cherokee</li>
<li>U+13C3 CHEROKEE LETTER NO: try adding cherokee</li>
<li>U+13D9 CHEROKEE LETTER DO: try adding cherokee</li>
<li>U+13DA CHEROKEE LETTER DU: try adding cherokee</li>
<li>U+13DE CHEROKEE LETTER TLE: try adding cherokee</li>
<li>U+13DF CHEROKEE LETTER TLI: try adding cherokee</li>
<li>U+13E2 CHEROKEE LETTER TLV: try adding cherokee</li>
<li>U+13E6 CHEROKEE LETTER TSO: try adding cherokee</li>
<li>U+13F4 CHEROKEE LETTER YV: try adding cherokee</li>
<li>U+1D2C MODIFIER LETTER CAPITAL A: not included in any glyphset definition</li>
<li>U+1D2D MODIFIER LETTER CAPITAL AE: not included in any glyphset definition</li>
<li>U+1D2E MODIFIER LETTER CAPITAL B: not included in any glyphset definition</li>
<li>U+1D30 MODIFIER LETTER CAPITAL D: not included in any glyphset definition</li>
<li>U+1D31 MODIFIER LETTER CAPITAL E: not included in any glyphset definition</li>
<li>U+1D33 MODIFIER LETTER CAPITAL G: not included in any glyphset definition</li>
<li>U+1D34 MODIFIER LETTER CAPITAL H: not included in any glyphset definition</li>
<li>U+1D35 MODIFIER LETTER CAPITAL I: not included in any glyphset definition</li>
<li>U+1D36 MODIFIER LETTER CAPITAL J: not included in any glyphset definition</li>
<li>U+1D37 MODIFIER LETTER CAPITAL K: not included in any glyphset definition</li>
<li>U+1D38 MODIFIER LETTER CAPITAL L: not included in any glyphset definition</li>
<li>U+1D39 MODIFIER LETTER CAPITAL M: not included in any glyphset definition</li>
<li>U+1D3A MODIFIER LETTER CAPITAL N: not included in any glyphset definition</li>
<li>U+1D3C MODIFIER LETTER CAPITAL O: not included in any glyphset definition</li>
<li>U+1D3E MODIFIER LETTER CAPITAL P: not included in any glyphset definition</li>
<li>U+1D3F MODIFIER LETTER CAPITAL R: not included in any glyphset definition</li>
<li>U+1D40 MODIFIER LETTER CAPITAL T: not included in any glyphset definition</li>
<li>U+1D41 MODIFIER LETTER CAPITAL U: not included in any glyphset definition</li>
<li>U+1D42 MODIFIER LETTER CAPITAL W: not included in any glyphset definition</li>
<li>U+1D43 MODIFIER LETTER SMALL A: not included in any glyphset definition</li>
<li>U+1D47 MODIFIER LETTER SMALL B: not included in any glyphset definition</li>
<li>U+1D48 MODIFIER LETTER SMALL D: not included in any glyphset definition</li>
<li>U+1D49 MODIFIER LETTER SMALL E: not included in any glyphset definition</li>
<li>U+1D4D MODIFIER LETTER SMALL G: not included in any glyphset definition</li>
<li>U+1D4F MODIFIER LETTER SMALL K: not included in any glyphset definition</li>
<li>U+1D50 MODIFIER LETTER SMALL M: not included in any glyphset definition</li>
<li>U+1D52 MODIFIER LETTER SMALL O: not included in any glyphset definition</li>
<li>U+1D56 MODIFIER LETTER SMALL P: not included in any glyphset definition</li>
<li>U+1D57 MODIFIER LETTER SMALL T: not included in any glyphset definition</li>
<li>U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition</li>
<li>U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition</li>
<li>U+1D61 MODIFIER LETTER SMALL CHI: not included in any glyphset definition</li>
<li>U+1D62 LATIN SUBSCRIPT SMALL LETTER I: not included in any glyphset definition</li>
<li>U+1D63 LATIN SUBSCRIPT SMALL LETTER R: not included in any glyphset definition</li>
<li>U+1D64 LATIN SUBSCRIPT SMALL LETTER U: not included in any glyphset definition</li>
<li>U+1D65 LATIN SUBSCRIPT SMALL LETTER V: not included in any glyphset definition</li>
<li>U+1D68 GREEK SUBSCRIPT SMALL LETTER RHO: not included in any glyphset definition</li>
<li>U+1D6A GREEK SUBSCRIPT SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+1D9C MODIFIER LETTER SMALL C: not included in any glyphset definition</li>
<li>U+1DA0 MODIFIER LETTER SMALL F: not included in any glyphset definition</li>
<li>U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: not included in any glyphset definition</li>
<li>U+2001 EM QUAD: not included in any glyphset definition</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2005 FOUR-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2006 SIX-PER-EM SPACE: not included in any glyphset definition</li>
<li>U+2007 FIGURE SPACE: not included in any glyphset definition</li>
<li>U+2008 PUNCTUATION SPACE: not included in any glyphset definition</li>
<li>U+200A HAIR SPACE: not included in any glyphset definition</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: takri, sundanese, telugu, dogra, hebrew, javanese, kayah-li, mahajani, chakma, khmer, newa, khudawadi, mandaic, pahawh-hmong, hatran, syloti-nagri, tamil, myanmar, hanifi-rohingya, kannada, tai-tham, new-tai-lue, yi, phags-pa, tirhuta, tibetan, devanagari, masaram-gondi, thaana, mongolian, sharada, bhaiksuki, buginese, tifinagh, manichaean, siddham, lao, avestan, syriac, lepcha, warang-citi, kharoshthi, cham, gurmukhi, batak, bengali, zanabazar-square, grantha, sogdian, arabic, gujarati, gunjala-gondi, oriya, tai-le, rejang, tai-viet, psalter-pahlavi, hanunoo, kaithi, malayalam, thai, limbu, sinhala, khojki, tagbanwa, modi, tagalog, meetei-mayek, saurashtra, brahmi, duployan, nko, buhid, balinese</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: takri, sundanese, telugu, dogra, hebrew, javanese, kayah-li, mahajani, chakma, khmer, newa, khudawadi, mandaic, pahawh-hmong, syloti-nagri, tamil, myanmar, hanifi-rohingya, kannada, tai-tham, new-tai-lue, yi, phags-pa, tirhuta, tibetan, devanagari, masaram-gondi, thaana, mongolian, sharada, bhaiksuki, buginese, tifinagh, manichaean, old-hungarian, siddham, lao, avestan, syriac, lepcha, warang-citi, kharoshthi, cham, gurmukhi, batak, bengali, zanabazar-square, grantha, sogdian, arabic, gujarati, gunjala-gondi, oriya, tai-le, rejang, tai-viet, psalter-pahlavi, hanunoo, kaithi, malayalam, thai, limbu, sinhala, khojki, tagbanwa, modi, tagalog, meetei-mayek, saurashtra, brahmi, duployan, nko, buhid, balinese</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: hebrew, thaana, arabic, syriac, phags-pa, nko</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, hebrew, syriac, phags-pa, nko</li>
<li>U+2010 HYPHEN: try adding one of: sundanese, sora-sompeng, hebrew, kayah-li, kharoshthi, cham, coptic, arabic, syloti-nagri, armenian, lisu, yi, kaithi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: arabic, syloti-nagri, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+202A LEFT-TO-RIGHT EMBEDDING: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+203C DOUBLE EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+2047 DOUBLE QUESTION MARK: not included in any glyphset definition</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2049 EXCLAMATION QUESTION MARK: try adding mongolian</li>
<li>U+2057 QUADRUPLE PRIME: try adding math</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+207A SUPERSCRIPT PLUS SIGN: not included in any glyphset definition</li>
<li>U+207C SUPERSCRIPT EQUALS SIGN: not included in any glyphset definition</li>
<li>U+207D SUPERSCRIPT LEFT PARENTHESIS: not included in any glyphset definition</li>
<li>U+207E SUPERSCRIPT RIGHT PARENTHESIS: not included in any glyphset definition</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+208A SUBSCRIPT PLUS SIGN: not included in any glyphset definition</li>
<li>U+208C SUBSCRIPT EQUALS SIGN: not included in any glyphset definition</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: not included in any glyphset definition</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: not included in any glyphset definition</li>
<li>U+2090 LATIN SUBSCRIPT SMALL LETTER A: not included in any glyphset definition</li>
<li>U+2091 LATIN SUBSCRIPT SMALL LETTER E: not included in any glyphset definition</li>
<li>U+2092 LATIN SUBSCRIPT SMALL LETTER O: not included in any glyphset definition</li>
<li>U+2093 LATIN SUBSCRIPT SMALL LETTER X: not included in any glyphset definition</li>
<li>U+2095 LATIN SUBSCRIPT SMALL LETTER H: not included in any glyphset definition</li>
<li>U+2096 LATIN SUBSCRIPT SMALL LETTER K: not included in any glyphset definition</li>
<li>U+2097 LATIN SUBSCRIPT SMALL LETTER L: not included in any glyphset definition</li>
<li>U+2098 LATIN SUBSCRIPT SMALL LETTER M: not included in any glyphset definition</li>
<li>U+2099 LATIN SUBSCRIPT SMALL LETTER N: not included in any glyphset definition</li>
<li>U+209A LATIN SUBSCRIPT SMALL LETTER P: not included in any glyphset definition</li>
<li>U+209B LATIN SUBSCRIPT SMALL LETTER S: not included in any glyphset definition</li>
<li>U+209C LATIN SUBSCRIPT SMALL LETTER T: not included in any glyphset definition</li>
<li>U+2100 ACCOUNT OF: not included in any glyphset definition</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: not included in any glyphset definition</li>
<li>U+2102 DOUBLE-STRUCK CAPITAL C: try adding math</li>
<li>U+2103 DEGREE CELSIUS: not included in any glyphset definition</li>
<li>U+2105 CARE OF: not included in any glyphset definition</li>
<li>U+2106 CADA UNA: not included in any glyphset definition</li>
<li>U+2109 DEGREE FAHRENHEIT: not included in any glyphset definition</li>
<li>U+210A SCRIPT SMALL G: try adding math</li>
<li>U+210B SCRIPT CAPITAL H: try adding math</li>
<li>U+210C BLACK-LETTER CAPITAL H: try adding math</li>
<li>U+210D DOUBLE-STRUCK CAPITAL H: try adding math</li>
<li>U+210E PLANCK CONSTANT: try adding math</li>
<li>U+2110 SCRIPT CAPITAL I: try adding math</li>
<li>U+2111 BLACK-LETTER CAPITAL I: try adding math</li>
<li>U+2112 SCRIPT CAPITAL L: try adding math</li>
<li>U+2115 DOUBLE-STRUCK CAPITAL N: try adding math</li>
<li>U+2119 DOUBLE-STRUCK CAPITAL P: try adding math</li>
<li>U+211A DOUBLE-STRUCK CAPITAL Q: try adding math</li>
<li>U+211B SCRIPT CAPITAL R: try adding math</li>
<li>U+211C BLACK-LETTER CAPITAL R: try adding math</li>
<li>U+211D DOUBLE-STRUCK CAPITAL R: try adding math</li>
<li>U+2120 SERVICE MARK: not included in any glyphset definition</li>
<li>U+2121 TELEPHONE SIGN: not included in any glyphset definition</li>
<li>U+2124 DOUBLE-STRUCK CAPITAL Z: try adding math</li>
<li>U+2128 BLACK-LETTER CAPITAL Z: try adding math</li>
<li>U+212A KELVIN SIGN: not included in any glyphset definition</li>
<li>U+212B ANGSTROM SIGN: not included in any glyphset definition</li>
<li>U+212C SCRIPT CAPITAL B: try adding math</li>
<li>U+212D BLACK-LETTER CAPITAL C: try adding math</li>
<li>U+212F SCRIPT SMALL E: try adding math</li>
<li>U+2130 SCRIPT CAPITAL E: try adding math</li>
<li>U+2131 SCRIPT CAPITAL F: try adding math</li>
<li>U+2133 SCRIPT CAPITAL M: try adding math</li>
<li>U+2134 SCRIPT SMALL O: try adding math</li>
<li>U+2139 INFORMATION SOURCE: not included in any glyphset definition</li>
<li>U+213B FACSIMILE SIGN: not included in any glyphset definition</li>
<li>U+2145 DOUBLE-STRUCK ITALIC CAPITAL D: try adding math</li>
<li>U+2146 DOUBLE-STRUCK ITALIC SMALL D: try adding math</li>
<li>U+2147 DOUBLE-STRUCK ITALIC SMALL E: try adding math</li>
<li>U+2148 DOUBLE-STRUCK ITALIC SMALL I: try adding math</li>
<li>U+2149 DOUBLE-STRUCK ITALIC SMALL J: try adding math</li>
<li>U+2160 ROMAN NUMERAL ONE: try adding symbols</li>
<li>U+2161 ROMAN NUMERAL TWO: try adding symbols</li>
<li>U+2162 ROMAN NUMERAL THREE: try adding symbols</li>
<li>U+2163 ROMAN NUMERAL FOUR: try adding symbols</li>
<li>U+2164 ROMAN NUMERAL FIVE: try adding symbols</li>
<li>U+2165 ROMAN NUMERAL SIX: try adding symbols</li>
<li>U+2166 ROMAN NUMERAL SEVEN: try adding symbols</li>
<li>U+2167 ROMAN NUMERAL EIGHT: try adding symbols</li>
<li>U+2168 ROMAN NUMERAL NINE: try adding symbols</li>
<li>U+2169 ROMAN NUMERAL TEN: try adding symbols</li>
<li>U+216A ROMAN NUMERAL ELEVEN: try adding symbols</li>
<li>U+216B ROMAN NUMERAL TWELVE: try adding symbols</li>
<li>U+216C ROMAN NUMERAL FIFTY: try adding symbols</li>
<li>U+216D ROMAN NUMERAL ONE HUNDRED: try adding symbols</li>
<li>U+216E ROMAN NUMERAL FIVE HUNDRED: try adding symbols</li>
<li>U+216F ROMAN NUMERAL ONE THOUSAND: try adding symbols</li>
<li>U+2170 SMALL ROMAN NUMERAL ONE: try adding symbols</li>
<li>U+2171 SMALL ROMAN NUMERAL TWO: try adding symbols</li>
<li>U+2172 SMALL ROMAN NUMERAL THREE: try adding symbols</li>
<li>U+2173 SMALL ROMAN NUMERAL FOUR: try adding symbols</li>
<li>U+2174 SMALL ROMAN NUMERAL FIVE: try adding symbols</li>
<li>U+2175 SMALL ROMAN NUMERAL SIX: try adding symbols</li>
<li>U+2176 SMALL ROMAN NUMERAL SEVEN: try adding symbols</li>
<li>U+2177 SMALL ROMAN NUMERAL EIGHT: try adding symbols</li>
<li>U+2178 SMALL ROMAN NUMERAL NINE: try adding symbols</li>
<li>U+2179 SMALL ROMAN NUMERAL TEN: try adding symbols</li>
<li>U+217A SMALL ROMAN NUMERAL ELEVEN: try adding symbols</li>
<li>U+217B SMALL ROMAN NUMERAL TWELVE: try adding symbols</li>
<li>U+217C SMALL ROMAN NUMERAL FIFTY: try adding symbols</li>
<li>U+217D SMALL ROMAN NUMERAL ONE HUNDRED: try adding symbols</li>
<li>U+217E SMALL ROMAN NUMERAL FIVE HUNDRED: try adding symbols</li>
<li>U+217F SMALL ROMAN NUMERAL ONE THOUSAND: try adding symbols</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2216 SET MINUS: try adding math</li>
<li>U+2217 ASTERISK OPERATOR: try adding math</li>
<li>U+2218 RING OPERATOR: try adding one of: symbols, math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, yi, symbols, math</li>
<li>U+2223 DIVIDES: try adding math</li>
<li>U+2225 PARALLEL TO: try adding math</li>
<li>U+2236 RATIO: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+226A MUCH LESS-THAN: try adding math</li>
<li>U+226B MUCH GREATER-THAN: try adding math</li>
<li>U+22C5 DOT OPERATOR: try adding one of: symbols, math</li>
<li>U+22EF MIDLINE HORIZONTAL ELLIPSIS: try adding math</li>
<li>U+2303 UP ARROWHEAD: try adding symbols</li>
<li>U+2374 APL FUNCTIONAL SYMBOL RHO: try adding math</li>
<li>U+2400 SYMBOL FOR NULL: try adding symbols</li>
<li>U+2401 SYMBOL FOR START OF HEADING: try adding symbols</li>
<li>U+2402 SYMBOL FOR START OF TEXT: try adding symbols</li>
<li>U+2403 SYMBOL FOR END OF TEXT: try adding symbols</li>
<li>U+2404 SYMBOL FOR END OF TRANSMISSION: try adding symbols</li>
<li>U+2405 SYMBOL FOR ENQUIRY: try adding symbols</li>
<li>U+2406 SYMBOL FOR ACKNOWLEDGE: try adding symbols</li>
<li>U+2407 SYMBOL FOR BELL: try adding symbols</li>
<li>U+2408 SYMBOL FOR BACKSPACE: try adding symbols</li>
<li>U+2409 SYMBOL FOR HORIZONTAL TABULATION: try adding symbols</li>
<li>U+240A SYMBOL FOR LINE FEED: try adding symbols</li>
<li>U+240B SYMBOL FOR VERTICAL TABULATION: try adding symbols</li>
<li>U+240C SYMBOL FOR FORM FEED: try adding symbols</li>
<li>U+240D SYMBOL FOR CARRIAGE RETURN: try adding symbols</li>
<li>U+240E SYMBOL FOR SHIFT OUT: try adding symbols</li>
<li>U+240F SYMBOL FOR SHIFT IN: try adding symbols</li>
<li>U+2410 SYMBOL FOR DATA LINK ESCAPE: try adding symbols</li>
<li>U+2411 SYMBOL FOR DEVICE CONTROL ONE: try adding symbols</li>
<li>U+2412 SYMBOL FOR DEVICE CONTROL TWO: try adding symbols</li>
<li>U+2413 SYMBOL FOR DEVICE CONTROL THREE: try adding symbols</li>
<li>U+2414 SYMBOL FOR DEVICE CONTROL FOUR: try adding symbols</li>
<li>U+2415 SYMBOL FOR NEGATIVE ACKNOWLEDGE: try adding symbols</li>
<li>U+2416 SYMBOL FOR SYNCHRONOUS IDLE: try adding symbols</li>
<li>U+2417 SYMBOL FOR END OF TRANSMISSION BLOCK: try adding symbols</li>
<li>U+2418 SYMBOL FOR CANCEL: try adding symbols</li>
<li>U+2419 SYMBOL FOR END OF MEDIUM: try adding symbols</li>
<li>U+241A SYMBOL FOR SUBSTITUTE: try adding symbols</li>
<li>U+241B SYMBOL FOR ESCAPE: try adding symbols</li>
<li>U+241C SYMBOL FOR FILE SEPARATOR: try adding symbols</li>
<li>U+241D SYMBOL FOR GROUP SEPARATOR: try adding symbols</li>
<li>U+241E SYMBOL FOR RECORD SEPARATOR: try adding symbols</li>
<li>U+241F SYMBOL FOR UNIT SEPARATOR: try adding symbols</li>
<li>U+2420 SYMBOL FOR SPACE: try adding symbols</li>
<li>U+2421 SYMBOL FOR DELETE: try adding symbols</li>
<li>U+2474 PARENTHESIZED DIGIT ONE: try adding one of: symbols, math</li>
<li>U+2475 PARENTHESIZED DIGIT TWO: try adding one of: symbols, math</li>
<li>U+2476 PARENTHESIZED DIGIT THREE: try adding symbols</li>
<li>U+2477 PARENTHESIZED DIGIT FOUR: try adding symbols</li>
<li>U+2478 PARENTHESIZED DIGIT FIVE: try adding symbols</li>
<li>U+2479 PARENTHESIZED DIGIT SIX: try adding symbols</li>
<li>U+247A PARENTHESIZED DIGIT SEVEN: try adding symbols</li>
<li>U+247B PARENTHESIZED DIGIT EIGHT: try adding symbols</li>
<li>U+247C PARENTHESIZED DIGIT NINE: try adding symbols</li>
<li>U+247D PARENTHESIZED NUMBER TEN: try adding symbols</li>
<li>U+247E PARENTHESIZED NUMBER ELEVEN: try adding symbols</li>
<li>U+247F PARENTHESIZED NUMBER TWELVE: try adding symbols</li>
<li>U+2480 PARENTHESIZED NUMBER THIRTEEN: try adding symbols</li>
<li>U+2481 PARENTHESIZED NUMBER FOURTEEN: try adding symbols</li>
<li>U+2482 PARENTHESIZED NUMBER FIFTEEN: try adding symbols</li>
<li>U+2483 PARENTHESIZED NUMBER SIXTEEN: try adding symbols</li>
<li>U+2484 PARENTHESIZED NUMBER SEVENTEEN: try adding symbols</li>
<li>U+2485 PARENTHESIZED NUMBER EIGHTEEN: try adding symbols</li>
<li>U+2486 PARENTHESIZED NUMBER NINETEEN: try adding symbols</li>
<li>U+2487 PARENTHESIZED NUMBER TWENTY: try adding symbols</li>
<li>U+2488 DIGIT ONE FULL STOP: try adding symbols</li>
<li>U+2489 DIGIT TWO FULL STOP: try adding symbols</li>
<li>U+248A DIGIT THREE FULL STOP: try adding symbols</li>
<li>U+248B DIGIT FOUR FULL STOP: try adding symbols</li>
<li>U+248C DIGIT FIVE FULL STOP: try adding symbols</li>
<li>U+248D DIGIT SIX FULL STOP: try adding symbols</li>
<li>U+248E DIGIT SEVEN FULL STOP: try adding symbols</li>
<li>U+248F DIGIT EIGHT FULL STOP: try adding symbols</li>
<li>U+2490 DIGIT NINE FULL STOP: try adding symbols</li>
<li>U+2491 NUMBER TEN FULL STOP: try adding symbols</li>
<li>U+2492 NUMBER ELEVEN FULL STOP: try adding symbols</li>
<li>U+2493 NUMBER TWELVE FULL STOP: try adding symbols</li>
<li>U+2494 NUMBER THIRTEEN FULL STOP: try adding symbols</li>
<li>U+2495 NUMBER FOURTEEN FULL STOP: try adding symbols</li>
<li>U+2496 NUMBER FIFTEEN FULL STOP: try adding symbols</li>
<li>U+2497 NUMBER SIXTEEN FULL STOP: try adding symbols</li>
<li>U+2498 NUMBER SEVENTEEN FULL STOP: try adding symbols</li>
<li>U+2499 NUMBER EIGHTEEN FULL STOP: try adding symbols</li>
<li>U+249A NUMBER NINETEEN FULL STOP: try adding symbols</li>
<li>U+249B NUMBER TWENTY FULL STOP: try adding symbols</li>
<li>U+249C PARENTHESIZED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+249D PARENTHESIZED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+249E PARENTHESIZED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+249F PARENTHESIZED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24A0 PARENTHESIZED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24A1 PARENTHESIZED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24A2 PARENTHESIZED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24A3 PARENTHESIZED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24A4 PARENTHESIZED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24A5 PARENTHESIZED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24A6 PARENTHESIZED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24A7 PARENTHESIZED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24A8 PARENTHESIZED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24A9 PARENTHESIZED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24AA PARENTHESIZED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24AB PARENTHESIZED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24AC PARENTHESIZED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24AD PARENTHESIZED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24AE PARENTHESIZED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24AF PARENTHESIZED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24B0 PARENTHESIZED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24B1 PARENTHESIZED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24B2 PARENTHESIZED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24B3 PARENTHESIZED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24B4 PARENTHESIZED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24B5 PARENTHESIZED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: not included in any glyphset definition</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: not included in any glyphset definition</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+2731 HEAVY ASTERISK: try adding symbols</li>
<li>U+2758 LIGHT VERTICAL BAR: try adding symbols</li>
<li>U+2762 HEAVY EXCLAMATION MARK ORNAMENT: try adding symbols</li>
<li>U+2A74 DOUBLE COLON EQUAL: try adding math</li>
<li>U+2A75 TWO CONSECUTIVE EQUALS SIGNS: try adding math</li>
<li>U+2A76 THREE CONSECUTIVE EQUALS SIGNS: try adding math</li>
<li>U+3001 IDEOGRAPHIC COMMA: try adding one of: chinese-hongkong, chinese-simplified, mongolian, japanese, tai-le, yi, phags-pa, chinese-traditional</li>
<li>U+3008 LEFT ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-simplified, japanese, tai-le, yi, phags-pa, chinese-traditional</li>
<li>U+3009 RIGHT ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-simplified, japanese, tai-le, yi, phags-pa, chinese-traditional</li>
<li>U+300A LEFT DOUBLE ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-simplified, mongolian, japanese, tai-le, lisu, yi, phags-pa, chinese-traditional</li>
<li>U+300B RIGHT DOUBLE ANGLE BRACKET: try adding one of: chinese-hongkong, chinese-simplified, mongolian, japanese, tai-le, lisu, yi, phags-pa, chinese-traditional</li>
<li>U+3250 PARTNERSHIP SIGN: not included in any glyphset definition</li>
<li>U+32CC SQUARE HG: not included in any glyphset definition</li>
<li>U+32CD SQUARE ERG: not included in any glyphset definition</li>
<li>U+32CE SQUARE EV: not included in any glyphset definition</li>
<li>U+32CF LIMITED LIABILITY SIGN: not included in any glyphset definition</li>
<li>U+3371 SQUARE HPA: not included in any glyphset definition</li>
<li>U+3372 SQUARE DA: not included in any glyphset definition</li>
<li>U+3373 SQUARE AU: not included in any glyphset definition</li>
<li>U+3374 SQUARE BAR: not included in any glyphset definition</li>
<li>U+3375 SQUARE OV: not included in any glyphset definition</li>
<li>U+3376 SQUARE PC: not included in any glyphset definition</li>
<li>U+3377 SQUARE DM: not included in any glyphset definition</li>
<li>U+3378 SQUARE DM SQUARED: not included in any glyphset definition</li>
<li>U+3379 SQUARE DM CUBED: not included in any glyphset definition</li>
<li>U+337A SQUARE IU: not included in any glyphset definition</li>
<li>U+3380 SQUARE PA AMPS: not included in any glyphset definition</li>
<li>U+3381 SQUARE NA: not included in any glyphset definition</li>
<li>U+3383 SQUARE MA: not included in any glyphset definition</li>
<li>U+3384 SQUARE KA: not included in any glyphset definition</li>
<li>U+3385 SQUARE KB: not included in any glyphset definition</li>
<li>U+3386 SQUARE MB: not included in any glyphset definition</li>
<li>U+3387 SQUARE GB: not included in any glyphset definition</li>
<li>U+3388 SQUARE CAL: not included in any glyphset definition</li>
<li>U+3389 SQUARE KCAL: not included in any glyphset definition</li>
<li>U+338A SQUARE PF: not included in any glyphset definition</li>
<li>U+338B SQUARE NF: not included in any glyphset definition</li>
<li>U+338E SQUARE MG: not included in any glyphset definition</li>
<li>U+338F SQUARE KG: not included in any glyphset definition</li>
<li>U+3390 SQUARE HZ: not included in any glyphset definition</li>
<li>U+3391 SQUARE KHZ: not included in any glyphset definition</li>
<li>U+3392 SQUARE MHZ: not included in any glyphset definition</li>
<li>U+3393 SQUARE GHZ: not included in any glyphset definition</li>
<li>U+3394 SQUARE THZ: not included in any glyphset definition</li>
<li>U+3396 SQUARE ML: not included in any glyphset definition</li>
<li>U+3397 SQUARE DL: not included in any glyphset definition</li>
<li>U+3398 SQUARE KL: not included in any glyphset definition</li>
<li>U+3399 SQUARE FM: not included in any glyphset definition</li>
<li>U+339A SQUARE NM: not included in any glyphset definition</li>
<li>U+339C SQUARE MM: try adding chinese-simplified</li>
<li>U+339D SQUARE CM: try adding chinese-simplified</li>
<li>U+339E SQUARE KM: not included in any glyphset definition</li>
<li>U+339F SQUARE MM SQUARED: not included in any glyphset definition</li>
<li>U+33A0 SQUARE CM SQUARED: not included in any glyphset definition</li>
<li>U+33A1 SQUARE M SQUARED: try adding chinese-simplified</li>
<li>U+33A2 SQUARE KM SQUARED: not included in any glyphset definition</li>
<li>U+33A3 SQUARE MM CUBED: not included in any glyphset definition</li>
<li>U+33A4 SQUARE CM CUBED: not included in any glyphset definition</li>
<li>U+33A5 SQUARE M CUBED: not included in any glyphset definition</li>
<li>U+33A6 SQUARE KM CUBED: not included in any glyphset definition</li>
<li>U+33A7 SQUARE M OVER S: not included in any glyphset definition</li>
<li>U+33A8 SQUARE M OVER S SQUARED: not included in any glyphset definition</li>
<li>U+33A9 SQUARE PA: not included in any glyphset definition</li>
<li>U+33AA SQUARE KPA: not included in any glyphset definition</li>
<li>U+33AB SQUARE MPA: not included in any glyphset definition</li>
<li>U+33AC SQUARE GPA: not included in any glyphset definition</li>
<li>U+33AD SQUARE RAD: not included in any glyphset definition</li>
<li>U+33AE SQUARE RAD OVER S: not included in any glyphset definition</li>
<li>U+33AF SQUARE RAD OVER S SQUARED: not included in any glyphset definition</li>
<li>U+33B0 SQUARE PS: not included in any glyphset definition</li>
<li>U+33B1 SQUARE NS: not included in any glyphset definition</li>
<li>U+33B3 SQUARE MS: not included in any glyphset definition</li>
<li>U+33B4 SQUARE PV: not included in any glyphset definition</li>
<li>U+33B5 SQUARE NV: not included in any glyphset definition</li>
<li>U+33B7 SQUARE MV: not included in any glyphset definition</li>
<li>U+33B8 SQUARE KV: not included in any glyphset definition</li>
<li>U+33B9 SQUARE MV MEGA: not included in any glyphset definition</li>
<li>U+33BA SQUARE PW: not included in any glyphset definition</li>
<li>U+33BB SQUARE NW: not included in any glyphset definition</li>
<li>U+33BD SQUARE MW: not included in any glyphset definition</li>
<li>U+33BE SQUARE KW: not included in any glyphset definition</li>
<li>U+33BF SQUARE MW MEGA: not included in any glyphset definition</li>
<li>U+33C2 SQUARE AM: not included in any glyphset definition</li>
<li>U+33C3 SQUARE BQ: not included in any glyphset definition</li>
<li>U+33C4 SQUARE CC: not included in any glyphset definition</li>
<li>U+33C5 SQUARE CD: not included in any glyphset definition</li>
<li>U+33C6 SQUARE C OVER KG: not included in any glyphset definition</li>
<li>U+33C7 SQUARE CO: not included in any glyphset definition</li>
<li>U+33C8 SQUARE DB: not included in any glyphset definition</li>
<li>U+33C9 SQUARE GY: not included in any glyphset definition</li>
<li>U+33CA SQUARE HA: not included in any glyphset definition</li>
<li>U+33CB SQUARE HP: not included in any glyphset definition</li>
<li>U+33CC SQUARE IN: not included in any glyphset definition</li>
<li>U+33CD SQUARE KK: not included in any glyphset definition</li>
<li>U+33CE SQUARE KM CAPITAL: not included in any glyphset definition</li>
<li>U+33CF SQUARE KT: not included in any glyphset definition</li>
<li>U+33D0 SQUARE LM: not included in any glyphset definition</li>
<li>U+33D1 SQUARE LN: not included in any glyphset definition</li>
<li>U+33D2 SQUARE LOG: not included in any glyphset definition</li>
<li>U+33D3 SQUARE LX: not included in any glyphset definition</li>
<li>U+33D4 SQUARE MB SMALL: not included in any glyphset definition</li>
<li>U+33D5 SQUARE MIL: not included in any glyphset definition</li>
<li>U+33D6 SQUARE MOL: not included in any glyphset definition</li>
<li>U+33D7 SQUARE PH: not included in any glyphset definition</li>
<li>U+33D8 SQUARE PM: not included in any glyphset definition</li>
<li>U+33D9 SQUARE PPM: not included in any glyphset definition</li>
<li>U+33DA SQUARE PR: not included in any glyphset definition</li>
<li>U+33DB SQUARE SR: not included in any glyphset definition</li>
<li>U+33DC SQUARE SV: not included in any glyphset definition</li>
<li>U+33DD SQUARE WB: not included in any glyphset definition</li>
<li>U+33DE SQUARE V OVER M: not included in any glyphset definition</li>
<li>U+33DF SQUARE A OVER M: not included in any glyphset definition</li>
<li>U+33FF SQUARE GAL: not included in any glyphset definition</li>
<li>U+F6BE : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB05 LATIN SMALL LIGATURE LONG S T: not included in any glyphset definition</li>
<li>U+FB06 LATIN SMALL LIGATURE ST: not included in any glyphset definition</li>
<li>U+FB29 HEBREW LETTER ALTERNATIVE PLUS SIGN: try adding hebrew</li>
<li>U+FE10 PRESENTATION FORM FOR VERTICAL COMMA: not included in any glyphset definition</li>
<li>U+FE11 PRESENTATION FORM FOR VERTICAL IDEOGRAPHIC COMMA: not included in any glyphset definition</li>
<li>U+FE13 PRESENTATION FORM FOR VERTICAL COLON: not included in any glyphset definition</li>
<li>U+FE14 PRESENTATION FORM FOR VERTICAL SEMICOLON: not included in any glyphset definition</li>
<li>U+FE15 PRESENTATION FORM FOR VERTICAL EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+FE16 PRESENTATION FORM FOR VERTICAL QUESTION MARK: not included in any glyphset definition</li>
<li>U+FE19 PRESENTATION FORM FOR VERTICAL HORIZONTAL ELLIPSIS: not included in any glyphset definition</li>
<li>U+FE30 PRESENTATION FORM FOR VERTICAL TWO DOT LEADER: try adding chinese-simplified</li>
<li>U+FE31 PRESENTATION FORM FOR VERTICAL EM DASH: try adding chinese-simplified</li>
<li>U+FE32 PRESENTATION FORM FOR VERTICAL EN DASH: not included in any glyphset definition</li>
<li>U+FE33 PRESENTATION FORM FOR VERTICAL LOW LINE: not included in any glyphset definition</li>
<li>U+FE34 PRESENTATION FORM FOR VERTICAL WAVY LOW LINE: try adding chinese-simplified</li>
<li>U+FE35 PRESENTATION FORM FOR VERTICAL LEFT PARENTHESIS: try adding chinese-simplified</li>
<li>U+FE36 PRESENTATION FORM FOR VERTICAL RIGHT PARENTHESIS: try adding chinese-simplified</li>
<li>U+FE37 PRESENTATION FORM FOR VERTICAL LEFT CURLY BRACKET: not included in any glyphset definition</li>
<li>U+FE38 PRESENTATION FORM FOR VERTICAL RIGHT CURLY BRACKET: not included in any glyphset definition</li>
<li>U+FE3D PRESENTATION FORM FOR VERTICAL LEFT DOUBLE ANGLE BRACKET: try adding one of: mongolian, chinese-simplified</li>
<li>U+FE3E PRESENTATION FORM FOR VERTICAL RIGHT DOUBLE ANGLE BRACKET: try adding one of: mongolian, chinese-simplified</li>
<li>U+FE3F PRESENTATION FORM FOR VERTICAL LEFT ANGLE BRACKET: try adding chinese-simplified</li>
<li>U+FE40 PRESENTATION FORM FOR VERTICAL RIGHT ANGLE BRACKET: try adding chinese-simplified</li>
<li>U+FE47 PRESENTATION FORM FOR VERTICAL LEFT SQUARE BRACKET: not included in any glyphset definition</li>
<li>U+FE48 PRESENTATION FORM FOR VERTICAL RIGHT SQUARE BRACKET: not included in any glyphset definition</li>
<li>U+FE49 DASHED OVERLINE: not included in any glyphset definition</li>
<li>U+FE4A CENTRELINE OVERLINE: not included in any glyphset definition</li>
<li>U+FE4B WAVY OVERLINE: try adding chinese-simplified</li>
<li>U+FE4C DOUBLE WAVY OVERLINE: try adding chinese-simplified</li>
<li>U+FE4D DASHED LOW LINE: not included in any glyphset definition</li>
<li>U+FE4E CENTRELINE LOW LINE: try adding chinese-simplified</li>
<li>U+FE4F WAVY LOW LINE: try adding chinese-simplified</li>
<li>U+FE50 SMALL COMMA: try adding chinese-simplified</li>
<li>U+FE51 SMALL IDEOGRAPHIC COMMA: try adding chinese-simplified</li>
<li>U+FE52 SMALL FULL STOP: try adding chinese-simplified</li>
<li>U+FE54 SMALL SEMICOLON: not included in any glyphset definition</li>
<li>U+FE55 SMALL COLON: try adding chinese-simplified</li>
<li>U+FE56 SMALL QUESTION MARK: try adding chinese-simplified</li>
<li>U+FE57 SMALL EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+FE58 SMALL EM DASH: not included in any glyphset definition</li>
<li>U+FE59 SMALL LEFT PARENTHESIS: not included in any glyphset definition</li>
<li>U+FE5A SMALL RIGHT PARENTHESIS: try adding chinese-simplified</li>
<li>U+FE5B SMALL LEFT CURLY BRACKET: not included in any glyphset definition</li>
<li>U+FE5C SMALL RIGHT CURLY BRACKET: not included in any glyphset definition</li>
<li>U+FE5F SMALL NUMBER SIGN: not included in any glyphset definition</li>
<li>U+FE60 SMALL AMPERSAND: not included in any glyphset definition</li>
<li>U+FE61 SMALL ASTERISK: try adding chinese-simplified</li>
<li>U+FE62 SMALL PLUS SIGN: not included in any glyphset definition</li>
<li>U+FE63 SMALL HYPHEN-MINUS: try adding chinese-simplified</li>
<li>U+FE64 SMALL LESS-THAN SIGN: try adding chinese-simplified</li>
<li>U+FE65 SMALL GREATER-THAN SIGN: try adding chinese-simplified</li>
<li>U+FE66 SMALL EQUALS SIGN: not included in any glyphset definition</li>
<li>U+FE68 SMALL REVERSE SOLIDUS: not included in any glyphset definition</li>
<li>U+FE69 SMALL DOLLAR SIGN: not included in any glyphset definition</li>
<li>U+FE6A SMALL PERCENT SIGN: not included in any glyphset definition</li>
<li>U+FE6B SMALL COMMERCIAL AT: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF04 FULLWIDTH DOLLAR SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: japanese, chinese-simplified</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0B FULLWIDTH PLUS SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF10 FULLWIDTH DIGIT ZERO: try adding one of: japanese, chinese-simplified</li>
<li>U+FF11 FULLWIDTH DIGIT ONE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF12 FULLWIDTH DIGIT TWO: try adding one of: japanese, chinese-simplified</li>
<li>U+FF13 FULLWIDTH DIGIT THREE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF14 FULLWIDTH DIGIT FOUR: try adding one of: japanese, chinese-simplified</li>
<li>U+FF15 FULLWIDTH DIGIT FIVE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF16 FULLWIDTH DIGIT SIX: try adding one of: japanese, chinese-simplified</li>
<li>U+FF17 FULLWIDTH DIGIT SEVEN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF18 FULLWIDTH DIGIT EIGHT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF19 FULLWIDTH DIGIT NINE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF1C FULLWIDTH LESS-THAN SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF1D FULLWIDTH EQUALS SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF1E FULLWIDTH GREATER-THAN SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF21 FULLWIDTH LATIN CAPITAL LETTER A: try adding one of: japanese, chinese-simplified</li>
<li>U+FF22 FULLWIDTH LATIN CAPITAL LETTER B: try adding one of: japanese, chinese-simplified</li>
<li>U+FF23 FULLWIDTH LATIN CAPITAL LETTER C: try adding one of: japanese, chinese-simplified</li>
<li>U+FF24 FULLWIDTH LATIN CAPITAL LETTER D: try adding one of: japanese, chinese-simplified</li>
<li>U+FF25 FULLWIDTH LATIN CAPITAL LETTER E: try adding one of: japanese, chinese-simplified</li>
<li>U+FF26 FULLWIDTH LATIN CAPITAL LETTER F: try adding one of: japanese, chinese-simplified</li>
<li>U+FF27 FULLWIDTH LATIN CAPITAL LETTER G: try adding one of: japanese, chinese-simplified</li>
<li>U+FF28 FULLWIDTH LATIN CAPITAL LETTER H: try adding one of: japanese, chinese-simplified</li>
<li>U+FF29 FULLWIDTH LATIN CAPITAL LETTER I: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2A FULLWIDTH LATIN CAPITAL LETTER J: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2B FULLWIDTH LATIN CAPITAL LETTER K: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2C FULLWIDTH LATIN CAPITAL LETTER L: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2D FULLWIDTH LATIN CAPITAL LETTER M: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2E FULLWIDTH LATIN CAPITAL LETTER N: try adding one of: japanese, chinese-simplified</li>
<li>U+FF2F FULLWIDTH LATIN CAPITAL LETTER O: try adding one of: japanese, chinese-simplified</li>
<li>U+FF30 FULLWIDTH LATIN CAPITAL LETTER P: try adding one of: japanese, chinese-simplified</li>
<li>U+FF31 FULLWIDTH LATIN CAPITAL LETTER Q: try adding one of: japanese, chinese-simplified</li>
<li>U+FF32 FULLWIDTH LATIN CAPITAL LETTER R: try adding one of: japanese, chinese-simplified</li>
<li>U+FF33 FULLWIDTH LATIN CAPITAL LETTER S: try adding one of: japanese, chinese-simplified</li>
<li>U+FF34 FULLWIDTH LATIN CAPITAL LETTER T: try adding one of: japanese, chinese-simplified</li>
<li>U+FF35 FULLWIDTH LATIN CAPITAL LETTER U: try adding one of: japanese, chinese-simplified</li>
<li>U+FF36 FULLWIDTH LATIN CAPITAL LETTER V: try adding one of: japanese, chinese-simplified</li>
<li>U+FF37 FULLWIDTH LATIN CAPITAL LETTER W: try adding one of: japanese, chinese-simplified</li>
<li>U+FF38 FULLWIDTH LATIN CAPITAL LETTER X: try adding one of: japanese, chinese-simplified</li>
<li>U+FF39 FULLWIDTH LATIN CAPITAL LETTER Y: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3A FULLWIDTH LATIN CAPITAL LETTER Z: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF3E FULLWIDTH CIRCUMFLEX ACCENT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: japanese, chinese-simplified</li>
<li>U+FF40 FULLWIDTH GRAVE ACCENT: try adding one of: japanese, chinese-simplified</li>
<li>U+FF41 FULLWIDTH LATIN SMALL LETTER A: try adding one of: japanese, chinese-simplified</li>
<li>U+FF42 FULLWIDTH LATIN SMALL LETTER B: try adding one of: japanese, chinese-simplified</li>
<li>U+FF43 FULLWIDTH LATIN SMALL LETTER C: try adding one of: japanese, chinese-simplified</li>
<li>U+FF44 FULLWIDTH LATIN SMALL LETTER D: try adding one of: japanese, chinese-simplified</li>
<li>U+FF45 FULLWIDTH LATIN SMALL LETTER E: try adding one of: japanese, chinese-simplified</li>
<li>U+FF46 FULLWIDTH LATIN SMALL LETTER F: try adding one of: japanese, chinese-simplified</li>
<li>U+FF47 FULLWIDTH LATIN SMALL LETTER G: try adding one of: japanese, chinese-simplified</li>
<li>U+FF48 FULLWIDTH LATIN SMALL LETTER H: try adding one of: japanese, chinese-simplified</li>
<li>U+FF49 FULLWIDTH LATIN SMALL LETTER I: try adding one of: japanese, chinese-simplified</li>
<li>U+FF4A FULLWIDTH LATIN SMALL LETTER J: try adding japanese</li>
<li>U+FF4B FULLWIDTH LATIN SMALL LETTER K: try adding one of: japanese, chinese-simplified</li>
<li>U+FF4C FULLWIDTH LATIN SMALL LETTER L: try adding one of: japanese, chinese-simplified</li>
<li>U+FF4D FULLWIDTH LATIN SMALL LETTER M: try adding one of: japanese, chinese-simplified</li>
<li>U+FF4E FULLWIDTH LATIN SMALL LETTER N: try adding one of: japanese, chinese-simplified</li>
<li>U+FF4F FULLWIDTH LATIN SMALL LETTER O: try adding one of: japanese, chinese-simplified</li>
<li>U+FF50 FULLWIDTH LATIN SMALL LETTER P: try adding one of: japanese, chinese-simplified</li>
<li>U+FF51 FULLWIDTH LATIN SMALL LETTER Q: try adding one of: japanese, chinese-simplified</li>
<li>U+FF52 FULLWIDTH LATIN SMALL LETTER R: try adding one of: japanese, chinese-simplified</li>
<li>U+FF53 FULLWIDTH LATIN SMALL LETTER S: try adding one of: japanese, chinese-simplified</li>
<li>U+FF54 FULLWIDTH LATIN SMALL LETTER T: try adding one of: japanese, chinese-simplified</li>
<li>U+FF55 FULLWIDTH LATIN SMALL LETTER U: try adding one of: japanese, chinese-simplified</li>
<li>U+FF56 FULLWIDTH LATIN SMALL LETTER V: try adding one of: japanese, chinese-simplified</li>
<li>U+FF57 FULLWIDTH LATIN SMALL LETTER W: try adding one of: japanese, chinese-simplified</li>
<li>U+FF58 FULLWIDTH LATIN SMALL LETTER X: try adding one of: japanese, chinese-simplified</li>
<li>U+FF59 FULLWIDTH LATIN SMALL LETTER Y: try adding one of: japanese, chinese-simplified</li>
<li>U+FF5A FULLWIDTH LATIN SMALL LETTER Z: try adding japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: japanese, yi, chinese-simplified, math</li>
<li>U+FF5C FULLWIDTH VERTICAL LINE: try adding one of: japanese, yi, chinese-simplified</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: japanese, yi, chinese-simplified, math</li>
<li>U+FF5E FULLWIDTH TILDE: try adding one of: yi, chinese-simplified</li>
<li>U+FF64 HALFWIDTH IDEOGRAPHIC COMMA: try adding yi</li>
<li>U+FFE0 FULLWIDTH CENT SIGN: try adding chinese-simplified</li>
<li>U+FFE1 FULLWIDTH POUND SIGN: try adding chinese-simplified</li>
<li>U+FFE2 FULLWIDTH NOT SIGN: not included in any glyphset definition</li>
<li>U+FFE3 FULLWIDTH MACRON: try adding one of: japanese, chinese-simplified</li>
<li>U+FFE4 FULLWIDTH BROKEN BAR: not included in any glyphset definition</li>
<li>U+FFE5 FULLWIDTH YEN SIGN: try adding one of: japanese, chinese-simplified</li>
<li>U+FFE8 HALFWIDTH FORMS LIGHT VERTICAL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain less than 150 CJK characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>There are only 102 CJK glyphs when there needs to be at least 150 in order to support the smallest CJK writing system, Kana.
The following CJK glyphs were found:
['uni3250', 'uni32CC', 'uni32CD', 'uni32CE', 'uni32CF', 'uni3371', 'uni3372', 'uni3373', 'uni3374', 'uni3375', 'uni3376', 'uni3377', 'uni3378', 'uni3379', 'uni337A', 'uni3380', 'uni3381', 'uni3383', 'uni3384', 'uni3385', 'uni3386', 'uni3387', 'uni3388', 'uni3389', 'uni338A', 'uni338B', 'uni338E', 'uni338F', 'uni3390', 'uni3391', 'uni3392', 'uni3393', 'uni3394', 'uni3396', 'uni3397', 'uni3398', 'uni3399', 'uni339A', 'uni339C', 'uni339D', 'uni339E', 'uni339F', 'uni33A0', 'uni33A1', 'uni33A2', 'uni33A3', 'uni33A4', 'uni33A5', 'uni33A6', 'uni33A7', 'uni33A8', 'uni33A9', 'uni33AA', 'uni33AB', 'uni33AC', 'uni33AD', 'uni33AE', 'uni33AF', 'uni33B0', 'uni33B1', 'uni33B3', 'uni33B4', 'uni33B5', 'uni33B7', 'uni33B8', 'uni33B9', 'uni33BA', 'uni33BB', 'uni33BD', 'uni33BE', 'uni33BF', 'uni33C2', 'uni33C3', 'uni33C4', 'uni33C5', 'uni33C6', 'uni33C7', 'uni33C8', 'uni33C9', 'uni33CA', 'uni33CB', 'uni33CC', 'uni33CD', 'uni33CE', 'uni33CF', 'uni33D0', 'uni33D1', 'uni33D2', 'uni33D3', 'uni33D4', 'uni33D5', 'uni33D6', 'uni33D7', 'uni33D8', 'uni33D9', 'uni33DA', 'uni33DB', 'uni33DC', 'uni33DD', 'uni33DE', 'uni33DF', 'uni33FF']
Please check that these glyphs have the correct unicodes.</p>
 [code: cjk-not-enough-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID is 'PfEd', a font editor default. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: bad]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/handy0.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 15 | 14 | 126 | 7 | 89 | 0 | 
| 0% | 0% | 6% | 6% | 50% | 3% | 35% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
