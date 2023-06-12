---
layout: page
title: Mars Rover
description: End of 2nd Year Project
img: assets/img/rover.jpeg
importance: 4
category: End-of-Year Projects
---
In a team of 7 people, implemented a rover with the main purpose being to navigate around an arena autonomously, avoid obstacles and send data to a database used to map the arena. My work mainly focused in the Energy and Drive sub-systems.

For the Energy Subsystem, as 4 PV panels were to be used to power the rover, many approaches were taken to maximise the efficiency and achieve a robust system. These included:
- testing all possible panel configurations with 2 Buck-Boost Converters to achieve maximum power generation under certain voltage and current constraints
- implementing an MPPT algorithm which took into account partial shading
- developing a Battery Charge Algorithm to keep the battery within its rated voltage and prevent a battery breakdown
- designing a State of Charge Algorithm for range estimation hence ensuring the rover is able to return back to the charging station

For the Drive Subsystem, my work focused on:
- developing PID controllers to enable the rover to move straight and turn at the correct angle depending on the command provided by the user
- implementing position and angle/distance measurement algorithms using data from an OFS and gyroscope
- debugging hardware issues using software and hardware techniques such as developing a soft-start algorithm and adding low-pass filters to prevent overcurrent and voltage spikes


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/team.jpeg" title="team image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rover.jpeg" title="rover image" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    On the left, five of the team's members at the end of the project. On the right, a view of our Mars rover.
</div>
