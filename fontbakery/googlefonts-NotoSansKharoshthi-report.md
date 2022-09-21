## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] NotoSansKharoshthi-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/kharoshthi.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansKharoshthi/googlefonts/ttf/NotoSansKharoshthi-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/kharoshthi.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐨀 𐨁𐨀</span> (fontdiff-und-Khar_diffenator.html)</li>


<pre>Expected: A_khar=3+589|I_diagonal_short=1@393,-190+0|uni25CC=1+594|space=1+260|A_khar=0+589</pre>



<pre>Got     : A_khar=3+589|I_khar=1+0|space=1+260|A_khar=0+589</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1438 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M368.0,-15.0L289.0,7.0Q307.0,42.0 330.5,96.5Q354.0,151.0 377.0,216.0Q400.0,281.0 415.0,348.0Q430.0,415.0 430.0,474.0Q430.0,522.0 417.0,560.0Q404.0,598.0 374.5,620.0Q345.0,642.0 294.0,642.0Q234.0,642.0 203.0,611.5Q172.0,581.0 172.0,539.0Q172.0,514.0 184.0,486.0Q196.0,458.0 221.0,432.0L158.0,380.0Q122.0,416.0 105.0,456.0Q88.0,496.0 88.0,536.0Q88.0,584.0 112.0,625.0Q136.0,666.0 182.0,691.0Q228.0,716.0 294.0,716.0Q378.0,716.0 426.5,684.5Q475.0,653.0 495.5,599.5Q516.0,546.0 516.0,478.0Q516.0,416.0 501.5,349.0Q487.0,282.0 464.5,216.0Q442.0,150.0 416.5,91.0Q391.0,32.0 368.0,-15.0Z"  transform="translate(0, 801)"/>
<path d="M-208.0,381.0Q-185.0,455.0 -164.0,532.0Q-143.0,609.0 -125.0,680.0Q-107.0,751.0 -96.0,806.0L-56.0,794.0L-87.0,639.0Q-101.0,569.0 -119.0,499.0Q-137.0,429.0 -156.0,362.0L-208.0,381.0Z"  transform="translate(589, 801)"/>
<path d=""  transform="translate(589, 801)"/>
<path d="M368.0,-15.0L289.0,7.0Q307.0,42.0 330.5,96.5Q354.0,151.0 377.0,216.0Q400.0,281.0 415.0,348.0Q430.0,415.0 430.0,474.0Q430.0,522.0 417.0,560.0Q404.0,598.0 374.5,620.0Q345.0,642.0 294.0,642.0Q234.0,642.0 203.0,611.5Q172.0,581.0 172.0,539.0Q172.0,514.0 184.0,486.0Q196.0,458.0 221.0,432.0L158.0,380.0Q122.0,416.0 105.0,456.0Q88.0,496.0 88.0,536.0Q88.0,584.0 112.0,625.0Q136.0,666.0 182.0,691.0Q228.0,716.0 294.0,716.0Q378.0,716.0 426.5,684.5Q475.0,653.0 495.5,599.5Q516.0,546.0 516.0,478.0Q516.0,416.0 501.5,349.0Q487.0,282.0 464.5,216.0Q442.0,150.0 416.5,91.0Q391.0,32.0 368.0,-15.0Z"  transform="translate(849, 801)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2032 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M368.0,-15.0L289.0,7.0Q307.0,42.0 330.5,96.5Q354.0,151.0 377.0,216.0Q400.0,281.0 415.0,348.0Q430.0,415.0 430.0,474.0Q430.0,522.0 417.0,560.0Q404.0,598.0 374.5,620.0Q345.0,642.0 294.0,642.0Q234.0,642.0 203.0,611.5Q172.0,581.0 172.0,539.0Q172.0,514.0 184.0,486.0Q196.0,458.0 221.0,432.0L158.0,380.0Q122.0,416.0 105.0,456.0Q88.0,496.0 88.0,536.0Q88.0,584.0 112.0,625.0Q136.0,666.0 182.0,691.0Q228.0,716.0 294.0,716.0Q378.0,716.0 426.5,684.5Q475.0,653.0 495.5,599.5Q516.0,546.0 516.0,478.0Q516.0,416.0 501.5,349.0Q487.0,282.0 464.5,216.0Q442.0,150.0 416.5,91.0Q391.0,32.0 368.0,-15.0Z"  transform="translate(0, 801)"/>
<path d="M-212.0,176.0L-267.0,199.0Q-244.0,264.0 -219.5,343.5Q-195.0,423.0 -171.5,506.5Q-148.0,590.0 -128.0,668.0Q-108.0,746.0 -96.0,806.0L-56.0,794.0L-86.0,639.0Q-104.0,558.0 -125.5,475.5Q-147.0,393.0 -169.0,316.5Q-191.0,240.0 -212.0,176.0Z"  transform="translate(982, 611)"/>
<path d="M323.0,514.0Q323.0,487.0 297.0,487.0Q271.0,487.0 271.0,514.0Q271.0,540.0 297.0,540.0Q323.0,540.0 323.0,514.0ZM408.0,496.0Q408.0,470.0 383.0,470.0Q355.0,470.0 355.0,496.0Q355.0,523.0 383.0,523.0Q408.0,523.0 408.0,496.0ZM239.0,496.0Q239.0,470.0 212.0,470.0Q186.0,470.0 186.0,496.0Q186.0,523.0 212.0,523.0Q239.0,523.0 239.0,496.0ZM480.0,448.0Q480.0,422.0 455.0,422.0Q428.0,422.0 428.0,448.0Q428.0,475.0 455.0,475.0Q480.0,475.0 480.0,448.0ZM167.0,448.0Q167.0,422.0 140.0,422.0Q114.0,422.0 114.0,447.0Q114.0,475.0 140.0,475.0Q167.0,475.0 167.0,448.0ZM529.0,376.0Q529.0,349.0 502.0,349.0Q476.0,349.0 476.0,376.0Q476.0,402.0 503.0,402.0Q529.0,402.0 529.0,376.0ZM118.0,376.0Q118.0,349.0 93.0,349.0Q65.0,349.0 65.0,376.0Q65.0,402.0 92.0,402.0Q118.0,402.0 118.0,376.0ZM546.0,291.0Q546.0,265.0 521.0,265.0Q494.0,265.0 494.0,291.0Q494.0,317.0 521.0,317.0Q546.0,317.0 546.0,291.0ZM101.0,291.0Q101.0,265.0 75.0,265.0Q48.0,265.0 48.0,291.0Q48.0,317.0 75.0,317.0Q101.0,317.0 101.0,291.0ZM529.0,206.0Q529.0,180.0 502.0,180.0Q476.0,180.0 476.0,206.0Q476.0,233.0 502.0,233.0Q529.0,233.0 529.0,206.0ZM118.0,206.0Q118.0,180.0 92.0,180.0Q65.0,180.0 65.0,206.0Q65.0,233.0 92.0,233.0Q118.0,233.0 118.0,206.0ZM480.0,133.0Q480.0,107.0 455.0,107.0Q428.0,107.0 428.0,133.0Q428.0,160.0 455.0,160.0Q480.0,160.0 480.0,133.0ZM167.0,133.0Q167.0,107.0 140.0,107.0Q114.0,107.0 114.0,133.0Q114.0,160.0 140.0,160.0Q167.0,160.0 167.0,133.0ZM408.0,85.0Q408.0,60.0 383.0,60.0Q355.0,60.0 355.0,85.0Q355.0,112.0 383.0,112.0Q408.0,112.0 408.0,85.0ZM239.0,87.0Q239.0,60.0 212.0,60.0Q186.0,60.0 186.0,85.0Q186.0,112.0 212.0,112.0Q239.0,112.0 239.0,87.0ZM323.0,69.0Q323.0,42.0 297.0,42.0Q271.0,42.0 271.0,69.0Q271.0,95.0 297.0,95.0Q323.0,95.0 323.0,69.0Z"  transform="translate(589, 801)"/>
<path d=""  transform="translate(1183, 801)"/>
<path d="M368.0,-15.0L289.0,7.0Q307.0,42.0 330.5,96.5Q354.0,151.0 377.0,216.0Q400.0,281.0 415.0,348.0Q430.0,415.0 430.0,474.0Q430.0,522.0 417.0,560.0Q404.0,598.0 374.5,620.0Q345.0,642.0 294.0,642.0Q234.0,642.0 203.0,611.5Q172.0,581.0 172.0,539.0Q172.0,514.0 184.0,486.0Q196.0,458.0 221.0,432.0L158.0,380.0Q122.0,416.0 105.0,456.0Q88.0,496.0 88.0,536.0Q88.0,584.0 112.0,625.0Q136.0,666.0 182.0,691.0Q228.0,716.0 294.0,716.0Q378.0,716.0 426.5,684.5Q475.0,653.0 495.5,599.5Q516.0,546.0 516.0,478.0Q516.0,416.0 501.5,349.0Q487.0,282.0 464.5,216.0Q442.0,150.0 416.5,91.0Q391.0,32.0 368.0,-15.0Z"  transform="translate(1443, 801)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𐨧𐨿𐨩</span> (fontdiff-und-Khar_diffenator.html)</li>


