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
* B.S. in Computer Science, Peking University, GPA 3.71/4.00 (Top 15%), 2016 -- 2020

Work experience
======
* Robotics Institute, Carnegie Mellon University, Research Intern for Prof. Martial Hebert, June 2019 -- Aug 2019
  * Created a few-shot learning benchmark from ADE20K to imitate realistic conditions of long-tail distribution, multiple information sources
  * Explored representation learning from multiple information sources by multi-task learning and curriculum learning
  * Improved few-shot learning accuracy by 10% to 20% relatively
  * Paper at [Learning Generalizable Representations via Diverse Supervision](https://arxiv.org/abs/1911.12911)
* Vision and Media Computing Group, Peking University, Research Intern for Prof. Shiliang Zhang, June 2018 -- Now
  * Pose Guided Person Image Synthesis
    * Proposed geometric based preprocessing operations to preserve the salient visual details from source images
    * Combined information from multiple source images into a single target using a self-supervised learned
    * Superseded the visual quality of the state-of-the-art on Market-1501 and CUHK-03

Publications
======
  [Learning Generalizable Representations via Diverse Supervision](https://arxiv.org/abs/1911.12911), <b> Ziqi Pang\*</b>, Zhiyuan Hu\*, Pavel Tokmakov, Yuxiong Wang, Martial Hebert (\* indicates equal contribution) 
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Forum for American-Chinese Exchange at Stanford University, Organizer, Mar 2017 -- Mar 2019
