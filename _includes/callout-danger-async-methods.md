{% callout danger %}
#### Metodi asincroni e transizioni

Tutti i metodi API sono **asincroni** e avviano una **transizione**. Ritornano al chiamante non appena viene avviata la transizione ma **prima che termini**. Inoltre, una chiamata al metodo su un **componente in transizione verrà ignorata**.

[Per maggiori informazioni guarda la documentazione Javascript di Bootstrap.]({{ site.baseurl }}/docs/{{ site.docs_version }}/getting-started/javascript/)
{% endcallout %}
