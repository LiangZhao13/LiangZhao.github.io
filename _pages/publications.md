---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*: Corresponding author; #: Contributed equally

Journal Articles (Peer-reviewed)
===
2. **Zhao, L**., Bai, Y*., 2024. Joint-optimized coverage path planning framework for USV-assisted offshore bathymetric mapping: From theory to practice. Knowledge-Based Systems, 294, p.116921. [[Link]](https://doi.org/10.1016/j.oceaneng.2024.116921)
3. **Zhao, L**., Bai, Y*., 2024. Energy efficient coverage planning for USV-assisted inland bathymetry under current effects: An analysis on sweep direction. Ocean Engineering, 305, p.117910. [[Link]](https://doi.org/10.1016/j.oceaneng.2024.117910))
4. **Zhao, L**., Bai, Y*., Paik, JK., 2024. Optimal coverage path planning for USV-assisted coastal bathymetric survey: Models, solutions, and lake trials. Ocean Engineering, 294, p.116921. [[Link]](https://doi.org/10.1016/j.oceaneng.2024.116921)
3. **Zhao, L**., Bai, Y., 2023. Data harvesting in uncharted waters: Interactive learning empowered path planning for USV-assisted maritime data collection under fully unknown environments. Ocean Engineering, 287, p.115781. [[Link]](https://doi.org/10.1016/j.oceaneng.2023.115781)
4. **Zhao, L**., Bai, Y*., Paik, JK., 2023. Global-local hierarchical path planning scheme for unmanned surface vehicles under dynamically unforeseen environments. Ocean Engineering, 280, p.114750. [[Link]](https://doi.org/10.1016/j.oceaneng.2023.114750), [[Data]](https://github.com/LiangZhao13/Data-for-Global-local.git)
5. **Zhao, L**., Bai, Y*., Paik, JK., 2023. Achieving optimal-dynamic path planning for unmanned surface vehicles: a rational multi-objective approach and a sensory-vector re-planner. Ocean Engineering, 285, p.115433. [[Link]](https://doi.org/10.1016/j.oceaneng.2023.115433), [[Data]](https://github.com/LiangZhao13/Data-for-AENSGA-II.git)
6. **Zhao, L**., Bai, Y*., Paik, JK., 2023. Global path planning and waypoint following for heterogeneous unmanned surface vehicles assisting inland water monitoring. Journal of Ocean Engineering and Science. (In press) [[Link]](https://doi.org/10.1016/j.joes.2023.07.002)
7. **Zhao, L**., Wang, F., Bai, Y., 2022. Route planning for autonomous vessels based on improved artificial fish swarm algorithm. Ships and Offshore Structures 18, 897–906. [[Link]](https://doi.org/10.1080/17445302.2022.2081423), [[Code]](https://github.com/LiangZhao13/Code-for-IAFSA.git)
9. Wang, F., **Zhao, L**., 2023. Coordinated Trajectory Planning for Multiple Autonomous Underwater Vehicles: A Parallel Grey Wolf Optimizer. Journal of Marine Science and Engineering 11, 1720.
10. Wang, F., Bai, Y., **Zhao, L**., 2023. Physical Consistent Path Planning for Unmanned Surface Vehicles under Complex Marine Environment. Journal of Marine Science and Engineering 11(6), p.1164. 
11. Wang, F., Bai, Y*., Bai, J., **Zhao, L**., 2022. Deep reinforcement learning in dynamic positioning control: by rewarding small response of riser angles. Ships and Offshore Structures 1–8. 



<!--8. **Zhao, L**., Wang, F., Bai, Y*., 2021. Current status and challenges of unmanned surface vehicle path planning. Ship Engineering. 44(4), 1-7+48.\[in Chinese]. [[PDF]](https://liangzhao13.github.io/files/reviewpathplanning.pdf)-->


Conferences
===
2. **Zhao, L**., Bai, Y., Paik, J.K., 2023. Data harvesting in uncharted waters: Interactive learning empowered path planning for USV-assisted maritime data collection under fully unknown environments. 2023 AI Ocean Technology Conference for PhD Students, Zhoushan, China. (**Poster presentation**)
3. **Zhao, L**., Mao, R., Bai, Y., 2022. Local Path Planning for Unmanned Surface Vehicles based on Hybrid A* and B-spline, in: 2022 IEEE International Conference on Unmanned Systems (ICUS), Guangzhou, China. (**Oral presentation**) 
4. **Zhao, L**., Mao, R., Bai, Y., 2022. Observer Design for GNSS-aided Position Estimation of Autonomous Surface Vessels, in: 2022 IEEE International Conference on Unmanned Systems (ICUS), Guangzhou, China. (**Poster presentation**)










{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
