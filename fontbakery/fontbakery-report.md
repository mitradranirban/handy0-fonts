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



<details><summary>[17] Handy0-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2432, but got 1216 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 578, but got 289 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.fontbakery.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.12.8, while a newer 0.12.9 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



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
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1505 when it should be at least 2457</p>
 [code: bad-hhea-range]



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

- Glyph name: napostrophe	Contours detected: 1	Expected: 2

- Glyph name: omacron	Contours detected: 2	Expected: 3

- Glyph name: obreve	Contours detected: 2	Expected: 3

- Glyph name: ohungarumlaut	Contours detected: 3	Expected: 4

- Glyph name: Racute	Contours detected: 2	Expected: 3

- Glyph name: uni0156	Contours detected: 2	Expected: 3

- Glyph name: Rcaron	Contours detected: 2	Expected: 3

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

- Glyph name: uni1FED	Contours detected: 1	Expected: 3

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

- Glyph name: napostrophe	Contours detected: 1	Expected: 2

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
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* dcroat (U+0111): L&lt;&lt;778.0,1138.0&gt;--&lt;714.0,1174.0&gt;&gt; -&gt; L&lt;&lt;714.0,1174.0&gt;--&lt;630.0,1211.0&gt;&gt;

* five (U+0035): L&lt;&lt;662.0,82.0&gt;--&lt;685.0,82.0&gt;&gt; -&gt; L&lt;&lt;685.0,82.0&gt;--&lt;768.0,85.0&gt;&gt;

* five (U+0035): L&lt;&lt;685.0,82.0&gt;--&lt;768.0,85.0&gt;&gt; -&gt; L&lt;&lt;768.0,85.0&gt;--&lt;820.0,85.0&gt;&gt;

* three (U+0033): L&lt;&lt;694.0,1129.0&gt;--&lt;694.0,1180.0&gt;&gt; -&gt; L&lt;&lt;694.0,1180.0&gt;--&lt;693.0,1191.0&gt;&gt;

* uni00B3 (U+00B3): L&lt;&lt;694.0,1129.0&gt;--&lt;694.0,1180.0&gt;&gt; -&gt; L&lt;&lt;694.0,1180.0&gt;--&lt;693.0,1191.0&gt;&gt;

* x (U+0078): L&lt;&lt;182.0,149.0&gt;--&lt;260.0,174.0&gt;&gt; -&gt; L&lt;&lt;260.0,174.0&gt;--&lt;329.0,202.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* Dcroat (U+0110): B&lt;&lt;201.0,1322.0&gt;-&lt;194.0,1298.0&gt;-&lt;194.0,1299.0&gt;&gt;/L&lt;&lt;194.0,1299.0&gt;--&lt;197.0,737.0&gt;&gt; = 0.30584645181375864

* Eng (U+014A): B&lt;&lt;423.0,491.0&gt;-&lt;437.0,438.0&gt;-&lt;441.0,410.0&gt;&gt;/B&lt;&lt;441.0,410.0&gt;-&lt;441.0,415.0&gt;-&lt;440.5,419.5&gt;&gt; = 8.13010235415596

* K (U+004B): L&lt;&lt;400.0,584.0&gt;--&lt;400.0,605.0&gt;&gt;/B&lt;&lt;400.0,605.0&gt;-&lt;399.0,597.0&gt;-&lt;395.0,580.5&gt;&gt; = 7.125016348901757

* cent (U+00A2): L&lt;&lt;270.0,880.0&gt;--&lt;270.0,879.0&gt;&gt;/B&lt;&lt;270.0,879.0&gt;-&lt;279.0,937.0&gt;-&lt;294.0,974.0&gt;&gt; = 8.820379552021036

* d (U+0064): B&lt;&lt;668.0,917.0&gt;-&lt;635.0,1021.0&gt;-&lt;579.0,1106.0&gt;&gt;/B&lt;&lt;579.0,1106.0&gt;-&lt;580.0,1105.0&gt;-&lt;557.0,1138.0&gt;&gt; = 11.62216796356958

* dcaron (U+010F): B&lt;&lt;668.0,917.0&gt;-&lt;635.0,1021.0&gt;-&lt;579.0,1106.0&gt;&gt;/B&lt;&lt;579.0,1106.0&gt;-&lt;580.0,1105.0&gt;-&lt;557.0,1138.0&gt;&gt; = 11.62216796356958

* dcaron (U+010F): B&lt;&lt;843.0,1262.0&gt;-&lt;832.0,1320.0&gt;-&lt;818.0,1333.0&gt;&gt;/B&lt;&lt;818.0,1333.0&gt;-&lt;819.0,1332.0&gt;-&lt;807.0,1342.0&gt;&gt; = 2.1210963966611036

* eng (U+014B): B&lt;&lt;414.0,478.0&gt;-&lt;437.0,433.0&gt;-&lt;441.0,418.0&gt;&gt;/B&lt;&lt;441.0,418.0&gt;-&lt;438.0,441.0&gt;-&lt;448.0,460.0&gt;&gt; = 7.500009206965077

