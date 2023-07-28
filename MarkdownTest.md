---
layout: post
key: blog
title: "Generating Diagrams with Mermaid in Markdown"
date: 2018-09-15
tags: [Mermaid]
mermaid: true
---

### Hello World!

This is mermaid
<pre class="mermaid">
graph LR
    A --- B
    B-->C[Happy]
    B-->D(Sad);
</pre>

```mermaid
graph LR
    A --- B
    B-->C[Happy]
    B-->D(Sad);
```
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
