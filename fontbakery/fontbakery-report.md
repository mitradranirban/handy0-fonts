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



<details><summary>[21] handy0.ttf</summary>
<div>
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
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2095, but got 2094 instead</p>
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







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1638) and hhea ascent (2094) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



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
<p>&quot;Copyright (c) 2024, Dr Anirban Mitra&quot;</p>
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
<td align="left">handy0</td>
<td align="left">handy0</td>
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


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201C (LEFT DOUBLE QUOTATION MARK)


- 0x201D (RIGHT DOUBLE QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;377&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;377&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



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

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: Aring	Contours detected: 2	Expected: 3 or 4

- Glyph name: Ecircumflex	Contours detected: 1	Expected: 2

- Glyph name: Edieresis	Contours detected: 1	Expected: 3

- Glyph name: Igrave	Contours detected: 1	Expected: 2

- Glyph name: Iacute	Contours detected: 1	Expected: 2

- Glyph name: Icircumflex	Contours detected: 1	Expected: 2

- Glyph name: Idieresis	Contours detected: 1	Expected: 3

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Ntilde	Contours detected: 1	Expected: 2

- Glyph name: Ograve	Contours detected: 2	Expected: 3

- Glyph name: Oacute	Contours detected: 2	Expected: 3

- Glyph name: Ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: Otilde	Contours detected: 2	Expected: 3

- Glyph name: Odieresis	Contours detected: 2	Expected: 4

- Glyph name: Ugrave	Contours detected: 1	Expected: 2

- Glyph name: Uacute	Contours detected: 1	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 1	Expected: 2

- Glyph name: Udieresis	Contours detected: 1	Expected: 3

- Glyph name: Yacute	Contours detected: 1	Expected: 2

- Glyph name: agrave	Contours detected: 1	Expected: 3

- Glyph name: aacute	Contours detected: 1	Expected: 3

- Glyph name: acircumflex	Contours detected: 1	Expected: 3

- Glyph name: atilde	Contours detected: 1	Expected: 3

- Glyph name: adieresis	Contours detected: 1	Expected: 4

- Glyph name: aring	Contours detected: 1	Expected: 4

- Glyph name: egrave	Contours detected: 1	Expected: 3

- Glyph name: eacute	Contours detected: 1	Expected: 3

- Glyph name: ecircumflex	Contours detected: 1	Expected: 3

- Glyph name: edieresis	Contours detected: 1	Expected: 4

- Glyph name: idieresis	Contours detected: 2	Expected: 3

- Glyph name: ntilde	Contours detected: 1	Expected: 2

- Glyph name: ograve	Contours detected: 1	Expected: 3

- Glyph name: oacute	Contours detected: 1	Expected: 3

- Glyph name: ocircumflex	Contours detected: 1	Expected: 3

- Glyph name: otilde	Contours detected: 1	Expected: 3

- Glyph name: odieresis	Contours detected: 1	Expected: 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: ugrave	Contours detected: 1	Expected: 2

- Glyph name: uacute	Contours detected: 1	Expected: 2

- Glyph name: ucircumflex	Contours detected: 1	Expected: 2

- Glyph name: udieresis	Contours detected: 1	Expected: 3

- Glyph name: yacute	Contours detected: 1	Expected: 2

- Glyph name: ydieresis	Contours detected: 1	Expected: 3

- Glyph name: Aring	Contours detected: 2	Expected: 3 or 4

- Glyph name: B	Contours detected: 1	Expected: 2 or 3

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Ecircumflex	Contours detected: 1	Expected: 2

- Glyph name: Edieresis	Contours detected: 1	Expected: 3

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Iacute	Contours detected: 1	Expected: 2

- Glyph name: Icircumflex	Contours detected: 1	Expected: 2

- Glyph name: Idieresis	Contours detected: 1	Expected: 3

- Glyph name: Igrave	Contours detected: 1	Expected: 2

- Glyph name: Ntilde	Contours detected: 1	Expected: 2

- Glyph name: Oacute	Contours detected: 2	Expected: 3

- Glyph name: Ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: Odieresis	Contours detected: 2	Expected: 4

- Glyph name: Ograve	Contours detected: 2	Expected: 3

- Glyph name: Otilde	Contours detected: 2	Expected: 3

- Glyph name: Uacute	Contours detected: 1	Expected: 2

- Glyph name: Ucircumflex	Contours detected: 1	Expected: 2

- Glyph name: Udieresis	Contours detected: 1	Expected: 3

- Glyph name: Ugrave	Contours detected: 1	Expected: 2

- Glyph name: V	Contours detected: 2	Expected: 1

- Glyph name: Yacute	Contours detected: 1	Expected: 2

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: aacute	Contours detected: 1	Expected: 3

- Glyph name: acircumflex	Contours detected: 1	Expected: 3

- Glyph name: adieresis	Contours detected: 1	Expected: 4

- Glyph name: agrave	Contours detected: 1	Expected: 3

- Glyph name: aring	Contours detected: 1	Expected: 4

- Glyph name: at	Contours detected: 1	Expected: 2

- Glyph name: atilde	Contours detected: 1	Expected: 3

- Glyph name: bar	Contours detected: 2	Expected: 1

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 1	Expected: 3

- Glyph name: ecircumflex	Contours detected: 1	Expected: 3

- Glyph name: edieresis	Contours detected: 1	Expected: 4

- Glyph name: egrave	Contours detected: 1	Expected: 3

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: f	Contours detected: 2	Expected: 1

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: idieresis	Contours detected: 2	Expected: 3

- Glyph name: ntilde	Contours detected: 1	Expected: 2

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: oacute	Contours detected: 1	Expected: 3

- Glyph name: ocircumflex	Contours detected: 1	Expected: 3

- Glyph name: odieresis	Contours detected: 1	Expected: 4

- Glyph name: ograve	Contours detected: 1	Expected: 3

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 1	Expected: 3

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: uacute	Contours detected: 1	Expected: 2

- Glyph name: ucircumflex	Contours detected: 1	Expected: 2

- Glyph name: udieresis	Contours detected: 1	Expected: 3

- Glyph name: ugrave	Contours detected: 1	Expected: 2

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: v	Contours detected: 2	Expected: 1

- Glyph name: w	Contours detected: 2	Expected: 1

- Glyph name: yacute	Contours detected: 1	Expected: 2

- Glyph name: ydieresis	Contours detected: 1	Expected: 3
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
plusminus</p>
<p>Width = 790:
divide</p>
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
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* A (U+0041): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* A (U+0041): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* Aacute (U+00C1): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* Aacute (U+00C1): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* Acircumflex (U+00C2): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* Acircumflex (U+00C2): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* Agrave (U+00C0): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* Agrave (U+00C0): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* Aring (U+00C5): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* Aring (U+00C5): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* Atilde (U+00C3): X=424.0,Y=1432.0 (should be at cap-height 1434?)

* Atilde (U+00C3): X=1027.0,Y=1436.0 (should be at cap-height 1434?)

* B (U+0042): X=524.0,Y=1.0 (should be at baseline 0?)

* D (U+0044): X=433.0,Y=1436.0 (should be at cap-height 1434?)

* E (U+0045): X=178.0,Y=1436.0 (should be at cap-height 1434?)

* Eacute (U+00C9): X=178.0,Y=1436.0 (should be at cap-height 1434?)

* Ecircumflex (U+00CA): X=178.0,Y=1436.0 (should be at cap-height 1434?)

* Edieresis (U+00CB): X=178.0,Y=1436.0 (should be at cap-height 1434?)

* Egrave (U+00C8): X=178.0,Y=1436.0 (should be at cap-height 1434?)

* Eth (U+00D0): X=433.0,Y=1436.0 (should be at cap-height 1434?)

* N (U+004E): X=1935.5,Y=1432.0 (should be at cap-height 1434?)

* Ntilde (U+00D1): X=807.0,Y=1434.5 (should be at cap-height 1434?)

* Ntilde (U+00D1): X=1536.5,Y=1.0 (should be at baseline 0?)

* Q (U+0051): X=126.5,Y=1432.5 (should be at cap-height 1434?)

* R (U+0052): X=1017.0,Y=1435.0 (should be at cap-height 1434?)

* R (U+0052): X=287.0,Y=1432.0 (should be at cap-height 1434?)

* S (U+0053): X=721.5,Y=1.5 (should be at baseline 0?)

* S (U+0053): X=372.5,Y=1432.0 (should be at cap-height 1434?)

* S (U+0053): X=551.0,Y=1433.0 (should be at cap-height 1434?)

* S (U+0053): X=554.0,Y=1433.0 (should be at cap-height 1434?)

* S (U+0053): X=609.0,Y=1435.0 (should be at cap-height 1434?)

* U (U+0055): X=212.0,Y=1636.0 (should be at ascender 1638?)

* Uacute (U+00DA): X=212.0,Y=1636.0 (should be at ascender 1638?)

* Ucircumflex (U+00DB): X=212.0,Y=1636.0 (should be at ascender 1638?)

* Udieresis (U+00DC): X=212.0,Y=1636.0 (should be at ascender 1638?)

* Ugrave (U+00D9): X=212.0,Y=1636.0 (should be at ascender 1638?)

* V (U+0056): X=1491.0,Y=1433.0 (should be at cap-height 1434?)

* Z (U+005A): X=971.0,Y=1435.0 (should be at cap-height 1434?)

* braceleft (U+007B): X=425.5,Y=2.0 (should be at baseline 0?)

* braceright (U+007D): X=111.5,Y=2.0 (should be at baseline 0?)

* cedilla (U+00B8): X=133.0,Y=-412.0 (should be at descender -410?)

* cedilla (U+00B8): X=135.0,Y=-412.0 (should be at descender -410?)

* cedilla (U+00B8): X=258.0,Y=-408.0 (should be at descender -410?)

* dollar (U+0024): X=614.0,Y=-2.0 (should be at baseline 0?)

* e (U+0065): X=346.0,Y=1.0 (should be at baseline 0?)

* eacute (U+00E9): X=346.0,Y=1.0 (should be at baseline 0?)

* ecircumflex (U+00EA): X=346.0,Y=1.0 (should be at baseline 0?)

* edieresis (U+00EB): X=346.0,Y=1.0 (should be at baseline 0?)

* egrave (U+00E8): X=346.0,Y=1.0 (should be at baseline 0?)

* five (U+0035): X=310.0,Y=1637.0 (should be at ascender 1638?)

* four (U+0034): X=52.0,Y=1637.0 (should be at ascender 1638?)

* four (U+0034): X=574.0,Y=2.0 (should be at baseline 0?)

* m (U+006D): X=174.0,Y=-2.0 (should be at baseline 0?)

* nine (U+0039): X=684.0,Y=1433.0 (should be at cap-height 1434?)

* nine (U+0039): X=684.0,Y=-2.0 (should be at baseline 0?)

* nine (U+0039): X=797.5,Y=1434.5 (should be at cap-height 1434?)

* o (U+006F): X=503.0,Y=-2.0 (should be at baseline 0?)

* oacute (U+00F3): X=503.0,Y=-2.0 (should be at baseline 0?)

* ocircumflex (U+00F4): X=503.0,Y=-2.0 (should be at baseline 0?)

* odieresis (U+00F6): X=503.0,Y=-2.0 (should be at baseline 0?)

* ograve (U+00F2): X=503.0,Y=-2.0 (should be at baseline 0?)

* one (U+0031): X=335.0,Y=1433.0 (should be at cap-height 1434?)

* onehalf (U+00BD): X=341.0,Y=1.0 (should be at baseline 0?)

* ordmasculine (U+00BA): X=503.0,Y=-2.0 (should be at baseline 0?)

* oslash (U+00F8): X=503.0,Y=-2.0 (should be at baseline 0?)

* otilde (U+00F5): X=503.0,Y=-2.0 (should be at baseline 0?)

* parenleft (U+0028): X=675.0,Y=-408.0 (should be at descender -410?)

* parenleft (U+0028): X=787.0,Y=-411.0 (should be at descender -410?)

* q (U+0071): X=514.0,Y=2.0 (should be at baseline 0?)

* seven (U+0037): X=13.0,Y=1636.0 (should be at ascender 1638?)

* threequarters (U+00BE): X=257.0,Y=-1.0 (should be at baseline 0?)

* two (U+0032): X=237.0,Y=1432.0 (should be at cap-height 1434?)

* underscore (U+005F): X=-51.0,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* quotesingle (U+0027): B&lt;&lt;1369.5,1178.0&gt;-&lt;1365.0,1177.0&gt;-&lt;1358.0,1176.0&gt;&gt;/B&lt;&lt;1358.0,1176.0&gt;-&lt;1369.0,1176.0&gt;-&lt;1376.0,1179.0&gt;&gt; = 8.13010235415596
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

* Acircumflex (U+00C2): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Adieresis (U+00C4): L&lt;&lt;170.0,393.0&gt;--&lt;171.0,508.0&gt;&gt;

* Agrave (U+00C0): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Aring (U+00C5): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* Atilde (U+00C3): L&lt;&lt;154.0,373.0&gt;--&lt;155.0,488.0&gt;&gt;

* B (U+0042): L&lt;&lt;1439.0,140.0&gt;--&lt;1440.0,309.0&gt;&gt;

* B (U+0042): L&lt;&lt;155.0,846.0&gt;--&lt;154.0,634.0&gt;&gt;

* C (U+0043): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* Ccedilla (U+00C7): L&lt;&lt;106.0,741.0&gt;--&lt;107.0,331.0&gt;&gt;

* E (U+0045): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;1016.0,115.0&gt;--&lt;548.0,117.0&gt;&gt;

* F (U+0046): L&lt;&lt;62.0,1123.0&gt;--&lt;61.0,975.0&gt;&gt;

* I (U+0049): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Iacute (U+00CD): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Icircumflex (U+00CE): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Idieresis (U+00CF): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* Igrave (U+00CC): L&lt;&lt;462.0,685.0&gt;--&lt;463.0,959.0&gt;&gt;

* J (U+004A): L&lt;&lt;787.0,685.0&gt;--&lt;788.0,506.0&gt;&gt;

* M (U+004D): L&lt;&lt;534.0,1351.0&gt;--&lt;674.0,1352.0&gt;&gt;

* N (U+004E): L&lt;&lt;1974.0,1040.0&gt;--&lt;1975.0,1189.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;1990.0,1015.0&gt;--&lt;1991.0,1164.0&gt;&gt;

* O (U+004F): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Oacute (U+00D3): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Ocircumflex (U+00D4): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Odieresis (U+00D6): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Ograve (U+00D2): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Oslash (U+00D8): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* Otilde (U+00D5): L&lt;&lt;145.0,664.0&gt;--&lt;143.0,898.0&gt;&gt;

* asterisk (U+002A): L&lt;&lt;253.0,857.0&gt;--&lt;102.0,858.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;281.0,119.0&gt;--&lt;283.0,709.0&gt;&gt;

* brokenbar (U+00A6): L&lt;&lt;281.0,928.0&gt;--&lt;285.0,1491.0&gt;&gt;

* four (U+0034): L&lt;&lt;953.0,1223.0&gt;--&lt;954.0,1107.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;123.0,899.0&gt;--&lt;700.0,895.0&gt;&gt;

* logicalnot (U+00AC): L&lt;&lt;701.0,997.0&gt;--&lt;123.0,1001.0&gt;&gt;
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

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* B (U+0042) has a counter-clockwise outer contour

* C (U+0043) has a counter-clockwise outer contour

* Ccedilla (U+00C7) has a counter-clockwise outer contour

* D (U+0044) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Eth (U+00D0) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* G (U+0047) has a counter-clockwise outer contour

* H (U+0048) has a counter-clockwise outer contour

* I (U+0049) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* J (U+004A) has a counter-clockwise outer contour

* K (U+004B) has a counter-clockwise outer contour

* L (U+004C) has a counter-clockwise outer contour

* M (U+004D) has a counter-clockwise outer contour

* N (U+004E) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* O (U+004F) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Odieresis (U+00D6) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Oslash (U+00D8) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* P (U+0050) has a counter-clockwise outer contour

* Q (U+0051) has a counter-clockwise outer contour

* R (U+0052) has a counter-clockwise outer contour

* S (U+0053) has a counter-clockwise outer contour

* T (U+0054) has a counter-clockwise outer contour

* U (U+0055) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* V (U+0056) has a counter-clockwise outer contour

* W (U+0057) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* Y (U+0059) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Z (U+005A) has a counter-clockwise outer contour

* a (U+0061) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acute (U+00B4) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* ampersand (U+0026) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* asciicircum (U+005E) has a counter-clockwise outer contour

* asciitilde (U+007E) has a counter-clockwise outer contour

* asterisk (U+002A) has a counter-clockwise outer contour

* at (U+0040) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* b (U+0062) has a counter-clockwise outer contour

* backslash (U+005C) has a counter-clockwise outer contour

* bar (U+007C) has a counter-clockwise outer contour

* bar (U+007C) has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* braceright (U+007D) has a counter-clockwise outer contour

* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* c (U+0063) has a counter-clockwise outer contour

* ccedilla (U+00E7) has a counter-clockwise outer contour

* cedilla (U+00B8) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* colon (U+003A) has a counter-clockwise outer contour

* comma (U+002C) has a counter-clockwise outer contour

* copyright (U+00A9) has a counter-clockwise outer contour

* currency (U+00A4) has a counter-clockwise outer contour

* d (U+0064) has a counter-clockwise outer contour

* degree (U+00B0) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* dieresis (U+00A8) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* dollar (U+0024) has a counter-clockwise outer contour

* e (U+0065) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* eight (U+0038) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* equal (U+003D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* f (U+0066) has a counter-clockwise outer contour

* five (U+0035) has a counter-clockwise outer contour

* four (U+0034) has a counter-clockwise outer contour

* g (U+0067) has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* greater (U+003E) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* h (U+0068) has a counter-clockwise outer contour

* hyphen (U+002D) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* j (U+006A) has a counter-clockwise outer contour

* k (U+006B) has a counter-clockwise outer contour

* l (U+006C) has a counter-clockwise outer contour

* less (U+003C) has a counter-clockwise outer contour

* logicalnot (U+00AC) has a counter-clockwise outer contour

* m (U+006D) has a counter-clockwise outer contour

* macron (U+00AF) has a counter-clockwise outer contour

* mu (U+00B5) has a counter-clockwise outer contour

* n (U+006E) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* numbersign (U+0023) has a counter-clockwise outer contour

* o (U+006F) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

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

* quotesingle (U+0027) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* r (U+0072) has a counter-clockwise outer contour

* registered (U+00AE) has a counter-clockwise outer contour

* s (U+0073) has a counter-clockwise outer contour

* section (U+00A7) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* slash (U+002F) has a counter-clockwise outer contour

* sterling (U+00A3) has a counter-clockwise outer contour

* t (U+0074) has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* two (U+0032) has a counter-clockwise outer contour

* u (U+0075) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* underscore (U+005F) has a counter-clockwise outer contour

* uni0000 (U+0000) has a counter-clockwise outer contour

* uni00AD (U+00AD) has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* v (U+0076) has a path with no bounds (probably a single point)

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a counter-clockwise outer contour

* w (U+0077) has a path with no bounds (probably a single point)

* x (U+0078) has a counter-clockwise outer contour

* y (U+0079) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* yen (U+00A5) has a counter-clockwise outer contour

* z (U+007A) has a counter-clockwise outer contour

* zero (U+0030) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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
| 0 | 0 | 13 | 11 | 128 | 7 | 92 | 0 | 
| 0% | 0% | 5% | 4% | 51% | 3% | 37% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
