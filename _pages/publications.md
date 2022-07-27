---
title: "Publications"
permalink: /publications/
author_profile: true
---
*: Corresponding author; #: Contributed equally

Journal Articles
===
1. **Zhao, L**., Bai, Y*., Bai, J., Wang, F., 2022. A Practical Path Planning Approach for Unmanned Surface Vehicles Considering Multiple Modality Constraints and Objectives. Ocean Engineering. (Under review)
2. **Zhao, L**., Wang, F., Bai, Y*., 2022. Route planning for autonomous vessels based on improved artificial fish swarm algorithm. Ships and Offshore Structures 1–10. [https://doi.org/10.1080/17445302.2022.2081423](https://doi.org/10.1080/17445302.2022.2081423)
3. **Zhao, L***., Bai, Y., Wang, F., Bai, J. 2022. Path Planning for Autonomous Surface Vessels Based on Improved Artificial Fish Swarm Algorithm: A Further Study. Ships and Offshore Structures.
4. **Zhao, L**., Wang, F., Bai, Y*. 2022. Current status and challenges of unmanned surface vehicle path planning. Ship Engineering. 44(4), 1-7.\[in Chinese]. [http://doi:10.13788/j.cnki.cbgc.2022.04.01](http://doi:10.13788/j.cnki.cbgc.2022.04.01).




Conferences
===
1. **Zhao, L**., Mao, RY., Bai, Y., Wang, F. 2022. Local Path Planning for Unmanned Surface Vehicles based on Hybrid A* and B-spline. 5th IEEE International Conference on Unmanned Systems (ICUS 2022). Oct 14-16. Guangzhou, China. (EI indexed)
2. **Zhao, L**., Mao, RY., Bai, Y. 2022. Observer Design for GNSS-aided Position Estimation of Autonomous Surface Vessels. 5th IEEE International Conference on Unmanned Systems (ICUS 2022). Oct 14-16. Guangzhou, China. (EI indexed)









{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
