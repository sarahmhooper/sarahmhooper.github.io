---
layout: page
permalink: /research/
title: Research
# description: Long description long descroption long description
nav: true
nav_order: 1

years: [1967, 1956, 1950, 1935, 1905]

---

**Current research.** I’ve been lucky to work on projects throughout the medical imaging pipeline, from upstream image acquisition [8, 9], preprocessing [5], and synthesis [2] to downstream image analysis [1, 6, 7]. I’ve recently focused on a line of work around medical image segmentation. I've developed methods to train segmentation networks with limited labeled data [1, 4, 10], evaluated these networks on clinical tasks [1], and explored how we can leverage segmentation to improve other ML pipelines [3, ongoing].

**Future interests.** In the short-term, I’m interested in continuing to leverage recent progress in self-supervision and foundation models to enable rapid development of high-quality computer vision models for healthcare. Longer-term, I think there is great potential in considering a wider breadth of the imaging pipeline---including acquisition hardware, reconstruction algorithms, downstream analysis---together when developing ML-based applications for medical imaging. Ultimately, I hope to help transition these technological advances into usable systems that make measurable improvements in healthcare.

**Past work.** In the past, I’ve explored other areas at the intersection of technology and healthcare. As an undergraduate at Rice University, I worked with a large team in Electrical Engineering investigating automated seizure detection to control deep brain stimulation systems. I’ve also enjoyed learning about and working in global health. Through an internship and collaboration with the Bill and Melinda Gates Foundation, I’ve investigated promising technologies for noninvasive malaria diagnostics and methods to leverage febrile illness surveillance systems to improve pandemic preparedness. With Rice360, I worked on a low-cost tool to warm air delivered by bCPAP machines to neonates in respiratory distress.


<!-- _pages/publications.md -->
<div class="publications">
# bibliography -f papers
  
{%- for y in page.years %}
 <h2 class="year">{{y}}</h2>
 {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