<pre>Expected: SubYa.alt=0@412,15+0|Bha_khar=0@100,0+798</pre>



<pre>Got     : SubYa.alt=0@779,157+0|Bha_khar=0@100,0+798</pre>



<pre>                      ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 798 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M-392.0,-197.0Q-364.0,-210.0 -330.0,-210.0Q-238.0,-210.0 -228.0,-125.0Q-235.0,-126.0 -243.0,-126.0Q-251.0,-126.0 -259.0,-126.0Q-270.0,-126.0 -281.0,-124.5Q-292.0,-123.0 -304.0,-121.0L-274.0,-50.0Q-269.0,-51.0 -262.5,-51.5Q-256.0,-52.0 -247.0,-52.0Q-204.0,-52.0 -188.5,-34.0Q-173.0,-16.0 -160.0,23.0L-81.0,9.0Q-88.0,-42.0 -103.5,-63.0Q-119.0,-84.0 -148.0,-100.0Q-148.0,-181.0 -196.5,-227.5Q-245.0,-274.0 -330.0,-274.0Q-381.0,-274.0 -419.0,-259.0L-392.0,-197.0Z"  transform="translate(779, 958)"/>
<path d="M99.0,635.0L113.0,709.0L606.0,709.0L592.0,635.0L399.0,635.0Q385.0,592.0 367.0,534.0L369.0,534.0Q447.0,524.0 506.0,495.0Q565.0,466.0 598.5,417.5Q632.0,369.0 632.0,298.0Q632.0,252.0 616.0,211.5Q600.0,171.0 572.0,133.0L501.0,165.0Q518.0,192.0 532.0,224.5Q546.0,257.0 546.0,291.0Q546.0,359.0 497.0,402.0Q448.0,445.0 347.0,463.0L345.0,463.0Q322.0,383.0 299.0,296.5Q276.0,210.0 256.0,129.0Q236.0,48.0 223.0,-14.0L145.0,-1.0Q153.0,61.0 170.5,141.5Q188.0,222.0 211.0,309.0Q234.0,396.0 259.5,480.5Q285.0,565.0 310.0,635.0L99.0,635.0Z"  transform="translate(100, 801)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 798 2370" transform="matrix(1 0 0 -1 0 0)">
<path d="M-392.0,-197.0Q-364.0,-210.0 -330.0,-210.0Q-238.0,-210.0 -228.0,-125.0Q-235.0,-126.0 -243.0,-126.0Q-251.0,-126.0 -259.0,-126.0Q-270.0,-126.0 -281.0,-124.5Q-292.0,-123.0 -304.0,-121.0L-274.0,-50.0Q-269.0,-51.0 -262.5,-51.5Q-256.0,-52.0 -247.0,-52.0Q-204.0,-52.0 -188.5,-34.0Q-173.0,-16.0 -160.0,23.0L-81.0,9.0Q-88.0,-42.0 -103.5,-63.0Q-119.0,-84.0 -148.0,-100.0Q-148.0,-181.0 -196.5,-227.5Q-245.0,-274.0 -330.0,-274.0Q-381.0,-274.0 -419.0,-259.0L-392.0,-197.0Z"  transform="translate(412, 816)"/>
<path d="M99.0,635.0L113.0,709.0L606.0,709.0L592.0,635.0L399.0,635.0Q385.0,592.0 367.0,534.0L369.0,534.0Q447.0,524.0 506.0,495.0Q565.0,466.0 598.5,417.5Q632.0,369.0 632.0,298.0Q632.0,252.0 616.0,211.5Q600.0,171.0 572.0,133.0L501.0,165.0Q518.0,192.0 532.0,224.5Q546.0,257.0 546.0,291.0Q546.0,359.0 497.0,402.0Q448.0,445.0 347.0,463.0L345.0,463.0Q322.0,383.0 299.0,296.5Q276.0,210.0 256.0,129.0Q236.0,48.0 223.0,-14.0L145.0,-1.0Q153.0,61.0 170.5,141.5Q188.0,222.0 211.0,309.0Q234.0,396.0 259.5,480.5Q285.0,565.0 310.0,635.0L99.0,635.0Z"  transform="translate(100, 801)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Pha_khar (U+10A25): B<<473.5,403.5>-<424.0,447.0>-<320.0,463.0>>/L<<320.0,463.0>--<320.0,463.0>> = 8.746162262555211 [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 6 | 110 | 7 | 103 | 0 |
| 0% | 0% | 3% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
