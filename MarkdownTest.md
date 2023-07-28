---
mermaid : true
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

{% if page.mermaid %}
  {% include mermaid.html %}
{% endif %}