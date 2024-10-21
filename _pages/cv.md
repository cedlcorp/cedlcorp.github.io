---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<div style="position: relative; padding-bottom: 100%; height: 0; overflow: hidden;">
  <iframe src="https://drive.google.com/file/d/1OLf0gRn0Xkqmmx60YfKaaBy0AZDL8sCE/preview" frameborder="0" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" allowfullscreen></iframe>
</div>

<script>
  window.addEventListener('load', function() {
    var iframe = document.getElementById('myIframe');
    iframe.onload = function() {
      iframe.style.height = iframe.contentWindow.document.body.scrollHeight + 'px';
    };
  });
</script>

<!-- ![hanjunpark_cv](/images/hanjunpark_20240712cv_final-1.png) -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
