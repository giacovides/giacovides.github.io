---
layout: page
title: Arithmetic accelerator on FPGA
description: Coursework for 3rd Year module ELEC60011 - Digital Systems Design
img: assets/img/board.png
importance: 3
category: Machine Learning and Digital Hardware
---
The project focused on the acceleration of computationally intensive applications through the design and implementation of customised hardware blocks on an FPGA, taking into account the tradeoff between latency and resource utilisation.

In the project, we firstly explored how an off-chip memory is essential in order to perform calculations with large
memory requirements. The computation was then accelerated firstly through the use of embedded multipliers. This was
followed by designing custom floating point blocks for basic arithmetic operations (addition, subtraction, multiplication).
Rolled and unrolled custom CORDIC blocks were then designed for calculating the cosine part of the expression, which was
the most computationally intensive part. Finally, a double input design was implemented, to maximise throughput and hence reduce latency, with minimal increase in resource utilisation.

Overall, between the first and last implementation, the latency decreased drastically from 142.3 seconds to 0.0994 seconds, resulting in a 99.93% decrease in latency.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/board.png" title="board image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/design.png" title="design image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the DE1-SoC board with the Cyclone V FPGA used during the project. On the right, a flowchart of the final proposed design which achieved an optimal latency of 99.4ms.
</div>
