---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}

{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

[Jump to the current week](#week-2-linear-algebra-and-regression-br-small-read-a-href-resources-notes-notes-chapter-2-pdf-page-7-note-2-pages-7-13-a-the-a-href-faqs-week-2-lecture-faqs-a-and-a-href-resources-notes-notes-chapter-2-pdf-page-10-note-2-pages-10-19-a-small){: .btn } [Assignment Solutions](https://edstem.org/us/courses/61623/discussion/5141768){: .btn .btn-purple }

<!-- {: .green }

> Welcome to DSC 40A! See you in class this week. To begin, fill out the (required) [Welcome Survey](https://forms.gle/qA5xnzXiNZc55nii6). -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
