---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently pursuing a master's degree at [South China University of Technology](https://www.scut.edu.cn/) and will graduate in July 2026. Before that, I obtained a bachelor's degree in mechanical engineering from [East China University of Technology](https://www.ecust.edu.cn/).

Research Interests
======
Thermal error compensation for precision CNC machine tools
Time series prediction based on deep learning
Transfer learning
Digital Twin
Particle damping vibration reduction

News
======
---
2025-10-10 | Qi passed the mid-term review of his master's thesis
2023-8-31|Qi began his master's studies at South China University of Technology and conducted research on the topic of thermal error compensation for machine tools.
---

Publication
======
<ul>
  {% for post in site.publications reversed %}
    
  {% endfor %}
</ul>

<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

Projects & Research
======
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).
