## FontBakery report

fontbakery version: 0.12.8



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[2] Handy0-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>'smcp' or 'liga' lookups not found in GSUB table.</p>
 [code: missing-lookups]



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



<details><summary>[18] Handy0-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.fontbakery.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.8, while a newer 0.12.9 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2024 Handy0 Project Authors (github.com/mitradranirban/handy0-fonts)&quot;</p>
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
<td align="left"><strong>Handy0 Regular</strong></td>
<td align="left"><strong>Handy0</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Handy0 Regular</td>
<td align="left">Handy0 Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">Handy0-Regular</td>
<td align="left">Handy0-Regular</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Handy0</strong></td>
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
    <summary>🔥 <b>FAIL</b> Stricter unitsPerEm criteria for Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.head.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font em size (unitsPerEm) is 4096 which may be too large (causing filesize bloat), unless you are sure that the detail level in this font requires that much precision.</p>
 [code: large-value]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
acutecomb (U+0301), gravecomb (U+0300), hookabovecomb (U+0309), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: glyph1	Contours detected: 2	Expected: 0

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: at	Contours detected: 1	Expected: 2

- Glyph name: B	Contours detected: 1	Expected: 2 or 3

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: bar	Contours detected: 2	Expected: 1

- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 3	Expected: 4

- Glyph name: aring	Contours detected: 3	Expected: 4

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: eth	Contours detected: 1	Expected: 2

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 3	Expected: 4

- Glyph name: oslash	Contours detected: 2	Expected: 3

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

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: lcaron	Contours detected: 3	Expected: 2

- Glyph name: napostrophe	Contours detected: 3	Expected: 2

- Glyph name: omacron	Contours detected: 2	Expected: 3

- Glyph name: obreve	Contours detected: 2	Expected: 3

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Racute	Contours detected: 2	Expected: 3

- Glyph name: uni0156	Contours detected: 2	Expected: 3

- Glyph name: Rcaron	Contours detected: 2	Expected: 3

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni01CE	Contours detected: 2	Expected: 3

- Glyph name: uni01D2	Contours detected: 2	Expected: 3

- Glyph name: uni01DF	Contours detected: 4	Expected: 5

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01F0	Contours detected: 1	Expected: 2

- Glyph name: uni01F5	Contours detected: 2	Expected: 3

- Glyph name: uni02BC	Contours detected: 2	Expected: 1

- Glyph name: uni1FED	Contours detected: 1	Expected: 3

- Glyph name: quoteleft	Contours detected: 2	Expected: 1

- Glyph name: quoteright	Contours detected: 2	Expected: 1

- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

- Glyph name: quotedblleft	Contours detected: 4	Expected: 2

- Glyph name: quotedblright	Contours detected: 4	Expected: 2

- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

- Glyph name: uni20A8	Contours detected: 2	Expected: 3

- Glyph name: B	Contours detected: 1	Expected: 2 or 3

- Glyph name: D	Contours detected: 1	Expected: 2

- Glyph name: Dcaron	Contours detected: 2	Expected: 3

- Glyph name: Dcroat	Contours detected: 1	Expected: 2

- Glyph name: Eth	Contours detected: 1	Expected: 2

- Glyph name: Racute	Contours detected: 2	Expected: 3

- Glyph name: Rcaron	Contours detected: 2	Expected: 3

- Glyph name: Uhorn	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: Z	Contours detected: 2	Expected: 1

- Glyph name: Zacute	Contours detected: 3	Expected: 2

- Glyph name: Zcaron	Contours detected: 3	Expected: 2

- Glyph name: Zdotaccent	Contours detected: 3	Expected: 2

- Glyph name: a	Contours detected: 1	Expected: 2

- Glyph name: aacute	Contours detected: 2	Expected: 3

- Glyph name: abreve	Contours detected: 2	Expected: 3

- Glyph name: acircumflex	Contours detected: 2	Expected: 3

- Glyph name: adieresis	Contours detected: 3	Expected: 4

- Glyph name: agrave	Contours detected: 2	Expected: 3

- Glyph name: amacron	Contours detected: 2	Expected: 3

- Glyph name: aring	Contours detected: 3	Expected: 4

- Glyph name: at	Contours detected: 1	Expected: 2

