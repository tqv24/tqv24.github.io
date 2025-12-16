---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---


Below are my presentations. You can preview each PDF directly on this page, or click to download/view in a new tab:

{% assign presentations = site.static_files | where_exp: "file", "file.path contains '/files/' and file.extname == '.pdf'" %}
{% for file in presentations %}
  <div style="margin-bottom: 2.5em;">
    <strong>{{ file.name }}</strong> &mdash; <a href="{{ file.path }}" target="_blank">Download/View PDF</a>
    <div style="margin-top: 0.5em; border: 1px solid #ccc; border-radius: 6px; overflow: hidden;">
      <embed src="{{ file.path }}" type="application/pdf" width="100%" height="500px">
        <p>Your browser does not support PDF preview. <a href="{{ file.path }}" target="_blank">Click here to download.</a></p>
      </embed>
    </div>
  </div>
{% endfor %}
