# asyncEach


```njk
{%- asyncEach ref in collections.referenzen -%}
  {% include "referenz--card.njk"%}
{%- endeach -%}
