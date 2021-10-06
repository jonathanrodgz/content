---
title: Browsing context
slug: Glossary/Browsing_context
tags:
  - Glossary
---
<p>A <strong>browsing context</strong> is the environment in which a browser displays a {{domxref("Document")}}. In modern browsers, it usually is a <em>tab</em>, but can be a <em>window</em> or even only parts of a page, like a <em>frame</em> or an <em>iframe</em>.</p>

<p>Each browsing context has a specific origin, the origin of the active document and a history that memorize all the displayed documents, in order.</p>

<p>Communication between browsing context is severely constrained. Between browsing context of the same origin, a {{domxref("BroadcastChannel")}} can be opened and used.</p>

<h2 id="see_also">See also</h2>

<ul>
 <li>See {{glossary("origin")}}</li>
</ul>