- Glyph name: atilde	Contours detected: 2	Expected: 3

- Glyph name: bar	Contours detected: 2	Expected: 1

- Glyph name: degree	Contours detected: 1	Expected: 2

- Glyph name: e	Contours detected: 1	Expected: 2

- Glyph name: eacute	Contours detected: 2	Expected: 3

- Glyph name: ebreve	Contours detected: 2	Expected: 3

- Glyph name: ecaron	Contours detected: 2	Expected: 3

- Glyph name: ecircumflex	Contours detected: 2	Expected: 3

- Glyph name: edieresis	Contours detected: 3	Expected: 4

- Glyph name: edotaccent	Contours detected: 2	Expected: 3

- Glyph name: egrave	Contours detected: 2	Expected: 3

- Glyph name: eight	Contours detected: 2	Expected: 3

- Glyph name: emacron	Contours detected: 2	Expected: 3

- Glyph name: eth	Contours detected: 1	Expected: 2

- Glyph name: g	Contours detected: 1	Expected: 2 or 3

- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcaron	Contours detected: 2	Expected: 3 or 4

- Glyph name: gcircumflex	Contours detected: 2	Expected: 3 or 4

- Glyph name: gdotaccent	Contours detected: 2	Expected: 3 or 4

- Glyph name: lcaron	Contours detected: 3	Expected: 2

- Glyph name: napostrophe	Contours detected: 3	Expected: 2

- Glyph name: o	Contours detected: 1	Expected: 2

- Glyph name: oacute	Contours detected: 2	Expected: 3

- Glyph name: ocircumflex	Contours detected: 2	Expected: 3

- Glyph name: odieresis	Contours detected: 3	Expected: 4

- Glyph name: ograve	Contours detected: 2	Expected: 3

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: omacron	Contours detected: 2	Expected: 3

- Glyph name: onequarter	Contours detected: 2	Expected: 3 or 4

- Glyph name: ordfeminine	Contours detected: 1	Expected: 2 or 3

- Glyph name: oslash	Contours detected: 2	Expected: 3

- Glyph name: otilde	Contours detected: 2	Expected: 3

- Glyph name: percent	Contours detected: 3	Expected: 4 or 5

- Glyph name: quotedblbase	Contours detected: 4	Expected: 2

- Glyph name: quotedblleft	Contours detected: 4	Expected: 2

- Glyph name: quotedblright	Contours detected: 4	Expected: 2

- Glyph name: quoteleft	Contours detected: 2	Expected: 1

- Glyph name: quoteright	Contours detected: 2	Expected: 1

- Glyph name: quotesinglbase	Contours detected: 2	Expected: 1

- Glyph name: quotesingle	Contours detected: 2	Expected: 1

- Glyph name: tcaron	Contours detected: 3	Expected: 2

- Glyph name: threequarters	Contours detected: 2	Expected: 3 or 4

- Glyph name: uhorn	Contours detected: 2	Expected: 1

- Glyph name: uni00AD	Contours detected: 1	Expected: 0

- Glyph name: uni0123	Contours detected: 2	Expected: 3 or 4

- Glyph name: uni0156	Contours detected: 2	Expected: 3

- Glyph name: uni01CE	Contours detected: 2	Expected: 3

- Glyph name: uni01D2	Contours detected: 2	Expected: 3

- Glyph name: uni01DF	Contours detected: 4	Expected: 5

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01F0	Contours detected: 1	Expected: 2

- Glyph name: uni02BC	Contours detected: 2	Expected: 1

- Glyph name: uni1FED	Contours detected: 1	Expected: 3

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



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
<pre><code>* A (U+0041): X=269.0,Y=2.0 (should be at baseline 0?)

* A (U+0041): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* AE (U+00C6): X=269.0,Y=2.0 (should be at baseline 0?)

* AE (U+00C6): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Aacute (U+00C1): X=269.0,Y=2.0 (should be at baseline 0?)

* Aacute (U+00C1): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Abreve (U+0102): X=269.0,Y=2.0 (should be at baseline 0?)

* Abreve (U+0102): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Acircumflex (U+00C2): X=269.0,Y=2.0 (should be at baseline 0?)

* Acircumflex (U+00C2): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Adieresis (U+00C4): X=269.0,Y=2.0 (should be at baseline 0?)