* m (U+006D): B&lt;&lt;675.5,518.5&gt;-&lt;674.0,476.0&gt;-&lt;670.0,444.0&gt;&gt;/L&lt;&lt;670.0,444.0&gt;--&lt;699.0,549.0&gt;&gt; = 8.314629186417422

* oslash (U+00F8): B&lt;&lt;488.0,847.0&gt;-&lt;520.0,904.0&gt;-&lt;530.0,922.0&gt;&gt;/B&lt;&lt;530.0,922.0&gt;-&lt;522.0,907.0&gt;-&lt;526.0,883.0&gt;&gt; = 0.9821171632238195

* uni0122 (U+0122): B&lt;&lt;1031.0,-420.0&gt;-&lt;1024.0,-417.0&gt;-&lt;1021.0,-417.0&gt;&gt;/B&lt;&lt;1021.0,-417.0&gt;-&lt;1033.0,-415.0&gt;-&lt;1041.0,-405.0&gt;&gt; = 9.462322208025613

* uni0123 (U+0123): B&lt;&lt;311.0,1044.0&gt;-&lt;319.0,1042.0&gt;-&lt;320.0,1042.0&gt;&gt;/B&lt;&lt;320.0,1042.0&gt;-&lt;310.0,1041.0&gt;-&lt;301.0,1029.0&gt;&gt; = 5.710593137499633

* uni0136 (U+0136): B&lt;&lt;70.0,-413.0&gt;-&lt;63.0,-410.0&gt;-&lt;60.0,-410.0&gt;&gt;/B&lt;&lt;60.0,-410.0&gt;-&lt;72.0,-408.0&gt;-&lt;80.0,-398.0&gt;&gt; = 9.462322208025613

* uni0136 (U+0136): L&lt;&lt;400.0,584.0&gt;--&lt;400.0,605.0&gt;&gt;/B&lt;&lt;400.0,605.0&gt;-&lt;399.0,597.0&gt;-&lt;395.0,580.5&gt;&gt; = 7.125016348901757

* uni0137 (U+0137): B&lt;&lt;736.0,-439.0&gt;-&lt;729.0,-436.0&gt;-&lt;726.0,-436.0&gt;&gt;/B&lt;&lt;726.0,-436.0&gt;-&lt;738.0,-434.0&gt;-&lt;746.0,-424.0&gt;&gt; = 9.462322208025613

* uni013B (U+013B): B&lt;&lt;756.0,-465.0&gt;-&lt;749.0,-462.0&gt;-&lt;746.0,-462.0&gt;&gt;/B&lt;&lt;746.0,-462.0&gt;-&lt;758.0,-460.0&gt;-&lt;766.0,-450.0&gt;&gt; = 9.462322208025613

* uni013C (U+013C): B&lt;&lt;180.0,-441.0&gt;-&lt;173.0,-438.0&gt;-&lt;170.0,-438.0&gt;&gt;/B&lt;&lt;170.0,-438.0&gt;-&lt;182.0,-436.0&gt;-&lt;190.0,-426.0&gt;&gt; = 9.462322208025613

* uni0145 (U+0145): B&lt;&lt;1019.0,-325.0&gt;-&lt;1012.0,-322.0&gt;-&lt;1009.0,-322.0&gt;&gt;/B&lt;&lt;1009.0,-322.0&gt;-&lt;1021.0,-320.0&gt;-&lt;1029.0,-310.0&gt;&gt; = 9.462322208025613

* uni0146 (U+0146): B&lt;&lt;373.0,-403.0&gt;-&lt;366.0,-400.0&gt;-&lt;363.0,-400.0&gt;&gt;/B&lt;&lt;363.0,-400.0&gt;-&lt;375.0,-398.0&gt;-&lt;383.0,-388.0&gt;&gt; = 9.462322208025613

* uni0156 (U+0156): B&lt;&lt;160.0,-407.0&gt;-&lt;153.0,-404.0&gt;-&lt;150.0,-404.0&gt;&gt;/B&lt;&lt;150.0,-404.0&gt;-&lt;162.0,-402.0&gt;-&lt;170.0,-392.0&gt;&gt; = 9.462322208025613

* uni0157 (U+0157): B&lt;&lt;204.0,-435.0&gt;-&lt;197.0,-432.0&gt;-&lt;194.0,-432.0&gt;&gt;/B&lt;&lt;194.0,-432.0&gt;-&lt;206.0,-430.0&gt;-&lt;214.0,-420.0&gt;&gt; = 9.462322208025613

* uni01E8 (U+01E8): L&lt;&lt;400.0,584.0&gt;--&lt;400.0,605.0&gt;&gt;/B&lt;&lt;400.0,605.0&gt;-&lt;399.0,597.0&gt;-&lt;395.0,580.5&gt;&gt; = 7.125016348901757

* uni0218 (U+0218): B&lt;&lt;591.0,-449.0&gt;-&lt;584.0,-446.0&gt;-&lt;581.0,-446.0&gt;&gt;/B&lt;&lt;581.0,-446.0&gt;-&lt;593.0,-444.0&gt;-&lt;601.0,-434.0&gt;&gt; = 9.462322208025613

