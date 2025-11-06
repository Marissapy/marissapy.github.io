---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Download CV

You can download my CV in the following formats:

- [English CV (PDF)](/files/CV_PY.pdf)
- [中文简历 (PDF)](/files/CV_Chinese.pdf)

---

## English CV Preview

<iframe src="/files/CV_PY.pdf" width="100%" height="800px" style="border: none;">
  <p>Your browser does not support PDFs. <a href="/files/CV_PY.pdf">Download the PDF</a> instead.</p>
</iframe>

---

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