* Adieresis (U+00C4): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Agrave (U+00C0): X=269.0,Y=2.0 (should be at baseline 0?)

* Agrave (U+00C0): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Amacron (U+0100): X=269.0,Y=2.0 (should be at baseline 0?)

* Amacron (U+0100): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Aogonek (U+0104): X=269.0,Y=2.0 (should be at baseline 0?)

* Aogonek (U+0104): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Aring (U+00C5): X=269.0,Y=2.0 (should be at baseline 0?)

* Aring (U+00C5): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Aringacute (U+01FA): X=269.0,Y=2.0 (should be at baseline 0?)

* Aringacute (U+01FA): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* Atilde (U+00C3): X=269.0,Y=2.0 (should be at baseline 0?)

* Atilde (U+00C3): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* B (U+0042): X=1084.0,Y=-2.0 (should be at baseline 0?)

* D (U+0044): X=2212.0,Y=-2.0 (should be at baseline 0?)

* Dcaron (U+010E): X=2212.0,Y=-2.0 (should be at baseline 0?)

* Dcroat (U+0110): X=317.0,Y=2870.0 (should be at cap-height 2868?)

* Dcroat (U+0110): X=2212.0,Y=-2.0 (should be at baseline 0?)

* Dcroat (U+0110): X=1232.0,Y=2866.0 (should be at cap-height 2868?)

* Dcroat (U+0110): X=1183.0,Y=2869.0 (should be at cap-height 2868?)

* S (U+0053): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* S (U+0053): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* S (U+0053): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* Sacute (U+015A): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* Sacute (U+015A): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* Sacute (U+015A): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* Scaron (U+0160): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* Scaron (U+0160): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* Scaron (U+0160): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* Scedilla (U+015E): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* Scedilla (U+015E): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* Scedilla (U+015E): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* Scircumflex (U+015C): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* Scircumflex (U+015C): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* Scircumflex (U+015C): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* Z (U+005A): X=1942.0,Y=2870.0 (should be at cap-height 2868?)

* Zacute (U+0179): X=1942.0,Y=2870.0 (should be at cap-height 2868?)

* Zcaron (U+017D): X=1942.0,Y=2870.0 (should be at cap-height 2868?)

* Zdotaccent (U+017B): X=1942.0,Y=2870.0 (should be at cap-height 2868?)

* b (U+0062): X=628.0,Y=-2.0 (should be at baseline 0?)

* ccedilla (U+00E7): X=932.0,Y=-2.0 (should be at baseline 0?)

* dcaron (U+010F): X=1665.0,Y=2867.0 (should be at cap-height 2868?)

* degree (U+00B0): X=660.0,Y=2867.0 (should be at cap-height 2868?)

* nine (U+0039): X=1101.0,Y=-2.0 (should be at baseline 0?)

* nine (U+0039): X=1368.0,Y=2866.0 (should be at cap-height 2868?)

* ogonek (U+02DB): X=-7.0,Y=1.0 (should be at baseline 0?)

* openbullet (U+25E6): X=660.0,Y=2867.0 (should be at cap-height 2868?)

* parenright (U+0029): X=1059.0,Y=2870.0 (should be at cap-height 2868?)

* quotesingle (U+0027): X=2747.0,Y=2867.0 (should be at cap-height 2868?)

* tcaron (U+0165): X=1659.0,Y=2867.0 (should be at cap-height 2868?)

* threequarters (U+00BE): X=512.0,Y=1.0 (should be at baseline 0?)

* trademark (U+2122): X=-1400.0,Y=2869.0 (should be at cap-height 2868?)

* underscore (U+005F): X=-102.0,Y=2.0 (should be at baseline 0?)

* uni01CD (U+01CD): X=269.0,Y=2.0 (should be at baseline 0?)

* uni01CD (U+01CD): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* uni01DE (U+01DE): X=269.0,Y=2.0 (should be at baseline 0?)

* uni01DE (U+01DE): X=2076.0,Y=2866.0 (should be at cap-height 2868?)

* uni0218 (U+0218): X=1218.0,Y=2870.0 (should be at cap-height 2868?)

* uni0218 (U+0218): X=1108.0,Y=2866.0 (should be at cap-height 2868?)