* uni0219 (U+0219): B&lt;&lt;368.0,-427.0&gt;-&lt;361.0,-424.0&gt;-&lt;358.0,-424.0&gt;&gt;/B&lt;&lt;358.0,-424.0&gt;-&lt;370.0,-422.0&gt;-&lt;378.0,-412.0&gt;&gt; = 9.462322208025613

* uni021A (U+021A): B&lt;&lt;716.0,-401.0&gt;-&lt;709.0,-398.0&gt;-&lt;706.0,-398.0&gt;&gt;/B&lt;&lt;706.0,-398.0&gt;-&lt;718.0,-396.0&gt;-&lt;726.0,-386.0&gt;&gt; = 9.462322208025613

* uni021B (U+021B): B&lt;&lt;727.0,-399.0&gt;-&lt;720.0,-396.0&gt;-&lt;717.0,-396.0&gt;&gt;/B&lt;&lt;717.0,-396.0&gt;-&lt;729.0,-394.0&gt;-&lt;737.0,-384.0&gt;&gt; = 9.462322208025613

* uni02BC (U+02BC): B&lt;&lt;1366.5,1316.5&gt;-&lt;1364.0,1329.0&gt;-&lt;1359.0,1333.0&gt;&gt;/B&lt;&lt;1359.0,1333.0&gt;-&lt;1360.0,1332.0&gt;-&lt;1348.0,1342.0&gt;&gt; = 6.34019174590985

* uni0326 (U+0326): B&lt;&lt;-102.0,-153.0&gt;-&lt;-109.0,-150.0&gt;-&lt;-112.0,-150.0&gt;&gt;/B&lt;&lt;-112.0,-150.0&gt;-&lt;-100.0,-148.0&gt;-&lt;-92.0,-138.0&gt;&gt; = 9.462322208025613

* v (U+0076): L&lt;&lt;169.0,236.0&gt;--&lt;175.0,232.0&gt;&gt;/B&lt;&lt;175.0,232.0&gt;-&lt;155.0,252.0&gt;-&lt;129.0,319.0&gt;&gt; = 11.309932474020227

* zero (U+0030): B&lt;&lt;242.0,45.0&gt;-&lt;120.0,123.0&gt;-&lt;96.0,235.0&gt;&gt;/B&lt;&lt;96.0,235.0&gt;-&lt;96.0,234.0&gt;-&lt;83.0,270.0&gt;&gt; = 12.094757077012089
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* A (U+0041): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* AE (U+00C6): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Aacute (U+00C1): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Abreve (U+0102): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Acircumflex (U+00C2): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Adieresis (U+00C4): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Agrave (U+00C0): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Amacron (U+0100): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Aogonek (U+0104): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Aring (U+00C5): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Aringacute (U+01FA): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Atilde (U+00C3): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* Dcroat (U+0110): L&lt;&lt;194.0,1299.0&gt;--&lt;197.0,737.0&gt;&gt;

* germandbls (U+00DF): L&lt;&lt;272.0,205.0&gt;--&lt;273.0,485.0&gt;&gt;

* nine (U+0039): L&lt;&lt;207.0,1504.0&gt;--&lt;208.0,1150.0&gt;&gt;

* six (U+0036): L&lt;&lt;776.0,110.0&gt;--&lt;775.0,464.0&gt;&gt;

* three (U+0033): L&lt;&lt;402.0,1613.0&gt;--&lt;530.0,1612.0&gt;&gt;

* uni00B3 (U+00B3): L&lt;&lt;402.0,1613.0&gt;--&lt;530.0,1612.0&gt;&gt;

* uni01CD (U+01CD): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;

* uni01DE (U+01DE): L&lt;&lt;11.0,194.0&gt;--&lt;6.0,820.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ỉ i̦̇ ỉ̦ i̦̊ i̦̋ i̧̇ ỉ̧ i̧̊ i̧̋ j̆ j̇ j̉ j̊ j̋ j̦̀ j̦́ j̦̃ j̦̄ j̦̆</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Basaa (Latn, 332,940 speakers), Ebira (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Fur (Latn, 1,230,163 speakers), Avokaya (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Ejagham (Latn, 120,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Mango (Latn, 77,000 speakers), Nzakara (Latn, 50,000 speakers), Ekpeye (Latn, 226,000 speakers), Dii (Latn, 71,000 speakers), Nateni (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Yala (Latn, 200,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ma’di (Latn, 584,000 speakers), Dan (Latn, 1,099,244 speakers), Zapotec (Latn, 490,000 speakers), Vute (Latn, 21,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers), Mundani (Latn, 34,000 speakers).</p>
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
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, math, old-permic, syriac, malayalam, tai-le, canadian-aboriginal, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+226A MUCH LESS-THAN: try adding math</li>
<li>U+226B MUCH GREATER-THAN: try adding math</li>
<li>U+22C5 DOT OPERATOR: try adding one of: symbols, math</li>
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
| 0 | 0 | 6 | 14 | 117 | 7 | 107 | 0 | 
| 0% | 0% | 2% | 6% | 47% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
