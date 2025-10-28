---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Mechanical Engineering**, [South China University of Technology](https://www.scut.edu.cn/), 2026.7
* **B.S. in Mechanical Engineering**, [East China University of Technology](https://www.ecust.edu.cn/), 2023.6

Work experience
======
* **2023.8-2026.6: Research Assistant**
  * South China University of Technology
  * Guangdong Provincial Key Laboratory of Precision Equipment and Manufacturing Technology (PEMT)
  * Supervisor: [Zhong Chen](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=w7uswTQAAAAJ)

* **2024.9-2026.3: Intern**
  * Jiesida Intelligent Technology (Guangdong) Co., Ltd.
  * Duties included: research and development
  * Supervisor: Qisen Wu
  
Skills
======
* **Research**
* **Programming**
* **Deep Learing**
* **Finite Element Analysis, FEA**
* **Digital Twin**

Publications
======
{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Research and Projects
======
{% for post in site.rp reversed %} {% include rp.html %} {% endfor %}
