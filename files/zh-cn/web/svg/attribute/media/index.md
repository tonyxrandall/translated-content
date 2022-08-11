---
title: media
slug: Web/SVG/Attribute/media
translation_of: Web/SVG/Attribute/media
---
<div>{{SVGRef}}</div>

<p><code><strong>media</strong></code>属性指定只有符合{{Glossary("media query")}}的样式表才会被应用。 </p>

<p>只有一个元素使用这个属性： {{SVGElement("style")}}</p>

<h2>示例</h2>

<pre class="brush: css hidden">html, body, svg {
  height: 100%;
}</pre>

<pre class="brush: html">&lt;svg viewBox="0 0 240 220" xmlns="http://www.w3.org/2000/svg"&gt;
  &lt;style&gt;
    rect { fill: black; }
  &lt;/style&gt;
  &lt;style media="all and (min-width: 600px)"&gt;
    rect { fill: seagreen; }
  &lt;/style&gt;

  &lt;text y="15"&gt;Resize the window to see the effect&lt;/text&gt;
  &lt;rect y="20" width="200" height="200" /&gt;
&lt;/svg&gt;</pre>

<p>{{EmbedLiveSample("示例", "200", "200")}}</p>

<h2 id="Usage_notes">Usage notes</h2>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row">Value</th>
   <td><code><a href="/en-US/docs/Web/CSS/@media#media-query-list">&lt;media-query-list&gt;</a></code></td>
  </tr>
  <tr>
   <th scope="row">Default value</th>
   <td><code>all</code></td>
  </tr>
  <tr>
   <th scope="row">Animatable</th>
   <td>Yes</td>
  </tr>
 </tbody>
</table>

<dl>
 <dt><code>&lt;media-query-list&gt;</code></dt>
 <dd>
 <p>This value holds a media query that needs to match in order for the style sheet to be applied.</p>

 <p>如果没有指定，样式表就会被应用。</p>
 </dd>
</dl>

<h2 id="Specifications">规范</h2>

{{Specifications}}

<h2 id="浏览器兼容性">浏览器兼容性</h2>

<p>{{Compat}}</p>