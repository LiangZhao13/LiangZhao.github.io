---
title: "Publications"
permalink: /publications/
author_profile: true
---
*: Corresponding author; #: Contributed equally

Journal Articles (Peer-reviewed)
===
1. **Zhao, L**., Bai, Y*., Paik, JK., 2022. Global-local hierarchical path planning scheme for unmanned surface vehicles under dynamically unforeseen environments. Ocean Engineering, p.114750. [[Data]](https://github.com/LiangZhao13/Data-for-Global-local.git) 
2. **Zhao, L**., Bai, Y*., 2022. Ultimate strength models for spherical shells under external pressure: A comparative study. Ships and Offshore Structures 1-12. [[Code]](https://github.com/LiangZhao13/Strength-Model-Calculation.git), [[Data]](https://github.com/LiangZhao13/Strength-Model-Calculation.git)
3. **Zhao, L**., Wang, F., Bai, Y*., 2021. Route planning for autonomous vessels based on improved artificial fish swarm algorithm. Ships and Offshore Structures 1–10. [[Code]](https://github.com/LiangZhao13/Code-for-IAFSA.git)
4. **Zhao, L**., Bai, Y., Wang, F., Bai, J., 2022. Path planning for autonomous surface vessels based on improved artificial fish swarm algorithm: a further study. Ships and Offshore Structures 1-13.
5. **Zhao, L**., Wang, F., Bai, Y*., 2021. Current status and challenges of unmanned surface vehicle path planning. Ship Engineering. 44(4), 1-7+48.\[in Chinese].
6. Wang, F., Bai, Y*., Bai, J., **Zhao, L**., 2022. Deep reinforcement learning in dynamic positioning control: by rewarding small response of riser angles. Ships and Offshore Structures 1–8. 






Conferences
===
1. **Zhao, L**., Mao, R., Bai, Y., 2022. Local Path Planning for Unmanned Surface Vehicles based on Hybrid A* and B-spline, in: 2022 IEEE International Conference on Unmanned Systems (ICUS). pp. 81–85. [[PDF]](http//:LiangZhao13.github.io/files/Local_Path_Planning_for_Unmanned_Surface_Vehicles_based_on_Hybrid_A_and_B-spline.pdf)
2. **Zhao, L**., Mao, R., Bai, Y., 2022. Observer Design for GNSS-aided Position Estimation of Autonomous Surface Vessels, in: 2022 IEEE International Conference on Unmanned Systems (ICUS). pp. 237–241.










{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
