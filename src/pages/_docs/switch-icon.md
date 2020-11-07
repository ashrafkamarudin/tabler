---
title: Switch icon
menu: docs.components.switch-icon
---

## Default markup

{% capture code %}
{% include ui/switch-icon.html icon="circle" icon-b-class="icon-filled" icon-b-color="blue"  %}
{% endcapture %}
{% include example.html code=code wrapper="d-flex space-x-2" %}

## Switch animations

{% capture code %}
{% include ui/switch-icon.html icon="circle" icon-b-class="icon-filled" icon-b-color="blue"  %}
{% include ui/switch-icon.html variant="fade" icon-b-class="icon-filled"  %}
{% include ui/switch-icon.html variant="scale" icon="star" icon-b-class="icon-filled" icon-b-color="yellow" %}
{% include ui/switch-icon.html variant="flip" icon="thumb-up" icon-b-color="facebook" %}
{% include ui/switch-icon.html variant="slide-up" icon="brand-twitter" icon-b-color="twitter" %}
{% include ui/switch-icon.html variant="slide-left" icon="check" icon-b="x" icon-b-color="red" %}
{% include ui/switch-icon.html variant="slide-down" icon="arrow-down" icon-b="arrow-up" icon-a-color="muted" icon-b-color="muted" %}
{% include ui/switch-icon.html variant="slide-right" icon="car" icon-b="scooter" icon-b-color="muted" %}
{% endcapture %}
{% include example.html code=code wrapper="d-flex space-x-2" %}