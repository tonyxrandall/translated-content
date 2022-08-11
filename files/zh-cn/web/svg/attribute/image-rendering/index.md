---
title: image-rendering
slug: Web/SVG/Attribute/image-rendering
tags:
  - SVG
  - SVG 属性
translation_of: Web/SVG/Attribute/image-rendering
---
<p>« <a href="/en/SVG/Attribute">SVG Attribute reference home</a></p>
<p><code>image-rendering</code> 属性向浏览器提供了一个提示，即在图片处理时，如何进行速度 vs 质量之间的权衡。<br>
 <br>
 作为一个显示属性，它也可以在 CSS 样式文件中作为属性而存在，请参考  {{ cssxref("image-rendering","CSS image-rendering") }} 获取更多的信息</p>
<h2 id="使用语境">使用语境</h2>
<table class="standard-table">
 <tbody>
  <tr>
   <th scope="row">类别</th>
   <td>Presentation attribute</td>
  </tr>
  <tr>
   <th scope="row">值</th>
   <td><strong>auto</strong> | optimizeSpeed | optimizeQuality | inherit</td>
  </tr>
  <tr>
   <th scope="row">动画效果</th>
   <td>Yes</td>
  </tr>
 </tbody>
</table>
<dl>
 <dt>
  auto</dt>
 <dd>
  表示用户代理可以在速度和质量间做适当的权衡，但是质量将比速度更重要一些。</dd>
 <dt>
  optimizeSpeed</dt>
 <dd>
  表示用户代理应该更注重速度。</dd>
 <dt>
  optimizeQuality</dt>
 <dd>
  表示用户代理应该更注重质量</dd>
</dl>
<h2 id="示例">示例</h2>
<h2 id="元素">元素</h2>
<p>下面的元素可以能够使用 <code>image-rendering</code> 属性</p>
<ul>
 <li>{{ SVGElement("image") }}</li>
</ul>

<h2 id="规范">规范</h2>

{{Specifications}}

<h2 id="参考">参考</h2>
<ul>
 <li>{{ cssxref("image-rendering","CSS image-rendering") }}</li>
</ul>