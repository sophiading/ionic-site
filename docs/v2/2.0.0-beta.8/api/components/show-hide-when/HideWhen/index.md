---
layout: "v2_fluid/docs_base"
version: "2.0.0-beta.8"
versionHref: "/docs/v2/2.0.0-beta.8"
path: ""
category: api
id: "hidewhen"
title: "HideWhen"
header_sub_title: "Ionic API Documentation"
doc: "HideWhen"
docType: "class"
show_preview_device: true
preview_device_url: "/docs/v2/demos/hide-when/"
angular_controller: APIDemoCtrl 
---









<h1 class="api-title">
<a class="anchor" name="hide-when" href="#hide-when"></a>

HideWhen






</h1>

<a class="improve-v2-docs" href="http://github.com/driftyco/ionic/edit/2.0//src/components/show-hide-when/show-hide-when.ts#L115">
Improve this doc
</a>






<p>The <code>hideWhen</code> attribute takes a string that represents a plaform or screen orientation.
The element the attribute is added to will only be hidden when that platform or screen orientation is active.</p>
<p>Complements the <a href="../ShowWhen">showWhen attribute</a>. If the <code>hideWhen</code> attribute is used on an
element that also has the <code>showWhen</code> attribute, the element will not show if <code>hideWhen</code> evaluates
to <code>true</code> or <code>showWhen</code> evaluates to <code>false</code>. If the <code>hidden</code> attribute is also added, the element
will not show if <code>hidden</code> evaluates to <code>true</code>.</p>
<p>View the <a href="../../../platform/Platform">Platform API docs</a> for more information on the different
platforms you can use.</p>


<h2><a class="anchor" name="Directive" href="#Directive"></a>Directive</h2>
<h3>selector: <code>[hideWhen]</code></h3>
<!-- @usage tag -->

<h2><a class="anchor" name="usage" href="#usage"></a>Usage</h2>

<pre><code class="lang-html">&lt;div hideWhen=&quot;android&quot;&gt;
 I am hidden on Android!
&lt;/div&gt;

&lt;div hideWhen=&quot;ios&quot;&gt;
 I am hidden on iOS!
&lt;/div&gt;

&lt;div hideWhen=&quot;android,ios&quot;&gt;
 I am hidden on Android and iOS!
&lt;/div&gt;

&lt;div hideWhen=&quot;portrait&quot;&gt;
 I am hidden on Portrait!
&lt;/div&gt;

&lt;div hideWhen=&quot;landscape&quot;&gt;
 I am hidden on Landscape!
&lt;/div&gt;
</code></pre>




<!-- @property tags -->



<!-- instance methods on the class -->


<!-- related link -->

<h2><a class="anchor" name="related" href="#related"></a>Related</h2>

<a href='../ShowWhen'>ShowWhen API Docs</a>,
<a href='../../../platform/Platform'>Platform API Docs</a><!-- end content block -->


<!-- end body block -->

