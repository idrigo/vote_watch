# Hello

{% capture includeGuts %}
{% include plot.html %}
{% endcapture %}
{{ includeGuts | replace: '    ', ''}}


