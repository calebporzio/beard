---
extends: _layouts.subpage
section: subpage_content
---
<h3 class="tcg50 ft7 md-ft10 fw3 mb2 md-mb3 flex aic acc">Text Alignment <a class="badge br3 bg1 tcw ft1 md-ft3 uppercase ls1 fw6 ml1" title="These helpers accept responsive prefixes">Responsive</a></h3>

<table class="w100 mb6 ft4 tcg60 lh2">
    <thead>
        <tr class="brdr1--bottom bcg10">
            <th class="pv1">Name</th>
            <th class="pv1">Class</th>
        </tr>
    </thead>
    <tr class="brdr1--bottom bcg10">
        <td class="pv1">Text Align Left</td>
        <td class="pv1"><code>.tal</code></td>
    </tr>
    <tr class="brdr1--bottom bcg10">
        <td class="pv1">Text Align Center</td>
        <td class="pv1"><code>.tac</code></td>
    </tr>
    <tr class="brdr1--bottom bcg10">
        <td class="pv1">Text Align Right</td>
        <td class="pv1"><code>.tar</code></td>
    </tr>
</table>

<h3 class="tcg50 ft6 fw3 mb2 md-mb3 flex aic acc">Example:</h3>

<pre class="mb4"><code class="language-html">
&lt;p class="tal md-tac lg-tar xlg-tal"&gt;Here is some aligned text&lt;/p&gt;
</code></pre>

<p class="tcg50 ft5 fw3 mb4 lh2">The text above would be aligned left by default, center on the medium breakpoint, right on the large breakpoint, and back to left on the extra large breakpoint.</p>
