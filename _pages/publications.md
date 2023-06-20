---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*: Corresponding author; #: Contributed equally

Journal Articles (Peer-reviewed)
===
2. **Zhao, L**., Bai, Y*., Paik, JK., 2023. Global-local hierarchical path planning scheme for unmanned surface vehicles under dynamically unforeseen environments. Ocean Engineering, 280, p.114750. [[PDF]](https://liangzhao13.github.io/files/zhao2023a.pdf), [[Data]](https://github.com/LiangZhao13/Data-for-Global-local.git) 
3. **Zhao, L**., Bai, Y*., 2022. Ultimate strength models for spherical shells under external pressure: A comparative study. Ships and Offshore Structures 1-12. [[PDF]](https://liangzhao13.github.io/files/Zhao2022Ultimate.pdf), [[Code]](https://github.com/LiangZhao13/Strength-Model-Calculation.git), [[Data]](https://github.com/LiangZhao13/Strength-Model-Calculation.git)
4. **Zhao, L**., Wang, F., Bai, Y., 2023. Route planning for autonomous vessels based on improved artificial fish swarm algorithm. Ships and Offshore Structures 18, 897–906. [[PDF]](https://liangzhao13.github.io/files/Zhao2022Route.pdf), [[Code]](https://github.com/LiangZhao13/Code-for-IAFSA.git)
5. **Zhao, L**., Bai, Y., Wang, F., Bai, J., 2022. Path planning for autonomous surface vessels based on improved artificial fish swarm algorithm: a further study. Ships and Offshore Structures 1-13. [[PDF]](https://liangzhao13.github.io/files/Zhao2022Path.pdf)
6. **Zhao, L**., Wang, F., Bai, Y*., 2021. Current status and challenges of unmanned surface vehicle path planning. Ship Engineering. 44(4), 1-7+48.\[in Chinese]. [[PDF]](https://liangzhao13.github.io/files/reviewpathplanning.pdf)
7. Wang, F., Bai, Y., **Zhao, L***., 2023. Physical Consistent Path Planning for Unmanned Surface Vehicles under Complex Marine Environment. Journal of Marine Science and Engineering 11(6), p.1164. [[PDF]](https://liangzhao13.github.io/files/zhao2023jmse.pdf)
9. Wang, F., **Zhao, L**., Bai, Y., 2022. Path Planning For Unmanned Surface Vehicles Based On Modified Artificial Fish Swarm Algorithm With Local Optimizer. Mathematical Problems in Engineering 2022, 1–15.
10. Wang, F., Bai, Y*., Bai, J., **Zhao, L**., 2022. Deep reinforcement learning in dynamic positioning control: by rewarding small response of riser angles. Ships and Offshore Structures 1–8. 






Conferences
===
1. **Zhao, L**., Mao, R., Bai, Y., 2022. Local Path Planning for Unmanned Surface Vehicles based on Hybrid A* and B-spline, in: 2022 IEEE International Conference on Unmanned Systems (ICUS). pp. 81–85. [[PDF]](https://liangzhao13.github.io/files/Local_Path_Planning_for_Unmanned_Surface_Vehicles_based_on_Hybrid_A_and_B-spline.pdf)
2. **Zhao, L**., Mao, R., Bai, Y., 2022. Observer Design for GNSS-aided Position Estimation of Autonomous Surface Vessels, in: 2022 IEEE International Conference on Unmanned Systems (ICUS). pp. 237–241.[[PDF]](https://liangzhao13.github.io/files/Observer_Design_for_GNSS-aided_Position_Estimation_of_Autonomous_Surface_Vessels.pdf)










{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
