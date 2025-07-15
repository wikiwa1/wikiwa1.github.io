---
layout: archive
title: "Curriculum Vitae (CV)"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<span style="display: flex; align-items: center; gap: 0.5em; margin-bottom: 1em;">
  <label for="cv-select">Choose CV version:</label>
  <select id="cv-select" onchange="document.getElementById('pdf-embed').src=this.value; document.getElementById('cv-download-link').href=this.value;">
    <option value="{{ site.baseurl }}/files/2025-professional-cv.pdf">Professional CV</option>
    <option value="{{ site.baseurl }}/files/2024-academic-cv.pdf">Academic CV</option>
  </select>
</span>

If file does not load below, <a id="cv-download-link" href="{{ site.baseurl }}/files/2025-professional-cv.pdf">try downloading (pdf).</a>

<embed id="pdf-embed" src="{{ site.baseurl }}/files/2025-professional-cv.pdf" width="650" height="800" type='application/pdf'>