* uni0218 (U+0218): X=926.0,Y=2866.0 (should be at cap-height 2868?)

* uni02BC (U+02BC): X=2747.0,Y=2867.0 (should be at cap-height 2868?)

* uni0326 (U+0326): X=-297.0,Y=1.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=917.0,Y=2869.0 (should be at cap-height 2868?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* dcroat (U+0111): L&lt;&lt;1556.0,2276.0&gt;--&lt;1428.0,2348.0&gt;&gt; -&gt; L&lt;&lt;1428.0,2348.0&gt;--&lt;1260.0,2422.0&gt;&gt;

* five (U+0035): L&lt;&lt;1370.0,163.0&gt;--&lt;1536.0,170.0&gt;&gt; -&gt; L&lt;&lt;1536.0,170.0&gt;--&lt;1640.0,170.0&gt;&gt;

* three (U+0033): L&lt;&lt;1388.0,2258.0&gt;--&lt;1388.0,2360.0&gt;&gt; -&gt; L&lt;&lt;1388.0,2360.0&gt;--&lt;1386.0,2382.0&gt;&gt;

* three (U+0033): L&lt;&lt;1589.0,2370.0&gt;--&lt;1590.0,2360.0&gt;&gt; -&gt; L&lt;&lt;1590.0,2360.0&gt;--&lt;1590.0,2314.0&gt;&gt;

* uni00B3 (U+00B3): L&lt;&lt;1388.0,2258.0&gt;--&lt;1388.0,2360.0&gt;&gt; -&gt; L&lt;&lt;1388.0,2360.0&gt;--&lt;1386.0,2382.0&gt;&gt;

* uni00B3 (U+00B3): L&lt;&lt;1589.0,2370.0&gt;--&lt;1590.0,2360.0&gt;&gt; -&gt; L&lt;&lt;1590.0,2360.0&gt;--&lt;1590.0,2314.0&gt;&gt;

* x (U+0078): L&lt;&lt;364.0,298.0&gt;--&lt;520.0,348.0&gt;&gt; -&gt; L&lt;&lt;520.0,348.0&gt;--&lt;658.0,404.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Eng (U+014A): B&lt;&lt;847.0,983.0&gt;-&lt;873.0,882.0&gt;-&lt;882.0,820.0&gt;&gt;/B&lt;&lt;882.0,820.0&gt;-&lt;881.0,838.0&gt;-&lt;881.0,856.0&gt;&gt; = 5.0796078600145425

* K (U+004B): L&lt;&lt;800.0,1168.0&gt;--&lt;800.0,1210.0&gt;&gt;/B&lt;&lt;800.0,1210.0&gt;-&lt;793.0,1178.0&gt;-&lt;772.0,1078.0&gt;&gt; = 12.33908727832618

* cent (U+00A2): L&lt;&lt;540.0,1760.0&gt;--&lt;540.0,1758.0&gt;&gt;/B&lt;&lt;540.0,1758.0&gt;-&lt;559.0,1878.0&gt;-&lt;588.0,1949.0&gt;&gt; = 8.997143421065033

* eng (U+014B): B&lt;&lt;829.0,956.0&gt;-&lt;875.0,862.0&gt;-&lt;882.0,837.0&gt;&gt;/B&lt;&lt;882.0,837.0&gt;-&lt;876.0,880.0&gt;-&lt;897.0,920.0&gt;&gt; = 7.698774646618311

* lcaron (U+013E): B&lt;&lt;786.0,2268.0&gt;-&lt;771.0,2262.0&gt;-&lt;750.0,2262.0&gt;&gt;/B&lt;&lt;750.0,2262.0&gt;-&lt;780.0,2268.0&gt;-&lt;786.0,2268.0&gt;&gt; = 11.309932474020195

* m (U+006D): B&lt;&lt;1354.0,1226.0&gt;-&lt;1354.0,1015.0&gt;-&lt;1340.0,888.0&gt;&gt;/L&lt;&lt;1340.0,888.0&gt;--&lt;1398.0,1098.0&gt;&gt; = 9.148974761964256

* napostrophe (U+0149): B&lt;&lt;3784.0,1392.0&gt;-&lt;3769.0,1386.0&gt;-&lt;3748.0,1386.0&gt;&gt;/B&lt;&lt;3748.0,1386.0&gt;-&lt;3778.0,1392.0&gt;-&lt;3784.0,1392.0&gt;&gt; = 11.309932474020195

* oe (U+0153): B&lt;&lt;1119.0,964.0&gt;-&lt;1121.0,985.0&gt;-&lt;1125.0,989.0&gt;&gt;/B&lt;&lt;1125.0,989.0&gt;-&lt;1119.0,984.0&gt;-&lt;1115.0,989.0&gt;&gt; = 5.1944289077348

* oslash (U+00F8): B&lt;&lt;977.0,1694.0&gt;-&lt;1039.0,1806.0&gt;-&lt;1060.0,1844.0&gt;&gt;/B&lt;&lt;1060.0,1844.0&gt;-&lt;1044.0,1816.0&gt;-&lt;1053.0,1767.0&gt;&gt; = 0.8184554616877073

* quotedblbase (U+201E): B&lt;&lt;1076.0,-160.0&gt;-&lt;1061.0,-166.0&gt;-&lt;1040.0,-166.0&gt;&gt;/B&lt;&lt;1040.0,-166.0&gt;-&lt;1070.0,-160.0&gt;-&lt;1076.0,-160.0&gt;&gt; = 11.309932474020195

* quotedblbase (U+201E): B&lt;&lt;566.0,-180.0&gt;-&lt;551.0,-186.0&gt;-&lt;530.0,-186.0&gt;&gt;/B&lt;&lt;530.0,-186.0&gt;-&lt;560.0,-180.0&gt;-&lt;566.0,-180.0&gt;&gt; = 11.309932474020195

* quotedblleft (U+201C): B&lt;&lt;427.0,2990.0&gt;-&lt;442.0,2996.0&gt;-&lt;463.0,2996.0&gt;&gt;/B&lt;&lt;463.0,2996.0&gt;-&lt;433.0,2990.0&gt;-&lt;427.0,2990.0&gt;&gt; = 11.309932474020195

* quotedblleft (U+201C): B&lt;&lt;937.0,3010.0&gt;-&lt;952.0,3016.0&gt;-&lt;973.0,3016.0&gt;&gt;/B&lt;&lt;973.0,3016.0&gt;-&lt;943.0,3010.0&gt;-&lt;937.0,3010.0&gt;&gt; = 11.309932474020195

* quotedblright (U+201D): B&lt;&lt;1076.0,2444.0&gt;-&lt;1061.0,2438.0&gt;-&lt;1040.0,2438.0&gt;&gt;/B&lt;&lt;1040.0,2438.0&gt;-&lt;1070.0,2444.0&gt;-&lt;1076.0,2444.0&gt;&gt; = 11.309932474020195

* quotedblright (U+201D): B&lt;&lt;566.0,2424.0&gt;-&lt;551.0,2418.0&gt;-&lt;530.0,2418.0&gt;&gt;/B&lt;&lt;530.0,2418.0&gt;-&lt;560.0,2424.0&gt;-&lt;566.0,2424.0&gt;&gt; = 11.309932474020195

* quoteleft (U+2018): B&lt;&lt;427.0,2990.0&gt;-&lt;442.0,2996.0&gt;-&lt;463.0,2996.0&gt;&gt;/B&lt;&lt;463.0,2996.0&gt;-&lt;433.0,2990.0&gt;-&lt;427.0,2990.0&gt;&gt; = 11.309932474020195

* quoteright (U+2019): B&lt;&lt;566.0,2424.0&gt;-&lt;551.0,2418.0&gt;-&lt;530.0,2418.0&gt;&gt;/B&lt;&lt;530.0,2418.0&gt;-&lt;560.0,2424.0&gt;-&lt;566.0,2424.0&gt;&gt; = 11.309932474020195

* quotesinglbase (U+201A): B&lt;&lt;566.0,424.0&gt;-&lt;551.0,418.0&gt;-&lt;530.0,418.0&gt;&gt;/B&lt;&lt;530.0,418.0&gt;-&lt;560.0,424.0&gt;-&lt;566.0,424.0&gt;&gt; = 11.309932474020195

* quotesingle (U+0027): B&lt;&lt;2752.0,2358.0&gt;-&lt;2737.0,2352.0&gt;-&lt;2716.0,2352.0&gt;&gt;/B&lt;&lt;2716.0,2352.0&gt;-&lt;2746.0,2358.0&gt;-&lt;2752.0,2358.0&gt;&gt; = 11.309932474020195

* tcaron (U+0165): B&lt;&lt;1664.0,2358.0&gt;-&lt;1649.0,2352.0&gt;-&lt;1628.0,2352.0&gt;&gt;/B&lt;&lt;1628.0,2352.0&gt;-&lt;1658.0,2358.0&gt;-&lt;1664.0,2358.0&gt;&gt; = 11.309932474020195

* uni0136 (U+0136): L&lt;&lt;800.0,1168.0&gt;--&lt;800.0,1210.0&gt;&gt;/B&lt;&lt;800.0,1210.0&gt;-&lt;793.0,1178.0&gt;-&lt;772.0,1078.0&gt;&gt; = 12.33908727832618

* uni01E8 (U+01E8): L&lt;&lt;800.0,1168.0&gt;--&lt;800.0,1210.0&gt;&gt;/B&lt;&lt;800.0,1210.0&gt;-&lt;793.0,1178.0&gt;-&lt;772.0,1078.0&gt;&gt; = 12.33908727832618

* uni02BC (U+02BC): B&lt;&lt;2752.0,2358.0&gt;-&lt;2737.0,2352.0&gt;-&lt;2716.0,2352.0&gt;&gt;/B&lt;&lt;2716.0,2352.0&gt;-&lt;2746.0,2358.0&gt;-&lt;2752.0,2358.0&gt;&gt; = 11.309932474020195

* v (U+0076): L&lt;&lt;338.0,472.0&gt;--&lt;350.0,464.0&gt;&gt;/B&lt;&lt;350.0,464.0&gt;-&lt;309.0,505.0&gt;-&lt;258.0,638.0&gt;&gt; = 11.309932474020227
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Dcroat (U+0110): L&lt;&lt;388.0,2598.0&gt;--&lt;394.0,1474.0&gt;&gt;

* germandbls (U+00DF): L&lt;&lt;545.0,410.0&gt;--&lt;546.0,970.0&gt;&gt;

* nine (U+0039): L&lt;&lt;414.0,3008.0&gt;--&lt;416.0,2301.0&gt;&gt;

* six (U+0036): L&lt;&lt;1552.0,220.0&gt;--&lt;1550.0,927.0&gt;&gt;

* three (U+0033): L&lt;&lt;805.0,3226.0&gt;--&lt;1060.0,3224.0&gt;&gt;

* uni00B3 (U+00B3): L&lt;&lt;805.0,3226.0&gt;--&lt;1060.0,3224.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ỉ i̦̇ ỉ̦ i̦̊ i̦̋ i̧̇ ỉ̧ i̧̊ i̧̋ j̆ j̇ j̉ j̊ j̋ j̦̀ j̦́ j̦̃ j̦̄ j̦̆</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Vute (Latn, 21,000 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ekpeye (Latn, 226,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Dan (Latn, 1,099,244 speakers), Mango (Latn, 77,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Yala (Latn, 200,000 speakers), Navajo (Latn, 166,319 speakers), Mundani (Latn, 34,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Koonzime (Latn, 40,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Zapotec (Latn, 490,000 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers).</p>
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
<li>U+02B6 MODIFIER LETTER SMALL CAPITAL INVERTED R: not included in any glyphset definition</li>
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tifinagh, canadian-aboriginal, malayalam, syriac, coptic, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+06D4 ARABIC FULL STOP: try adding one of: arabic, yezidi, hanifi-rohingya</li>
<li>U+226A MUCH LESS-THAN: try adding math</li>
<li>U+226B MUCH GREATER-THAN: try adding math</li>
<li>U+22C5 DOT OPERATOR: try adding one of: math, symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- J + acutecomb

- i + acutecomb

- j + acutecomb
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



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







* ⚠️ **WARN** <p>OS/2 VendorID value 'anir' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Handy0-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 15 | 116 | 7 | 107 | 0 | 
| 0% | 0% | 2% | 6% | 46% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
